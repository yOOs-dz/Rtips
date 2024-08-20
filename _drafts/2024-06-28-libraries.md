---
layout: post
title: مكتبات آر
description: هنا بعض المعلومات الأساسية حول المكتبة على آر
img: <img src="https://raw.githubusercontent.com/yOOs-dz/bayany/main//images/logo_Rtips.png" width='100' height= auto/>
---
## مدخل
تعتبر كل مكتبة حزمة معلومات مكونة من مجموعة من التعليمات لغرض ما و كذا مجموعة من المعطيات إضافة إلى قاعدة منصة آر و التي ```R-base``` و التي تحوي التعليمات البرمجمية الأساسية للغة آر و كذا معطيات أخرى.
## تعليمة تنصيب المكتبات
لتنصيب كل مكتبة ، تكتب التعليمة التالية ` مع اسم الحزمة-المكتبة بين مزدوجتين أو ظفرين كدليل للتعليمة ```Argument```.
```
install.packages('...')
```
في حال أردت تنصيب أكثر من مكتبة تضع مجموعة المكتبات على صيغة ```شعاع``` - ```vector``` أي بالصيغة:

```c('','','',...)```

### مثال :
```
install.packages(c("FactoMineR", "factoextra"))
```
## تعليمة تشغيل المكتبات بعد التنصيب
بعد التنصيب ، يمكن تشغيل المكتبات بغرض استعمالها و ذلك باستعمال تعليمة ```library()``` مع اسم المكتبة كدليل و دون وضع مزدوجتين أو ظفرين. أنظر الأمثلة أسفله.

### أمثلة
```
library (readr)#charge library to read_csv
library(dplyr)
#library(lattice)
#library("FactoMineR")
#library("factoextra")
#library(missMDA)
library(ggplot2)
```
