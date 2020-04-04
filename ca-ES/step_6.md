## Explicant la teva història

Afegirem ara una segona part a la teva història.

+ Ves a la línia 15 del codi i afegeix un altre conjunt d'etiquetes `<div>` i `</div>` d’inici i final. D’aquesta manera es crearà un requadre nou per a la següent part de la teva història.

![screenshot](images/story-div.png)

+ Afegeix un paràgraf de text dins l'etiqueta nova `<div>`:

```html
<p>Més text aquí!</p>
```

![screenshot](images/story-paragraph.png)

+ Pots visualitzar una imatge al requadre nou afegint aquest codi a dins de la teva etiqueta `<div>`:

```html
<img src="">
```

![screenshot](images/story-img-tag.png)

Observa que les etiquetes `<img>` són una mica diferents de les altres etiquetes: no tenen una etiqueta final.

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