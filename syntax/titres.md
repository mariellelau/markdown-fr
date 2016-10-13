# Titres

Comme nous avons commencé à écrire un document en Markdown, nous avons besoin d'ajouter un tire et quelques sous-titres.

Le Markdown supporte deux styles de titres, Setext et atx. 

Le style de titre Setext est "souligné", utilisant des signes égals (pour le premier niveau de titre) et des tirets (pour le seconde niveau de titre). Par exemple : 

```
Ceci est un H1
=============

Ceci est un H2
-------------
```
N'importe quel nombre d'égal (=) ou de tirets (-) peut  pour souligner. 

Le style de titre atx utilise de 1 à 6 caractères hashtags au début de la ligne, correspondant au niveau de titre de 1 à 6. Par exempe, 

```
# Ceci est un H1

## Ceci est un H2

###### Ceci est un H6

Optionnellement, vous pouvez "fermer" les styles de titre atx. Ceci est uniquement esthétique - vous pouvez utiliser ceci si vous pensez que c'est plus clair. Les hashtags fermant n'ont pas besoin d'avoir le même nombre d'hashtags utilisés pour ouvrir le titre. (Le nombre d'hashtags ouvrants détermine le niveau de titre) :


```
# Ceci est un H1 #

## Ceci est un H2 ##

### Ceci est un H3 ######
```


---

Voici un quizz à propos des titres en Markdown : 

Sélectionne le titre valide : :
- [x] `# Salut`
- [ ] `#Salut`

> Les titres ont besoin d'un espace entre le caractère hashtag et le texte. 

Sélectionne le titre valide :
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seulement '=' et '-' sont acceptés pour souligner un titre.

---


