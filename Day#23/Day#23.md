## الخطوات:
- إنشاء مشروع وتسمية المشروع TitanicProject
- فتح Terminal ثم تنزيل Django عن طريق الأمر
    > python -m pip install django 
- إنشاء مشروع TitanicSite عن طريق كتابة الأمر 
    > django-admin startproject TitanicSite 
- الدخول للمشروع عن طريق كتابة cd TitanicSite ثم إنشاء تطبيق TitanicApp عن طريق كتابة الأمر 
    > python manage.py startapp TitanicApp 
- بداخل ملف settings.py نقوم بإضافة التطبيق كالتالي: 
    > INSTALLED_APPS = ['TitanicApp']
- لصق ملف ml_model وملف البيانات train.csv في مجلد المشروع TitanicSite وتحميل المكتبات المطلوبة.
- تنفيذ ملف ml_model ليتم إنشاء ملفات.pkl.
- بداخل مجلد TitanicApp نقوم بلصق ملف views.py و مجلد templates.
- داخل مجلد TitanicSite نقوم بتعديل ملف urls.py كالتالي:
    
    ``` python 
    from TitanicApp.views import home, result
    urlpatterns = [
        path('admin/', admin.site.urls),
        path('', home, name='home'),
        path('result/', result, name='result')
    ]
    ```
    
- نقوم بتشغيل الملف عن طريق الأمر:
    > python manage.py runserver

 
