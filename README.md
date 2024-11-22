# Configurer OpenSSH

ssh-keygen -t rsa 
ssh -T git@github.com

Vérifier les fichiers id_rsa et id_rsa.pub
Copier le contenu de id_rsa.pub sur le compte Github/Settings/SSH and GPG

# Publier son code

Télécharger et installer Git: https://git-scm.com/downloads

git init
git remote add origin git@github.com:<COMPTE>/<REPOSITORY>.git (Remplacer COMPTe et REPOSITORY)
// vérifier que le fichier .gitignore existe bien dans le dossier en cours
git add .
git commit -am "Initial commit"
git push -u origin master

