# reformer-programming-tool
This is a tool to assist Pilates instructors in creating programs for clients that allow for flow optimization as well as accomodate for special populations
# Reformer Flow

**A session programming tool for Pilates reformer instructors.**

Live tool at [pujagandhi.com/reformer-flow](https://pujagandhi.com/reformer-programming-tool)

---

## The Problem

Pilates reformer instructors program sessions by hand often on paper, in notes apps, or from memory. There is no purpose-built digital tool for reformer sequencing.

This creates a recurring frustration: **poorly sequenced sessions require clients to constantly reposition their bodies and wait while the instructor adjusts spring resistance between exercises.** Every unnecessary transition interrupts the flow of the session, reduces workout efficiency, and affects the client experience.

For instructors running back-to-back sessions, this friction compounds. A well-sequenced program isn't just better for the client it signals professionalism and expertise.

---

## The Solution

Reformer Flow is a browser-based programming tool that lets instructors:

- **Build and codify an exercise library**  storing each exercise's spring settings, body position, and primary/secondary muscle groups in one place
- **Sequence sessions visually** dragging and reordering exercises in a program builder
- **Optimize for flow** the tool automatically flags spring changes and body position changes between consecutive exercises, so instructors can reorder their sequence to minimize disruption
- **Track a Flow Score** a composite metric that scores how smooth a session sequence is, based on the number of position and spring transitions

---

## Who It's For

**Primary user:** Pilates instructors and studio owners who program reformer sessions for clients.

These users typically have deep exercise knowledge but no technical background. The tool is designed to feel intuitive without any onboarding â€” if you understand a reformer, you understand the interface.

---

## Key Features

| Feature | Description |
|---|---|
| Exercise Library | Store exercises with spring settings, body direction, and muscle groups |
| Spring Visualizer | Color-coded spring display (Red, Blue, Yellow, Green) matching standard reformer equipment |
| Body Part Tagging | Tag primary and secondary muscles; the tool prevents double-tagging |
| Program Builder | Build session sequences with drag-and-drop reordering |
| Flow Analysis | Real-time count of spring changes, position changes, and a Flow Score |
| Transition Warnings | Inline alerts on each exercise when a position or spring change is required |
| Persistent Storage | All data saves to the browser automatically â€” no account required |

---

## Product Decisions

**Why browser-based with no login?**
The target user is a working instructor, often programming between sessions on a laptop or tablet. A login-gated tool adds friction at the exact moment when low friction matters most. Browser localStorage means zero setup and instant access.

**Why a Flow Score?**
Instructors instinctively know a well-sequenced session when they feel it, but may not have a way to evaluate a program on paper before running it with a client. Quantifying flow gives the instructor an at-a-glance signal without requiring them to manually trace through every transition.

**Why color-coded springs?**
The reformer industry standardizes spring colors across most major equipment brands (Balanced Body, Stott, Peak). Matching the visual language of the equipment reduces cognitive load â€” instructors don't need to translate between the tool and the machine.

---

## Built With

- Vanilla HTML, CSS, and JavaScript no frameworks or dependencies
- Browser localStorage for data persistence
- Designed as a single-file app for easy hosting and portability

---

## Roadmap

The following features are planned for future iterations, prioritized by instructor impact:

**Near-term**
- [ ] Client profiles attach programs to specific clients and track session history
- [ ] Exercise categories and filters group by body focus, difficulty, or equipment type
- [ ] Duplicate and remix programs copy a program as a starting point for a new one

**Medium-term**
- [ ] Smart sequencing suggestions automatically reorder a program to minimize transitions
- [ ] Export to PDF shareable session sheets for printing or sending to clients
- [ ] Exercise video / image links attach reference media to each exercise

**Longer-term**
- [ ] Mobile-optimized view for use during a live session
- [ ] Multi-instructor studio accounts shared exercise library across a team
- [ ] Analytics track which exercises and programs are used most across a client roster

---

## About

Built by [Puja Gandhi](https://pujagandhi.com)  a Pilates professional and aspiring product manager with a background across both fitness and technology.

This project was built to explore the intersection of domain expertise and product thinking: identifying a real workflow pain point, designing a solution around user behavior, and shipping a functional tool end-to-end.

---

*Feedback and contributions welcome. Open an issue or reach out at [gandhi.pj@gmail.com](https://pujagandhi.com).*
