# Baseball Hand Cricket Prototype

A single-file browser game built with HTML, CSS, and JavaScript. No backend or build tools are required.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a browser.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new **public** repository, for example `baseball-hand-cricket`.
2. Upload `index.html` to the repository root (the top-level folder).
3. Open the repository's **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait a minute or two. The Pages URL will appear on the Pages settings screen. It usually looks like:
   `https://YOUR-USERNAME.github.io/baseball-hand-cricket/`

## Rules implemented
- Team A chooses Odd or Even for the toss; Team B gets the opposite parity.
- Both teams pick a toss number from 1 to 6. The sum parity decides the toss winner.
- Toss winner chooses batting or bowling first.
- Each ball: batter and bowler can choose at the same time using separate number controls (batter at the top/left card, bowler at the right/bottom card on mobile).
- Each player’s chosen number stays hidden until both players have locked in their choices.
- Once both have chosen, the result is revealed automatically; after 2 seconds, the next ball begins automatically without pressing a button.
- Same number: both numbers score (e.g. 4 + 4 = 8).
- Strike pair: bowler number is one above/below batter number; 1 and 6 also count as a strike pair.
- Strike gives no runs. Three consecutive strikes dismiss the batter. A non-strike resets the strike streak.
- Different numbers that are not a strike: only the batter's number scores.
- Each team bats once; innings ends when all players are out.
- The prototype is designed for two people sharing one device. Both choices are visually hidden until both are locked in; this is a casual same-device privacy aid, not secure secrecy if someone watches the other person tap.
