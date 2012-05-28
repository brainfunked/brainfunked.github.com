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

Late 2010, I was introduced to [Ruby](http://www.ruby-lang.org) - my first
proper Object Oriented (OO) programming language. Before that, I had
experience with scripting using shell or Perl. Both of these I could wield
procedurally. With shell scripts, there isn't any other option anyway.

Initially, I wrote rudimentary bug fixes and made the occasional, small feature
additions in a small Rails project. A few months later, I'd taken over the
development and maintenance of the project. This allowed me to learn basic
Ruby. I was still writing procedural code, however. It worked, but it was far
from pretty with some methods as long as 50 to 60 lines at times! The project
had been completed and I hadn't yet written a class of my own. I even wrote
decently complex a couple of analytics scripts, using
[MongoDB](http://www.mongodb.org), in Ruby. By then it was the latter half of
2011 and yet, I hadn't used the keyword 'class' anywhere. For someone coding
for eight odd months in a fundamentally OO language like Ruby, that seems a bit
  weird (now). Though, the did code work perfectly and churned out the expected
  output and more.

There was a problem, however. Doing feature additions to any of this Ruby
(and Rails) code was nothing short of hellish. I had learnt the Ruby basics
from the [Pickaxe Book](http://pragprog.com/book/ruby/programming-ruby), but
next to nothing about OOP itself. I'd read that OOP leads to maintainable code
that is easier to work with than procedural code, though perhaps after a
certain size boundary.  However, the biggest annoyance for me was when I
couldn't understand others' production quality Ruby code. There's huge amounts
of it on github and I couldn't understand most of it! _Those people do all
kinds of magic with classes and objects and I gawk at it like a child!_

OK, I knew of writing classes and creating objects from The Pickaxe Book.  But
that was just that. I had no OO design nous. The problem was that I still
couldn't figure out exactly how I'd be able to write maintainable code by
wielding the Object Oriented Programming (OOP) paradigm. Understanding
production quality Ruby code would require much better knowledge of Ruby too.
But with important projects coming up, I needed to be able to think in objects
too, if I were to get the *design* right.

Learning Object Oriented Programming
------------------------------------

After fumbling around on the Internet to learn OOP, I picked up Matt Weisfeld's
[Object-Oriented Thought
Process](http://www.amazon.com/Object-Oriented-Thought-Process-The-Edition/dp/0672330164/ref=sr_1_1?ie=UTF8&qid=1338037401&sr=8-1).
It was good going, at least initially. Classes, objects etc. made more sense
now. I had answers not to just the 'how', but also some 'why'. Even
inheritance made sense. What I did find a bit problematic was the tight
coupling between the OO concepts being explained and their implementations in
Java, C# etc. In fact, some of the concepts are actually *defined* based on
their implementation. That didn't sit up quite well with me. In the meanwhile,
I had garnered much better knowledge of Ruby thanks to Russ Olsen's excellent
[Eloquent
Ruby](http://www.amazon.com/gp/product/0321584104/ref=as_li_ss_tl?ie=UTF8&tag=eloqruby-20&linkCode=as2&camp=217145&creative=399349&creativeASIN=0321584104).

At the beginning of March 2012, our team had a discussion about OOP. The idea
was to understand the OO concepts. As it turned out, we also ended up drawing
upon the basic need for OOP itself. For me, it was a huge step forward for
understanding of OO. That essential question, *why*, had been answered in my
head and maybe that's why, OO finally made sense to me. I could draw up the
evolution of a program from Procedural to OO. This was purely conceptual,
pristine a thought process and the best part was that I could actually
translate this to implementations. Ruby really helped there. I could do away
with the boilerplate and concentrate on reproducing the Object Model I'd
thought up.

Around this time, I somehow stumbled upon the
[DCI](http://en.wikipedia.org/wiki/Data,_Context,_and_Interaction) paradigm.
The object model I'd come up with for a project I'd been working on at the
time had been very close to DCI - purely coincidentally, since I had drawn it
up before stumbling upon DCI. Anyway, I found DCI really interesting. I watched
James Coplien's [presentation](http://vimeo.com/8235574) in the meanwhile.
Interestingly, it gave me even more understand of object orientation. Finally,
I realised the problem - way too many programmers are taught *Class Oriented
Programming*.  They learn the OO concepts necessary for them to be able to
churn out code in the programming language of their choice. They learn
concepts the way they've been explained in Weisfeld's book - inside out.

Thinking in Objects
-------------------

So, in these recent few months, I've acquired (what seems like) a decent bit of
knowledge regarding OOP. [Ruby Rogues](http://rubyrogues.com) talked of OOP in
a couple of podcasts. I've come across lots of blog posts about OO design, code
smells, coupling etc. One of the most important steps was to learn of [Design
Patterns](http://c2.com/cgi/wiki?DesignPatterns). OO has started to make some
sense to me now.

One of the most pleasing moments in this journey of mine came about with the
realisation that I'd started to have *feelings* about my OO design - feelings
that tell me when something isn't quite right and needs to be designed
differently. Learning about [Behaviour Driven
Development](http://en.wikipedia.org/wiki/Behavior_Driven_Development) from the
[RSpec Book](http://pragprog.com/book/achbd/the-rspec-book) helped me verify
and act upon these feelings.

So, now that I am comfortable with OOP, I figure I could start writing about
my learning process in the hope that it might help others and most
importantly, myself, evolve with the OO Thought Process. As to why it matters,
I hope to be able to present the answer to that question here too, however
much I've learnt of it.

About Learning
--------------

[As it so happens](http://en.wikipedia.org/wiki/Bill_(Kill_Bill)), I've also
learnt a bit about Learning itself. What I'm trying to do with Thinking in
Objects is to utilise some of this knowledge and see if it can be put to some
good use. So, in case you're curious about what I'm trying to do, do read up
[On Learning](/essays/on-learning.html).

<!---
vim: tw=79:spell:spelllang=en_gb:
-->
