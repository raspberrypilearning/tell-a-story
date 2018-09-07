## Pričanje priče

Dodajmo drugi dio priče.

+ Idi u 15. red kôda i dodaj još jedan par oznaka, početnu `<div>` i završnu `</div>`. Tako ćeš kreirati novo polje za sljedeći dio tvoje priče.

![screenshot](images/story-div.png)

+ Dodaj pasus teksta unutar svoje nove `<div>` oznake:

```html
<p>Još teksta ovdje!</p>
```

![screenshot](images/story-paragraph.png)

+ U svoje novo polje možeš da dodaš i sliku tako što ćeš dodati sljedeći kôd unutar oznake `<div>`:

```html
<img src="">
```

![screenshot](images/story-img-tag.png)

Primijeti da su oznake `<img>` malo drugačije od ostalih oznaka: nemaju završnu oznaku.

+ To get an image to show up, you need to add the **source** (`src`) of the image inside the speech marks.

Click the image icon to see the images available for your story.

![screenshot](images/story-see-images.png)

+ Decide which image you want to add and remember its name, for example `buildings.png`.

+ Click on `index.html` to get back to your code.

![screenshot](images/story-image-name.png)

+ Add the name of the image between the speech marks in your `<img>` tag.

```html
<img src="buildings.png">
```

![screenshot](images/story-image-name-add.png)