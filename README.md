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


2. Try un-tar-ing the appropriate binary file for your system:
  
<code>
$ tar -xzvf ceptre-<SYSTEM>.tar.gz
</code>

If that doesn't work, follow instructions at https://github.com/chrisamaphone/interactive-lp
   to download and install.

2. Test: 

<code>
./ceptre love-triangle.cep 
</code>

## Basics: a 2-rule example

1. Love triangle story world. Key idea: implement interaction rules with
   *multiset rewriting* notation, e.g.

   <code>
   jealousy
     : $eros A B * $eros C A * neq C A 
       -o anger C A * anger C B.
   </code>

  File: love-triangle.cep

## Interactive story worlds

  File: quest.cep

## Autonomous and social NPCs

  File: social.cep



