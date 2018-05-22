# ktane
Sleek version of the bomb manual for the game "Keeping Talking and Nobody Explodes"

### Horizontal Wires

<img src="img/horizontal.wires.svg?sanitize=true" width="800">

### Buttons

<img src="img/buttons.svg?sanitize=true" width="200">

### Keypads

### Simon

### Who's on First

### Memory
notation:
```
Lx = label x
Px = position x
LSx = label a stage x
PSx = position at stage x
```
hint/advice:
The expert (with the manual) should note the progression between stage like this:
```
S1: P L
S2: P L
S3: P L
S4: P L
S5: doesn't matter
```
with P and L, respectively, each position and label pressed for each stage.

Procedure :
```
Stage1:
1 => P2
2 => P2
3 => P3
4 => P4

Stage2:
1 => L4
2 => PS1
3 => P1
4 => PS1

Stage3:
1 => LS2
2 => LS1
3 => P3
4 => L4

Stage4:
1 => PS1
2 => P1
3 => PS2
4 => PS2

Stage5:
1 => LS1
2 => LS2
3 => LS4
4 => LS3
```

### Morse Code

<img src="img/morse.svg?sanitize=true" width="400">

### Vertical Wires (Complicated Wires)

### Wire Sequences

### Mazes

### Passwords

Do a **TEA** pass (defuser go through all the dials looking only for **t**, **e**, **a**)
Then match against the table:

```
----e house
----t first point right (#1 dial contains f / p / r)
---te write
--a-- small
--a-e place
--a-t plant
--e-- spell
--e-e where
--eat great
-a--e large
-ate- water
-e--- below
-e-e- never
-ea-- learn
-t--- still study (#3 dial contains i / u)
-t-e- other
a---t about
a-a-- again
a-te- after
e-e-- every
t---- thing think (#5 dial contains g / k)
t--ee three
t-e-- their
t-e-e there these (#4 dial contains r / s)

----- could found sound which world would (see below)
```

How to handle the no-match (`-----`) case:

`c / f / s in #1 ?` -> could / found / sound

`i / r / u in #3 ?` -> which / world / would


## Needy
### Knobs
LEDs configurations:
Up:

| | |X| |X|X|
|X|X|X|X| |x|

notation:
```
T = Top led on
B = Bottom led on
A = Both leds on
N = None, both leds off
```
LEDs configurations:

UP:
BBABTA / TBANAB

Down:
BAABNB / TBTNTB

Left:
BNNBAB / NNNBAN

Right:
ABATAT / ABATBN
