## رواية قصتك

دعنا نضيف جزء ثاني لقصتك.

+ انتقل إلى السطر 15 من التعليمات البرمجية، وقم بإضافة مجموعة أخرى من `<div>` و ` </div>` علامات البداية والنهاية. سيؤدي هذا إلى إنشاء صندوق جديد للجزء التالي من قصتك.

![لقطة شاشة](images/story-div.png)

+ أضف فقرة من النص داخل العلامة `<div>` الجديدة:

```html
<p>المزيد من النص هنا!</p>
```

![لقطة شاشة](images/story-paragraph.png)

+ يمكنك عرض صورة في صندوقك الجديد عن طريق إضافة هذا الكود في العلامة `<div>` الخاصة بك:

```html
<img src="">
```

![لقطة الشاشة](images/story-img-tag.png)

Notice that `<img>` tags are a bit different to other tags: they don't have an end tag.

+ To get an image to show up, you need to add the **source** (`src`) of the image inside the speech marks.

Click the image icon to see the images available for your story.

![لقطة الشاشة](images/story-see-images.png)

+ Decide which image you want to add and remember its name, for example `buildings.png`.

+ Click on `index.html` to get back to your code.

![لقطة الشاشة](images/story-image-name.png)

+ Add the name of the image between the speech marks in your `<img>` tag.

```html
<img src="buildings.png">
```

![لقطة الشاشة](images/story-image-name-add.png)