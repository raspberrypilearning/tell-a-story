## Contando sua história

Vamos adicionar uma segunda parte à sua história.

+ Vá para a linha 15 do código e adicione outro conjunto de `<div>` e `</div>`, ou seja, tags de início e fim. Isso vai criar uma nova caixa para a próxima parte de sua história.

![screenshot](images/story-div.png)

+ Adicione um parágrafo de texto dentro da sua nova tag `<div>`:

```html
<p>Mais texto aqui!</p>
```

![screenshot](images/story-paragraph.png)

+ Você pode exibir uma imagem em sua nova caixa adicionando este código dentro de sua tag `<div>`:

```html
<img src="">
```

![screenshot](images/story-img-tag.png)

Observe que as tags `<img>` são um pouco diferentes das outras tags: elas não tem uma tag final.

+ Para fazer uma imagem aparecer, você precisa colocar a **fonte** (`src`) da imagem dentro das aspas.

Clique no ícone de imagem para ver as imagens disponíveis para sua história.

![screenshot](images/story-see-images.png)

+ Decide which image you want to add and remember its name, for example `buildings.png`.

+ Click on `index.html` to get back to your code.

![screenshot](images/story-image-name.png)

+ Add the name of the image between the speech marks in your `<img>` tag.

```html
<img src="buildings.png">
```

![screenshot](images/story-image-name-add.png)