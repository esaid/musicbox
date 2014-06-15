Musicbox
========

A plucked string music synthesiser and player.

Initially this will be only the Forth software required to implement the synthesiser on a
[GA144 chip](http://www.greenarraychips.com/home/products/index.html). For proof of concept I am using the EVB001 evaluation board.

This allows a speaker or headphones to be attached to the DAC output pin to hear the plucked string music.

A music webserver
-----------------

The next level of the project is to convert the plucked string audio stream into streamed MP3 and output the stream via a web server.
This requires implementing an MP3 encoder in the GA144 and outputting the data to a [WizNet W550io module.](http://wizwiki.net/wiki/doku.php?id=products:wiz550io:start)

A standalone web appliance
----------------------

The final level is to design and build a small PCB to hold a GA144 and sockets to plug in the W550io to create a standalone web appliance.

Watch this space :)
