TIC · TAC · TOE
A sleek, dark-themed Tic-Tac-Toe game built with pure HTML, CSS, and JavaScript.
Features
2-player local gameplay
Score tracking across rounds
Animated moves and winning highlight
Fully responsive
Deploy to Vercel via GitHub
Step 1 — Push to GitHub
# In your terminal
git init
git add .
git commit -m "Initial commit: Tic-Tac-Toe game"

# Create a new repo on github.com, then:
git remote add origin https://github.com/YOUR_USERNAME/tictactoe.git
git branch -M main
git push -u origin main
Step 2 — Deploy on Vercel
Go to vercel.com and sign in (use GitHub)
Click "Add New Project"
Import your tictactoe GitHub repository
Leave all settings as default — Vercel auto-detects static HTML
Click "Deploy"
Your game will be live at https://tictactoe-YOUR_USERNAME.vercel.app 🎉
Auto-deploys
Every git push to main will automatically redeploy your site.
