# Clutch

**Launch a coin the second a moment happens. The crowd decides what lasts.**

Clutch is a play-money moment market for sports, in the style of memecoins. Anyone can launch a coin on a moment, like a walk-off, a 13-second knockout or a breakout rookie game. Prices move on a bonding curve, and the moments the crowd backs graduate to a Hall of Fame.

**Live demo:** https://alagiewon.github.io/clutch-app/

<p>
  <img src="screenshots/01-board.png" width="240" alt="Live board">
  <img src="screenshots/02-coin.png" width="240" alt="Coin page">
</p>

## What it does

- **Live board.** Shows new launches, live buys and sells, King of the Hill, and a Trending now rail of moments nobody has launched yet.
- **Two kinds of coin:**
  - **Career bets** follow a player's rise over time.
  - **Moment relics** capture a single viral play.

  Coins stay tied to their player or team, so they can pump again on new milestones.
- **Bonding-curve pricing.** Each coin has a market cap, a raise target and a holder count, and it graduates when it hits its target.
- **Simulated market.** Bot traders (set to Chill, Live or Frenzy) make the board feel alive in a single-player prototype.
- **IP-safe card art.** You can choose pictograms, AI illustrations of anonymous athletes, or ticker cards, plus a mock "licensed preview" mode. No team logos are used.

## Tech

- The app is a single HTML file with vanilla JavaScript, CSS, and Canvas charts. There are no frameworks or build step.
- State is saved in the browser. Every player starts with $1,000 of play money.

## Status

This is a concept prototype and personal project. It uses **play money only**: there's no real currency, crypto or wallet.

Built by Alagie · prototyped with Claude as a coding partner.
