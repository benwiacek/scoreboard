# Rugby Scoreboard

An interactive scoreboard for rugby matches with real-time score tracking, game timer, and detailed statistics.

<img width="600" height="400" alt="scoreboard-screenshot" src="https://github.com/user-attachments/assets/5b3867b5-ffc4-456a-bea0-9db506323667" />

[**Live Demo**](https://scoreboard-ben.netlify.app/)

## Features

- Track scores for home and guest teams
- Multiple scoring options: tries (5 pts), conversions (2 pts), drop goals (3 pts), penalties (3 pts)
- Live game timer with start/stop functionality
- Detailed stats breakdown for each team
- Reset button to start a new game

## Built with

JavaScript, HTML, CSS

## How it works

- DOM manipulation to update scores and stats in real-time
- `setInterval()` for the game timer
- Separate counters for each scoring type
- Zero-padded display formatting for scores and time
