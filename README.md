see
===

C scratchpad

* To compile a program using the gcc compiler use the following command line:

  % gcc -g -Wall -ohello hello.c

  The additional switch -Wall turns on the warnings.

  The GNU compiler contains several extensions to the basic C
  language. If you want to turn these features off, use the following
  command line:

  % gcc -g -Wall -ansi -pedantic -ohello hello.c
     
  The switch -ansi turns off features of GNU C that are incompatible
  with ANSI C. The -pedantic switch causes the compiler to issue a
  warning for any non-ANSI feature it encounters.

  Source: Practical C Programming, 3e

* 
