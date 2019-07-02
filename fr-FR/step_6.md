## Raconte ton histoire

Ajoutons une deuxième partie à ton histoire.

+ Go to line 15 of the code, and add in another set of `<div>` and `</div>` start and end tags. This will create a new box for the next part of your story.

![screenshot](images/story-div.png)

+ Add a paragraph of text inside your new `<div>` tag:

```html
<p>More text here!</p>
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