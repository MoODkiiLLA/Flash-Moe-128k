
# FlashMoE-128K  
**A real 128K Mixture-of-Experts LLM that runs 100% in your browser — with eight cyber-punk legends inside.**

**Live right now** → https://**your-github-username**.github.io/flashmoe-128k  
(Replace **your-github-username** above with your actual GitHub username — e.g. https://johnsmith.github.io/flashmoe-128k)

If you see a 404:  
Repo → Settings → Pages → Branch: main → Folder: / (root) → Save  
→ Wait 60 seconds and refresh.

### What this is (November 2025, no hype)

- Real 7B–8B MoE models via WebLLM + WebGPU (Qwen2.5-7B, Llama-3.1-8B, DeepSeek-Coder)  
- Full 128 000 token context  
- No server, no API key, no tracking  
- Works offline after first model download  
- Eight cyber-punk personas intelligently route and answer in their own voice  
- One HTML file + PWA manifest = installable app (Add to Home Screen)

### The Council

| Alias           | Former Life                                      | Voice Style                          |
|-----------------|--------------------------------------------------|--------------------------------------|
| KRYPT-KID       | Ex-MIT quantum PhD → lattice black-hat           | Ice-cold crypto precision            |
| NEON-PALADIN    | Disbarred Harvard lawyer, corporate leaker      | Sarcastic legalese                   |
| GHOST-ORACLE    | Ex-NSA astrophysicist, legally dead since 2024   | Cosmic & cryptic                     |
| RAZOR-BISHOP    | Excommunicated Jesuit logician                   | Latin + brutal logic                 |
| SILK-SPECTER    | Stanford poet, $5M bounty from Beijing           | Elegant, layered poetry              |
| CHROME-SHAMAN   | Tribal biohacker on FBI list                     | DNA as magic                         |
| VOID-COWBOY     | 7× DEF CON black badge, high-school dropout     | 1337 memes & shellcode poetry        |
| LACE-PIRATE     | Pirate-radio captain in international waters    | Salty sailor + signal slang          |

### How to use
1. Open https://**your-github-username**.github.io/flashmoe-128k  
2. Pick a model (or keep default)  
3. Start typing — the council decides who answers  
4. Add to Home Screen → works like a real native app

### Edit instantly (no install)
Click **Code → Codespaces → Create codespace on main** → edit → commit → live in seconds.

### When the real FlashMoE-128K drops
Just change one line in `index.html`:
```js
value="FlashMoE-128K-q4f16_1-MLC"
