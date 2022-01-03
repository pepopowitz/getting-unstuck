---
Layout: module
# 1. Explain
# the problem
---

Trail: 1. Explain

## Write about the problem

---

Trail: 1. Explain,Write

### Email

### Slack

### StackOverflow

### Blog post

### Journal

### GitHub issue

### Slack **to slackbot**

Notes:

You might not even have to send the message!

Just writing it up might be enough to help you find the problem.

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

---

Trail: 1. Explain

## Talk to a person

Notes:

Maybe you feel weird talking to an inanimate object and you'd prefer...

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

or even writing a blog post about a particular topic and finding yourself researching it so that you understand it deeply enough to write the blog post,

you've experienced this.

...

Now you're not teaching someone a skill when you're explaining why you're stuck...

but you're teaching them your mental model of the problem space .

...

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

### Inspires you to think about how you'd learn the topic

Notes:

...

It also has a meta effect - while learning, you're thinking about **how** you're learning

and how others might best learn it

Psychologists call this "metacognitive processing".

---

Trail: 1. Explain,Why?,Protege Effect

> **Control**: Learn these things
>
> **Experiment**: Learn these things, _then teach them_

[Muis, Krista, et al. "Learning by preparing to teach: Fostering self-regulatory processes and achievement during complex mathematics problem solving."](http://psycnet.apa.org/doiLanding?doi=10.1037%2Fedu0000071)

Notes:

There have been a few studies about the protege effect

Highlighting one from 2016

- Control: learn these things
- experiment: Learn these things knowing you'll have to teach it

---

Trail: 1. Explain,Why?,Protege Effect

> ...students in the learning by **preparing to teach** intervention developed a more detailed and better-organized concept map of the problem...

[Muis, Krista, et al. "Learning by preparing to teach: Fostering self-regulatory processes and achievement during complex mathematics problem solving."](http://psycnet.apa.org/doiLanding?doi=10.1037%2Fedu0000071)

Notes:

findings

---

Trail: 1. Explain,Why?,Protege Effect

> ...learning by **preparing to teach**...

[Muis, Krista, et al. "Learning by preparing to teach: Fostering self-regulatory processes and achievement during complex mathematics problem solving."](http://psycnet.apa.org/doiLanding?doi=10.1037%2Fedu0000071)

Notes:

I want to zoom in on that large quote I just had up there.

It refers to the experiment group as the "learning by preparing to teach" group

They never _actually_ taught it

Neat thing about the protege effect is that you don't actually have to teach for it to work for you -

you just have to EXPECT to teach

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

<!-- .slide: data-background="/images/drawings/eye-schematic.png" class="eye" data-background-size="contain" -->

## Symbols vs. Reality

Notes:

When we see this drawing, we recognize it instantly as an eye

But that's not what an eye looks like.

That's just a _symbol_ of an eye. A shortcut, or a heuristic.

---

Trail: 1. Explain,Why?,Challenge Assumptions

<!-- .slide: data-background="/images/drawings/eye-realistic.png" class="eye" data-background-size="contain" -->

## Symbols vs. Reality

Notes:

This is what an eye ACTUALLY looks like

It's not a symbol, or a heuristic

It has incredible detail and subtlety.

- lots of colors in iris
- reflection of lashes
- bloody fleshy thing in the corner

---

Trail: 1. Explain,Why?,Challenge Assumptions,Symbols vs. Reality

<!-- .slide: data-background="/images/drawings/deps-0-complex.png" class="deps-complex" data-background-size="contain" -->

Notes:

When you are focused on a problem in your code, you use symbols.

You make assumptions.

You build up this model in your head of all the pieces that are working together.

We treat them in our head as black boxes.

They are symbols, and you just assume they work as intended.

---

Trail: 1. Explain,Why?,Challenge Assumptions,Symbols vs. Reality

<!-- .slide: data-background="/images/drawings/deps-1-complex.png" class="deps-complex" data-background-size="contain" -->

Notes:

But behind each black box lies complexity & detail

...

So much complexity that if wee _don't_ treat them as black boxes....

---

Trail: 1. Explain,Why?,Challenge Assumptions,Symbols vs. Reality

<!-- .slide: data-background="/images/drawings/deps-all-complex.png" class="deps-complex" data-background-size="contain" -->

Notes:

We couldn't possibly understand the system. There would just be too much going on.

Too many details.

When you get stuck, it often means our symbols don't reflect reality.

Our black boxes aren't doing what we _think_ they're doing.

Explaining the problem forces you to evaluate every assumption and every black box, and explore the details of each of them.

And that's when you uncover the issue.
