## Raconte ton histoire

Ajoutons une deuxième partie à ton histoire.

+ Va à la ligne 15 du code et ajoute un autre lot de balises de début et de fin `<div>` et ` </div>`. Cela créera une nouvelle boîte pour la prochaine partie de ton histoire.

![screenshot](images/story-div.png)

+ Ajoute un paragraphe de texte dans ta nouvelle balise `<div>`:

```html
<p> Plus de texte ici! </p>
```

![screenshot](images/story-paragraph.png)

+ Tu peux afficher une image dans votre nouvelle boîte en ajoutant ce code dans ta balise `<div>`:

```html
<img src="">
```

![screenshot](images/story-img-tag.png)

Note que les balises `<img>` sont un peu différentes des autres balises: elles n’ont pas de balise de fin.

+ Pour faire apparaître une image, tu dois ajouter la source **. ** (` src ` ) de l'image à l'intérieur des repères de parole.

Clique sur l'icône de l'image pour voir les images disponibles pour ton histoire.

![screenshot](images/story-see-images.png)

+ Decide which image you want to add and remember its name, for example `buildings.png`.

+ Click on `index.html` to get back to your code.

![screenshot](images/story-image-name.png)

+ Add the name of the image between the speech marks in your `<img>` tag.

```html
<img src="buildings.png">
```

![screenshot](images/story-image-name-add.png)