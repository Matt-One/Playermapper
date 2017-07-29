<h1>Playermapper</h1>
<H2>Visual WoW Map for Trinitycore - [IN DEVELOPMENT]</H2>
High detailed view of players live location in the WoW world that can be integrated to any web server site with a Google map style of functionality.
<br>
<br>
> Please note: This is a current work in progress. If you want to contribute to the project please contact me via these options or fork this repo, make your fix and submit a P.R.  :-)

<ul>
<li>IRC [~cellyson@Rizon-8476EC9E.hfc.comcastbusiness.net]</li>
<li>Discord chat: @CDawg [#8963]</li>
<li><a href="https://community.trinitycore.org/messenger/compose/?to=11159">Trinitycore message</a></li>
</ul>
<br>

3.3.5a Video Demo
[![335a Demo](https://github.com/CDawg/Playermapper/blob/master/demo/335a_vid.jpg)](https://youtu.be/BMf5aOFGuiE)

> Please do NOT fill out a github issue saying that a feature is broken without checking this list first! I will only help those that have cloned the repo and using the latest commit. This project is continually evolving with improvements made almost weekly. If you are not using the latest commit, you will not get help.

<h3>Tasklist</h3>
<b>Completed Maps:</b>
<br>
☑ Azeroth
<br>
☑ Outland
<br>
☑ Northrend
<br>
☐ Cataclysm: new Azeroth/Deepholm
<br>
☐ MoP: Pandaria
<br>
☐ Wod: Draenor
<br>
☐ Legion: Broken Isles
<br>
<br>
<b>Completed Features:</b>
<br>
☑ Map zoom in/out
<br>
☑ Map dragging (Google Map style navigation)
<br>
☑ Minimap
<br>
☑ Navigation for older browsers
<br>
☑ Multi Realm support
<br>
☑ Player Search
<br>
☐ LIVE player positioning (optional will need core patch)
<br>
☐ Zone search
<br>
☐ Zone boundaries
<br>
☐ Zone detail identification
<br>
☐ add GM visibility [enable/disable] feature
<br>
☐ Instance Identification
<br>
☐ Player group feature (who is grouped in world)
<br>
<br>
<b>WoW Platform Support:</b>
<br>
☑ TrinityCore
<br>
☐ Mangos
<br>
<br>
<b>Misc:</b>
<br>
☐
<br>

<h2>Installation & Requirements - [Difficulty level : Medium to Advanced]</h2>

> Please note: If you are inexperienced on running a web or database server please read how to set one up, I will NOT help you set up/troubleshoot server issues.

<h3>Linux requirements</h3>
<ul>
<li>Apache 2.0+ or Nginx 1.12+</li>
<ul><li>Apache Rewrite Module (Optional)</li></ul>
<li>PhP 5.3.5+</li>
<li>php-mysql 5.3+</li>
<li>MySQL 5.5+/MariaDB</li>
</ul>
<br>

> Please note: This environment was set up using Linux OS, so I did my best to relay what you need in order to run this on your Windows web machine. If you have never ran a web machine on Windows, I would recommend starting with Apache for Windows. I will NOT help you set up your web server.

<h3>Windows requirements</h3>
Windows 7+
<ul>
<li>Apache - https://httpd.apache.org/download.cgi</li>
<li>PhP 5+ - http://windows.php.net/</li>
<li>MySQL 5.5+ or MariaDB 10.2+</li>
<li>Git Extensions</li>
</ul>
<br>

> I would NOT recommend to download as a zip, CLONE the repo from github to attach the latest commit revision. I will NOT help you if you are not using the latest commit.

<h2>Setup Instructions</h2>
1. git clone to your web directory
<br>
2. Rename the config.php.dist to config.php (This file is not accessible to the public)
<br>
3. change the settings within config.php
<br>
4.
