

PREREQUIS :

Sur le poste de déploiement :
Ansible ; saisir ip des serveurs de prod & preprod dans /etc/ansible/hosts

Sur les hotes :
Un utilisateur appartenant au groupe sudo
Envoyer La clé publique du poste admin (duquel est lancé le script) sur les serveurs de prod et preprod



Se placer à la racine du dossier pour lancer le script avec la commande :
ansible-playbook playbook.yml --user=nom_utilisateur --ask-sudo-pass
et entrer le mdp utilisateur


