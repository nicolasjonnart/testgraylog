

PREREQUIS :


Sur le poste de déploiement :
Ansible ; saisir ip des serveurs de prod & preprod dans /etc/ansible/hosts

Sur les hotes (debian stable) :
Un utilisateur appartenant au groupe sudo
Envoyer La clé publique du poste admin (duquel est lancé le script) sur les serveurs de prod et preprod


Se placer à la racine.
Editer le fichier playbook.yml et y personnaliser les variables.
Lancer le script avec la commande :
ansible-playbook playbook.yml --user=nom_utilisateur --ask-sudo-pass ; et entrer le mdp utilisateur


