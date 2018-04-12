## سرد قصتك

لنضِف جزءًا آخر إلى قصتك.

+ انتقل إلى السطر 15 من التعليمات البرمجية، وأضف وسمَي البداية والنهاية `<div>` و`</div>` لإضافة عنصر آخر. سينشئ ذلك مربعًا جديدًا للجزء التالي من القصة.

![screenshot](images/story-div.png)

+ أضف فقرة من النص داخل الوسم الجديد `<div>`:

```html
<p>More text here!</p>
```

![screenshot](images/story-paragraph.png)

+ يمكنك عرض صورة في المربع الجديد بإضافة هذه التعليمة البرمجية داخل الوسم `<div>`:

```html
<img src="">
```

![screenshot](images/story-img-tag.png)

لاحظ أن أوسمة `<img>` تختلف قليلًا عن الأوسمة الأخرى: فليس لها وسم نهاية.

+ لإظهار الصورة، ستحتاج إلى إضافة **مصدر** الصورة (`src`) داخل علامتَي الاقتباس.

انقر فوق أيقونة الصور لترى الصور المتوفرة لقصتك:

![screenshot](images/story-see-images.png)

+ حدِّد الصورة التي تريد إضافتها وتذكَّر اسمها، مثل `buildings.png`.

+ انقر فوق علامة التبويب `index.html` للعودة إلى التعليمات البرمجية.

![screenshot](images/story-image-name.png)

+ أضف اسم الصورة بين علامتَي الاقتباس داخل الوسم `<img>`.

```html
<img src="buildings.png">
```

![screenshot](images/story-image-name-add.png)
