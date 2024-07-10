# لبناء صفحة ويب للتحكم باتجاه حركة الروبوت وربطها بقاعدة البيانات
## اولاً نقوم بتنزيل XAMPP
### طريقة تنزيل XAMPP
1.نقوم بالكتابه في المتصفح Download XAMPP
![ش](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/0d49ee10-50a3-49a0-87eb-7edde9be197e)


  
2.نقوم بالنقر على Download حسب نوع الجهاز

![م](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/72d3f107-ea56-4513-8d1c-576c6fd4626e)


3.بعد مايتم تحميله نقوم بتشغيله وتشغيل Apache وMySQL


![م](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/72d3f107-ea56-4513-8d1c-576c6fd4626e)
  >


## ثانياً
نقوم بأنشاء مجلد 
### طريقة انشاء مجلد 
هذا الكمبيوتر الشخصي> القرص المحلي(C)> htdocs < XAMPP >بعدها نقوم بأنشاء مجلد 


![انشاء](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/31d91d1e-7502-40ec-8ff5-89f8209f25f6)
  >
## ثالثاً
نقوم بأستخدام Visual Studio Code لتصميم واجهة التحكم بالروبوت
![photo1720583775 (1)](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/1242c76d-dc1b-41fe-a205-f105dc7f762d)
  

1.قم بفتح المجلد الذي تم انشاءه

المجلد الذي قمت بأنشائه اسمه(Server)

                 [jj](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/f8b8fb55-8b6d-4dbc-83a9-18af2506cb17)



![صص](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/ba5826f9-13d0-4465-a8cc-6960005c483f)
  

2. نقوم بأنشاء ملفان index.html و index.php
   
![ملف](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/f304f07c-00c3-47ea-b958-3408a89bdb8e)
     

3.نقوم بكتابة كود HTML لتصميم الواجهة داخل ملفindex.html 
![الاول](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/f670759f-43ac-472c-bd7a-d59fe0897628)

![الثالث](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/6cf65126-e974-4d8b-895e-aa1d0d02d20a)

![33](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/60114dea-be25-4466-a4b1-b1a0cd2978f9)


نقوم بتشغيل الكود
![تشغيل](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/82a44680-4ab4-4a95-9eb6-b55ea8e6d87b)



## شكل الواجهة
![واجهه](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/7b2f619b-109c-42e3-99c7-90d6554035a9)

## رابعاً
### نقوم بالذهاب للمتصفح وكتابة localhost/phpmyadmin لأنشاء قاعدة البيانات
![لوكال بحث](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/77afd5cd-37a0-422d-8a68-0c004cb08364)

![قاعدة البيانات](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/fa530723-1417-469b-82a7-ad4ad6dc54c4)
>

### طريقة انشاء جدول داخل قاعدة البيانات
## 1.انشاء قاعدة بيانات                                                                                                                                                                
                                                                                                                                                                   New>Database name>Create
![قاعدده2](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/52662156-23c7-4444-a1d7-79ec810f2374)
                                                                                                                                                                  
  
  
*قاعدة البيانات التي قمت بأنشاءها هي(sh) 

 ## 2.انشاء جدول داخل قاعدة البيانات
نقوم بأدخال اسم الجدول وعدد الاعمدة

![انشاء جدول](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/e242a485-d834-4023-8a55-808fc33245f3)


نقوم بأدخال اسم العمود ونوعه ثم Save 

![مكونات الجدول](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/6eecedf5-ae93-472e-8e41-32f8cd19080b)

تم انشاء قاعدة بيانات (sh)داخلها جدول(direction)

![النهايه](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/5cdd32db-b320-4c84-aebc-67e910f35b47)



# خامساً
## ربط واجهة التحكم بقاعدة البيانات
### طريقة ربط واجهة التحكم بقاعدة البيانات
## 1.فتح المجلد بالكامل على متصفح ( اسم المجلد/localhost)

![فتح لمجلدد](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/b5f6a5d8-bc1f-47ab-84f5-2dd9a058e432)
  >
## 2.كتابة كود php داخل ملف index.phpلربط الواجهة بقاعدة البيانات

![كودphp](https://github.com/Shahad187/Designing-an-interface-to-control-the-robot-s-movement-and-linking-it-to-the-database/assets/173778628/10790cec-489e-44c6-b5fc-791aa127a877)

>


# 3.الان عندما نذهب للواجهة ونقوم بالنقر على احد الاوامر سيتم ارسال الامر لقاعدة البيانات مثل ماهو موجود في الفديو


Uploading 14460104085912.mp4…

  
[![ربط قاعدة بيانات] ( https://files.fm/f/ujnp6w784p)

