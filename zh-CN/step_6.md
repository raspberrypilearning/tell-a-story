## 讲述你的故事

让我们在你的故事中添加第二部分。

+ 转到代码的第15行，然后添加另一组`<div>`和`</div>`开始和结束标签。 这将为你的故事的下一部分创建一个新的框。

![截图](images/story-div.png)

+ 在新的`<div>`标签之间内添加一段文字：

```html
<p>添加更多文字！</p>
```

![截图](images/story-paragraph.png)

+ 您可以通过在您的`<div>`标签之间添加此代码以在您的新的故事框中显示图像：

```html
<img src="">
```

![截图](images/story-img-tag.png)

注意`<img>`标签与其他标签有一点不同：它们没有结束标签。

+ 为了能够显示图像，你需要将图像的 **源文件名** (`src`) 加入双引号之间.

点击图标查看您的故事中可用的图像。

![截图](images/story-see-images.png)

+ 确定要添加的图像并记住其文件名，例如` buildings.png ` 。

+ 点击`index.html`来返回到你的代码。

![截图](images/story-image-name.png)

+ 在`<img>`标签的双引号之间加入图像的文件名。

```html
<img src="buildings.png">
```

![截图](images/story-image-name-add.png)