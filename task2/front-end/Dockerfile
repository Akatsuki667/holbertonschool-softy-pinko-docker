# Utiliser la dernière version de nginx comme image de base
FROM nginx:latest

# Copier les fichiers du front-end dans le répertoire approprié de nginx
COPY softy-pinko-front-end/ /var/www/html/softy-pinko-front-end/

# Copier notre fichier de configuration nginx personnalisé
COPY softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
