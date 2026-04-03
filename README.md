# Shodan Exam Study App

Study tool for the Goju-Ryu Karate-Do Shodan (1st Dan) examination under IOGKF Denmark.

Live at **https://proteusiq.github.io/dan/**

## Pages

- **index.html** -- Landing page with countdown to exam date
- **shodan.html** -- Study cards, multiple-choice quiz, and flashcards
- **dan.html** -- Full 51-question mock exam with retry

## Content

Questions and answers are based on:

- KD-80 Karatehistorien (pensum edition, 2021)
- Official Shodan examination document (v1)

Covers historie (history), teknik (technique), bunkai (application), and terminologi (terminology).

## Security

All answer data is encrypted with AES-256-GCM (Web Crypto API, PBKDF2 key derivation, 100k iterations). No plaintext answers exist in the source. A password is required to unlock each study page.

## Stack

Three static HTML files. No build step, no dependencies, no framework. Hosted on GitHub Pages.
