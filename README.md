# Disney Park Trivia

Pass-and-play trivia party game (PWA) for EPCOT, Magic Kingdom and Hollywood Studios.

- 1-8 players, custom names, choose number of questions and parks.
- Four answers; a wrong answer disappears every few seconds.
- 3 points with four answers left, 2 with three, 1 with two, 0 if only the correct answer remains. Wrong answers score 0.
- Seen questions are remembered on the device (localStorage) and skipped until the pool runs out.

Add questions in `questions.js`, one per line: `Question|Correct answer|Wrong 1|Wrong 2|Wrong 3`. Bump `CACHE` in `sw.js` after changes.
