# La formation Concourse CI


## Lancement local d'une instance de concourse

[[_TOC_]]

### Installation de docker et docker-compose

Nous allons mettre en place une instance locale de Concourse-CI pour réaliser les TPs.

Si vous réalisez le TP en local sur votre machine, vous devez disposer de **docker**, ainsi que de **docker-compose**.

Si vous utilisez l'environnement Cloud fourni par le formateur :

- Sur Google Cloud Shell (GCP), ces deux outils sont préinstallés.
- Sur AWS Cloud9, il faut installler docker compose (voir ci-dessous)

````sh
# Installation de docker et docker-compose sur Ubuntu
sudo apt update
sudo apt install -y docker docker-compose
````

### Télechargement du fichier `docker-compose.yml`

Télécharger le fichier 

````sh
wget https://gitlab.com/oxiane-formation-concourse-ci/deploiement/-/raw/main/docker-compose.yml
````

#### Version adaptée pour AWS (Cloud9)

````sh
wget https://gitlab.com/oxiane-formation-concourse-ci/deploiement/-/raw/aws-cloud9/docker-compose.yml
````

#### Version adaptée pour GCP (Google Shell Editor)

Sur Google Shell Editor, on peut prédire l'URL de la preview en utilisant la variable `$WEB_HOST`.

````sh
wget https://gitlab.com/oxiane-formation-concourse-ci/deploiement/-/raw/gcp-google-shell/docker-compose.yml
````
