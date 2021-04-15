---
layout: page
title: Download
permalink: /download
main_menu: yes
---
<div id="main" class="alt">
    <section id="one">
        <div class="inner">
            <header class="major">
                <h1>Download VSXu</h1>
            </header>
            
            <span id="initial_choice">
                <p>
                  Current Version: {{ site.current_version }} Released {{ site.current_version_date }} <br/>
                  System Requirements: Windows 10 64-bit, Nvidia or AMD GPU<br/>
                  <ul class="actions horizontal">
                      <li><a href="#" class="button" 
                      onClick="
                          document.getElementById('download_player').style.display = 'block'; 
                          document.getElementById('download_artiste').style.display = 'none';
                          document.getElementById('initial_choice').style.display = 'none';
                      "
                      >VSXu Player</a></li>
                  </ul>
                  <i>If you specifically want to create visuals, get Artiste:</i><br/>
                  <br/>
                  <ul class="actions horizontal">
                      <li><a href="#" class="button" 
                      onClick="
                          document.getElementById('download_artiste').style.display = 'block'; 
                          document.getElementById('download_player').style.display = 'none';
                          document.getElementById('initial_choice').style.display = 'none';
                      "
                      >VSXu Artiste</a></li>
                  </ul>
                </p>
            </span>
                        
            <p id="download_player" style="display:none">
                <span class="icon fa-windows"></span> <a 
                  href="https://store.steampowered.com/app/981590/VSXu_Player/?utm_source=vsxu_com&campaign=download_page" target="_blank"
                  onClick="analytics.trackDownloadEvent('steam download');"
              >Download VSXu Player on Steam</a><br/>
                <br/>
                <i>VSXu Player is now available through Steam!</i><br/>
                <i>This has a number of benefits for you - including automatic updates, more visuals and new features.</i><br/>
                <br/>
            </p>
            
            <p id="download_artiste" style="display:none">
                <span class="icon fa-windows"></span> <a href="https://github.com/vovoid/vsxu/releases/download/v0.6.3/VSXu_0.6.3_amd64.exe" target="_blank"
                onClick="analytics.trackDownloadEvent('artiste download');"
                >VSXu Artiste v0.6.3 for Windows 64-bit</a><br/>
                <i>This is the previous version of VSXu Artiste. VSXu Artiste will be released on Steam in the future but as of now, it's a regular download.</i><br/>
                <br/>
                <b>Also check out the Steam version of VSXu Player</b> where you can get additional DLC for player:<br/>
                <a href="https://store.steampowered.com/app/981590/VSXu_Player/" target="_blank">VSXu Player on Steam</a><br/>
            </p>
        </div>
    </section>
</div>
