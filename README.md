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

Ask for first, third and fifth dial.
Filter garbage letter using:

* position 1: a b c e f g h l n o p r s t w
* position 3: a e g h i l o r t u v
* position 5: d e g h k l n r t w y

Then match word:

```
#1 #3 #5
a  a  n -> again
   o  t -> about
   t  r -> after
b  l  w -> below
c  u  d -> could
e  e  y -> every
f  r  t -> first
   u  d -> found
g  e  t -> great
h  u  e -> house
l  a  n -> learn
   r  e -> large
n  v  r -> never
o  h  r -> other
p  a  e -> place
      t -> plant
   i  t -> point
r  g  t -> right
s  a  l -> small
   e  l -> spell
   i  l -> still
   u  d -> sound
      y -> study
t  e  e -> these / there
      r -> their
   i  g -> thing
      k -> think
   r  e -> three
w  e  e -> where
   i  e -> write
      h -> which
   r  d -> world
   t  r -> water
   u  d -> would
```

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
