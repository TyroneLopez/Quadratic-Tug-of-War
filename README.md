# Quadratic Tug of War

An augmented reality (AR) classroom game for Grade 10 Mathematics. Two teams race to solve quadratic problems by pinching floating answer blocks in the air with their hands. Every correct answer pulls the rope toward their side.

The game uses the webcam and Google MediaPipe hand tracking. It runs in the browser from a single HTML file, with nothing to install.

## Topics covered

| Topic | Students… |
|---|---|
| Nature of roots | compute the discriminant b² − 4ac and classify the roots (real, rational and unequal; real, irrational and unequal; real, rational and equal; not real) |
| Roots of a quadratic equation | find both values of x |
| Equation from zeros | write y = x² + bx + c given the zeros |
| Equation from vertex and a point | write y = a(x − h)² + k |
| Equation from 3 points | write y = ax² + bx + c |
| Problem solving | solve projectile, fencing (maximum area) and maximum-product problems |
| Mixed | get a random question from any topic above |

Questions are generated at random with whole-number answers, so every round is new.

## How to play

1. **Set up:** enter the team names, pick a play style, the number of rounds (1, 3 or 5) and the time per round (2 to 5 minutes).
2. **Flip the coin:** the team that wins the toss chooses the topic or lets the other team choose.
3. **Race:** the screen is split in half, one side per team. A player pinches a block with thumb and index finger, carries it to an answer box, and opens their fingers to drop it.
4. **Pull:**
   - A correct answer pulls **12** plus up to **8 speed bonus**.
   - Every 3rd correct answer in a row is a **Power Pull (×2)**.
   - A wrong answer makes the team **slip**, and it is frozen for 3 seconds.
5. **Win:** pull the flag to your line. When time runs out, the side the flag is on wins. A tie goes to **sudden death**: the next correct answer wins.

### Play styles

- **Champions:** the same two players solve the whole round while teammates coach.
- **Relay:** players switch after every correct answer. Shy students can cheer first and step in when they are ready.

Scratch paper, mental solving and coaching are all allowed. How the team uses them is part of its strategy.

## Running it

**Option 1: GitHub Pages (recommended).** Turn on Pages for this repository, then open the site link in Chrome or Edge and allow camera access.

**Option 2: Local file.** Download `index.html` and open it in Chrome or Edge.

**Requirements:**

- **Webcam:** a laptop webcam works.
- **Internet on first load:** to fetch the hand-tracking model.
- **Big screen (recommended):** an LED TV or projector. Use the **Fullscreen** button.

There is also a **Start with mouse** option for testing without a camera.

### Teacher controls

- **Pause:** resume, end the round now, or start a new match.
- **Skip:** gives a team a new question if it is stuck.
- **Fullscreen:** fills the classroom display.

## Built with

- HTML, CSS and JavaScript, all in one file
- [MediaPipe Hand Landmarker](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) for hand tracking
- Google Fonts: Lilita One and Atkinson Hyperlegible

## Author

Tyrone Marcial V. Lopez, LPT, MST
