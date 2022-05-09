# MIDIr
MIDI-based esolang made for fun, still not workable but available if someone actually knows how to implement it.

As i know next to nothing in programming, i'm just following some of the basic rules of C# since it's the only language i've worked on.

![MIDIr Logo](https://user-images.githubusercontent.com/104397117/167442775-53d24e80-8245-4e73-b0f9-e63d3cec66d8.png)

So, how do you write code on it ?

First you must use a program that can write MIDI files, be it any DAW with a Piano Roll (like FL Studio), a tracker with MIDI Support or a score/engraving program (like Musescore or Sibelius), you can manually edit the MIDI using a code editor but with a proper program it is more practical.

For example, this is the "Hello World" Program that writes all letters from A to Z

The MIDI is equivalent to ` Console.WriteLine("ABCDEFGHIJKLMNOPQRSTUVWXYZ")`

The Dictionary goes as

![image](https://user-images.githubusercontent.com/104397117/167449193-e6886e77-f69b-410c-8fd7-ee39572fa1ee.png)


for putting the Letter on Lower case, just put the C0 Note playing on the exact same time as it.
