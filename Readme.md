# ⏱ Timekeeper

A single-file time calculator that does the clock math for you — exact deadlines, and exact durations between two times.

![Status](https://img.shields.io/badge/status-prototype-yellow)
![Stack](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20JS-informational)
![Dependencies](https://img.shields.io/badge/dependencies-none-success)
![License](https://img.shields.io/badge/license-TBD-lightgrey)

---

## Why this exists

Two situations where doing the math in your head is annoying and error-prone:

**1. You're given a duration, you need the actual clock time.**
It's 12:00 PM and something is due in 20 hours 14 minutes. Is that tomorrow morning? What time, what date, exactly? Timekeeper takes the current time (or any start time you set) and a duration, and tells you precisely when it lands — including whether it rolls into the next day.

**2. You're given two clock times, you need to know the gap between them.**
A flyer says an event runs from 10:12 AM to 4:16 PM. How long is that, exactly, in hours and minutes? Timekeeper takes both times and tells you the exact duration between them — so you know how long you'll actually be there.

---

## Features

- **Live clock** — always ticking, used as the default "now" reference throughout
- **Add Duration mode** — from now (or a custom time) + days/hours/minutes → the resulting deadline, shown as both time and full date
- **Time Between Two Times mode** — two independently set times, each defaulting to today but fully editable → exact duration between them; handles either order and tells you which one comes first
- **Drum-wheel time pickers** — scroll to select hour / minute / AM-PM like a native picker; double-tap any wheel to type a value directly
- **Light / dark theme toggle**
- **Zero dependencies, zero build step** — one HTML file, works offline

---

## Tech Stack

HTML, CSS, vanilla JavaScript. No framework, no backend, no external libraries.

---

## Status

🚧 **In progress — prototype.**

It's functional and ready to use as-is, but this is not a finished product yet. No license file, no versioning, no issue templates. Expect rough edges and ongoing changes.

---

## Usage

Download `timekeeper.html` and open it in any browser. No install, no server, no setup.

---

## Author

Built by **Mark Obosojie Ohio** — DeMARK TV
