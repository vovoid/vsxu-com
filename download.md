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
              Current Version: {{ site.current_version }} Released {{ site.current_version_date }} 
              System Requirements: Windows 10 64-bit, Nvidia or AMD GPU
            </p>
            <span id="before_download"></span>

            <ul class="actions horizontal">
                <li><a href="#before_download" class="button" 
                onClick="
                    document.getElementById('download_player').style.display = 'block'; 
                "
                >VSXu Player</a></li>
                <li><a href="#before_download" class="button" 
                onClick="
                    document.getElementById('download_windows').style.display = 'block'; 
                "
                >VSXu Artiste</a></li>
            </ul>
        
            <p id="before_download_buttons">&nbsp;</p>

            <p id="download_player" style="display:none">
                <span class="icon fa-windows"></span>
                VSXu Player is now available through Steam.<br/>
                This has a number of benefits for you - including automatic updates, more visuals and new features.<br/>   
                <a href="https://store.steampowered.com/app/981590/VSXu_Player/" target="_blank">VSXu Player on Steam</a><br/>
            </p>
            
            <p id="download_artiste" style="display:none">
                <span class="icon fa-windows"></span>
                You can download the previous version of VSXu Artiste here:  
                <a href="#" target="_blank">VSXu Artiste v0.6.3 for Windows 64-bit</a><br/>
                <br/>
                Please also check out the Steam version of VSXu Player where you can get additional DLC for player:<br>
                <a href="https://store.steampowered.com/app/981590/VSXu_Player/" target="_blank">VSXu Player on Steam</a><br/>
            </p>
            
            <p id="before_support">&nbsp;</p>
            <p>&nbsp;</p>

            <div style="display:none" id="paypal">
                <h2>Thank you for downloading!</h2>
                <h3>We invite you to:</h3>
                <table>
                <tr>
                <td style="width:50%;">
                    <h4><a href="https://store.steampowered.com/app/929630/Luna_Sky_RDX/">Check out our game</a>:</h4>
                    <iframe src="https://store.steampowered.com/widget/929630/" frameborder="0" width="646" height="190"></iframe>
                </td>
                <td style="width:50%">
                    <h4>Like us on Facebook!</h4>
                    <iframe src="http://www.facebook.com/plugins/like.php?href=https%3A%2F%2Fwww.facebook.com%2Fpages%2FVovoid-VSXu%2F129044247131992&amp;send=false&amp;layout=standard&amp;width=450&amp;show_faces=false&amp;action=like&amp;colorscheme=dark&amp;font&amp;height=35" style="border:none;height:30px;width:100%"></iframe>
                    <br>
                    <iframe id="twitter-widget-0" scrolling="no" frameborder="0" allowtransparency="true" class="twitter-follow-button twitter-follow-button-rendered" title="Twitter Follow Button" src="http://platform.twitter.com/widgets/follow_button.89bd237a86eeb0e8b1de842a4b88b09b.en.html#dnt=false&amp;id=twitter-widget-0&amp;lang=en&amp;screen_name=VovoidMediaTech&amp;show_count=true&amp;show_screen_name=true&amp;size=l&amp;time=1490522543370" style="position: static; visibility: visible; width: 300px; height: 28px;" data-screen-name="VovoidMediaTech"></iframe>
                    <br>
                    <a href="http://vovoid.info">Join us on Discord</a>
                 </td>
                 </tr>
                 </table>
            </div>
        </div>
    </section>
</div>
