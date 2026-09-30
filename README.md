# Gym Companion

A fitness web app with a React front end and a Node.js/MySQL back end. It helps users plan workouts and track their diet.

Built as a two-person team project for the Professional Practice in IT (PPIT) module, Year 3, GMIT (2022).

## Features

**Front end (React):**
- BMI calculator
- BMR calculator
- Calorie tracker (log meals and keep a running total)
- Nutrition facts page
- A navigation bar that routes between all the components

**Back end (Node.js + MySQL):**
- User sign-up and login (passwords stored AES-encrypted in MySQL)
- Workout plans by body type and body part, generated from an exercise database
- Diet plans and training-day selection
- Server-rendered EJS views for the account and plan screens

## Tech stack

React 18 · React Router · React Bootstrap / Reactstrap · Node.js · Express · MySQL · EJS

## Getting started

1. Create the database with `fitness.sql` (it creates `fitnessDB`).
2. Install dependencies and start the React app:
   ```bash
   npm install
   npm start
   ```
3. Start the back end (`src/backend/server.js`) with Node.

`setupProject.pdf` has the full setup steps.

## Documentation

- `PPIT-Documentation/`: project proposal, sprints and user stories, and the final report
- `TestingPPIT/`: business requirements, unit test plan and regression test plan
- `PPIT-ProjectScreencast.mp4`: video walkthrough

## Team

| | Contribution |
|---|---|
| **Aaron Darcy** | React front end: navbar and routing, BMI and BMR calculators, calorie tracker, nutrition page, documentation sections |
| **Liam** ([@LiamB16](https://github.com/LiamB16)) | Node.js back end (`MySqlDao.js`, `server.js`, EJS views), database design and data, front-end/back-end integration, test plan with unit and regression testing, architecture diagrams, user stories |
