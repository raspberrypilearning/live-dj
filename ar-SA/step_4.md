## إضافة عينة

دعونا نضيف عينة حلقة فوق حلقة الطبل الأساسية.

+ لتشغيل عينة في الوقت ذاته مع الطبول، قم بإنشاء `live_loop` يسمى `:sample`.
    
    ![لقطة الشاشة](images/dj-sample-loop.png)

+ أضف العينة `:loop_compus`، مما يجعلها تلعب كل 8 ضربات.
    
    ![لقطة الشاشة](images/dj-sample-bug.png)

+ إذا قمت باختبار العينة الخاصة بك، ستلاحظ أنها **لا تتطابق مع الطبول** على الإطلاق!
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/beat-bug.mp3" type="audio/mpeg"> المتصفح الخاص بك لا يدعم عنصر <code>الصوت </code>. </audio>
    </div>
+ أول شيء ستحتاج إلى القيام به هو `مزامنة` العينة الخاصة بك مع ايقاع الطبلة.
    
    ![لقطة الشاشة](images/dj-sample-sync.png)

+ هذا لا يزال غير صحيح! أضف الكود لطباعة مدة العينة:
    
    ![لقطة الشاشة](images/dj-sample-duration.png)

+ إذا قمت بالرجوع للخلف عبر سجل ** log ** ، سترى أنه على الرغم من أن العينة تكرر كل 8 نبضات ، ** فانها لا تستمر 8 نبضات **.
    
    ![لقطة الشاشة](images/dj-sample-log.png)
    
    (يمكنك الآن إزالة الرمز لطباعة مدة العينة.)

+ لمطابقة عينتك مع الطبول ، ستحتاج إلى تمديد ** stretch ** العينة بحيث تستمر 8 نبضات بالضبط.
    
    ![لقطة الشاشة](images/dj-sample-stretch.png)

+ اختبر الرمز بالضغط على تشغيل "Run" مرة أخرى - ** لست بحاجة إلى إيقاف الموسيقى وإعادة تشغيلها **! يجب أن تسمع الآن أن عينتك تشتغل في الوقت ذاته مع إيقاع الطبل الخاص بك.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/beat-fixed.mp3" type="audio/mpeg"> المتصفح الخاص بك لا يدعم عنصر <code>الصوت </code>. </audio>
    </div>