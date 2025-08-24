---
title: d20 Dice Roller
description: A d20 diceroller with player save functions.
layout: home
date: 2019-10-02 19:13:21 -0700
---


<div 
	class="diceBox_container" 
	style="width: 100%; aspect-ratio: 4 / 3; background-color: #FFFFFF;">
	<iframe height="100%"  width="100%" src="https://nickogibson.github.io/app/DiceRoller/" title="d20 Dice Roller"></iframe>
</div>

A d20 Dice Roller with player hand saving functions.
[source code: github.com/nickogibson/Dice-Roller](https://github.com/nickogibson/Dice-Roller)

**Want to embed the dice roller on your page?**
The diceroller is hosted on github

Embedding:
```html 
<iframe 
  src="https://nickogibson.github.io/app/DiceRoller/" 
  title="d20 Dice Roller" 
  style="width: 100%; aspect-ratio: 4 / 3; border: none;">
</iframe>
```

- Change width and height to either a px value or desired width/height %.
- for example height="500px"
- 100% is the mobile friendly version.

**Styling**

If your page has black background or other color that can't see the text well. You'll have to style the dicebox differently. For example

```html
<div 
	class="diceBox_container" 
	style="width: 100%; aspect-ratio: 4 / 3; 
	background-color: transparent;
	color: #eee;">
	<iframe height="100%"  width="100%" src="https://nickogibson.github.io/app/DiceRoller/" title="d20 Dice Roller"></iframe>
</div>
```

Then you can style  the thing in CSS however you want.

Example:
```css
diceBox_container {
  background-color: #333; /* Dark background */
  color: #eee; /* Light text */
}

/* Style the main title */
h1 {
  color: #ffc107; /* Amber color */
  font-size: 3em;
  font-family: 'Yanone Kaffeesatz', sans-serif;
}

/* Style the results area */
#rolls {
  background-color: #222;
  font-size: 2.2em;
  font-weight: bold;
  color: #4CAF50; /
}
```