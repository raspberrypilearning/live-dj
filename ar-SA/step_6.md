## إضافة صوت عميق

الآن دعونا نضيف بعض نوتات الصوت العميق إلى الموسيقى الخاصة بك.

+ ابدأ بإنشاء `live_loop` جديد يسمى `:bass`. هذه الحلقة الجديدة يجب أن تكون متزامنة` sync ` مع الطبول.
    
    ![لقطة الشاشة](images/dj-bass-loop.png)

+ أضف كود للعب نوتة واحدة كل 8 نبضات. تستخدم النوتة التي تم تشغيلها التجميع `:chipbass`.
    
    ![لقطة الشاشة](images/dj-bass-note.png)

+ اضغط على "تشغيل Run" (لا حاجة لإيقاف الموسيقى وإعادة تشغيلها). يجب أن تسمع النوتة تشتغل كل 8 نبضات.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/bass-single.mp3" type="audio/mpeg"> Your browser does not support the <code>audio</code> element. </audio>
    </div>
+ إن **chord** هي مجموعة من النوتات يتم تشغيلها معا.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/chord.mp3" type="audio/mpeg"> Your browser does not support the <code>audio</code> element. </audio>
    </div>
    بدلاً من تشغيل نفس النوتة كل 8 ايقاعات، يمكنك `الاختيار` نوتة عشوائية من **chord**. In this case, the chord is **C Minor**.
    
    ![لقطة الشاشة](images/dj-bass-random-note.png)

+ النغمة "وسط" C هو في الواقع `:c4`. لتشغيل نغمات أقل جهورا، أضف رقمًا أقل من 4 بعد اسم الوتر.
    
    ![لقطة الشاشة](images/dj-bass-lower-note.png)

+ استخدم ` sustain ` لاختيار عدد الضربات التي تحملها النوتة.
    
    ![لقطة الشاشة](images/dj-bass-longer-note.png)

+ يمكنك أيضًا استخدام `amp` لاختيار صوت القاعدة. عدد أقل من 1 سيكون أكثر هدوءاً، و أعلى من 1 سيكون أعلى.
    
    ![لقطة الشاشة](images/dj-bass-amp.png)

+ يمكنك أيضا إضافة عينة (أعلى) للعب في بداية كل نوتة.
    
    ![لقطة الشاشة](images/dj-bass-sample.png)

+ Press 'Run' to test your code. ليس هناك حاجة لإيقاف الموسيقى الخاصة بك وإعادة تشغيلها.
    
    <div id="audio-preview" class="pdf-hidden">
      <audio controls preload> <source src="resources/bass.mp3" type="audio/mpeg"> Your browser does not support the <code>audio</code> element. </audio>
    </div>