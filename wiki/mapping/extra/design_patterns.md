---
layout: doc
---

# Extra 02: Design Patterns
Learn how to refine your own maps

## Common terms
- **Subdivision**: To split a beat in several, smaller ones. This can be achieved by raising the beat divisor.

## Introduction
A design pattern is a term, commonly used in programming, to refer to a method that can be applied to solve
a recurrent problem.  
All of them can be explained in a single statement, and have a series of steps to follow in order to get to the
desired solution.

We can apply this concept to Rhythia, where design patterns help avoid common mistakes while mapping,
or improve a map's development. Most of them can be applied in 1 step while mapping.

:::tip
**Only apply a pattern when needed! Do not enforce them!**
:::

### Pattern Families
We refer to a "pattern family" as a group of design patterns which focus on the same matter.  
<u>Every design pattern must belong to a pattern family.</u>  

In Rhythia, we can split design patterns into 2 separate, independent families:
- **Execution**/Gameplay
- **Representation**/Sync

:::tip
**Creativity** depends fully on the mapper, so there's no way of artificially improving it.
:::

## Execution pattern family
It consists of design patterns which enhance how the map looks like in game:
- **Alternating flow**: Instead of keeping the player from going on the same direction forever, it's better to 
switch direction every few seconds.
:::info
Vibros are an exception to this rule.
:::

## Representation pattern family
It consists of design patterns which help build the map's rhythmic structure and emphasis:
- **3-5-9 Patterning**: When mapping over a **binary** [time signature](https://en.wikipedia.org/wiki/Time_signature) (ex. 4/4),
you can structure most patterns in groups of 3, 5 and 9 notes.  
This helps produce slides, spirals and mixed sections (jumps + slides/spirals).

:::tip
More generally, you should think of patterns which length fit the beat divisor's modulo + 
the linking note (located on the next beat).   

For the example earlier (4/4), you may use:
- 3 notes (4 % 2 = 0, then 2 + 1 = **3**)
- 5 notes (4 % 4 = 0, then 4 + 1 = **5**)
- 9 notes (8 % 4 = 0, then 8 + 1 = **9**)
- etc.  
:::

- **Speed changes**: A way of introducing emphasis changes (without changing the song's BPM) is by editing the
**spacing** between notes.
- In general, intense sections should have a wider spacing as break sections, and vice versa.
- Quantum can also be used to make smaller gap differences when increasing/decreasing the map's intensity.

- **Melodic layering**: Sometimes it's better to plan mapping a section beforehand, since there are cases where 
overlapping 2 or more patterns, each corresponding to a different melody/rhythm, results in an awkward rhythm choice.  
Songs with multiple time signatures at once will often have this issue.  

To solve this, it's important to <u>focus on more than one melody ONLY if necessary</u>.
- If a new melody is introduced, but it clashes with the current rhythmic structure, 
you can switch one melody out with the new one.
