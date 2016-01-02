**WeBox** is a free, client-side only, open source web based Visual Novel engine!
It is built upon JS, JQUERY, HTML4 and AJAX only! This is the engine of the Israeli Visual Novel "the white world" (http://thewhiteworld.co.il).

You may fork it to your liking as long as you give us some credit somewhere =)

Supports all browsers of any version except IE (where support is from IE6 and above).

In order to make your own initialization you need to go to "engine.js", and change the last lines.
So you'll have:

-------------------------------------------------------------
...

E = new Engine();

// Other initializations: E.play('title_track.mp3'); E.textSpeed=X; etc...

-------------------------------------------------------------

Making new commands, editing them, making advanced GUI and more is requiring customization of engine.js, some in the same manner, some might require you to actually do it in the apropriate class (it's pretty well documented).
Feel free to add those. You can see an example in my TheWhiteWorld repository.

ENJOY!

