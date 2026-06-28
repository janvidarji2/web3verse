# web3verse
A 4-page Web3 educational website built for Arbitrum Builder Pods — featuring live crypto prices, SHA-256 block mining simulator, and Web3 concept explainers. Built with vanilla HTML/CSS/JS
# Web3Verse 🌐⛓️

A single-page Web3 educational website built for the **Arbitrum Builder Pods** assignment.  
All 4 sections live in one HTML file — navigate without any page reload.

## Pages

| Page | What It Does |
|------|-------------|
| 🏠 **Home** | Landing page — hero with animated chain visual, 6 Web3 features, how blockchain works (4 steps), explore section|
| 📚 **Concepts** | 4 side-by-side comparisons: Web2 vs Web3, Ethereum vs Bitcoin (table), Public vs Private Key, Blockchain vs Traditional DB |
| 📈 **Live Prices** | Real-time ETH, BTC, SOL, MATIC, ARB, ADA from CoinGecko API — 24h change with ▲/▼ arrows, sparklines, coin filter |
| ⛏️ **Block Simulator** | Real SHA-256 proof-of-work — mine Block 1, change its data, Block 2 breaks instantly (immutability demo) |

## How to Run

**Option 1 — Just open in browser:**
```
Double-click web3.html
```

**Option 2 — Local server (recommended for CoinGecko API):**
```bash
python -m http.server 8080
# Open http://localhost:8080
```

**Option 3 — VS Code Live Server** (right-click index.html → Open with Live Server)

## Tech Stack

- **Pure HTML / CSS / JavaScript** — zero dependencies, zero build step
- **Web Crypto API** (`crypto.subtle`) — real browser-native SHA-256
- **CoinGecko Public API** — no API key needed
- **Google Fonts** — Syne + Inter + JetBrains Mono

## Features Checklist

- ✅ 4 pages in 1 file — shared nav, no reloads
- ✅ Active page highlighted in navbar
- ✅ Fully responsive (mobile nav with hamburger)
- ✅ Green ▲ / Red ▼ arrows on price change
- ✅ Refresh button re-fetches live data
- ✅ Real SHA-256 mining (Web Crypto API)
- ✅ Block Valid / Block Invalid display
- ✅ Chain breaks when Block 1 data is changed
- ✅ Consistent dark design across all sections
- ✅ Footer: name, GitHub, batch on every page

## Known Issues
- CoinGecko free API has rate limits — if error appears, wait ~60s and refresh
- Mining speed depends on browser (SHA-256 is async, UI stays responsive)
## screenshots
<img width="1600" height="900" alt="WhatsApp Image 2026-06-28 at 4 48 53 PM" src="https://github.com/user-attachments/assets/cb83f02c-f762-49be-9c5e-a53a3d062441" />

<img width="1600" height="900" alt="WhatsApp Image 2026-06-28 at 4 48 53 PM (1)" src="https://github.com/user-attachments/assets/4095e50d-5446-43dd-83f6-06004a6ba5d4" />

<img width="1600" height="900" alt="WhatsApp Image 2026-06-28 at 4 48 53 PM" src="https://github.com/user-attachments/assets/2106f2b0-4d24-48f2-9237-24876907b555" />

<img width="1600" height="900" alt="WhatsApp Image 2026-06-28 at 4 48 53 PM (3)" src="https://github.com/user-attachments/assets/d6e98434-cf3f-4a2e-a59a-803f821e96ed" />

<img width="1600" height="900" alt="WhatsApp Image 2026-06-28 at 4 48 53 PM (4)" src="https://github.com/user-attachments/assets/54f77f0e-7ed4-4501-81b4-15212ddf1f6b" />


<img width="1600" height="900" alt="WhatsApp Image 2026-06-28 at 4 48 53 PM (6)" src="https://github.com/user-attachments/assets/c2b0bd27-111f-4467-bfdd-7d0b7361b988" />


<img width="1600" height="900" alt="WhatsApp Image 2026-06-28 at 4 48 53 PM (7)" src="https://github.com/user-attachments/assets/29f63769-c066-4de9-947b-fc220ac45861" />

<img width="1600" height="900" alt="WhatsApp Image 2026-06-28 at 4 48 53 PM (8)" src="https://github.com/user-attachments/assets/36b38d42-7655-4594-bd25-fa9872e5cc13" />


<img width="1600" height="900" alt="WhatsApp Image 2026-06-28 at 4 48 53 PM (9)" src="https://github.com/user-attachments/assets/06a84ef4-9e6d-43a3-a71d-0066f26d832d" />





- Built by **JANVI** · Arbitrum Builder Pods Batch 2025
