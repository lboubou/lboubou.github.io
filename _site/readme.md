Jekyll

Install Jekyll :

Il faut tous d'abord installer Ruby :
sudo apt-get install ruby-full

Le mettre a jours:
sudo gem update –system

Installer Jekyll :
sudo gem install jekyll

Il faut installer Curl pour installer NodeJS :

sudo apt-get install curl

Commande pour NodeJS :

curl --silent --location https://deb.nodesource.com/setup_0.12 | sudo bash -

Puis (pour terminer l’installation) : 

sudo apt-get install --yes nodejs

Puis, il faut se placer dans le dossier à la racine du site :

jekyll new nomdusite
cd nomdusite
jekyll serve

URL : http://localhost:4000/

Install de GIT :

Crée un compte GitHUB

ouvrir un nouveau terminal
sudo apt-get install libcurl4-gnutls-dev libexpat1-dev gettext \libz-dev libssl-dev
sudo apt-get install git 

Aller a https://pages.github.com/ et suivre les indications

se placer dans le dossier du site à cloner et remplacer les username
git clone https://github.com/username/username.github.io

"Vous semblez avoir cloné un dépôt vide". Il faut donc créer un fichier pour vérifier que cela fonctionne.
touch readme.md
git add .
git commit -m "mon premier fichier"
git push

/////
Problème :
git config --global user.email "you@example.com"
git config --global user.name "Your Name"

enlever le “--global” →

git config user.email "you@example.com"
git config user.name "Your Name"
/////

lien pour création fichier md :

http://writeme.mattstow.com/


mettre à jour le git (en étant placer dans le dossier) :

git commit -a -m "Ce que vous avez modifier et signaler"
git push
