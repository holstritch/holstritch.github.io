---
layout: page
title: Warped Kart Racers
description: The ultimate kart racing game featuring the stars of American Dad!, Family Guy, King of the Hill and Solar Opposites!
img: assets/img/WarpedKeyArt.jpg
importance: 1
category: Game Credits
related_publications: false
---

<strong>Devices: iphone, ipad, Apple TV, Mac
<br>
Engine: Unity</strong>
<br>

Warped Kart Racers is an Apple Arcade Exclusive released on iOS, Mac and Apple TV with support for controller, keyboard and touch controls.

Whilst working on this project it became Apple Arcade's longest supported title and sat within the Top 10 for 18 months!
<br>
<h4>During my time on this project, I developed two new game modes where I implemented a new feature, fixed bugs, added new functionality, UI and VFX.</h4>
<br>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Customisation.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Korvo.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Hank.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Image captions: three images showing car customisation, kart racing and the match leaderboard.
</div>

<h2>Overcharged</h2>
<br>
In Overcharged mode the player gains charge by drifting, this charge value affects the speed of their kart and can also be used as a quick speed boost.

This was a really exciting game mode for me as I worked closely with the designer to prototype a drifting to charge mechanic, which felt great and made it into the release!
<br>

<ul>
  <li>drift to charge mechanic</li>
  <li>UI & VFX for charge bar & charge button</li>
  <li>dynamic UI to show the game mode button depending on the weekly schedule</li>
  <li>percentage tag in league mode which calculates the players weekly league score</li>
  <li>bug fixes for collision issues, unresponsive drifting etc</li>

</ul>

<h4>New Feature: Drift to Charge!</h4>
<br>
I implemented the drift to charge mechanic which increases the charge value based on time spent drifting. This charge value can only decrease when it's spent by the player for a quick boost in speed and the value also directly impacts the karts current speed. As items were removed in this game mode, we were able to reuse the button for the input which spends charge and triggers the speed boost. Alongside prototyping and implementing this mechanic, there was a lot of polish with UI and VFX to make it feel more intuitive to the player. Such as, the charge bar which flashes red when low on charge and changes from green to blue to indicate full charge.  
<br>
<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/overcharged1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/overcharged2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Image captions: in the first image the player has low charge, in the second the player is boosting while at full charge.
</div>

<h2>Crowned</h2>
<br>
In Crowned mode the player aims to steal the crown from other players. They gain points by hitting the player with the crown and by holding onto the crown themselves.

<ul>
  <li>adding 'crowned' player onto the minimap</li>
  <li>updates to localisation</li>
  <li>new achievements on the app store</li>
  <li>bugs fixes for the leaderboard & achievement board, UI scoring, collision issues etc</li>
</ul>
<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/crowned.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Image caption: another character has just stolen the crown.
</div>


