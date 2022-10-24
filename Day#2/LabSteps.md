
خطوات إرسال Labs على GitHub

1- في أعلى الصفحة، اضغط على Fork.

![](https://paper-attachments.dropbox.com/s_820E856EE4C6C56B229073F756DD1C27685F3CE325E28FAEA0736E1BD7202C90_1658352274515_fork1.jpg)



2- اضغط على Create fork.

![](https://paper-attachments.dropbox.com/s_820E856EE4C6C56B229073F756DD1C27685F3CE325E28FAEA0736E1BD7202C90_1658352312458_fork22.jpg)




3- اضغط على Code. 

![](https://paper-attachments.dropbox.com/s_820E856EE4C6C56B229073F756DD1C27685F3CE325E28FAEA0736E1BD7202C90_1658352348316_code.jpg)



4- قم بنسخ الرابط المرفق.

![](https://paper-attachments.dropbox.com/s_820E856EE4C6C56B229073F756DD1C27685F3CE325E28FAEA0736E1BD7202C90_1658352417083_code2.jpg)



5- بعد ذلك، افتح Git Bash ، ثم قم بتغيير المسار الحالي الى موقع المجلد الذي ترغب في استنساخ مستودعك (your repository) فيه. لتغيير المسار قم باستخدام أمر cd.

على سبيل المثال، إذا كنت تريد أن يكون المستودع الخاص بك في مجلد "python-course"، يمكنك تغيير المسار كما يلي:


    cd python-course



6- قم بنسخ مستودعك (your repository) من GitHub الى جهازك المحلي من خلال أمر `git clone`.


    git clone https://github.com/TUWAIQ-PYTHON-COURSE/FIRST_REPO.git
    https://github.com/NAlMutlaq/Day2-Lab1-CLI.git

بعد أمر `git clone`، يجب أن ترى مخرجات مشابهه لهذه المخرجات. هذه المخرجات دلاله على نجاح الاستنساخ.


    Cloning into 'FIRST_REPO'...
    remote: Enumerating objects: 6, done.
    remote: Counting objects: 100% (6/6), done.
    remote: Compressing objects: 100% (3/3), done.
    remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 
    Receiving objects: 100% (6/6), done.


الان سيكون هناك نسخه من Lab اليوم بالمجلد الذي تم تحديد مساره مسبقًا. قم بفتحه وابدأ بتنفيذ جميع المتطلبات.


7- قم بتغيير المسار الى مسار مجلد Lab اليوم.


    cd todayLab


8- بعد انتهائك من تنفيذ جميع المتطلبات، قم بالرجوع الى Git Bash وأضف الملف الذي قمت بتعديله او اضافته من خلال أمر `. git add` 


    git add .


9- استخدم أمر `git commit` لأضافة رسالة قصيرة تصف التغيرات التي أُجريت.


    git commit -m "Your commit message"


10- يمكنك رفع التغييرات التي أجريتها الى GitHub من خلال:


    git push
    Username for 'https://github.com': 
    Password for


11-  نظرا لأن العديد من الأشخاص يمكن أن يتعاونوا في المستودع (repository)، فأنت بحاجة إلى التأكد من تحديث نسختك بكل مره تقوم بالتعديل او الإضافة. يمكنك تحديث تغييراتك إلى GitHub من خلال:


    git pull


12- بعد ذلك، قم بالرجوع الى GitHub واضغط على pull requests بأعلى الصفحه.

![](https://paper-attachments.dropbox.com/s_820E856EE4C6C56B229073F756DD1C27685F3CE325E28FAEA0736E1BD7202C90_1658384245839_pull+request.jpg)



13- اضغط على New pull request.

![](https://paper-attachments.dropbox.com/s_820E856EE4C6C56B229073F756DD1C27685F3CE325E28FAEA0736E1BD7202C90_1658384915631_new+pull+req.jpg)



14- اضغط على Create pull request.

![](https://paper-attachments.dropbox.com/s_03AFD6650236B603E3F9207388DC1BF92CF637607BD424533F6429D05269F4A2_1658621695342_ccc.jpg)


15- يتم منحك فرصة أخيرة للتعليق على طلب pull request. ملاحظه، هذا تعليق للمالك وليس جزءا من الطلب نفسه. بعد ذلك اضغط على Create pull request.

![](https://paper-attachments.dropbox.com/s_03AFD6650236B603E3F9207388DC1BF92CF637607BD424533F6429D05269F4A2_1658621705599_c.jpg)



عند ظهور رسالة تطلب منك token access قم باتباع الخطوات التالية:


https://techglimpse.com/git-push-github-token-based-passwordless/


