# Cible

http://pedale-mais-pas-trop.paqman.fr/

```bash
wget --mirror --convert-links --adjust-extension --page-requisites --no-parent --wait=1 http://pedale-mais-pas-trop.paqman.fr/
```


--mirror : récursif, avec timestamps
--convert-links : réécrit les liens pour qu’ils marchent en statique
--adjust-extension : ajoute .html si besoin
--page-requisites : récupère CSS, JS, images

Copy of wp-uploads

```
scp -r -P <port> <user>@<server>:/var/www/blog-pedale/wp-content/uploads/2015/06/ .
```