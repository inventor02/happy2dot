# happy2dot

**Work in progress!** I am a university student working on this in my spare time (I also have a job). I'm (relatively) new to Haskell, so
the ways I do things may not be the best. I'd love pointers on how to improve, if you want to provide them!

happy2dot is a program that has one aim: convert the output from [Happy](https://haskell-happy.readthedocs.io/)'s `.info` files in
to a Graphviz representation of the finite state machine it uses.

To do this, we use Happy itself to parse the `.info` file, as well as [Alex](https://haskell-alex.readthedocs.io/) to lex it.

It would not go amiss to give a brief mention to Kate F's brilliant [libfsm](https://github.com/katef/libfsm) collection of tools
which is what inspired me to give this a go in the first place.