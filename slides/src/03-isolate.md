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
