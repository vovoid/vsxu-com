---
layout: page-inner
title: Documentation - FAQ
permalink: /documentation/faq
---
<div id="main" class="alt">
    <section id="one">
        <div class="inner">
            <ul class="actions horizontal">
                <li>
                    <a href="/documentation" class="button">
                        Documentation
                    </a>
                </li>
                <li>|</li>
                <li>
                    <a href="/documentation/faq" class="button special">
                        FAQ
                    </a>
                </li>
                <li>
                    <a href="/documentation/vsxu-live" class="button">
                        Video - VSXu Live
                    </a>
                </li>
                <li>
                    <a href="/documentation/changelog" class="button">
                        Changelog
                    </a>
                </li>
            </ul>
            
            <header class="major">
                <h1>
                    Frequently Asked Questions about VSXu
                </h1>
            </header>
            <p>
            Click on a question to view the answer.
            </p>
              
            <h2 onclick="$('.question_fullscreen').show()" style="cursor:pointer">
              Q: How do I run in fullscreen mode?
            </h2>
            <div class="question_fullscreen" style="padding-left:20px; display:none">
                <p>
                Unless you remapped your key, it should be "F" on the keyboard.
                </p>
            </div>
            
            <hr>
            
            <h2 onclick="$('.question_audio').show()" style="cursor:pointer">
              Q: VSXu is not reacting to sound!
            </h2>
            <div class="question_audio" style="padding-left:20px; display:none">
              <p>
                  VSXu uses a feature in Windows called "WASAPI". Some software does not play well with this.<br>
                  If you have any audio augmenting software from your computer manufacturer or other tools that meddle
                  with the sound we recommend that you uninstall them and try again.
                  Unfortunately some bluetooth hardware has also been known to cause problems. In this case you can try
                  to play back from a different device.
                <br>
            </p>
            </div>
            
     <hr>
              
          <h2 onclick="$('.question_recording').show()" style="cursor:pointer">
              Q: How do I record the output of VSXu?
          </h2>
          <div class="question_recording" style="padding-left:20px; display:none">
              <h2>Streaming</h2>
              <p>
                  Most people use <a href="https://obsproject.com/">OBS</a> for recording and streaming.<br/>
                  Nvidia Shadowplay is also useful.
              </p>
          </div>
      </div>
  </section>
</div>
