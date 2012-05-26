---
title:      Thinking in Objects
category:   technical
layout:     post
date:       2012-05-26
---

Thinking in Objects
===================

Preface
-------

In 2010, I was introduced to Ruby - my first properly Object Oriented (OO)
programming language. Before that, I had experience with scripting using shell
or Perl. Both of these I could wield procedurally. With shell scripts, there
isn't any other option anyway.

Initially, I wrote rudimentary bug fixes and small feature additions in a small
Rails project. A few months later, I'd taken over the development and
maintenance of the project. This allowed me to learn basic Ruby. I was still
writing procedural code, however. It worked, but it was far from pretty. The
project had been completed and I hadn't yet written a class of my own. I even
wrote decently complex a couple of script for analytics, using
[MongoDB](http://www.mongodb.org), in Ruby. And yet, I hadn't used the keyword
*class* anywhere. Again, the code worked perfectly well and churned out the
expected output and more.

There was a problem, however. Doing feature additions to any of this Ruby code
was hellish. Around this time I learnt what the *class* keyword in Ruby does
and what objects are. The problem was that I still couldn't figure out exactly
how I'd be able to write maintainable code by wielding the Object Oriented
Programming (OOP) methodology. After all, I'd read that that's one of the
benefits of doing OOP.

Learning Object Oriented Programming
------------------------------------

After fumbling around on the Internet to learn OOP, I picked up Matt Weisfeld's
[Object-Oriented Thought
Process](http://www.amazon.com/Object-Oriented-Thought-Process-The-Edition/dp/0672330164/ref=sr_1_1?ie=UTF8&qid=1338037401&sr=8-1).
It was good going, initially. Classes, objects etc made sense. Even inheritance
made sense. What I did find a bit problematic was that the book is tightly
coupled to the implementation of OO in Java, C# etc. Some concepts are defined
based on their implementation. Some of this didn't really translate well to
Ruby either.

One fine day, our team had a discussion about OOP. While figuring out the need
for OOP, I somehow ended up defining the whole flow from Procedural to OO code.
  The evolution of such code. This thought had nothing to do with any specific
  implementation and was purely about the OO concepts themselves.

What I realised soon afterwards, was that there are way too many programmers
who learn OOP the way it is taught in Weisfeld's book. I had also stumbled upon
James Coplien's [blog post](http://www.artima.com/articles/dci_vision.html) and
[presentation](http://vimeo.com/8235574) in the meanwhile. It made sense to me.
But regarding my OOP learning process, it gave me the term *Class Oriented
Programming*. It made sense then. Weisfeld's book talked of Class Oriented code
rather than Object Oriented.

Thinking in Objects
-------------------

All of this was somewhere back in Jan/Feb 2012. In these recent few months,
I've come across a lot of knowledge regarding OOP. [Ruby
Rogues](http://rubyrogues.com) talked of OOP in a couple of podcasts. I've come
across lots of blog posts about OO design, code smells, coupling etc. One of
the most important steps was to learn of [Design
Patterns](http://c2.com/cgi/wiki?DesignPatterns). OO has started to make some
sense to me now.

One of the most pleasing moments in this journey of mine was when I realised
that I'd started to have *feelings* about my OO design. Feelings that tell me
when something isn't quite right and needs to be designed differently. Learning
about [Behaviour Driven
Development](http://en.wikipedia.org/wiki/Behavior_Driven_Development) from the
[RSpec Book](http://pragprog.com/book/achbd/the-rspec-book) helped me verify
and act upon these feelings.

So, now that I am comfortable with OOP, I've decided blog about my learning
process in the hope that it might help others and most importantly, myself,
evolve with the OO Thought Process.
