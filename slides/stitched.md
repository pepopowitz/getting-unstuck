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
width: '100%'
height: '100%'
---
Footer: false

<!-- .slide: data-background="/images/title.jpg" class="title" -->

# Getting Unstuck

- Steven Hicks
- @pepopowitz
- steven.j.hicks@gmail.com
- stevenhicks.me/getting-unstuck

Notes:

---

Footer: false

<!-- .slide: data-background="/images/artsy.svg" data-background-size="750px" data-background-color="black" -->

Notes:

our mission is to expand the art market,

and we're doing that with a platform for collecting and discovering art.

---

Layout: module

# Stuck

Notes:

"Stuck" is a nebulous word.

Not very clear.

So I want to be clear about what I mean when I say "stuck".

Stuck is when you've been looking at code for minutes, or hours, or days, that you SWEAR should be working.

You've gone over it many times, and you can't figure out why it's not doing what you think it should be doing.

You've been looking at it so long you're frustrated.

...

My favorite thing in development is the act of getting unstuck,

or helping someone else get unstuck.

when I hear in standup that someone is stuck, my ears perk up.

Over the past few months, I've taken notes about how I and my coworkers get ourselves unstuck, and I want to share some tips with you.

...

My first strategy is...only kind of a strategy.
---
Layout: module
# 0. Embrace
# The Problem
---

## Survey time!

Notes:

1. Who in this room considers themselves a junior in their career? mid-level? senior?

(describe the breakdown)

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

Trail: 0. Embrace

# It takes time to solve problems

Notes:

So it's okay to be stuck - that's just you doing your job -

which is to solve problems, not commit lines of code.

...

with that, let's see some more actionable strategies -
---
Layout: module
# 1. Explain
# the problem
---

Trail: 1. Explain

## Write a message describing the problem

---

Trail: 1. Explain,Write

### Email

### Slack

  <!-- .element: class="fragment" -->

### Slack **to slackbot**

  <!-- .element: class="fragment" -->

### StackOverflow

  <!-- .element: class="fragment" -->

### Blog post

  <!-- .element: class="fragment" -->

### GitHub issue

  <!-- .element: class="fragment" -->

Notes:

You might not even have to send the message!

---

Layout: img-30

Trail: 1. Explain

## Talk to the duck

![Talk to the duck](/images/drawings/talk-to-the-duck.png)

Notes:

Explain what it is

Comes from a story in https://en.wikipedia.org/wiki/The_Pragmatic_Programmer

Doesn't have to be to a duck

Doesn't have to be to a real THING
But it _can_ be a real thing

it can be imaginary

But it is definitely most effective when it is out loud

Explain the problem to the duck.

Walk them through the code. Out loud.

...

the duck can be a fake thing...

---

Trail: 1. Explain

## Talk to a person

Notes:

TODO: pic: coworker in a duck costume?

Or it can be a real thing.

Same thing as before, except your coworkers are the duck

Ask them to come look over your shoulder

Explain the problem,

what is/isn't happening,

and walk them through the code.

---

Trail: 1. Explain

## Pair with a person

Notes:

Taking "talk to a person in a duck costume" a step further

we pair a TON at artsy

not all the time - that can overwhelm people

but a couple hours a day works really great for tricky problems.

---

Trail: 1. Explain

## Why do these work?

Notes:

I think they can partly be explained by something in psych called...

---

Trail: 1. Explain,Why?

## Protege Effect

### The best way to learn or understand something is to teach it.

Notes:

if you've ever taught someone something,

through 1on1, or a lunch n learn, or a workshop, or teaching interns,

you've seen this.

A couple things that happen when you're teaching something:

---

Trail: 1. Explain,Why?,Protege Effect

### Inspires you to learn the topic thoroughly

Notes:

Because you're going to have to explain it,

& you don't want to look a fool,

you use better learning strategies.

---

Trail: 1. Explain,Why?,Protege Effect

### Forces you to think more about how things are all fitting together, so you can explain it clearly

Notes:

...

It also has a meta effect - while learning, you're thinking about **how** you're learning

and how others might best learn it

Psychologists call this "metacognitive processing".

---

Trail: 1. Explain,Why?,Protege Effect

> ...students in the learning by **preparing to teach** intervention developed a more detailed and better-organized concept map of the problem...

[Muis, Krista, et al. "Learning by preparing to teach: Fostering self-regulatory processes and achievement during complex mathematics problem solving."](http://psycnet.apa.org/doiLanding?doi=10.1037%2Fedu0000071)

Notes:

Interesting thing about the protege effect is that you don't actually have to teach for it to work for you -

you just have to EXPECT to teach

This is from a study from 2016 demonstrating the protege effect

---

Layout: Summary

Trail: 1. Explain,Why?

## Challenge assumptions

Notes:

The other thing that happens when you explain something to someone:

To prove that the code you think is running is actually running

...

IMO, This is the most critical and important thing about ALL of these "explanation" strategies:

They prompt you to challenge assumptions.

---

Trail: 1. Explain,Why?,Challenge Assumptions

> "Experience this one thing for what it is, not what you think it is."

Mihaly Csikszentmihaly, "Creativity: Flow and the Psychology of Discovery and Intervention", 1997

Notes:

this makes me think about some ideas from Mihaly.

Mihaly - wrote "Creativity"

psychologist who introduces concept of "Flow"

it's kind of philosophical, almost zen

....

this is similar to what I remember being taught in art class

And what my kids are learning about their art

---

Trail: 1. Explain,Why?,Challenge Assumptions

## Draw what you see, not what you THINK you see

---

Trail: 1. Explain,Why?,Challenge Assumptions

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

Trail: 1. Explain,Why?,Challenge Assumptions

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

Trail: 1. Explain,Why?,Challenge Assumptions

<!-- .slide: data-background="/images/drawings/eye-schematic.png" class="eye" data-background-size="contain" -->

## Schematic

Notes:

Are really just symbols

visual heuristics, kind of

When we see this drawing, we recognize it instantly as an eye

And when you ask me to draw an eye, as a child in the schematic stage, this is what I'd draw.

---

Trail: 1. Explain,Why?,Challenge Assumptions

<!-- .slide: data-background="/images/drawings/eye-realistic.png" class="eye" data-background-size="contain" -->

## Schematic vs. Realistic

Notes:

But then the artist transitions to realism

And this is what an eye ACTUALLY looks like

It's not a symbol, or a heuristic

It has incredible detail and subtlety.

---

Trail: 1. Explain,Why?,Challenge Assumptions,Schemas & Symbols

<!-- .slide: data-background="/images/drawings/deps-0-complex.png" class="deps-complex" data-background-size="contain" -->

Notes:

When you are focused on a problem in your code, you use symbols.

You make assumptions.

You build up this model in your head of all the pieces that are working together.

We treat them in our head as black boxes.

They are symbols, and you just assume they work as intended.

---

Trail: 1. Explain,Why?,Challenge Assumptions,Schemas & Symbols

<!-- .slide: data-background="/images/drawings/deps-1-complex.png" class="deps-complex" data-background-size="contain" -->

Notes:

But behind each black box lies complexity & detail

...

We _have_ to treat them as black boxes, though -

because if we didn't....

---

Trail: 1. Explain,Why?,Challenge Assumptions,Schemas & Symbols

<!-- .slide: data-background="/images/drawings/deps-all-complex.png" class="deps-complex" data-background-size="contain" -->

Notes:

We couldn't possibly understand the system. There would just be too much going on.

Too many details.

But our black boxes don't always work as intended.

Explaining the problem forces you to evaluate every assumption and every black box, and explore the details of each of them.

And that's when you uncover the issue.
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

<!-- .slide: data-background="/images/drawings/remove-code-1.png" class="remove-code" data-background-size="contain" -->

## Delete code iteratively

Notes:

Binary search for the code that isn't working

---

Trail: 2. Isolate, Remove Code

<!-- .slide: data-background="/images/drawings/remove-code-2.png" class="remove-code" data-background-size="contain" -->

## Delete code iteratively

Notes:

This isn't always as simple as just deleting lines - often you'll need to rewrite code to accommodate the deleted lines.

But you've removed complexity.

---

Trail: 2. Isolate, Remove Code

<!-- .slide: data-background="/images/drawings/remove-code-3.png" class="remove-code" data-background-size="contain" -->

## Delete code iteratively

Notes:

And eventually, you'll be able to isolate a smaller block of focus.

And then instead of dealing with 50 lines of code that don't work, you have 10.

---

Trail: 2. Isolate, Remove Code

<!-- .slide: data-background="/images/drawings/back-out-1.png" class="back-out-code" data-background-size="contain" -->

## Back out your changes iteratively

Notes:

Similarly, you can do a binary search of your recent changes.

Assuming everything worked before you started making changes,

---

Trail: 2. Isolate, Remove Code

<!-- .slide: data-background="/images/drawings/back-out-2.png" class="back-out-code" data-background-size="contain" -->

## Back out your changes iteratively

Notes:

You can iteratively reverse them until things are working again -

---

Trail: 2. Isolate, Remove Code

<!-- .slide: data-background="/images/drawings/back-out-3.png" class="back-out-code" data-background-size="contain" -->

## Back out your changes iteratively

Notes:

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

TODO - lego camper as a demonstration of poc vs ripping code out

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## `> node`

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## [Quokka.js](https://quokkajs.com/)

quokkajs.com

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## [JSFiddle](http://jsfiddle.net)

jsfiddle.net

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## [CodePen](https://codepen.io)

codepen.io

---

Trail: 2. Isolate, Proof of Concept, JavaScript

## [CodeSandbox](https://codesandbox.io/)

codesandbox.io

---

Trail: 2. Isolate, Proof of Concept, C#/.NET

## [C# Pad](http://csharppad.com/)

csharppad.com

---

Trail: 2. Isolate, Proof of Concept, C#/.NET

## [.NET Fiddle](https://dotnetfiddle.net/)

dotnetfiddle.net

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

Trail: 3. Isolate, Proof of Concept

## [repl.it](https://repl.it)

repl.it

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

<!-- .slide: data-background="/images/drawings/deps-scary-0.png" class="deps-scary" data-background-size="contain" -->

Notes:

When you're faced with building a system with a bunch of pieces

And you don't know which pieces to start with

---

Trail: 2. Isolate, Eat The Frog

<!-- .slide: data-background="/images/drawings/deps-scary-1.png" class="deps-scary" data-background-size="contain" -->

Notes:

Choose the scariest thing about this system - the most risky - and start there.

You can throw away the code afterward!

But it will get you moving.

And it gives you information about how this system will eventually come together.

...

this is a good strategy in TDD, too - write code to figure out HOW you'll solve the hard problem; then throw it away & start over test-driven & with the knowledge of how you'll approach the problem.

---

Trail: 2. Isolate, Eat The Frog

<!-- .slide: data-background="/images/drawings/deps-scary-2.png" class="deps-scary" data-background-size="contain" -->

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

cuz testing is the best way to tighten your development feedback loop

of making changes, observing their effects, and repeating the cycle.

Without tests, your loop can be loose - it could be weeks or months before you see your code deployed and know if it worked.

With tests, your loop can be as tight as a couple seconds.

...

A few ways automated tests can help you isolate an issue:

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/unit-test-existing-1.png" class="unit-test-existing" data-background-size="contain" -->

## Unit tests of existing functions

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/unit-test-existing-2.png" class="unit-test-existing" data-background-size="contain" -->

## Unit tests of existing functions

Notes:

This will help you verify if a function is the problem, or an innocent bystander.

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/extract-1.png" class="unit-test-extract" data-background-size="contain" -->

## Unit tests of new functions

Notes:

Find pieces that look like they could be isolated.

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/extract-2.png" class="unit-test-extract" data-background-size="contain" -->

## Unit tests of new functions

Notes:

Extract them to a function.

Write unit tests against that function

Can help you narrow down whether this functionality is the problem

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/integration-1.png" class="integration " data-background-size="contain" -->

## Integration tests

Notes:

Effective strategy: integration tests iteratively from the top down -

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/integration-2.png" class="integration " data-background-size="contain" -->

## Integration tests

Notes:

Test the system together. Does it fail? If so...

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/integration-3.png" class="integration " data-background-size="contain" -->

## Integration tests

Notes:

choose a branch and write a test one level down.

Does that fail?

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/integration-4.png" class="integration " data-background-size="contain" -->

## Integration tests

Notes:

Write one another level down.

Repeat until you get an integration test that passes.

The culprit is likely related to the lowest failing integration test.

...

you can also combine them with debugging or logging your inputs iteratively down the tree, to find the culprit.

...

If you've struggled to write tests, and you'd like to talk more, please come find me.

I'll do everything I can to help you get over your hurdles.

---

Layout: Summary
Trail: 2. Isolate

## Break down problems

Notes:

Common thread for "isolation" strategies ^^^

Help break a problem down from something large to something small

When it has a smaller surface area, it's easier to figure out.
---
Layout: module
# 3. Escape
# The Problem
---

Trail: 3. Escape

## Relax

Notes:

Take a shower, take a nap, ....

When you relax, and shut your brain off from a problem, and let it wander,

other areas of your brain activate, and can find solutions without you trying.

you're also more open-minded to the problem - and less likely to dismiss ideas that don't seem obviously related.

Relaxing is just a great way to be creative.

---

Trail: 3. Escape

## Physical exercise

Notes:

- Increases blood flow to brain
- improves executive functions
- Improves mood (which can give you the push you need to get back at the problem)
- If rhythmic & repetitive, your mind can shut off & wander

---

Trail: 3. Escape

## Other hobbies

Notes:

Similar effects to resting - our brain explores new ideas

this is a very individualized strategy -

ash plays guitar,

maybe you like to draw,

i like to exercise.

---

Trail: 3. Escape

## Move on to another problem

Notes:

Put this one aside. Work on something else you know how to solve.

This _feels_ like a more productive version of escaping.

3 things can happen:

---

Trail: 3. Escape, Move On, Why?

### 1. Solving a simpler problem can boost your confidence

Notes:

I do this in rock climbing. I lose confidence working on a hard route.

After completing a couple simple climbs, I can attack the original problem with renewed confidence.

---

Trail: 3. Escape, Move On, Why?

### 2. Your brain might come up with the answer while thinking about other things

---

Trail: 3. Escape, Move On, Why?

### 3. When you come back to the original problem, you have to re-learn it a bit

Notes:

This can help you challenge assumptions, like talking to the duck.

...

These "escape" strategies take advantage of a couple psychological principles:

---

Trail: 3. Escape, Why?

## Analogical problem solving

Notes:

use information from one domain (the source or analogy)

to help solve a problem in another domain (the target)

http://cognitivepsychology.wikidot.com/problem-solving:analogy

...

This happens when you notice parallels between two very different activities;

this prompts you to notice OTHER parallels between them

which can include a reframing of the problem in a way you hadn't before.

---

Trail: 3. Escape, Why?

## Incubation

---

Trail: 3. Escape, Why?, Incubation

## 4 Stages of Creativity

1. Preparation
2. Incubation
3. Illumination
4. Verification

Graham Wallas, "The Art Of Thought", 1926

Notes:

Political scientist

1: problem is investigated consciously, in many directions

2: you put the problem away. Do nothing, or do a different problem. Unconscious processing.

3: the preparation & the incubation come together, and you have a sudden insight.

4: conscious analysis of the idea. Prove it out.

These don't happen in isolation - they very much play together.

---

Trail: 3. Escape, Why?, Incubation

## 5 Stages of Creativity

1. Preparation
2. Incubation
3. Illumination
4. Evaluation
5. Elaboration

Mihaly Csikszentmihaly, "Creativity: Flow and the Psychology of Discovery and Intervention", 1997

Notes:

4: vet the idea

5: expand on your new ideas. Test them, refine them, figure out how to best apply them.

---

Trail: 3. Escape, Why?, Incubation

> ...ideas churn around **below the threshold of consciousness**. It is during this time that **unusual connections** are likely to be made.

Mihaly Csikszentmihaly, "Creativity: Flow and the Psychology of Discovery and Intervention", 1997

Notes:

---

Trail: 3. Escape, Why?, Incubation

> When we intend to solve a problem consciously, we process information in a linear, logical fashion. But when ideas call to each other on their own, **without our leading them down a straight and narrow path**, unexpected combinations may come into being.

Mihaly Csikszentmihaly, "Creativity: Flow and the Psychology of Discovery and Intervention", 1997

Notes:

_unusual & unexpected_

---

Trail: 3. Escape, Why?, Incubation

<!-- .slide: data-background="/images/drawings/processing-linear.png" class="processing" data-background-size="contain" -->

Notes:

He even goes on to compare this to parallel computing, right in our wheelhouse:

when we are consciously thinking about a problem, we push it in a linear direction.

---

Trail: 3. Escape, Why?, Incubation

<!-- .slide: data-background="/images/drawings/processing-parallel.png" class="processing" data-background-size="contain" -->

Notes:

when we let it incubate, it expands to parallel processing.

This allows a freedom to your problem solving:

things can combine in ways that your conscious mind would reject.

...

From "Creativity":

The distinction between serial and parallel processing of information may also explain what happens during incubation. In a serial system like that of an old-fashioned calculator, a complex numerical problem must be solved in a sequence, one step at a time. In a parallel system such as in advanced computer software, a problem is broken up into its component steps, the partial computations are carried out simultaneously, and then these are reconstituted into a single final solution. Something similar to parallel processing may be taking place when the elements of a problem are said to be incubating. When we think consciously about an issue, our previous training and the effort to arrive at a solution push our ideas in a linear direction, usually along predictable or familiar lines. But intentionality does not work in the subconscious. Free from rational direction, ideas can combine and pursue each other every which way. Because of this freedom, original connections that would be at first rejected by the rational mind have a chance to become established.

---

Layout: Summary
Trail: 3. Escape

## Set It Aside

Notes:

Often when we're faced with a difficult problem, we think we need to really focus on it.

We think that we are procrastinating if we aren't actively attacking it.

But the truth is, for really complicated problems, where your brain and your creativity need to expand in many directions to find a solution, staying actively focused can be a detriment. Giving your brain some room to explore the space, on its own time, can help you explore ideas that your focused, rational mind would initially reject.

- walk
- work out
- Take a shower
- or a nap.
- Read a book about something unrelated.
- basement - woodworking.
- Knit.
- mountain biking, trail running, rock climbing.

Let your brain expand this problem in many other directions.
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

## Learn new ways to solve problems

Notes:

- Pair (even when not stuck)
- read code in other projects
- explore new technologies
- learn for the sake of learning

---

Trail: 4. Harden

## Wall of motivation

Notes:

I keep a trello board, to remind myself that I'm succeeding at my job.

Whatever measures as a win to you

For me it's messages of really helping people

praise I've gotten from workshops and talks

And times when I've showed great perseverance.

---

Trail: 4. Harden

## Keep a journal

Notes:

Another of my coworkers, Eloy, who lives on a houseboat in Amsterdam,

recommended when I first started at Artsy to keep a journal

of things I did every day - so I could see that I **AM** getting things done.

Sometimes they aren't things I can check off a list,

they are times when I knew I was doing my job of solving problems.

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

Notes:

Variety of mental & physical benefits

Especially leveling your emotions, which can factor into getting stuck

and increases your ability to persist through challenges

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

## Condition yourself

Notes:

Get in the reps

Strengthen yourself

Professional athletes condition themselves for incredible physical challenges.

Professional developers need to condition themselves for incredible mental challenges.
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

## 3. **Escape**: Set It Aside

<!-- .element: class="fragment" -->

## 4. **Harden**: Condition Yourself

<!-- .element: class="fragment" -->

Notes:

...

it is very possible that you've used every one of these strategies

Even so, it can be helpful to think about them the next time you're stuck.

---

Footer: false

<!-- .slide: data-background="/images/title.jpg" class="title" -->

# Thank you!

- Steven Hicks
- @pepopowitz
- steven.j.hicks@gmail.com
- stevenhicks.me/getting-unstuck

---

Trail: Resources

- https://medium.com/@williardx/to-start-meditating-stop-trying-to-empty-your-mind-fe67a7ed113b
- https://www.amazon.com/Creativity-Flow-Psychology-Discovery-Invention/dp/0060928204/ref=sr_1_3?s=books&ie=UTF8&qid=1356490941&sr=1-3&keywords=csikszentmihalyi+flow
- https://traviswhitecommunications.com/2012/12/26/creativity-in-five-steps/
- http://groups.psych.northwestern.edu/gentner/papers/Gentner02a.pdf
- https://www.blinkist.com/books/creativity-en?r=1&st=mihaly
- Protege effect: https://effectiviology.com/protege-effect-learn-by-teaching/
- Protege effect: http://psycnet.apa.org/doiLanding?doi=10.1037%2Fedu0000071
- Protege effect: https://link.springer.com/article/10.3758/s13421-014-0416-z
- Relax: http://mentalfloss.com/article/52586/why-do-our-best-ideas-come-us-shower
- Exercise: https://www.newyorker.com/tech/annals-of-technology/walking-helps-us-think
- Analogical problem solving: http://cognitivepsychology.wikidot.com/problem-solving:analogy
