## Adding a sample
Let's add a looping sample over the basic drum loop.



+ To play a sample in time with your drums, create another `live_loop` called `:sample`.

    ![screenshot](images/dj-sample-loop.png)

+ Add the sample `:loop_compus`, making it play every 8 beats.

    ![screenshot](images/dj-sample-bug.png)

+ If you test your sample, you'll notice that it __doesn't match the drums__ at all!

    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload>
      <source src="sounds/beat-bug.mp3" type="audio/mpeg">
    Your browser does not support the <code>audio</code> element.
    </audio>
    </div>

+ The first thing you'll need to do is `sync` your sample with the drum beat.

    ![screenshot](images/dj-sample-sync.png)

+ This still doesn't sound right! Add code to print the duration of the sample:

    ![screenshot](images/dj-sample-duration.png)

+ If you scroll back through the __log__, you'll see that although the sample is repeating every 8 beats, __the sample doesn't quite last 8 beats__.

    ![screenshot](images/dj-sample-log.png)

    (You can now remove the code to print the sample duration.)

+ To match your sample with the drums you'll need to __stretch__ the sample so that it lasts exactly 8 beats as well.

    ![screenshot](images/dj-sample-stretch.png)

+ Test your code by pressing 'Run' again -- __you don't need to stop and restart the music__! You should now hear that your sample plays in time with your drum beat.

    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload>
      <source src="sounds/beat-fixed.mp3" type="audio/mpeg">
    Your browser does not support the <code>audio</code> element.
    </audio>
    </div>



