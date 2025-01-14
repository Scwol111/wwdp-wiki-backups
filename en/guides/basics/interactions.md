---
title: Untitled Page
description: 
published: true
date: 2024-10-20T12:12:25.719Z
tags: 
editor: markdown
dateCreated: 2024-09-10T19:08:41.051Z
---

<div><left>
  <div class="maincontainer">
    <h1 id="interactions" class="toc-header"><a class="toc-anchor" href="#interactions">¶</a> Interactions</h1>
    <button type="button" class="collapsible"><h2 id="standard-interactions" class="toc-header"><a class="toc-anchor" href="#standard-interactions">¶</a> Standard Interactions</h2></button>
    <div class="content">
      <p>A left-click is the most common way to interact with objects. The specific interaction depends on the item currently held and the active combat stance. Some interactions require empty hands, while others need specific items.</p>
      <p>For example:</p>
      <ul>
        <li>Click on an item to pick it up.</li>
        <li>Click on a dispenser with a glass in hand to insert the glass.</li>
        <li>Click on a vending machine with a wrench to disable it.</li>
        <li>Click on yourself with food in hand to eat it. Clicking on others will make them eat the food in your hand.</li>
        <li>Click with active combat mode on another item or entity to attack it.</li>
      </ul>
      <p>If no other interaction occurs, a left-click will attempt to "activate" the object.</p>
    </div>
    <button type="button" class="collapsible"><h2 id="melee-combat" class="toc-header"><a class="toc-anchor" href="#melee-combat">¶</a> Melee Combat</h2></button>
    <div class="content">
      <p>Melee combat is activated by clicking <img src="/guides/basics/harmoff.png" style="vertical-align: middle"> on the hotbar with the left mouse button or simply pressing <kbd>1</kbd>.</p>
      <p>Melee combat uses two buttons:</p>
      <ul>
        <li><kbd>LMB</kbd> - heavy attack, suitable for single targets. You must aim directly at the target, not near it;</li>
        <li><kbd>RMB</kbd> - regular attack, suitable for hitting multiple targets. It has half the damage over the area in front, 1.2 times slower attack speed, and half a tile longer range than a heavy attack, and also consumes 8 stamina. You do not need to aim directly at the target.</li>
      </ul>
    </div>
    <button type="button" class="collapsible"><h2 id="activation-interactions-e" class="toc-header"><a class="toc-anchor" href="#activation-interactions-e">¶</a> Activation Interactions (<kbd>E</kbd>)</h2></button>
    <div class="content">
      <p>These are interactions performed regardless of what item is in your hand.</p>
      <p>They allow you to:</p>
      <ul>
        <li>Open and close doors, lockers, drawers, etc.</li>
        <li>Open the interface of backpacks, computers, etc.</li>
        <li>Switch entity modes (magnetic boots, welding tools, T-ray scanners, etc.).</li>
      </ul>
      <p>As mentioned earlier, if a left-click does not trigger a specific interaction, an activation interaction will occur instead. So, if you left-click on a door with an empty hand, it will open. But if you're holding a welding tool, you'll start sealing it. In that case, you can open the door with <kbd>E</kbd> instead of switching hands and pressing <kbd>LMB</kbd>.</p>
    </div>
    <button type="button" class="collapsible"><h2 id="alternative-interactions-altlmb" class="toc-header"><a class="toc-anchor" href="#alternative-interactions-altlmb">¶</a> Alternative Interactions (<kbd>Alt</kbd>+<kbd>LMB</kbd>)</h2></button>
    <div class="content">
      <p><kbd>Alt</kbd>+<kbd>LMB</kbd> for alternative interaction.<br>
        Common uses include:</p>
      <ul>
        <li>Extract an item (ID card from PDA, magazine from a gun).</li>
        <li>Split a stack in half.</li>
        <li>Lock a drawer with a code lock.</li>
        <li>Climb onto a table.</li>
      </ul>
    </div>
    <button type="button" class="collapsible"><h2 id="in-hand-use-z" class="toc-header"><a class="toc-anchor" href="#in-hand-use-z">¶</a> In-hand Use (<kbd>Z</kbd>)</h2></button>
    <div class="content">
      <p>Some interactions require you to use an item in your active hand. This can be done by clicking on the item in hand or simply pressing <kbd>Z</kbd>.<br>
        Used for:</p>
      <ul>
        <li>Opening cans of <a href="/guides/beverages" class="is-internal-link is-valid-page">drinks</a>.</li>
        <li>Eating <a href="/guides/food" class="is-internal-link is-valid-page">food</a>.</li>
        <li>Grabbing a fire axe with both hands.</li>
        <li>Opening/closing a weapon's bolt.</li>
      </ul>
      <p>As you may notice, <kbd>Alt</kbd>+<kbd>Z</kbd> performs the same function as <kbd>Alt</kbd>+<kbd>LMB</kbd> on the item in your active hand.</p>
    </div>
    <button type="button" class="collapsible"><h2 id="item-handing-f" class="toc-header"><a class="toc-anchor" href="#item-handing-f">¶</a> Item Handing (<kbd>F</kbd>)</h2></button>
    <div class="content">
      <p>Press <kbd>F</kbd>, then <kbd>LMB</kbd> on an entity to offer it an item.<br>
        To take an item offered to you, click the icon that appears on the right.<br>
    </p></div>
    <button type="button" class="collapsible"><h2 id="dragging" class="toc-header"><a class="toc-anchor" href="#dragging">¶</a> Dragging</h2></button>
    <div class="content">
      <p><kbd>Ctrl</kbd>+<kbd>LMB</kbd> on an entity to drag it.<br>
        <kbd>Ctrl</kbd>+<kbd>RMB</kbd> on a tile while dragging something will move the item to that tile.<br>
        You can stop dragging by:</p>
      <ul>
        <li><kbd>Ctrl</kbd>+<kbd>LMB</kbd> on the entity again.</li>
        <li>Clicking the dragging icon on the right side of the screen.</li>
        <li>Pressing <kbd>H</kbd>.</li>
      </ul>
    </div>
    <button type="button" class="collapsible"><h2 id="moving-large-objects" class="toc-header"><a class="toc-anchor" href="#moving-large-objects">¶</a> Moving Large Objects</h2></button>
    <div class="content">
      <p>There are items you need to interact with by dragging them to yourself or yourself to the items using <kbd>LMB</kbd>. For example:</p>
      <ul>
        <li>Drag yourself onto a table to climb it, or RMB on the table.</li>
        <li>Drag another player onto yourself to view their inventory.</li>
        <li>Drag another player onto a chair to seat them.</li>
        <li>Drag another player into a <a href="/guides/medicalequipment" class="is-internal-link is-valid-page">med scanner</a> to place them inside.</li>
      </ul>
    </div>
    <button type="button" class="collapsible"><h2 id="rmb-menu" class="toc-header"><a class="toc-anchor" href="#rmb-menu">¶</a> RMB Menu</h2></button>
    <div class="content">
      <p><kbd>RMB</kbd> on an item in the game opens a menu. This menu facilitates interaction with a specific item when it is hard to reach (e.g., a dump in a garbage chute). Interactions performed this way are the same as usual. This means you can use <kbd>Ctrl</kbd>+<kbd>LMB</kbd> or <kbd>E</kbd> combinations.</p>
      <p>There is no difference if you RMB an item in your inventory.</p>
    </div>
<button type="button" class="collapsible">
  <h2 id="interaction-menu-right-click-on-item-in-inventory-or-item-menu" class="toc-header">
    <a class="toc-anchor" href="#interaction-menu-right-click-on-item-in-inventory-or-item-menu">¶</a>
    Interaction Menu (<kbd>Right Click</kbd> on an item in the inventory or in the item menu)
  </h2>
</button>
<div class="content">
  <p>This menu displays a list of various actions you can perform with an item. The available actions usually depend on the selected object, the currently held item, and the distance from the player to the item.</p>
  <p>Many of the listed interactions can be performed using other bound keys, but some are exclusive to the interaction menu. The menu is useful when you're unsure about what interactions an object has. If you're unsure how to do something, it's worth checking the interaction menu.</p>
</div>
<button type="button" class="collapsible">
  <h2 id="tips" class="toc-header">
    <a class="toc-anchor" href="#tips">¶</a>
    Tips
  </h2>
</button>
<div class="content">
  <p>Interactions in the menu are divided into 4 groups:</p>
  <ul>
    <li>Actions are highlighted in bold + italics. These usually correspond to actions that can be triggered by clicking <kbd>Left Click</kbd>.</li>
    <li>Activation actions are highlighted in bold. They usually correspond to actions that can be initiated using <kbd>E</kbd>.</li>
    <li>Alternative interaction verbs are highlighted in italics. They ALWAYS correspond to interactions triggered by pressing <kbd>Alt</kbd>.</li>
    <li>Finally, there are general interactions, which have regular text.</li>
  </ul>
  <p>Within these groups, each action is sorted by priority. Generally, if an item is associated with more than one action, the action that appears first in this list should be performed first. For example, <kbd>Right Click</kbd> on a PDA will first extract the ID card, then the pen. If you want to extract the pen without removing the ID card, you need to use the action menu or the PDA’s user interface.</p>
</div>
<button type="button" class="collapsible">
  <h2 id="attention" class="toc-header">
    <a class="toc-anchor" href="#attention">¶</a>
    Attention
  </h2>
</button>
<div class="content">
  <p>Unfortunately, not all items have corresponding actions in the menu. For example, looking at the example of the PDA, you might think that pressing E will turn on the PDA’s flashlight. While this is true for the flashlight in general, the PDA will instead open the user interface.</p>
  <p>The only exception to this rule is <kbd>Alt</kbd> + <kbd>Left Click</kbd> actions. All <kbd>Alt</kbd> click interactions are displayed in the action menu, and the one performed by <kbd>Alt</kbd> click on an object will always appear first in the menu.</p>
</div>
<button type="button" class="collapsible">
  <h2 id="alerts" class="toc-header">
    <a class="toc-anchor" href="#alerts">¶</a>
    Alerts
  </h2>
</button>
<div class="content">
  <p>Alerts are informational icons that appear on the right side of the screen. Hovering over them may (sometimes) provide useful information. Some of these icons will also trigger an interaction if you click on them:</p>
  <ul>
    <li>Clicking the handcuff icon will attempt to break free from them.</li>
    <li>Clicking the "strapped" button will unstrap you from the chair.</li>
    <li>Clicking the dragging item alert will stop dragging that item.</li>
  </ul>
</div>
<button type="button" class="collapsible">
  <h2 id="action-bar" class="toc-header">
    <a class="toc-anchor" href="#action-bar">¶</a>
    Action Bar
  </h2>
</button>
<div class="content">
  <p>Can be bound to the numbers <kbd>1</kbd> - <kbd>0</kbd>.</p>
  <p>Some actions are available from the start, while others require specific items or equipment. Examples of actions include:</p>
  <ul>
    <li>Toggle Combat Mode ON/OFF.</li>
    <li>Toggle Breathing Tank ON/OFF.</li>
    <li>Toggle Flashlight ON/OFF.</li>
  </ul>
</div>
<button type="button" class="collapsible">
  <h2 id="top-screen-buttons" class="toc-header">
    <a class="toc-anchor" href="#top-screen-buttons">¶</a>
    Top Screen Buttons
  </h2>
</button>
<div class="content">
  <p>There are various buttons you can use to toggle different UI elements. All of these can also be used by pressing the buttons that appear in the top right corner of the screen. These include:</p>
  <ul>
    <li><kbd>Esc</kbd> Opens the menu.</li>
    <li><kbd>C</kbd> Opens the character menu. If you are a traitor, your objectives will be listed here.</li>
    <li><kbd>I</kbd> Shows the items you are currently wearing.</li>
    <li><kbd>G</kbd> Opens the crafting menu. Used for creating items and building walls.</li>
    <li><kbd>K</kbd> Opens the action viewer, which can be used to customize the action bar.</li>
    <li><kbd>F5</kbd> Opens the item spawn menu (used only in "Sandbox" mode).</li>
    <li><kbd>F7</kbd> Opens the admin panel (available only to admins).</li>
  </ul>
</div>
<button type="button" class="collapsible">
  <h2 id="other-controls" class="toc-header">
    <a class="toc-anchor" href="#other-controls">¶</a>
    Other Controls
  </h2>
</button>
<div class="content">
  <ul>
    <li><kbd>X</kbd> - Switches the active hand.</li>
    <li><kbd>Shift</kbd> + <kbd>Left Click</kbd> - Examine an entity.</li>
    <li><kbd>Shift</kbd> + <kbd>Middle Click</kbd> - Point at an entity.</li>
    <li><kbd>Q</kbd> - Drop the item held in the active hand.</li>
    <li><kbd>Ctrl</kbd> + <kbd>Q</kbd> - Throw the item held in the active hand.</li>
  </ul>
</div>
<button type="button" class="collapsible">
  <h2 id="known-issues" class="toc-header">
    <a class="toc-anchor" href="#known-issues">¶</a>
    Known Issues
  </h2>
</button>
<div class="content">
  <h3 id="interaction-duplication" class="toc-header">
    <a class="toc-anchor" href="#interaction-duplication">¶</a>
    Interaction Duplication
  </h3>
  <p>Some interactions can be performed in multiple ways. For example, you can eat food by activating it in your hands with <kbd>Z</kbd> or by clicking on yourself with the food in hand. Similarly, you can climb onto a table by dragging yourself onto it or using <kbd>Alt</kbd> + <kbd>Left Click</kbd>.</p>
  <p>This is done for convenience or to make some interactions more intuitive.</p>
  <h3 id="inconsistency" class="toc-header">
    <a class="toc-anchor" href="#inconsistency">¶</a>
    Inconsistency
  </h3>
  <p>Some interactions with similar items are carried out in different ways. For example, switches currently cannot be toggled with <kbd>E</kbd>; instead, you need to click on them with an empty hand, even though they should work like doors. This also applies to some other toggleable items.</p>
  <h3 id="prioritization" class="toc-header">
    <a class="toc-anchor" href="#prioritization">¶</a>
    Prioritization
  </h3>
  <p>In some cases, interactions have incorrect prioritization, which can interfere with performing certain actions. For example, using a wrench on a trash bin to unscrew it will result in the wrench falling into the trash bin.</p>
  <p>This can often be circumvented by using the <kbd>Right Click</kbd> menu, though in this case, unfortunately, the corresponding action may not be present in the menu.</p>
    </div>
  </div>  