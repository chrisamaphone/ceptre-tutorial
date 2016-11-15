# ceptre-tutorial
Tutorial materials for Ceptre. You will need: a unix-based command line
(e.g. Terminal on Mac OS X or Cygwin on Windows). You will need to install
git.

## Installation

1. Clone this repository: 

<code>
$ git clone https://github.com/chrisamaphone/ceptre-tutorial.git
</code>

Or download as zip file and unzip.


2. Get the binary file appropriate for your system from (XXX link), then
   un-tar it:
  
<code>
$ tar -xzvf ceptre-<SYSTEM>.tar.gz
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

Exercise:


## Autonomous and social NPCs

File: sim.cep

Key idea: using stages to separate actions and reactions.




