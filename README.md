# F1 Bingo 2025

Multiplayer bingo tracker for the 2025 F1 season. State is stored in a GitHub Gist so progress is never lost.

---

## Setup (one-time, done by Miguel)

### Step 1 — Create the data Gist

1. Go to https://gist.github.com
2. Create a **public** gist:
   - Filename: `f1bingo2025.json`
   - Content: `{}`
3. Copy the **Gist ID** — it's the long string at the end of the URL  
   e.g. `https://gist.github.com/yourusername/`**`a1b2c3d4e5f6a1b2c3d4e5f6`**

### Step 2 — Create a GitHub token (for saving)

1. Go to: https://github.com/settings/tokens/new
2. Name it "F1 Bingo"
3. Select only the **`gist`** scope
4. Click **Generate token** and copy it (you won't see it again)
5. Keep this token to yourself — it lets you write to the Gist

### Step 3 — Deploy to GitHub Pages

1. Create a new **public** GitHub repo (e.g. `f1-bingo-2025`)
2. Push `index.html` to the `main` branch
3. Go to repo **Settings → Pages → Source: Deploy from branch → main → / (root)**
4. Your app will be live at `https://yourusername.github.io/f1-bingo-2025/`

### Step 4 — First launch

1. Open the app URL
2. Click **"Setup / change Gist ID"**
3. Enter:
   - **Gist ID** (from Step 1)
   - **GitHub token** (from Step 2 — only you need this)
   - **Your name**: Miguel
4. Save — you're in!

---

## For Francisco and João

1. Open the app URL (Miguel shares it with you)
2. Click **"Setup / change Gist ID"**
3. Enter:
   - **Gist ID** (Miguel shares this with you — just the ID, not the token)
   - Leave the token field **empty** (you don't need it to view; only to save your card)
   - **Your name**: Francisco or João
4. Save, pick your name, enter your PIN
5. Done!

**PINs:**
- Francisco: `6969`
- João: `6767`
- Miguel: `2121`

> **Note:** To save your own card, each person needs their own GitHub token with `gist` scope. The Gist is public so anyone can read it; writing requires a token. Alternatively, Miguel can create tokens for everyone and share them privately.

---

## How it works

- **Checkbox squares** — tap the cell to mark/unmark
- **Counter squares** — use the − / + buttons to track progress toward the target
- **Row indicators** (R1–R5) — light up green when a full row is complete
- **Everyone's cards are visible** — switch between cards using the tabs at the top
- **Progress auto-saves** to the GitHub Gist ~1 second after each change
- **Refresh anytime** to load the latest state from all players
