# PASS OR CONFESS

<p align="center">
  <img src="pass.jpg" width="45%" alt="PASS OR CONFESS Screenshot 1">
  <img src="pass1.jpg" width="45%" alt="PASS OR CONFESS Screenshot 2">
</p>

A fast-paced social party game built entirely in HTML, CSS, and JavaScript.

Players take turns answering questions, revealing secrets, surviving chaos events, and convincing the group they're telling the truth. Every decision affects the scoreboard.

**Truth. Pressure. Chaos.**

---

## Features

### Multiple Question Categories

* Friends
* Deep
* Confession
* Spicy
* Chaos

Hundreds of prompts are included and shuffled automatically every game.

### Custom Game Settings

* 10, 20, 50, 100, or Endless rounds
* Optional turn timer
* Casual mode
* Party mode
* Risky mode
* Chaos mode

### Competitive Scoring System

* Confess and convince the group = gain points
* Lie and get caught = lose points
* Pass a question = lose points and receive a penalty

### Random Events

The game includes special surprise cards:

#### Power Cards

* Double Next Truth
* Immunity From Next Pass
* Steal Points
* Force Another Player To Answer

#### Bomb Cards

* Double Points Round
* Triple Or Nothing
* Swap Scores
* Reverse Scores
* Everyone Loses Points

### Streak Bonuses

Build honesty streaks to earn bonus points and climb the leaderboard.

### Statistics Tracking

The game stores local statistics including:

* Games played
* Highest score achieved
* Longest streak
* Most honest player

Statistics are saved using Local Storage.

### Mobile Friendly

Designed primarily for phones and pass-the-phone gameplay:

* Responsive UI
* Touch optimized
* Smooth animations
* Glassmorphism design

---

# How To Play

## 1. Configure The Game

Choose:

* Number of rounds
* Turn timer
* Difficulty level

---

## 2. Add Players

Add between **2 and 20 players**.

Players can:

* Be reordered
* Be removed
* Have custom names

---

## 3. Start The Match

The phone is passed to the active player.

Only that player should view the question.

---

## 4. Choose Your Fate

### CONFESS

Answer honestly.

The group votes:

* Truth = +2 points
* Lie = -2 points

Special cards can multiply points.

### PASS

Don't want to answer?

* Lose 1 point
* Receive a random penalty

Examples:

* Do pushups
* Speak in an accent
* Show your search history
* Let the group choose a punishment

---

## 5. Win The Game

When all rounds are completed:

* Scores are calculated
* Statistics are displayed
* A winner is crowned

The highest score wins.

---

# Built With

* HTML5
* CSS3
* Vanilla JavaScript
* Web Audio API
* Local Storage API

No frameworks.
No dependencies.
No backend.

---

# Project Structure

```text
index.html
├── UI System
├── Audio System
├── Storage System
├── Settings System
├── Prompt System
└── Game System
```

Everything runs from a single file.

---

# Why I Built This

PASS OR CONFESS was created as a lightweight social party game that can be played anywhere with a single phone.

The goal was to combine:

* Truth or Dare
* Social deduction
* Party game chaos
* Competitive scoring

into one fast and mobile-friendly experience.

---

# Creator

Created by Gajee Hub

Portfolio:
https://gajeee.github.io/Portfolio/

---

# License

This project is open-source and available for personal and educational use.
