---
title: "godot productivity tips"
date: 2018-08-30T17:41:57-03:00
draft: false
author: "Guilherme Oliveira"
twitter: "datOliveira"
type: "tutorial"
---

When developing games, time is one of your more important resources. Having ways to reduce the time it takes to get tasks done are always welcome - specially if said tasks are boring. In this tutorial, we'll present you with X tips on how to increase your productivity with the Godot Engine. Some of them are simple but should definitely help who is just getting started with the engine.

**1. Switch between workspaces**

Found yourself fiddling with your game viewport and coming back to code and vice-versa? You can easily switch between them using the F keys of your keyboard. 

- F1 is used for the 2D Workspace
- F2 for the 3D Workspace
- F3 for the Script Workspace 
- F4 for the AssetLibrary.

**2. Fullscreen workspace**

At times you'll know that you'll have to focus on a certain task for a bigger period of time in the same workspace. For this reason, it's useful to have it in fullscreen so you can focus on what you're doing and have more space to see everything. You can activate the fullscreen mode by pressing `control + shift + F11`.

**3. Hide scripts panel**

If you're working in a single script file and you know you won't switch to another one any time soon, it's a good idea to hide the scripts panel to give yourself some room. Note that you can also use this when in fullscreen mode. Simply press `control + \` and the scripts panel will disappear.

**4. Documentation inside the engine**

Godot's documentation is awesome. The best part is, you don't have to leave the engine to access it. Whenever you feel like taking a look at it, there are a few methods to access it. Click on either:

- Classes
- Search Help

![Classes and Search Help](/images/2018-08-30-godot-productivity-tips/online-classes-search.png)

Or look up for the documentation directly from code:

![Lookup Symbol](/images/2018-08-30-godot-productivity-tips/lookup-symbol.png)

**5. Switch between scripts**

It's not uncommon to switch lots of time between a few scripts when implementing a new functionality or trying to spot a bug in your code. The problem with that is that having to find your script in the scripts panel usually takes a few seconds, and having to move your hand from the keyboard to the mouse isn't always optimal. To avoid doing so, you can use `alt + left arrow`  and  `alt + right arrow` to "move" between the scripts that you have openned recently. 

**6. Folding Lines**

After you worked on a function and you know you won't be messing with it any time soon, folding it can save you space and make your code more readable. To so, go to the line where the function is defined and press `alt+F`.

You'll go from this:

![Unfolded Line](/images/2018-08-30-godot-productivity-tips/unfolded-line.png)

To this:

![Folded Line](/images/2018-08-30-godot-productivity-tips/folded-line.png)

**7. Path to resources**

Suppose you have the following piece of code:


{{< highlight gdscript "linenos=table,linenostart=1" >}}

var Bullet = preload('res://player/projectiles/Bullet.tscn')

func _shoot():
    var new_bullet = Bullet.instance()
    ...

{{< / highlight >}}


Having to type the whole path to the `Bullet` scene can be tedious and time consuming. To save time, simply drag the desired asset from the asset panel to your script and Godot will add the correct path to the code, like so:

Drag the asset to your script:

![Asset Path](/images/2018-08-30-godot-productivity-tips/asset-path.png)

And release your mouse button:

![Asset Path Complete](/images/2018-08-30-godot-productivity-tips/asset-path-complete.png)


Hopefully these tips will help you improve your productivity in Godot! If you have any other tips, let us know on one of our social medias! :)
