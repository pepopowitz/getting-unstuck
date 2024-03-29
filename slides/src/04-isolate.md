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

If your code is a timeline of commits (using git)

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

## `git bisect`

Notes:

This approach is even built into git, with the bisect command

Tell it where the last known good commit

& the first known bad commit

& it will checkout commits in between

using binary search to identify where the commit broke.

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

...

A few ways automated tests can help you isolate an issue:

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/unit-test-existing-1.png" class="unit-test-existing" data-background-size="contain" -->

## Unit tests of existing functions

Notes:

think of your system as a tree of functions calling each other

write isolated tests against each of them

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/unit-test-existing-2.png" class="unit-test-existing" data-background-size="contain" -->

## Unit tests of existing functions

Notes:

you might find the tests pass for most of them

but one you can't get to pass

This will help you verify if a function is the problem, or an innocent bystander.

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/extract-1.png" class="unit-test-extract" data-background-size="contain" -->

## Unit tests of new functions

Notes:

given a large, untested piece of code

hard to write tests to cover the whole thing

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

thinking again of our broken feature as a subtree of function calls

write an integration test that tests the entire subtree

---

Trail: 2. Isolate, Write Tests

<!-- .slide: data-background="/images/drawings/integration-2.png" class="integration " data-background-size="contain" -->

## Integration tests

Notes:

the test should fail because the system isn't working as you understand it

then...

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
