## Pričanje priče

Dodajmo drugi dio priče.

+ Idi u 15. red kôda i dodaj još jedan par oznaka, početnu `<div>` i završnu `</div>`. Tako ćeš kreirati novo polje za sljedeći dio tvoje priče.

![screenshot](images/story-div.png)

+ Dodaj pasus teksta unutar svoje nove `<div>` oznake:

```html
<p>Još teksta ovdje!</p>
```

![screenshot](images/story-paragraph.png)

+ You can display an image in your new box by adding this code inside your `<div>` tag:

```html
<img src="">
```

![screenshot](images/story-img-tag.png)

Notice that `<img>` tags are a bit different to other tags: they don't have an end tag.

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