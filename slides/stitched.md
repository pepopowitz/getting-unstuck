---
title: My Reveal Starter Kit - Steven J Hicks
theme: solarized
revealOptions:
  transition: 'none'
  controls: false
  progress: false
  center: true
css: _build/custom.css
preprocessor: _build/inject.js
---
Footer: false

<!-- .slide: data-background="/images/title.jpg" class="title" -->

# Getting Unstuck

- @pepopowitz
- steven.j.hicks@gmail.com
- stevenhicks.me/getting-unstuck

Notes: These are notes

and more notes here

---

## Intro

### Story?

Notes:

when I hear in standup that someone is stuck, my ears perk up.

My favorite thing in development is getting unstuck.

So....that's why I'm talking about this?

---

Layout: module

## Embrace The Problem

---

### Survey

Notes:

1. Who in this room considers themselves a junior in their career? mid-level? senior?

...

2. Who in this room can think of a time that they were stuck?

Keep your hands up

Juniors, look around.

This happens to all of us

And why does it happen to all of us?

---

### Getting stuck isn't a reflection of your skill level

---

### Getting stuck isn't a temporary roadbump preventing you from doing the job

---

### Getting stuck **IS THE JOB.**

Notes:

This is what we're getting paid to do! Solve problems. To get stuck, and then get unstuck. This is our unique skill. It's why we get paid to do our job instead of someone else.

Some strategies...

TODO - is there a place to reference will's article about meditation? https://medium.com/@williardx/to-start-meditating-stop-trying-to-empty-your-mind-fe67a7ed113b - it's parallel. Talks about having thoughts in your head & releasing them IS meditation.
---
Layout: module
## Explain the problem
---

Trail: Explain

### Write up an email/Slack message/StackOverflow post describing the problem

Notes:

You might not even have to post them!

---

Trail: Explain,Write

Pics:

- an email

---

Trail: Explain,Write

Pics:

- a stack overflow post

---

Trail: Explain,Write

Pics:

- a slack message

---

Trail: Explain,Write

Pics:

- a slack message to slackbot

---

Trail: Explain

### Talk to the duck

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

Trail: Explain

### Talk to a person

Notes:

Same thing as before, except your coworkers are the duck
Pic: person in a duck costume

Just ask if you can explain something to them

---

Trail: Explain,Why?

### Pair with a person

Taking "talk to a person in a duck costume" a step further

todo: some basic pairing advice?

---

Trail: Explain

## Why do these work?

---

Trail: Explain,Why?

1. Forces you to think more about how things are all fitting together, so you can explain it clearly

the best way to learn or understand something is to teach it.

---

Trail: Explain,Why?

Protege effect
https://effectiviology.com/protege-effect-learn-by-teaching/

todo - fill more in here.

---

Trail: Explain,Why?

2. Challenges assumptions

To prove that the code you think is running is actually running

---

Trail: Explain,Why?

## Challenge assumptions

Notes:

All these strategies for explaining the problem have one critical thing in common:

They require you to challenge assumptions.

---

Trail: Explain,Why?,Challenge Assumptions

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

Trail: Explain,Why?

### Draw what you see, not what you THINK you see

---

Trail: Explain,Why?

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

Trail: Explain,Why?

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

Trail: Explain,Why?

### Schemas

pic: schematic drawing

Notes:

Are really just symbols

visual heuristics, kind of

When we see this drawing, we recognize it instantly as an eye

And when you ask me to draw an eye, as a child in the schematic stage, this is what I'd draw.

---

Trail: Explain,Why?

### Schemas -> Realism

pic: schematic drawing
pic: realistic drawing

Notes:

But then the artist transitions to realism

And this is what an eye ACTUALLY looks like

It's not a symbol, or a heuristic

It has incredible detail and subtlety.

---

Trail: Explain,Why?,Schemas & Symbols

Pic: biz-logic, settings, db, mail as symbols

Notes:

When you are focused on a problem in your code, you use symbols.

You make assumptions.

You build up this model in your head of all the pieces that are working together.

But they are black boxes.

They are symbols in your head, and you just assume they work as intended.

...

We _have_ to do this - because if we didn't....

---

Trail: Explain,Why?,Schemas & Symbols

Pic: focus other blocks, one at a time?

Notes:

We couldn't possibly understand the system. There would just be too much going on.

Too many details.

But our black boxes don't always work as intended.

Explaining the problem forces you to evaluate every assumption and every black box, and expand the details of each of them.

Until you can identify what's not working right.

---

Layout: module

## Isolate The Problem
---

Trail: Isolate

### Risk analysis

Notes:

Ask yourself some questions

---

Trail: Isolate, Risk Analysis

### What is the thing I've introduced that I know the least about?

### What is the thing most likely for me to improperly use?

<!-- .element: class="fragment" -->

### What is the thing I'm making the most assumptions about?

<!-- .element: class="fragment" -->

---

Trail: Isolate

## Remove code

---

Trail: Isolate, Remove Code

#### Delete code iteratively

pic: deleting code iteratively/binary search

<!-- .element: class="fragment" -->

Notes:

Binary search for the code that isn't working

---

Trail: Isolate, Remove Code

#### Back out your changes iteratively

pic: backing out of code iteratively/binary search

<!-- .element: class="fragment" -->

Notes:

Assuming it worked before you started making changes

Another form of binary search for code that isn't working

---

Trail: Isolate, Remove Code

#### Note: Use small commits!

Notes:

Side note - this is one reason that small commits is really helpful. You don't have to push them, and you can keep amending the same commit.

---

Trail: Isolate

## Build a proof of concept

Notes:

This is often what you'll do when you're getting ready to submit an issue to a project

Build a proof of concept that demonstrates the problem, so it's easier to identify/fix the bug

---

Trail: Isolate, Proof of Concept

### JavaScript

- JSFiddle
- Codepen
- CodeSandbox.io
- Quokka.js
- node

---

Trail: Isolate, Proof of Concept

### C#/.NET

- csharppad.com
- dotnetfiddle.net

---

Trail: Isolate, Proof of Concept

### Ruby/Rails

- irb
- rails console
- bundle console (ruby console in the bundle context - like rails console w/o rails.)

Notes:

rails/ios - you pretty much have to spin up an app (ask in a slack channel about this)

---

Trail: Isolate

## Eat The Frog

Notes:

there's a category of stuck where you can't get started: **analysis paralysis**.

answer: identify the hardest problem, POC it.

eat the frog: twain, "Eat a live frog first thing in the morning and nothing worse will happen to you the rest of the day."

option to throw-away code afterward

this is related to a strategy in TDD - just write code to figure out HOW you'll solve the hard problem; then throw it away & start over with TDD & the knowledge of how you'll approach the problem.

If the "hardest problem" seems big, try to identify multiple problems in it, separate them, & approach them one at a time.

---

Trail: Isolate

### Log inputs

Notes:

Your code is a tree of function calls.

Somewhere along the way, one of the functions isn't getting what it needs.

Log inputs to them, to see who doesn't have what they need!

---

TODO - figure out how to work in just plain "write tests"

---

Trail: Isolate

### Extract functions & unit test them

Notes:

Find pieces that look like they could be isolated.

Extract them to a function, pure if possible.

Write unit tests against that function

Can help you narrow down what's working and what's not

---

Trail: Isolate

## Break down problems

Notes:

Common thread for "isolate" strategies ^^^
---
Layout: module
## Escape The Problem
---

Trail: Escape

### Relax

Notes:

Take a shower, take a nap, ....

http://mentalfloss.com/article/52586/why-do-our-best-ideas-come-us-shower
A. In creativity research, we refer to the three Bs—for the bathtub, the bed and the bus—places where ideas have famously and suddenly emerged. When we take time off from working on a problem, we change what we're doing and our context, and that can activate different areas of our brain. If the answer wasn't in the part of the brain we were using, it might be in another. If we're lucky, in the next context we may hear or see something that relates—distantly—to the problem that we had temporarily put aside.

---

Trail: Escape

### Physical exercise

find research on this

https://www.newyorker.com/tech/annals-of-technology/walking-helps-us-think
https://www.ncbi.nlm.nih.gov/pubmed/20890449

---

Trail: Escape

### Other hobbies

---

Trail: Escape

### Move on to another problem

Notes:

Put this one aside. Work on something else you know how to solve. 2 things can happen:

---

Trail: Escape, Move On

#### Your brain might come up with the answer while thinking about other things

--

#### When you come back to the original problem, you have to re-learn it a bit

Notes:

This can help you challenge assumptions, like talking to the duck.

escaping is a very individualized strategy - ash plays guitar

---

Trail: Escape, Why?

### Analogical problem solving

Notes:

use information from one domain (the source or analogy) to help solve a problem in another domain (the target)
http://cognitivepsychology.wikidot.com/problem-solving:analogy

---

Trail: Escape, Why?

### Incubation

Notes:

fill in mihaly stuff here!

---

Trail: Escape

## Harden yourself for the next time

TODO this isn't really escape, anymore. What is it?

--

### Wall of motivation

--

### Persistence

---

Trail: Escape, Harden Yourself

> Curiosity and drive are in many ways the yin and the yang that need to be combined in order to achieve something new.

---

## Secret: these strategies also work for non-coding problems.

## Notes

find a place - reaching out to another person is definitely on the table, but you should make a solid effort with other strategies before doing so

mihaly csikszen...
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

    So go for a walk. Go work out. Take a shower, or a nap. Play some vids. Read a book about something unrelated. Get in your basement and do some woodworking. Go mountain biking or trail running or rock climbing. Let your brain expand this problem in many other directions.

is there anything about the mental/emotional effects of feeling stuck?
like, how do you convince yourself everything is okay when you get stuck? one option might be to "track your achievements".
---
# Summary
---

Trail: Summary

## 1. **Embrace** The Problem

### Getting Unstuck **Is The Job**

---

Trail: Summary

## 1. **Embrace** The Problem

## 2. **Explain** The Problem

### Challenge Assumptions

---

Trail: Summary

## 1. **Embrace** The Problem

## 2. **Explain** The Problem

## 3. **Isolate** The Problem

### Break Problems Down

---

Trail: Summary

## 1. **Embrace** The Problem

## 2. **Explain** The Problem

## 3. **Isolate** The Problem

## 4. **Escape** The Problem

### ??? Summarize ???

---

Footer: false

<!-- .slide: data-background="/images/title.jpg" class="title" -->

# Thank you!

- @pepopowitz
- steven.j.hicks@gmail.com
- stevenhicks.me/getting-unstuck

Notes: These are notes

and more notes here

---
