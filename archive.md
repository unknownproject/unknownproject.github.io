---
layout: default
permalink: /archive.html
---
**My old articles right from the old blog [2016-2017] ect**

<a href="https://unknownproject.github.io/archive/OldBlog.7z"><b><u>[Blog - Full Archive - PDF + PNG IMAGES]</u></b></a>

<ul class="nav nav-tabs nav-justified panel panel-default panel-transparent" id="PageTabs" role="tablist">
	<li class="nav-item active">
        <a class="nav-link active" href="#blg" data-toggle="tab">[ BLOG ]</a>
    </li>
</ul>
<div class="tab-content">
      <div class="tab-pane active" id="blg">
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
		  <h1>Performance in the game sucks. But why ?</h1>
          <p>The game is actively using only one (main) software thread that was optimized to execute each frame for 33 ms. AI/Physics and other CPU operations are less or more intensive than graphics API calls. 3 more threads - LoadingScreen/StdAudioEngine/AsyncDiscAccess are executed when needed. In short - we're facing an old multithreading model. 
		  Windows is not a realtime OS. And its scheduler is executing and suspending threads to share CPU resources efficiently between all running applications. The real solution is to make the multithreading model more adaptive. But how - that is the question. </p>
		  <h1>===========================</h1>
		  <h1>Hotkeys don't work.</h1>
          <p>Most of these hotkeys have debugging purpose to force/activate special in-game variables or triggers. A bunch of them were bound to the fps counter display on purpose. </p>
		  <h1>===========================</h1>
	  </div>
	</div>
</div>

**[[ Back ]](./)**