# MIDIr
MIDI-based esolang made for fun, still not workable but available if someone actually knows how to implement it.

As i know next to nothing in programming, i'm just following some of the basic rules of C# since it's the only language i've worked on.

![MIDIr Logo](https://user-images.githubusercontent.com/104397117/167442775-53d24e80-8245-4e73-b0f9-e63d3cec66d8.png)

So, how do you write code on it ?

First you must use a program that can write MIDI files, be it any DAW with a Piano Roll (like FL Studio), a tracker with MIDI Support or a score/engraving program (like Musescore or Sibelius), you can manually edit the MIDI using a code editor but with a proper program it is more practical.

For example, this is the "Hello World" Program that writes all letters from A to Z

The MIDI is equivalent to ` Console.WriteLine("ABCDEFGHIJKLMNOPQRSTUVWXYZ")`

The Dictionary goes as



`
A1 -> A Letter

B1 -> B Letter

C1 -> C Letter (it is the lower than A and B on the Piano roll but it would be confusing to put A on it)

D1 -> D Letter

E1 -> E Letter

F1 -> F Letter

G1 -> G Letter



C2 -> H Letter

D2 -> I Letter

E2 -> J Letter

F2 -> L Letter

G2 -> K Letter

A2 -> M Letter

B2 -> N Letter



C3 -> O Letter

D3 -> P Letter

E3 -> Q Letter

F3 -> R Letter

G3 -> S Letter

A3 -> T Letter

B3 -> U Letter

C4 -> V Letter

D4 -> W Letter

E4 -> X Letter

F4 -> Y Letter

G4 -> Z Letter

`

for putting the Letter on Lower case, just put the C0 Note playing on the exact same time as it.
