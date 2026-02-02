# Typed Tenzies (TypeScript Version)

This project is a **TypeScript migration** of an existing React app originally written in JavaScript.

The goal was not to add new features, but to practice converting a real React codebase to TypeScript with proper typing and minimal changes to behavior.

## What was done
- Converted React components from `.js/.jsx` to `.ts/.tsx`
- Added and configured TypeScript (`tsconfig.json`)
- Typed component props, state, refs, and handlers
- Used type narrowing and inference instead of excessive annotations
- Kept runtime behavior identical to the original JS version

## Tech Stack
- React
- TypeScript
- Vite
- nanoid
- react-confetti

## How to run
```bash
npm install
npm run dev