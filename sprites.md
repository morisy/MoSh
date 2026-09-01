Sprite sheet for Starchart. Each sprite is a heading, an
optional "type:" line (ship / station / other), then the
pixel grid — one character per pixel:

  .  transparent       o  dark hull
  h  hull grey         l  light grey
  c  cyan (lights)     e  amber (engines)
  r  red (hardpoints)

Ships face right; the map rotates them in flight.
Ships and stations with type set are entered into the
random "look" pools; anything else is drawn only when a
body's type matches the sprite name (derelict, relay).

Edit by hand or with sprite-editor.html.

# freighter
type: ship

..hhhhhhh..
ehlhlhlhhc.
ehlhlhlhhcc
ehlhlhlhhc.
..hhhhhhh..

# shuttle
type: ship

e.hhll..
ehhhlllc
e.hhll..

# gunship
type: ship

..hhh.r...
ehhhhhhllc
..hhh.r...

# ring
type: station

..lll..
.l...l.
l..h..l
l.hch.l
l..h..l
.l...l.
..lll..

# spin
type: station

l.....l
.h...h.
..hch..
..chc..
..hch..
.h...h.
l.....l

# spar
type: station

..c..
..h..
.lhl.
..h..
.lhl.
..h..
.ooo.
..e..

# derelict

..oh.oo...
.ohh..oho.
oo.h.ooh.o
....o..o..

# relay

...l...
ll.h.ll
ll.c.ll
ll.h.ll
