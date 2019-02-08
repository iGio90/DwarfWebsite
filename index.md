`home` - [features](./features.html) - [install](./install.html) - [api](./api.html) - [examples](./examples.html)

--------

<br>

### What is Dwarf

As the title suggest, dwarf is a debugger, built on top of various frameworks and logics to simplify my life in reverse engineering tasks.
In the beginning, it was an experiment and a first approach to PyQt in the attempt to give an ui to [frida](http://frida.re).
It was mainly designed to work on Android but later, with a small effort, the support for iOS as been added with ease since they share the same arch.
Nowadays, mainly thanks to the community effort and the sure fact that opensource is the path (and of course to the power of [frida](http://frida.re),
Dwarf can debug on any operating system as a target and run on any desktop operating system (thanks to PyQt).

> #### Why you **shouldn't** use Dwarf.

* it's designed at needed. In the "reverse engineering" scene there are a lot of context in which a debugger could be used.
All the features has been coded and tested on different scenarios and thanks to the community (and a lot of if else) it handle most of the cases, but not all of them.
You could meet issues, and probably you will have to patch some code... that's not a big deal as the code base is pretty well structured
* if you are looking for something that gives you magic powers without the necessary environment, this is not the case and you should switch to another tool. 
Dwarf is coded also to give some space to work with an unrooted Android (in example), but most of the features would just not work.
Most of the effort has been spent into bringing compatibility for Windows, aka.. all paths bring to Rome, but linux is the best vehicle.

----

> #### Why you **should** give a try to Dwarf:

* because I'm sure you could find one of the [features](./features.html) very useful for the reason that takes you here.
* it's opensource
* it's built on top of the best technologies in terms of reverse engineering [frida](http://frida.re), [capstone](http://www.capstone-engine.org/), 
[keystone](http://www.keystone-engine.org/), [apktool](https://ibotpeaches.github.io/Apktool/), and so on
* the guys behind the scenes are always up on [slack](https://join.slack.com/t/resecret/shared_invite/enQtMzc1NTg4MzE3NjA1LTlkNzYxNTIwYTc2ZTYyOWY1MTQ1NzBiN2ZhYjQwYmY0ZmRhODQ0NDE3NmRmZjFiMmE1MDYwNWJlNDVjZDcwNGE)
ready to discuss new stuffs to implement
* because it kick asses