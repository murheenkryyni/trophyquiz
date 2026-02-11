# 🏆 Trophy Quiz

Trophy Quiz is a small, personal Christmas present project made for a trophy-obsessed partner.

It’s a simple browser game where the player guesses PlayStation trophies based on their name and image.

The goal is to test how well someone remembers their own trophy history.

## 🎮 How the Game Works

For each trophy, the player must guess:
- 🎯 Which game the trophy is from
- 🏅 What type of trophy it is (Platinum / Gold / Silver)
- 📅 What year it was earned

## Scoring
+1 point → Correct game
+1 point → Correct trophy type
+1 point → Correct year

💡 Using a hint reveals the description but costs 1 point

Each trophy is worth up to 3 points.

## ✨ Features

- Simple, lightweight HTML + JavaScript implementation
- Clean responsive UI with minimal CSS
- Multiple choice quiz system
- Score tracking & feedback messages
- Hint system
- Randomized questions

Progressive Web App (PWA) support:
- Installable on mobile
- Offline caching via Service Worker

## 📁 Project Structure
.
├── index.html              # Main game UI + logic
├── trophies-filtered.json  # Trophy dataset
├── service-worker.js       # Offline caching
├── manifest.json           # PWA configuration

## 📦 Trophy Data Format

Each trophy object looks like:

{
  "game": "Epic Mickey: Rebrushed",
  "name": "Small World",
  "description": "Paint or Thin the mad Clock Tower",
  "type": "silver",
  "image": "https://...",
  "rarity": 64.9,
  "date": "23rd Nov 2025"
}

## 🛠️ Built With
- HTML5
- Vanilla JavaScript
- CSS
- Service Workers (for offline support)

No frameworks, no dependencies.

## ❤️ About This Project

This was built as a fun, personal gift project — not meant to be a large-scale app, but a lightweight and meaningful little game.

## 📜 License

This project is personal and not licensed for redistribution.
