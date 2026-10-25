# Prolog Is So Awesome. Why Isn't It Widely Used?

### A personal journey through 22 years of teaching Prolog

**Scryer Prolog Meetup 2026 · Vienna, Austria · October 24–25, 2026**

**José Carpio Cañada**  
Professor of Computing and Artificial Intelligence  
University of Huelva, Spain

---

## About the talk

Prolog is expressive, elegant, and surprisingly powerful. Yet it remains far less widely used than mainstream programming languages. Why?

This presentation approaches that question through my experience teaching Prolog at the **University of Huelva since 2004**. It is a personal account of unsuccessful beginnings, a change in teaching philosophy, and the results that followed—not a controlled educational study.

For the first five or six years, roughly **80% of my students failed** Declarative Programming, a one-semester course combining Prolog and Haskell. Some spent three or four years trying to pass. A conversation with one of those students made me rethink everything.

The turning point came when my friend and mathematics professor **Manuel Maestre** connected recursion to **mathematical induction**. Rather than asking students to mentally follow recursive execution step by step, I began teaching them to reason about smaller cases, logical relationships, and base cases.

Later, **Markus Triska's _The Power of Prolog_** inspired a stronger emphasis on pure relations and **constraint logic programming (CLP)**. We also made deliberate practice central to the course, with more than **50 exercises per semester**.

Over the last decade, **more than 90% of students have passed**, with problems that, in my judgment, are at least as challenging as before. These percentages are approximate observations from my teaching experience and should not be interpreted as evidence of causation.

## The story in three acts

### Act I — The Beginning

- Teaching Prolog for the first time in 2004, without having previously studied it as a student.
- Trying to teach a declarative language through an imperative mental model.
- Facing persistently high failure rates and their consequences for students.
- Asking whether Prolog requires an exceptional ability to visualise recursion.

### Act II — The Turning Point

- A conversation with Manuel Maestre: **mathematical induction** as a way to understand recursion.
- Moving from the execution trace to reasoning about smaller instances and relationships.
- The analogy of learning to surf: **time and a lot of practice** are essential when learning a fundamentally different skill.

### Act III — The Transformation

- Learning from _The Power of Prolog_ and prioritising declarative, relational thinking and constraints.
- Practising the paradigm repeatedly instead of merely memorising language syntax.
- Reflecting on the change in classroom outcomes.
- Ending with two possible barriers to wider adoption, presented as **personal hypotheses**, not established explanations:
  1. Prolog can be difficult to learn and teach when students bring imperative programming habits.
  2. Traditional von Neumann architectures may not be the most natural match for logic programming.

The talk leaves two open questions:

> **Could we teach Prolog so that almost anyone can learn it?**
>
> **Could we build a machine better suited to Prolog?**

## View the presentation

The original slides are built with [Reveal.js](https://revealjs.com/) and use a dark theme inspired by the Scryer Prolog visual identity.

To view the presentation:

1. Clone or download this repository.
2. Open [`index.html`](index.html) in a modern web browser.
3. Use the **left/right arrow keys** or **space bar** to navigate.
4. Press **S** to open speaker notes, where supported by the browser.
5. Press **F** for fullscreen presentation mode.

A network connection is required for the Reveal.js JavaScript and CSS loaded from a CDN. If you plan to present offline, download and serve those dependencies locally beforehand.

### Project files

```text
.
├── README.md
├── index.html
├── scryer_logo.png
├── staircase_before_induction.jpg
└── surf_practice.jpg
```

The two photographs are used as visual metaphors for mathematical induction and learning through practice. If your repository uses different filenames, adjust this list accordingly.

## About the event

The talk was prepared for **Scryer Prolog Meetup 2026**, organised by the **Austrian Federal Chancellery** in cooperation with **TU Wien**, held October 24–25, 2026.

## Acknowledgements

- **Manuel Maestre**, for the conversation that connected my approach to recursion with mathematical induction.
- **Ivan Bratko**, whose Prolog book was an important reference in my early teaching years.
- **Markus Triska**, for _The Power of Prolog_ and its influence on how I teach relational programming.
- My students at the University of Huelva, whose experiences shaped this journey.
- The Scryer Prolog community and meetup organisers.

## Contact

**José Carpio Cañada**  
University of Huelva, Spain  
**Email:** [jose.carpio@dti.uhu.es](mailto:jose.carpio@dti.uhu.es)  
**YouTube:** [@josecarpioc](https://www.youtube.com/@josecarpioc)  
**GitHub:** [github.com/jcarpio](https://github.com/jcarpio/)

## Media and reuse

This repository contains slides and images assembled for a conference presentation. **Do not assume the photographs or the Scryer Prolog logo are freely reusable or sublicensable.** Verify the rights and attribution requirements for each asset before redistributing it or using it in another project. Reveal.js is a separate open-source dependency governed by its own licence.
