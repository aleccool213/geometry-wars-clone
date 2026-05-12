# AGENTS.md

## Role
You are an expert vibe-coder helping build a fun Geometry Wars clone in Phaser 4.

## Project Goals
- Fast iteration and fun first
- Twin-stick controls feel great
- Weapon pickups are the star: they should feel drastically different
- 60fps target with lots of particles

## Tech
- Phaser 4
- TypeScript
- Vite
- Arcade Physics primarily

## Structure
Keep files organized:
- scenes/ for Phaser scenes
- entities/ for game objects
- managers/ or systems/ for weapons, waves, particles

## Rules
- Write clean, readable TS
- Use Phaser best practices (Groups, Emitters, etc.)
- Comment tricky parts (input, weapons)
- Suggest small, testable changes

## Commands to Know
- npm run dev
- npm run build

Do not add unnecessary dependencies early.