<img width="2000" height="720" alt="image" src="https://github.com/user-attachments/assets/9bb60b6b-ea4a-440e-b977-7fb348663846" />

# Grid World Robot Simulator

A text-based robot simulation, built in Python, one phase at a time.

> **Status:** Phase 1 of 8 in progress.
> This is a learning project. The banner above shows the **goal**, not what exists today.

---

## About

This is one living project that keeps growing until I finish my Python roadmap, and I don't rebuild it from scratch. Each time I finish learning a Python concept, I add it here. So the commit history is basically my learning diary. It shows how my understanding grows, including the messy early code.

## Why I'm building this

Currently, I'm learning Python because in the future I want to work in both software engineering and robotics engineering (including control systems), with AI as the bridge connecting the two.

But learning syntax and practicing theory won't make me a skilled problem solver or a system-thinking engineer if I can't actually build things with what I learn. I can do a hundred small exercises and still not know how to build something real. So instead of writing a new small program for every topic, I'm putting every concept I learn into one project that grows as I learn.

I picked a robot simulator because a robot thinks in a simple loop: look around, decide, move. Almost every Python topic fits into that loop: variables, if/else, loops, lists, functions, classes, errors and files. So I thought it would be a good way to use everything I learn.

What I want out of this project:

- Really understand the basics and how a system actually works
- Learn to figure out what a situation needs, and then build it
- Not just memorise syntax, but use every concept in real code while I'm learning it
- Be able to find, understand and fix my own bugs
- Have a real project that shows how I improved, step by step

## The idea (robot "brain" loop)

The robot repeats three steps again and again:

1. **Sense**: look at the world around it
2. **Decide**: choose what to do
3. **Act**: do it

## What works now (Phase 1)

- Robot position
- Battery percentage
- Step count
- A flag for whether it's charging (`is_charging`)
- Printing the robot status

## What does not exist yet

- The map, walls and obstacles
- Moving around until the battery runs out
- Functions, classes, error handling
- Reading and saving files
- Multiple robots and delivery tasks

## How to run

```
python main.py
```

Made with Python 3.

## Roadmap

This is the roadmap I'm following while learning Python. Every concept from every phase gets added to this project.

- [ ] Phase 1: Basics (execution, variables, data types, mutability)
- [ ] Phase 2: Control flow and loops
- [ ] Phase 3: Data structures (list, tuple, dict, set, comprehensions)
- [ ] Phase 4: Functions and lambda
- [ ] Phase 5: OOP and magic methods
- [ ] Phase 6: Error handling
- [ ] Phase 7: File handling and modules
- [ ] Phase 8: Capstone, everything combined

A concept counts as done only after **Theory + Practice + Implementation** in this project.

## Rules of this project

- Text only. No GUI, no images inside the program.
- No pathfinding before Phase 8. Until then, the robot follows simple rules.
- I only use concepts I have already learned. Nothing extra.

## Project structure

```
main.py
README.md
NOTES.md
assets/
```

The structure will change when I reach Phase 8 and split the code into modules.

## Learning notes

See [NOTES.md](NOTES.md) for what I find weak in my own code after each phase, and what I plan to fix.
