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
            <p>
              Current Version: {{ site.current_version }} Released {{ site.current_version_date }} <br/>
              System Requirements: Windows 10 64-bit, Nvidia or AMD GPU<br/>
              <br/>
              <i>If you want to experience visuals, get Player!</i><br/>
              <i>If you want to create visuals, get Artiste.</i>
            </p>
            <span id="before_download"></span>

            <ul class="actions horizontal">
                <li><a href="#before_download" class="button" 
                onClick="
                    document.getElementById('download_player').style.display = 'block'; 
                    document.getElementById('download_artiste').style.display = 'none';
                "
                >VSXu Player</a></li>
                <li><a href="#before_download" class="button" 
                onClick="
                    document.getElementById('download_artiste').style.display = 'block'; 
                    document.getElementById('download_player').style.display = 'none';
                "
                >VSXu Artiste</a></li>
            </ul>
        
            <p id="before_download_buttons">&nbsp;</p>

            <p id="download_player" style="display:none">
                <span class="icon fa-windows"></span> <a href="https://store.steampowered.com/app/981590/VSXu_Player/" target="_blank">Download VSXu Player on Steam</a><br/>
                <i>VSXu Player is now available through Steam.</i><br/>
                <i>This has a number of benefits for you - including automatic updates, more visuals and new features.</i><br/>
                <br/>
            </p>
            
            <p id="download_artiste" style="display:none">
                <span class="icon fa-windows"></span> <a href="#" target="_blank">VSXu Artiste v0.6.3 for Windows 64-bit</a><br/>
                <i>This is the previous version of VSXu Artiste.</i><br/>
                <br/>
                <b>Also check out the Steam version of VSXu Player where you can get additional DLC for player:<br>
                <a href="https://store.steampowered.com/app/981590/VSXu_Player/" target="_blank">VSXu Player on Steam</a><br/>
            </p>
        </div>
    </section>
</div>
