# UNOS
ICHI
# 🎴 UNO - Multiplayer Game

Play UNO with your person in a different city. Free forever.

---

## How to run locally (test on your laptop first)

1. Open a terminal (press Windows key, type "cmd", hit Enter)
2. Navigate to this folder:
   ```
   cd path\to\uno
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Start the server:
   ```
   npm start
   ```
5. Open your browser and go to: **http://localhost:3000**

---

## How to deploy FREE online (so she can play from her city)

### Step 1 — Create a GitHub account
Go to github.com and sign up (free)

### Step 2 — Create a new repository
- Click the "+" button → "New repository"
- Name it "uno-game"
- Keep it public
- Click "Create repository"

### Step 3 — Upload your files
- Click "uploading an existing file"
- Drag and drop: server.js, index.html, package.json
- Click "Commit changes"

### Step 4 — Deploy on Render.com (free)
- Go to render.com and sign up with your GitHub account
- Click "New +" → "Web Service"
- Connect your "uno-game" repository
- Settings:
  - **Build Command:** `npm install`
  - **Start Command:** `npm start`
  - **Plan:** Free
- Click "Create Web Service"
- Wait 2-3 minutes for it to deploy
- You'll get a URL like: `https://uno-game-xxxx.onrender.com`

### Step 5 — Play!
- Both of you open that URL on your phones
- Make up a room code (anything like "LOVE" or "ANAS")
- Both enter the same room code
- Game starts automatically when both join!

---

## How to play

1. Enter your name and a room code
2. Share the room code with her
3. She enters the same room code
4. Cards are dealt automatically
5. Click a card to play it
6. Click "DRAW" if you have no playable cards
7. Hit **UNO!** when you have 1 card left
8. **Catch UNO** button to penalize her if she forgets to call it 😈

---

## Rules implemented
- All number cards (0-9)
- Skip, Reverse (acts as skip in 2-player), Draw 2
- Wild, Wild Draw 4
- UNO calling + catching penalty (+2 cards)
- Rematch button after game ends
