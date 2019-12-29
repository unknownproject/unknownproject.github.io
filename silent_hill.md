---
layout: default
permalink: /silent_hill.html
---

**Current version : 2.03 [Public] / 3.00 [Private].**
<ul class="nav nav-tabs nav-justified panel panel-default panel-transparent" id="PageTabs" role="tablist">
	<li class="nav-item active">
        <a class="nav-link active" href="#spc" data-toggle="tab">[ Special FAQ ]</a>
    </li>
    <li class="nav-item active">
        <a class="nav-link active" href="#faq" data-toggle="tab">[ FAQ ]</a>
    </li>
</ul>	

![Screenshot](https://raw.githubusercontent.com/unknownproject/unknownproject.github.io/master/assets/images/SHH.png)
**[[ ReadMe ]](https://raw.githubusercontent.com/unknownproject/Silent_Hill_Homecoming/master/Patches/ReadMe.txt)**
**[[ ChangeLog ]](https://raw.githubusercontent.com/unknownproject/Silent_Hill_Homecoming/master/Patches/ChangeLog.txt)**
**[[ HotKeys ]](https://raw.githubusercontent.com/unknownproject/Silent_Hill_Homecoming/master/Patches/HotKeys.txt)**
**[[ Stable Release ]](https://github.com/unknownproject/Silent_Hill_Homecoming/raw/master/Patches/Patch_2.0/Patch2.0_upd3_AiO_pt1.exe)**
**[[ Beta WIP ]](https://github.com/unknownproject/Silent_Hill_Homecoming/raw/master/Patches/Patch_2.0/BETA/Patch2.0_upd3_AiO_pt2_beta.exe)**

**EnemyHealth [v2.03] or later.**

|         Name         |   Type  | Normal mode | Hard mode |
|:---------------------|:--------|:------------|:----------|
| Sepulcher/FleshSack  | Monster |    200/55   |    300/85 |
| Scarlet              | Monster |    666      |    1000   |
| Asphyxia             | Monster |    300      |    500    |
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
		  <h1>I'm stupid and already installed your patch but I have 30 fps.</h1>
          <p>Open vars_pc.cfg and change 'fpsLimit' and 'maxFPSLimit' to 60/120/144/300.</p>
		  <h1>===========================</h1>
		  <h1>I'm stupid and don't want to read your shitty txts. Tell me how to set the game to use my native language.</h1>
          <p>Open default_pc.cfg and change 'language=english' to german/french/italian/spanish or czech/polish/russian [extra brain cells required].</p>
		  <h1>===========================</h1>
		  <h1>I'm stupid and don't want to read your shitty txts. Tell me how to set the game to use my preferred button prompts.</h1>
          <p>Realtime switch [Num+ and Num-] works for everything except dialogue trees. Open default_pc.cfg and change 'resmgrload = assets_pc_b.xml' to ASSETS_PS3_B.xml [PS3]/assets_xenon_b.xml [X360].</p>
		  <h1>===========================</h1>
		  <h1>My old controller doesn't work well with the game. What's wrong ?</h1>
          <p>This is the x-input era game so it's 100% compatible with Xbox360 gamepads only. Direct input controller must be configured via Xbox 360 Joystick Emulator software. Then Copy x360ce.ini and xinput1_3.dll to the '/Bin' folder.</p>
		  <h1>===========================</h1>
		  <h1>Who the fuck are you to call me "I'm stupid".</h1>
          <p>Fuck off, kid. Self-education is not for you.</p>
		  <h1>===========================</h1>
	  </div>
	</div>
</div>
<div class="tab-content">
      <div class="tab-pane active" id="faq">
        <div class="wrapper">
		  <h1>===========================</h1>
		  <h1>I have a black screen at startup, what can I do?</h1>
          <p>Delete vars_pc.cfg then restart the game. If it doesn't work, disable any compatibility settings you have applied on the game. If still doesn't work, remove any d3d wrapper that hasn't been tested in full game save from start to finish.</p>
		  Also reset your GPU settings to application controlled, do not override any settings. Adaptive V-Sync causes some bugs/glitches.
		  <h1>===========================</h1>
		  <h1>Game crashes when ALT+TABbing.</h1>
          <p>Game will always crash when switching to another app which is what ALT + TAB does.ANY 32 BIT application will crash if you have less than 30% of RAM or love to alt-tab a lot and have a working browser opened.</p>
		  <h1>===========================</h1>
		  <h1>*Game crashes at startup.</h1>
          <p>Game engine is unstable, launch the game up, while it does but don't click anything or do anything till the game loads into main menu.</p>
		  <h1>===========================</h1>
		  <h1>*Game doesn't checkpoint anymore or autosave at certain points of the game!</h1>
          <p>The latest update of 08/09/18 has disabled autosave/checkpoint this is because it caused the game to freeze a long period of time.</p>
		  <h1>===========================</h1>
		  <h1>Game crashes when I go to desktop and go to an app or program.</h1>
          <p>This happens when you switch to apps, the game cannot recover after it has been unfocused by going into desktop and being auto minimized.</p>
		  <h1>===========================</h1>
		  <h1>*QTE not responding to the buttons that I'm pressing.</h1>
          <p>The game engine fails to recognise input button when being rapidly pressed. And button counter also going down between delays. For some reason there are button-breaking sequences when you have to press the button at least 100 times.</p>
		  <h1>===========================</h1>
		  <h2>Partially Fixed in v.203</h2>
		  <h1>===========================</h1>
	  </div>
	</div>
</div>
**[[ Back ]](./)**