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
