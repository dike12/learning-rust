# 🦀 Rust Book Practice Projects

Welcome! I created this repository as I work my way through [The Rust Programming Language](https://doc.rust-lang.org/book/) (often just called "The Book"). 

Reading about Rust is one thing, but actually wrestling with the borrow checker and building things is how the knowledge actually sticks. This repo contains small, focused projects designed to test and solidify the concepts learned in specific chapters.

If you are also reading The Book, you can use this repository as a companion guide for practice!

## 🛠️ How to Use This Repo

To get the most out of this, I highly recommend the following workflow:

1. **Read the Chapters:** Go through the specified chapters in The Book.
2. **Attempt the Projects:** Look at the project names in the corresponding folder, open your terminal, run `cargo new [project_name]`, and try to build it yourself using *only* the concepts you've learned so far.
3. **Get Stuck? Peek at the Solutions:** If you hit a wall or just want to see how I approached the problem, check out the `src/main.rs` files in my project folders.

## 📂 Repository Structure

The projects are grouped by chapter blocks. Inside each block, you'll find individual Cargo projects.

```text
.
├── chapter_1-3_projects
│   ├── expense_calculator
│   ├── guessing_game
│   ├── The_Twelve_Days_of_Christmas
│   └── weighted_grade_gpa_estimator
├── chapter_4-6_projects
├── chapter_7-9_projects
├── chapter_10-13_projects
└── chapter_14-20_projects
```

## ⚠️ DISCLAIMER (For the Purists)

**Please read before opening an issue telling me my code isn't "idiomatic."**

The solutions in this repository are in *no way, shape, or form* the "best," most optimal, or most idiomatic way to write Rust. 

These projects are strictly constrained by the knowledge available up to that specific chapter in The Book. For example, a project in the `chapter_1-3_projects` folder will not use Vectors or Structs, because they haven't been introduced yet—even if using them would make the code much better. 

This is a learning repository, not production-grade enterprise software. If you see me doing something clunky with parallel arrays instead of a Struct in Chapter 3, it's a feature, not a bug!
