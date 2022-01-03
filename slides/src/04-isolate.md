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

<!-- .slide: data-background="/images/drawings/back-out-3.png" class="back-out-code" data-background-size="contain" -->

## Back out your changes iteratively

Notes:

We can apply this process to our recent changes, too, and back them out one at a time.

If your code is a timeline of commits (using git)

Assuming everything worked before you started making changes,

You can iteratively reverse them until things are working again.

---

<!-- .slide: data-background="/images/drawings/camper-complete.jpg" class="camper inverse" -->

Trail: 2. Isolate

Notes:

If you think of your system as this super sweet lego camper

And something in it isn't working right,

---

<!-- .slide: data-background="/images/drawings/camper-remove.jpg" class="camper inverse"-->

Trail: 2. Isolate

Notes:

Code removal is like taking it apart.

Pulling sections off, until you find that you used the wrong piece.

...

Sometimes though, we aren't even sure we have the right pieces to BUILD the camper.

---

<!-- .slide: data-background="/images/drawings/camper-poc.jpg" class="camper inverse" -->

Trail: 2. Isolate

Notes:

We don't know if the pieces are going to fit together.

We don't know if the wheel is going to work with the windshield is going to work with the raft,

And maybe the reason we're stuck in this code is because these couple of dependencies are completely incompatible with each other.

In these cases, it's useful to isolate by ....

---

Trail: 2. Isolate

## Build a proof of concept

Notes:

building a proof of concept that these pieces can play together nicely.

Demonstrate the problem or subsystem, so it's easier to identify/fix the bug

Build it in a sandboxed environment, with only the required pieces to prove the implementation.

...

a lot of times we're stuck because we

don't know where to start: **analysis paralysis**.

We know we need to build this thing but there's all this complexity,

and when we start trying to build it we get lost in thought.

...

a proof of concept can help, but you don't always know what concepts to prove.

---

Layout: img-50

Trail: 2. Isolate

## Eat The Frog

![Eat the frog](/images/drawings/frog.png)

Notes:

my recommendation: eat the frog.

---

Trail: 2. Isolate, Eat The Frog

> Eat a live frog first thing in the morning and nothing worse will happen to you the rest of the day.

Mark Twain

Notes:

also heard "..and nothing worse will happen to _either_ of you..."

---

Trail: 2. Isolate, Eat The Frog

<!-- .slide: data-background="/images/drawings/deps-scary-0.png" class="deps-scary" data-background-size="contain" -->

Notes:

When you're faced with building a system with a bunch of pieces

And you don't know which pieces to start with

- top-left: ui
- top-right: rails app
- bottom-left: elasticsearch
- bottom-right: mongodb

---

Trail: 2. Isolate, Eat The Frog

<!-- .slide: data-background="/images/drawings/deps-scary-1.png" class="deps-scary" data-background-size="contain" -->

Notes:

Choose the scariest thing about this system - the most risky - and start there.

You can throw away the code afterward!

But it will get you moving.

And it gives you information about how this system will eventually come together.

...

If the "hardest problem" seems too big...

---

Trail: 2. Isolate, Eat The Frog

<!-- .slide: data-background="/images/drawings/deps-scary-2.png" class="deps-scary" data-background-size="contain" -->

Notes:

try to identify multiple problems in it,

separate them,

& approach them one at a time.

Starting with the scariest.

---

Trail: 2. Isolate

## Write tests!

Notes:

Writing tests is one of the most useful skills for solving a problem.

cuz testing is the best way to tighten your development feedback loop

of making changes, observing their effects, and repeating the cycle.

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/integration-1.png" class="integration " data-background-size="contain" -->

Notes:

Whether it's through unit tests of a tree of function calls,

integration tests of a tree of components,

or end-to-end tests of a running app,

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/integration-2.png" class="integration " data-background-size="contain" -->

Notes:

Writing a failing test at a high level

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/integration-3.png" class="integration " data-background-size="contain" -->

Notes:
and then iteratively at more isolated/granular levels

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/integration-4.png" class="integration " data-background-size="contain" -->

Notes:

Can you help you identify which of those pieces of the broken lego camper are causing the problem.

---

Layout: Summary
Trail: 2. Isolate

## Break down problems

Notes:

Common thread for "isolation" strategies ^^^

Help break a problem down from something large to something small

When it has a smaller surface area, it's easier to figure out.
