# Memory Book Coder

A single-page tool for organising, coding, and connecting photos, mementos and narrative paragraphs for a printed memory book.

## Features

- Upload photos and scans — each gets a unique code like `2019-PH-001`
- Year selector on upload, with auto-detection from filename
- Four item types: **PH** Photo · **MT** Memento · **SC** Scan · **IT** Illustration
- Write paragraphs and link them to groups of photos — year is assigned automatically from the earliest linked photo
- Export renamed photos as a **ZIP** (files are renamed to their code on download)
- Export **CSV** for the photo index, paragraph index, and the full connection map
- Export a printable **HTML catalogue** grouped by year
- Dark mode, fully offline — no server, no database

## Usage

Open `index.html` in any modern browser. Everything runs locally in the browser; no data is sent anywhere.

## Deploy

The site is deployed automatically via Vercel on every push to `main`.

## File structure

```
index.html   ← the entire app (HTML + CSS + JS in one file)
vercel.json  ← tells Vercel to serve index.html for all routes
README.md
```
