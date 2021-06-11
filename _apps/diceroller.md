---
title: d20 Dice Roller
description: A d20 diceroller with player save functions.
layout: home
date: 2019-10-02 19:13:21 -0700
---


<iframe width="100%" height="700px" src="https://nickogibson.github.io/games.io/DiceRoller"></iframe>

A d20 Dice Roller with player hand saving functions.
[source code: github.com/nickogibson/Dice-Roller](https://github.com/nickogibson/Dice-Roller)
**Want to embed the dice roller on your page?**
The diceroller is hosted on github, and on IPFS as a test of what was possible.

Embedding the github link.
```markdown 
<iframe width="100%" height="500px" src="https://nickogibson.github.io/games.io/DiceRoller"></iframe>
```

Or the 'slightly' broken dicebox forever on ipfs:
 If you want to embed it you can do this:
```markdown 
<iframe width="100%" height="500px" src="https://gateway.pinata.cloud/ipfs/QmWKQE5QhMMdRjXZCunpdN1fHEGmJdEWfecCvPJCw3oZ6g/"></iframe>
```
 The link won't always load all 6 images from the cloud, and might require a page refresh to get ready.

- Change width and height to either a px value or desired width/height %.
- for example height="500px"
- 100% is the mobile friendly version.

If your page has black or other color background that can't see black text well. You'll have to style the dicebox differently. For example

```markdown
<div id="diceBox" width="100%" style="background-color: #FFFFFF; height:500px;"><iframe height="100%"  width="100%" src="https://nickogibson.github.io/games.io/DiceRoller"></iframe></div>
```

Adding id="diceBox" is optional but then you can change the thing in css instead.
Then you can maybe remove the scrollbar or change the whole thing

I don't plan on changing the code, even though it could be better. 
