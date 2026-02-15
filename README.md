# RealSpeak Content Repository

This repository stores the sentence packs for the Android app "RealSpeak".

The app downloads `current.json` from GitHub and upserts the data into a local Room database.

## Structure
- current.json → latest active content
- packs/ → historical versions
- backups/ → manual snapshots

## Content Rules
- Each sentence must have a stable unique ID
- Sentences are never deleted, only updated
- Deck size target: 100 sentences
- CEFR levels: A1–C2
- packVersion must increase on every update
