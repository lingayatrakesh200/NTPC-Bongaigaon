# NTPC Digital Logbook — Project Structure

## Current prototype

- `index.html` — complete application source: HTML + CSS + JavaScript.
- `FULL_CODE.txt` — exact copy of `index.html`.
- `README.txt` — project notes.

## Main flow

Login → Operator → Unit → Department → Shift → Equipment → Status → Readings → Save → Engineer Dashboard → Unit → Overview / History / Trends / Equipment

## Shifts

- A: 07:00–14:00
- B: 14:00–22:00
- C: 22:00–07:00

Shift Start / Mid / End are checkpoints inside the selected A/B/C duty shift.

## Prototype note

This is a front-end demo using browser storage. A production version would connect the Operator App and Engineer Web to a shared backend/database.
