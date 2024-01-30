# BJJ Match Score

This application helps in keeping track of points and scores for Brazilian Jiu-Jitsu matches.

This app is designed for Jiu-Jitsu matches and is inspired by the IBJJF rules. It features a countdown timer and a card for each participant. With this app, you can award points, advantages, and penalties to each participant and decide the end of the fight by points, submission, disqualification, or W.O.

## How it can be used
### Training
Practitioners who are preparing for competitions can use this app to get used to the point system. By having another person keep track of the points, practitioners can assess their scoring after a sparring session, regardless of winning or losing the match.
### Small competitions
In situations where small or internal tournaments are understaffed, the app can be used to keep track of the points. Instead of counting on multiple referees to mediate the match and mark the scores, the main referee can use the app to mediate the match and keep track of the points.


## Technical Aspects
- Little to no server-side communication, allowing the app to be used off-line.
- Cross-device and responsive looking to serve multiple platforms and screen sizes.
- Native features like preventing notifications from popping when the match is running, and vibration feedback when interacting with the score.
- To undo points, calculate scores, and possibly reproduce matches, Piles are adopted as data structure.

## Business Concepts
- Assistent app.
- Paid versions can customize colors and logo.

## Possibilities to Scale
- It could be possible to add more modalities or different competitive sports.
- Leaderboards.
- Share features.
- Integration between this app and displays for spectators, broadcasting the score in real-time.

