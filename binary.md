# Binary uses, thoughts & commentary

## Context
I build up all of the below on [the best way to count](https://youtu.be/rDDaEVcwIJM) video advocating for binary counting (as opposed to [seximal](https://youtu.be/qID2B4MK7Y0), decimal, dozenal, hexadecimal and other bases).

## Scaling
I would at least partially restore logarithmic spacing of scaling, which would be consistent with the spirit of SI, which can be conveniently used for scales in a far larger range than just our typical human grams, kilograms and tons.

One option would be to name each of the bytes within a long (and a little further) range can be named:
* B byta = l .... ....
* S shorta = l  .... .... .... ....
* C cola = l .... ....  .... .... .... .... -- commemorating the historical 24-bit colour spaces (when without the alpha channel).
* N inta = l  .... .... .... ....  .... .... .... ....
* Ti teba = l .... ....  .... .... .... ....  .... .... .... .... -- commemorating the Tebi prefix, which is also similar to SI Tera prefix.
* Mc maca = 2**48 -- for Mac addresses
* D desa = 2**56 -- for commemorating the historic Data Encryption Standard algorithm
* L longa = 2**56
* F feca = 2**72 -- commemorating Error Correction Codes
* Yi yoba = 2**80

Fractions:
* bi bypto = one bytth
* si shorcto
* ci colpto
* ni incto
* pi pibico
* mi macto
* di desto
* li locto
* fi fecto
* yi yobto

Another option is to name each of the shorts within an overlong range can be named:
* short = l  .... .... .... .... = 65,536 = approx 65.5 k
* int = l  .... .... .... ....  .... .... .... .... = 4,294,967,296 = approx. 4.3 G
* trishort = l  .... .... .... ....  .... .... .... ....  .... .... .... .... = 281,474,976,710,656 = approx. 280 T
* long = l  .... .... .... ....  .... .... .... ....  .... .... .... ....  .... .... .... ....
* quishort = l  .... .... .... ....  .... .... .... ....  .... .... .... ....  .... .... .... ....  .... .... .... ....
* sextishort
* septishort
* overlong

## Units
Reforming SI is very hard.

### Easy approach -- keep as is
The easiest approach is just to keep 7 basic units: second, metre, kilogram, ampere, candela, mol, kelvin. And just to adopt the new prefixes.

That would mean:
* 500 g of pasta becomes .,l kg of pasta = l... .... bikg of pasta (byptokilogram).
* A day is l .l.l ...l l... .... seconds (sometimes l more, while the leap second is still in use).

But these are actually very minor inconveniencies compared to creating the actual new base units. Let's explore them below.

### Hard approach -- new base SI units
We can introduce the new SI units by:

* make an Earth day equal about l shortatick (l .... .... .... .... ticks). 1 day = 256 bytaticks (bytas) = 4,096 hexaticks = 65,536 ticks = 1,048,576 hextoticks. Of course, precise definitions have to be like SI ones, just with different numbers. 1 second would be about . , ll.. ..l. ..l. lll. .l.. .l.l .... .ll. such ticks (1 tick = 1.318 359 375 seconds). If such a tick was a quarter note in a 4/4, that would correspond to the tempo of 91.0r2 bpm.

* Unify geographic coordinates and distance measurement. Make an Earth meridian arc equal to .,l Colametre. Which means 1 old metre = about 0.8388608 new ones. New metre would be about 1.192 old metres.
* Speed unit would become about: 1 old m/s = 1.10592 new m/tk.
* 1 old m^3 is approximately equal to .590296 new m^3. 1 old litre would be approximately equal to l. , .ll. l.ll new litres. This would define the new litre to be a cubic hextometre, 1 new L = 0.413 59 old litres.
* Define new pound to be about a mass of the new litre of water, i.e. 1 new pd = about 0.413 59 old kg (about 10/11 old lbs).
* Ampere, mol, candela, kelvin would be, too, redefined using binary bases, but the original SI spirit and reasoning.

## Example: speedometer
### Easy approach -- meters per second are kept.
```
 | ||..   |. ....   |. .|..
 | |...  .--------. |. |...
| .|..  /          \ |. ||..
| .... |            | || ....
  ||.. |-           | || .|..
  |... |-           | || |...
    |.. \          / || ||..
       . \        / |.. ....
             m/s
```

### Using new m/tk: 
```
 | ||..   |. ....   |. .|..
 | |...  .--------. |. |...
| .|..  /          \ |. ||..
| .... |_           | || ....
  ||.. |            | || .|..
  |... |-           | || |...
    |.. \          / || ||..
       . \        / |.. ....
            m/tk
```
