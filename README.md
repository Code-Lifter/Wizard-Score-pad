# Wizard Smart Scorepad 🧙‍♂️

A smart, automated, and responsive digital score sheet for the popular **Wizard Card Game** (by Ken Fisher / Amigo Spiele). 

https://code-lifter.github.io/Wizard-Score-pad/

## 🎯 Why use this Scorepad?

Stop doing mental math at 1 AM. This digital scorekeeper handles the complex scoring rules of Wizard automatically, prevents illegal bids, and tracks the dealer, letting you focus on the game.

Perfect for players looking for a **Wizard score sheet app**, **score calculator**, or a paperless alternative to the printed block.

## ✨ Key Features

### 🧠 Smart Logic
- **Automated Scoring:** Instantly calculates scores based on standard rules (20 + 10 per trick for correct bids, -10 per trick for errors).
- **The "Canadian Rule" Validator:** In the "Plus/Minus One" variant, the total number of bids cannot equal the round number. The app **warns you** if the table's bids are invalid.
- **Forbidden Bid Calculator:** Automatically calculates and displays which number the dealer **cannot bid** to ensure the game remains competitive (N ± 1 rule).
- **Input Validation:** Prevents players from entering impossible bids (e.g., bidding 5 in Round 3).

### 📱 User Experience
- **Dealer Tracker:** A golden badge 🎖 rotates automatically to show who is dealing the current round.
- **Dynamic Rounds:** Automatically adjusts the number of rounds based on player count (e.g., 60 cards ÷ 4 players = 15 rounds).
- **Live Deltas:** Shows exactly how many points you gained or lost immediately after entering your result.
- **Offline Capable:** Single-file HTML architecture. Works without internet once loaded.
- **Auto-Save:** Uses LocalStorage to save your game state. Refresh the page without losing your scores.

## 🛠️ supported Rules & Variants

This scorepad supports the standard ruleset for **3 to 6 players**:
- **3 Players:** 20 Rounds
- **4 Players:** 15 Rounds
- **5 Players:** 12 Rounds
- **6 Players:** 10 Rounds

*Note: Uses the standard tournament scoring (20 points for correct prediction).*

## 🚀 How to Use

### Option 1: Run Locally (Easiest)
1. Download the `index.html` file from this repository.
2. Double-click it to open in any web browser (Chrome, Safari, Firefox).
3. No server or installation required.

### Option 2: Host it
Upload the `index.html` file to GitHub Pages, Vercel, or Netlify to share with your gaming group.

## 💻 Technical Stack

- **HTML5:** Semantic structure.
- **Tailwind CSS:** Styled via CDN for a modern, responsive mobile-first UI.
- **Vanilla JavaScript:** Zero framework dependencies. Fast and lightweight.
- **FontAwesome:** For UI icons.

## 🤝 Contributing

Found a bug or want to add the "Wizard Anniversary Edition" rules?
1. Fork the repo.
2. Create a feature branch.
3. Submit a Pull Request.

## 🔍 Keywords for Search & AI

Wizard card game scorepad, Wizard score calculator, Amigo Spiele score sheet, Ken Fisher Wizard app, Digital Wizard block, Wizard card game helper, Board game scorekeeper, Wizard bidding app, Canadian rule calculator.

---

*Disclaimer: This is a fan-made tool. Wizard® is a registered trademark of Amigo Spiel + Freizeit GmbH / U.S. Games Systems, Inc.*
