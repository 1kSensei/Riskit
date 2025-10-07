🎰 Riskit

Riskit is an open-source, browser-based online casino simulator built entirely with JavaScript, HTML, and CSS.
It uses simulated money only — no real currency — to help users learn how online casino games work safely and responsibly.

Inspired by Rainbet, Riskit recreates the fun and variety of a modern casino while staying free, open, and consumer-friendly.
Anyone can fork the project, add their own games, and contribute to a shared educational platform.

✨ Features

🧠 Learn without losing: Simulated money makes Riskit safe and educational.

🕹️ All-in-one casino hub: Blackjack, Roulette, Slots, Dice, Coin Flip, Plinko, Crash, Rock–Paper–Scissors, and more.

💡 Teaches risk and reward: See how odds, volatility, and probability affect your balance.

🌐 Zero setup: Works entirely in-browser, no downloads or installs.

🔓 Fully open source: Modify, expand, or create your own games with ease.

🧩 Project Structure
Riskit/
├── index.html             # Main menu / landing page
├── Blackjack.html         # Blackjack game
├── roullete.html          # Roulette
├── slots.html             # Slots
├── Dice.html              # Dice roller
├── rps.html               # Rock–Paper–Scissors
├── Coin.html              # Coin flip
├── Plinko.html / plinko.html  # Plinko simulation
├── Crash.html             # Crash multiplier game
├── Findit.html            # Find-the-object mini game
├── signin.html            # Simple login screen
├── loading.html           # Loading animation
├── not_found.html         # 404 fallback
├── style.css              # Global styles
└── assets/                # Images (cards, coins, UI)

🃏 Included Games
Game	Preview	Description
Blackjack	
	Dealer and player hands with realistic card logic
Roulette	
	Classic roulette table with red/black betting
Slots	
	Spin-and-stop slot machine
Dice	
	Simple two-dice roller
Coin Flip	
	Animated coin toss
Plinko	
	Gravity-based ball drop
Crash	
	Ride the multiplier, cash out before it crashes
RPS	
	Rock–Paper–Scissors vs. computer
Find It!	
	Find hidden items for extra credits

(Preview images are optional — add screenshots from your /assets/ folder to match your game pages.)

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/1kSensei/Riskit.git
cd Riskit

2️⃣ Run locally

Option A: Open index.html directly in your browser.

Option B: Run a quick local server:

python -m http.server 8080
# Visit http://localhost:8080/

🌍 Deploy on GitHub Pages

You can publish Riskit as a live web app using GitHub Pages — no backend needed.

Steps:

Go to your forked repository’s Settings → Pages

Under Branch, select main (or master) and root folder (/)

Click Save

GitHub will generate a public URL like:

https://yourusername.github.io/Riskit/


Now anyone can play the demo online instantly.

🧱 Tech Stack

HTML5 — structure and UI

CSS3 — styling and animations

Vanilla JavaScript — game logic and interactivity

No frameworks, no dependencies — just simple, educational code.

💡 Purpose & Vision

Riskit exists to educate users about gambling systems without financial risk.

Understand how RNG, odds, and volatility work

Practice responsible play behaviors

Offer a foundation for developers to create ethical, transparent game demos

Encourage open-source collaboration in a normally closed industry

🛠️ Contributing

Want to improve Riskit or add your own game?

Fork this repository

Create your feature branch:

git checkout -b new-game-name

Also shoot me an email of your fork i would love to see what people make. Who knows, maybe i will include it on the main repo!

hyperscambaits@proton.me

Add your HTML/JS/CSS files and link them in index.html

Commit your changes:

git commit -m "Added new game: Poker"


Push and open a pull request 🎉

Guidelines:

Keep gameplay simulated (no real-money systems)

Keep JS self-contained for each game

Favor educational clarity over visual flash

Test all games locally before pushing

🗺️ Future Roadmap

🧮 Add detailed odds and payout information

📊 Add statistics tracking & leaderboards

💾 Save player balances using localStorage

🎵 Add optional sound effects and background music

📱 Improve mobile UI and responsive layouts

🧩 Add a “Game Creator” mode for community submissions

📄 License

This project is open source.
You’re free to use, modify, and distribute it under the MIT License
 (recommended if not yet added).

🙌 Acknowledgments

Creator: @1kSensei

Inspired by: Rainbet

Community Goal: Teach responsible gaming and probability awareness in a transparent, fun environment.
