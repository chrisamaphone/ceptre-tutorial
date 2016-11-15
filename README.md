# ceptre-tutorial
Tutorial materials for Ceptre. You will need: a unix-based command line
(e.g. Terminal on Mac OS X or Cygwin on Windows), libgmp on
Linux or OS X, basic command line knowledge (tar, cp, mv, etc.), and a text
editor for code.

## Installation

1. Clone this repository: 

<code>
$ git clone https://github.com/chrisamaphone/ceptre-tutorial.git
</code>

Or download as zip file and unzip.


2. Get the binary file appropriate for your system from [Google
   Drive](https://drive.google.com/drive/u/1/folders/0B6BJA78gViuAN3A0WlVkdXBjMk0), then
   un-tar it:
  
<code>
$ tar -xzvf ceptre-(SYSTEM).tar.gz
</code>

If that doesn't work, follow instructions at https://github.com/chrisamaphone/interactive-lp
   to download and install.

3. Test: 

<code>
./ceptre love-triangle.cep 
</code>

4. Optionally, download GraphViz: http://www.graphviz.org/ 

## Basics: a 1-rule example

File: otp.cep.

Key idea: writing rules with *multiset rewriting* notation.

RANDOM FANDOM! Generate OTPs from a cast of characters.

   <code>
    pair : available C1 * available C2 -o paired C1 C2.
   </code>


## Interactive story worlds

File: quest.cep

Key idea: interacting with rules.

Exercises:

- Add a rule for opening something (e.g. the chest).
- Add a rule for taking something out of something (e.g. the map out of the
  chest) and moving it to the surrounding room.


## Autonomous NPCs

File: quest-sim.cep

Key idea: using stages to separate interactive and autonomous behavior.

Exercise:
- Add a character-to-character interaction of your choosing.

## Social NPCs

File: quest-social.cep (or build on quest-sim.cep)

Key idea: writing backward-chaining rules and using predicates defined by
them to check conditions, e.g. "Does C1 like C2 enough to give them an item
that they want?"




