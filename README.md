# SRAE-Δ v5 – Cyber-Punk Council Grader

**One single HTML file that grades your writing with a crew of eight fictional hackers.**

Live demo (free forever):  
https://YOUR-USERNAME.github.io/srae-delta  
(Replace YOUR-USERNAME with your actual GitHub name. If you see a 404, go to Settings → Pages → choose “main” branch / root folder → Save. It will work in under a minute.)

### What this actually is
- A fun, self-contained web page (no server, no API, no internet needed after the first load)  
- You paste any text (up to ~128 000 tokens – that’s a whole book)  
- Eight imaginary cyber-punk characters read it and give you a score + short comment  
- Pure JavaScript – works offline, on phones, tablets, or laptops  
- Looks like a late-night hacker terminal (neon colors, glitch effects)

### How to use it
1. Open the link above  
2. Paste your essay, proof, code, or anything  
3. Click the big button  
4. Get a score (0–100) and see which characters reacted the strongest

### How to edit or improve it with GitHub + Codespaces (zero setup)
1. Open this repository  
2. Click the green **Code** button → **Codespaces** → **Create codespace on main**  
   → You get a full Visual Studio Code editor in your browser (no install needed)  
3. Edit `index.html` (change the characters, scoring rules, colors, anything)  
4. Click Commit → your live page updates in seconds

### Adding your own character
Just add a new entry in the `council` list inside the file. Example:

```js
{
  alias: "SHADOW-QUEEN",
  real: "Prof. Elena Voss",
  edu: "Oxford Mathematics → vanished after publishing unsolvable proof",
  rap: "Wanted in 27 countries for academic sabotage",
  specialty: "Impossible proofs",
  score: tokens => tokens.filter(w => /proof|lemma|contradiction/i.test(w)).length * 10
}
