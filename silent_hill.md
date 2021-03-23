---
layout: default
permalink: /silent_hill.html
---
**Current version : 2.50 / 3.0D [Public Beta] / 3.00 [Private]**
<a href="https://github.com/unknownproject/Silent_Hill_Homecoming/raw/master/Patches/Updater/Patch_Updater.zip"><b><u>[Download My Official Updater Utility]</u></b></a>
<ul class="nav nav-tabs nav-justified panel panel-default panel-transparent" id="PageTabs" role="tablist">
	<li class="nav-item active">
        <a class="nav-link active" href="#spc" data-toggle="tab">[ Special FAQ ]</a>
    </li>
    <li class="nav-item active">
        <a class="nav-link active" href="#faq" data-toggle="tab">[ FAQ ]</a>
    </li>
</ul>
![Screenshot](https://raw.githubusercontent.com/unknownproject/Silent_Hill_Homecoming/master/Patches/Updater/Scrnshot.png)
<a href="https://raw.githubusercontent.com/unknownproject/Silent_Hill_Homecoming/master/Patches/ReadMe.txt"><img src="/assets/images/rm.png" width="112" height="36"/></a>
<a href="https://raw.githubusercontent.com/unknownproject/Silent_Hill_Homecoming/master/Patches/ChangeLog.txt"><img src="/assets/images/cl.png" width="112" height="36"/></a>
<a href="https://raw.githubusercontent.com/unknownproject/Silent_Hill_Homecoming/master/Patches/HotKeys.txt"><img src="/assets/images/hk.png" width="112" height="36"/></a>
<a href="https://github.com/unknownproject/Silent_Hill_Homecoming/raw/master/Patches/Patch_2.0/Patch2.0_upd3_AiO_pt1.exe"><img src="/assets/images/or.png" width="112" height="36"/></a>
<a href="https://github.com/unknownproject/Silent_Hill_Homecoming/raw/master/Patches/PreReleases/Patch2.5_PreRelease.exe"><img src="/assets/images/au.png" width="112" height="36"/></a>

**EnemyHealth [v2.03 pt2 -> 2.50].**

|         Name         |   Type  | Normal mode | Hard mode |
|:---------------------|:--------|:------------|:----------|
| Sepulcher/FleshSack  | Monster |    200/55   |    300/85 |
| Scarlet              | Monster |    665      |    1000   |
| Asphyxia             | Monster |    300      |    450    |
| Amnion               | Monster |    510      |    765    |
| Curtis               | Human   |    150      |    225    |

==============================================================
Replacing/overriding of binds_pc_mjs.cfg is not recommended.

This file was configured to fix in-game commands for better mouse/keyboard compatibility.

If you want to customize your binds - use bindcfgs_pc.cfg instead.

Forget about main menu configuration.
==============================================================

<!--<a class="nav-link" href="#faq" data-toggle="tab">**FAQ**</a>-->
<div class="tab-content">
      <div class="tab-pane active" id="spc">
        <div class="wrapper">
		  <h1>===========================</h1>
		  <h1>I already installed your patch but I have 30 fps.</h1>
          <p>Open vars_pc.cfg and change 'fpsLimit' and 'maxFPSLimit' to 60/120/144/300 or whatever you wanted.</p>
		  <h1>===========================</h1>
		  <h1>I don't want to read your txts. Tell me how to set the game to use my native language.</h1>
          <p>Open default_pc.cfg and change 'language=english' to german/french/italian/spanish or czech/polish/russian [extra brain cells required].</p>
		  <h1>===========================</h1>
		  <h1>I don't want to read your txts. Tell me how to set the game to use my preferred button prompts.</h1>
          <p>Realtime switch [Num+ and Num-] works for everything except dialogue trees. Open default_pc.cfg and change 'resmgrload = assets_pc_b.xml' to ASSETS_PS3_B.xml [PS3]/assets_xenon_b.xml [X360].</p>
		  <h1>===========================</h1>
		  <h1>My old controller doesn't work well with the game. What's wrong ?</h1>
          <p>The X-Input era games are 100% compatible with Xbox360 gamepads only. Any DirectInput controller must be configured via Xbox 360 Joystick Emulator (or similar) software. Don't forget to copy x360ce.ini and xinput1_3.dll to the '/Bin' folder.</p>
		  <h1>===========================</h1>
		  <h1>How to mod the game ?</h1>
          <p>My patch features the enhanced resource manager to support mods. Copy your modified 'global.pak' to the "\Engine\extras\" folder. Open default_pc.cfg and delete or comment 'resmgrload = assets_pc_b.xml'. Don't touch any other strings. </p>
		  <h1>===========================</h1>
	  </div>
	</div>
</div>
<div class="tab-content">
      <div class="tab-pane active" id="faq">
        <div class="wrapper">
		  <h2>
		  <p>PAY ATTENTION TO THE <strong><a href="https://raw.githubusercontent.com/unknownproject/Silent_Hill_Homecoming/master/Patches/ChangeLog.txt">[ CHANGELOG ]</a></strong></p>
		  <p>DON'T FORGET TO CHECK THE <strong><a href="https://github.com/unknownproject/Silent_Hill_Homecoming/tree/master/Patches/SteamGuideBackup">[ STEAM GUIDE ]</a></strong></p>
		  </h2> 
		  <h1>===========================</h1>
	  </div>
	</div>
</div>
**[[ Back ]](./)**