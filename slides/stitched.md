---
title: Getting Unstuck - Steven J Hicks
theme: _assets/css/theme.css
revealOptions:
  transition: 'none'
  controls: false
  progress: false
  center: true
css: _assets/css/custom.css
preprocessor: _build/inject.js
---
Footer: false

<!-- .slide: data-background="/images/title.jpg" class="title" -->

# Getting Unstuck

- Steven Hicks
- @pepopowitz
- steven.j.hicks@gmail.com
- stevenhicks.me/getting-unstuck

Notes: These are notes

and more notes here

---

Layout: module

# Stuck

Notes:

when I hear in standup that someone is stuck, my ears perk up.

My favorite thing in development is getting unstuck.

So....that's why I'm talking about this?

---

TODO: Describe what "stuck" means

Notes:

So with that...let's talk about some strategies to get unstuck.

## My first strategy is...only kind of a strategy.
---
Layout: module
# 0. Embrace
# The Problem
---

## Survey time!

Notes:

1. Who in this room considers themselves a junior in their career? mid-level? senior?

...

2. Who in this room can think of a time that they were stuck?

Keep your hands up

Juniors, look around.

This happens to all of us

---

Trail: 0. Embrace

> It may feel frustrating and like you’re doing it wrong, but _that is the practice_.

Will Doenlen, ["To start meditating, stop trying to empty your mind"](https://medium.com/@williardx/to-start-meditating-stop-trying-to-empty-your-mind-fe67a7ed113b)

Notes:

My friend Will wrote an article called "To start meditating, stop trying to empty your mind"

Many newcomers to meditation think that they are bad at it, because their mind is not empty.

Their mind wanders, and they think about lots of different things.

...

Will makes the point that HAVING an empty mind is not what mediation is about, especially as a beginner.

It is about _mindfulness_, and noticing that your mind is wandering.

And that's it. (read quote)

...

Similarly, when it comes to getting stuck....

---

Trail: 0. Embrace

## Getting stuck isn't a reflection of your skill level

Notes:

Or experience level

As we saw by the hands

---

Trail: 0. Embrace

## Getting stuck isn't an impediment preventing you from doing the job

---

Trail: 0. Embrace

# Getting stuck

# **IS THE JOB.**

Notes:

This is what we're getting paid to do! Solve problems. To get stuck, and then get unstuck. This is our unique skill. It's why we get paid to do our job instead of someone else.
---
Layout: module
# 1. Explain
# the problem
---

Trail: 1. Explain

## Write a message describing the problem

Notes:

You might not even have to post them!

---

Trail: 1. Explain,Write

TODO: pic of an email

---

Trail: 1. Explain,Write

TODO: pic of a stack overflow post

---

Trail: 1. Explain,Write

TODO: pic of a slack message

---

Trail: 1. Explain,Write

TODO: pic of a slack message to slackbot

---

Trail: 1. Explain

## Talk to the duck

Pic: duck

Notes:

Explain what it is

Comes from a story in https://en.wikipedia.org/wiki/The_Pragmatic_Programmer

Doesn't have to be to a duck

Doesn't have to be to a real THING
But it _can_ be a real thing

it can be imaginary

But it is definitely most effective when it is out loud

---

Trail: 1. Explain

## Talk to a person

Notes:

Same thing as before, except your coworkers are the duck
Pic: person in a duck costume

Just ask if you can explain something to them

---

Trail: 1. Explain

## Pair with a person

Notes:

Taking "talk to a person in a duck costume" a step further

todo: some basic pairing advice?

---

Trail: 1. Explain

## Why do these work?

---

Trail: 1. Explain,Why?

### Forces you to think more about how things are all fitting together, so you can explain it clearly

Notes:

---

Trail: 1. Explain, Why?

### The best way to learn or understand something is to teach it.

---

Trail: 1. Explain,Why?,Teaching

## Protege effect

https://effectiviology.com/protege-effect-learn-by-teaching/

todo - fill more in here.

---

Trail: 1. Explain,Why?

### Challenges assumptions

To prove that the code you think is running is actually running

---

Layout: Summary

Trail: 1. Explain,Why?

## Challenge assumptions

Notes:

This is the most critical and important thing about ALL of these "explanation" strategies:

They prompt you to challenge assumptions.

---

Trail: 1. Explain,Why?,Challenge Assumptions

> "Experience this one thing for what it is, not what you think it is."

Mihaly Csikszentmihaly, "Creativity: Flow and the Psychology of Discovery and Intervention"

Notes:

Mihaly - wrote "Creativity"

psychologist who introduces concept of "Flow"

it's kind of philosophical, almost zen

....

this is similar to what I remember being taught in art class

And what my kids are learning about their art

---

Trail: 1. Explain,Why?

## Draw what you see, not what you THINK you see

---

Trail: 1. Explain,Why?

> 1. Scribble
> 2. Preschematic
> 3. Schematic
> 4. Dawning Realism
> 5. Pseudorealism
> 6. Period of decision/crisis

Viktor Lowenfeld's Stages Of Artistic Development, 1949

Notes:

Viktor Lowenfeld - professor of art education

1949

---

Trail: 1. Explain,Why?

> 1. Scribble
> 2. Preschematic
> 3. **Schematic**
> 4. **Dawning Realism**
> 5. Pseudorealism
> 6. Period of decision/crisis

Viktor Lowenfeld's Stages Of Artistic Development, 1949

Notes:

I want to focus on the 3rd and 4th stages - which is when a young artist - or sometimes a 41 year old artist, like myself - transitions from drawing schemas, or symbols, to realism.

---

Trail: 1. Explain,Why?

### Schemas

TODO: pic of schematic drawing

Notes:

Are really just symbols

visual heuristics, kind of

When we see this drawing, we recognize it instantly as an eye

And when you ask me to draw an eye, as a child in the schematic stage, this is what I'd draw.

---

Trail: 1. Explain,Why?

### Schemas -> Realism

TODO: pic of schematic drawing
TODO: pic of realistic drawing

Notes:

But then the artist transitions to realism

And this is what an eye ACTUALLY looks like

It's not a symbol, or a heuristic

It has incredible detail and subtlety.

---

Trail: 1. Explain,Why?,Schemas & Symbols

TODO: pic of biz-logic, settings, db, mail as symbols

Notes:

When you are focused on a problem in your code, you use symbols.

You make assumptions.

You build up this model in your head of all the pieces that are working together.

But they are black boxes.

They are symbols in your head, and you just assume they work as intended.

...

We _have_ to do this - because if we didn't....

---

Trail: 1. Explain,Why?,Schemas & Symbols

TODO: pic of focus other blocks, one at a time?

Notes:

We couldn't possibly understand the system. There would just be too much going on.

Too many details.

But our black boxes don't always work as intended.

Explaining the problem forces you to evaluate every assumption and every black box, and expand the details of each of them.

Until you can identify what's not working right.
---
Layout: module
# 2. Isolate
# The Problem
---

Trail: 2. Isolate

## Risk analysis

Notes:

Isolating the problem starts with some risk analysis.

Ask yourself some questions

---

Trail: 2. Isolate, Risk Analysis

### What is the thing I've introduced that I know the least about?

### What is the thing most likely for me to improperly use?

<!-- .element: class="fragment" -->

### What is the thing I'm making the most assumptions about?

<!-- .element: class="fragment" -->

Notes:

1. A dependency, or some new code, ...

2. A dependency, or some existing code, ...

3. Anything.

If you can give a solid answer to any of those questions,

there is a good chance that's where your stuck is coming from.

---

Trail: 2. Isolate

## Remove code

Notes:

Whether you were able to answer any of those questions,

you can start removing code to isolate the source.

---

Trail: 2. Isolate, Remove Code

## Delete code iteratively

TODO: pic of deleting code iteratively/binary search

<!-- .element: class="fragment" -->

Notes:

Binary search for the code that isn't working

This isn't always as simple as just deleting lines - often you'll need to rewrite code to accommodate the deleted lines.

But you've removed complexity.

And eventually, you'll be able to isolate a smaller block of focus.

And then instead of dealing with 50 lines of code that don't work, you have 10.

---

Trail: 2. Isolate, Remove Code

## Back out your changes iteratively

TODO: pic of backing out of code iteratively/binary search

<!-- .element: class="fragment" -->

Notes:

Similarly, you can do a binary search of your recent changes.

Assuming everything worked before you started making changes,

You can iteratively reverse them until things are working again -

And then you've again narrowed it down from 50 lines of code to 10 lines of code.

---

Trail: 2. Isolate, Remove Code

## Use small commits!

Notes:

Side note - this is one reason that small commits is really helpful.

You don't have to push them, and you can keep amending the same commit.

But committing frequently means you can revert changes with Git a little bit at a time.

---

Trail: 2. Isolate

## Build a proof of concept

Notes:

A binary search for the problematic code starts with a system of code, and prunes it.

An alternative approach is to start from scratch, and try to recreate the system as simply as possible,

building a proof of concept that these pieces should play together nicely.

...

This is often what you'll do when you're getting ready to submit an issue to a project

Build a proof of concept that demonstrates the problem, so it's easier to identify/fix the bug

---

Trail: 2. Isolate, Proof of Concept

TODO - illustrate somehow that I'm only including the pieces that I need to prove out

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## `> node`

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## Quokka.js

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## JSFiddle

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## Codepen

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## CodeSandbox.io

---

Trail: 2. Isolate, Proof of Concept, C#/.NET

## csharppad.com

---

Trail: 2. Isolate, Proof of Concept, C#/.NET

## dotnetfiddle.net

---

Trail: 2. Isolate, Proof of Concept, Ruby/Rails

## `> irb`

---

Trail: 2. Isolate, Proof of Concept, Ruby/Rails

## `> rails console`

---

Trail: 2. Isolate, Proof of Concept, Ruby/Rails

## `> bundle console`

Notes:

(ruby console in the bundle context - like rails console w/o rails.)

In all of these cases, you can run code directly in those consoles,

or you can save a .rb file (or two or three), and there are equivalent options to run those files.

---

Trail: 2. Isolate

## Eat The Frog

Notes:

there's a subcategory of being stuck

where you can't get started: **analysis paralysis**.

my recommendation: eat the frog.

---

Trail: 2. Isolate, Eat The Frog

> Eat a live frog first thing in the morning and nothing worse will happen to you the rest of the day.

Mark Twain

---

Trail: 2. Isolate, Eat The Frog

TODO: pic of dependencies together

Notes:

When you're faced with building a system with a bunch of pieces

And you don't know which pieces to start with

Choose the scariest thing about this system - the most risky - and start there.

You can throw away the code afterward!

But it will get you moving.

And it gives you information about how this system will eventually come together.

...

this is a good strategy in TDD, too - write code to figure out HOW you'll solve the hard problem; then throw it away & start over test-driven & with the knowledge of how you'll approach the problem.

---

Trail: 2. Isolate, Eat The Frog

TODO: pic of complicated dependency

Notes:

If the "hardest problem" seems too big,

try to identify multiple problems in it,

separate them,

& approach them one at a time.

Starting with the scariest.

---

Trail: 2. Isolate

## Log inputs

Notes:

Your code is a tree of function calls.

Somewhere along the way, one of the functions isn't getting what it needs.

Log inputs to them, to see who doesn't have what they need!

...

This is not an advanced tactic. It's something we learn to do pretty early as developers.

But you'd be surprised how many times you get stuck on a problem, and you forget that this will help you isolate the issue.

---

Trail: 2. Isolate

## Write tests!

Notes:

I get preachy about writing tests

It's one of the most useful skills for breaking down a problem.

---

Trail: 2. Isolate, Write Tests, Why?

## Tight Feedback Loops

TODO: drawing of tight feedback loops vs loose

Notes:

TODO: Explain what tight feedback loops are and why I care.

...

So here are some kinds of tests you can write that will help you isolate an issue.

---

Trail: 2. Isolate, Write Tests

## Unit tests of existing functions

TODO: drawing of unit test of existing function

Notes:

This will help you verify if a function is the problem, or an innocent bystander.

---

Trail: 2. Isolate, Write Tests

## Unit tests of new functions

TODO: drawing of unit test of new function

Notes:

Find pieces that look like they could be isolated.

Extract them to a function, pure if possible.

Write unit tests against that function

Can help you narrow down whether this functionality is the problem

---

Trail: 2. Isolate, Write Tests

## Integration tests

TODO: drawing of integration tests

---

Trail: 2. Isolate, Write Tests

## End-to-end tests

TODO: drawing of e2e tests

Notes:

Easier to write in ruby/rails

---

Layout: Summary
Trail: 2. Isolate

## Break down problems

Notes:

Common thread for "isolation" strategies ^^^
---
Layout: module
# 3. Escape
# The Problem
---

Trail: 3. Escape

## Relax

Notes:

Take a shower, take a nap, ....

---

Trail: 3. Escape, Relax, Why?

TODO - illustrate how changing context helps your brain explore new ideas

Notes:

http://mentalfloss.com/article/52586/why-do-our-best-ideas-come-us-shower
A. In creativity research, we refer to the three Bs—for the bathtub, the bed and the bus—places where ideas have famously and suddenly emerged. When we take time off from working on a problem, we change what we're doing and our context, and that can activate different areas of our brain. If the answer wasn't in the part of the brain we were using, it might be in another. If we're lucky, in the next context we may hear or see something that relates—distantly—to the problem that we had temporarily put aside.

---

Trail: 3. Escape

## Physical exercise

---

Trail: 3. Escape, Physical Exercise

TODO: find research on this

https://www.newyorker.com/tech/annals-of-technology/walking-helps-us-think
https://www.ncbi.nlm.nih.gov/pubmed/20890449

---

Trail: 3. Escape

## Other hobbies

Notes:

Similar effects to resting - our brain explores new ideas

this is a very individualized strategy - ash plays guitar

---

Trail: 3. Escape

## Move on to another problem

Notes:

Put this one aside. Work on something else you know how to solve. 2 things can happen:

---

Trail: 3. Escape, Move On, Why?

### Your brain might come up with the answer while thinking about other things

---

Trail: 3. Escape, Move On, Why?

### When you come back to the original problem, you have to re-learn it a bit

Notes:

This can help you challenge assumptions, like talking to the duck.

---

Trail: 3. Escape, Why?

## Analogical problem solving

TODO: illustrate this

Notes:

use information from one domain (the source or analogy)

to help solve a problem in another domain (the target)

http://cognitivepsychology.wikidot.com/problem-solving:analogy

---

Trail: 3. Escape, Why?

## Incubation

---

Trail: 3. Escape, Why?, Incubation

TODO: fill in mihaly stuff here!

---

## Notes

mihaly Csikszentmihalyi
mee-hi chick-sent-mee-hi
popularized "flow"
wrote a book called creativity
https://www.blinkist.com/books/creativity-en?r=1&st=mihaly

incubation - the idea that the brain works on problems once you've walked away from them
https://traviswhitecommunications.com/2012/12/26/creativity-in-five-steps/

    Mihaly Csikszentmihalyi — while not guaranteeing results — writes that creativity typically evolves through five stages.

      The first stage is preparation. Basically, you need to know the rules before you break them. Thomas Kuhn writes that scientific paradigms reflect a basic consensus of how the world operates. Prior to Copernicus, the astronomical paradigm held that the earth was the center of the universe. Before Copernicus could change the paradigm, he had to immerse himself in it. Only then could he make the observations that changed the paradigm.

      The second phase is incubation, “… during which ideas churn around below the threshold of consciousness.” This is when I like to go for a walk. I like to lay things aside, clear my head, and let my mind wander. It’s a haphazard process — sometimes nothing happens. Sometimes I simply forget what I was thinking about. Other times, however, something bubbles up that’s worth capturing. (One of the reasons I write this blog is to double back on my own thinking, recall what I wrote months ago, and perhaps make connections I would otherwise miss).

      Third, is the insight — the Aha moment. As we saw in the article on sleepiness and creativity (click here), focusing intently on the problem at hand may actually inhibit the Aha experience. When you focus, you block out random thoughts and stray ideas. But it’s those very thoughts and ideas that may produce the insight. When you’re tired — or when you can induce your mind to wander — those stray thoughts are not blocked out and can help you see things more creatively.

    From "Creativity":
      The distinction between serial and parallel processing of information may also explain what happens during incubation. In a serial system like that of an old-fashioned calculator, a   complex numerical problem must be solved in a sequence, one step at a time. In a parallel system such as in advanced computer software, a problem is broken up into its component steps, the partial computations are carried out simultaneously, and then these are reconstituted into a single final solution. Something similar to parallel processing may be taking place when the elements of a problem are said to be incubating. When we think consciously about an issue, our previous training and the effort to arrive at a solution push our ideas in a linear direction, usually along predictable or familiar lines. But intentionality does not work in the subconscious. Free from rational direction, ideas can combine and pursue each other every which way. Because of this freedom, original connections that would be at first rejected by the rational mind have a chance to become established.

    This ^^ is really similar to talking about asynchrony in code.

    Often when we're faced with a difficult problem, we think we need to really focus on it.

    We think that we are procrastinating if we aren't actively attacking it.

    But the truth is, for really complicated problems, where your brain and your creativity need to expand in many directions to find a solution, staying actively focused can be a detriment. Giving your brain some room to explore the space, on its own time, can help you explore ideas that your focused, rational mind would initially reject.

    So go for a walk. Go work out. Take a shower, or a nap. Read a book about something unrelated. Get in your basement and do some woodworking. Knit. Go mountain biking or trail running or rock climbing. Let your brain expand this problem in many other directions.
---
Layout: module
# 4. Harden 
# Yourself

Notes:

Harden yourself for the next time
---

Trail: 4. Harden

## Getting stuck **IS THE JOB**

Notes:

Remember our perspective from earlier

---

Trail: 4. Harden

## Wall of motivation

TODO: screenshot

Notes:

I keep a trello board, to remind myself that I'm succeeding at my job.

Whatever measures as a win to you

For me it's messages of really helping people

---

Trail: 4. Harden

## Keep a journal

Notes:

Another of my coworkers, Eloy, who lives on a houseboat in Amsterdam,

recommended when I first started at Artsy to keep a journal

of things I did every day - so I could see that I **AM** getting things done.

I **AM** getting unstuck, and solving problems, and contributing.

---

Trail: 4. Harden

## Exercise

Notes:

Can reduce anxiety & depression

I particularly recommend rock climbing

Hardens your problem solving skills & persistence.

---

Trail: 4. Harden

## Meditation

---

Trail: 4. Harden

## Talk about your struggles

Notes:

Get outside of your head.

Do more active 1on1's with your leader, or someone else that you feel psychologically safe around.

Someone you can be vulnerable with.

Talk about the times you felt stuck.

---

Layout: Summary

Trail: 4. Harden

TODO: summarize harden somehow
---
Layout: module
# Summary
---

Trail: Summary

## 0. **Embrace**: Getting Unstuck **Is The Job**

## 1. **Explain**: Challenge Assumptions

<!-- .element: class="fragment" -->

## 2. **Isolate**: Break Problems Down

<!-- .element: class="fragment" -->

## 3. **Escape**: Let It Incubate

<!-- .element: class="fragment" -->

## 4. **Harden**: Summary???

<!-- .element: class="fragment" -->

---

Footer: false

<!-- .slide: data-background="/images/title.jpg" class="title" -->

# Thank you!

- Steven Hicks
- @pepopowitz
- steven.j.hicks@gmail.com
- stevenhicks.me/getting-unstuck

Notes: These are notes

and more notes here

---

Trail: Resources
