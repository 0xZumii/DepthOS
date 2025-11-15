# DepthOS

> **The Operating System for Proof of Growth**

The Depth Protocol's native environment. A bootable Linux distribution where users experience the philosophy by *using* it, not just reading about it.

🌐 **Live at [depthos.online](https://depthos.online)**

---

## What Is This?

DepthOS is a full x86 Linux environment running in WebAssembly via v86. It's not a terminal emulator or a fake shell - it's a real operating system with a real kernel, real filesystem, and real commands.

Most protocols have a whitepaper. We have an OS you can boot into.

---

## Features

- ⚡ **Real Linux Kernel** running in your browser via WebAssembly
- 🧬 **12-Layer Architecture** - Complete Depth Protocol framework
- 🛡️ **Layer 0 Protocols** - Safety & grounding practices
- 🪞 **Shadow Work** - Interactive mirror protocol exercises
- 🌀 **Q-State Engine** - Identity simulation demos
- 🪙 **$DEPTH Integration** - Token info & earning mechanics
- 🎮 **Easter Eggs** - Hidden commands and surprises

---

## Quick Start (Local Development)

```bash
# Clone the repo
git clone https://github.com/depthprotocol/depthos.git
cd depthos

# Serve locally (Python)
python3 -m http.server 8000

# Or with Node
npx serve .

# Open in browser
open http://localhost:8000
```

---

## Project Structure

```
depthos/
├── index.html          # Main v86 wrapper & UI
├── README.md           # This file
├── bios/               # BIOS files (optional local cache)
├── disks/              # Custom OS images (coming soon)
└── docs/               # Documentation
```

---

## Deployment

### Vercel (Recommended)

```bash
npm i -g vercel
vercel --prod
```

### Netlify

```bash
npm i -g netlify-cli
netlify deploy --prod
```

### GitHub Pages

Push to repo, enable GitHub Pages in settings, point to main branch.

---

## Token Info

**$DEPTH** - The liquid utility & governance token

- **Network**: Base (Ethereum L2)
- **Contract**: `0x0c3509abda82ab64de2ce67018cecb4de7afeb07`
- **View on BaseScan**: [Link](https://basescan.org/token/0x0c3509abda82ab64de2ce67018cecb4de7afeb07)

---

## Connect

- 🐦 **Protocol**: [@D3pthProtoc0l](https://x.com/D3pthProtoc0l)
- 🐦 **Builder**: [@builtbyBrand0n](https://x.com/builtbyBrand0n)
- 💬 **Farcaster**: [@brvnd0n](https://farcaster.xyz/brvnd0n)
- 🎨 **Zora**: [@brvnd0n](https://zora.co/@brvnd0n)

---

## Live Apps

- 📱 **Frame Shift Engine**: [Try it](https://depthprotocol.github.io/-frameshiftengine/)
- 📊 **Depth Nexus**: [Explore](https://depthprotocol.github.io/depth-nexus/)

---

## Roadmap

### v1.0 (Current)
- [x] v86 integration working
- [x] Immersive boot sequence
- [x] Basic Linux environment
- [ ] Custom DepthOS disk image
- [ ] Interactive layer demos
- [ ] Token earning mechanics

### v2.0 (Future)
- [ ] Persistent user state
- [ ] Actual blockchain connectivity
- [ ] Plugin system
- [ ] Community contributions
- [ ] Mobile experience

---

## Philosophy

**"Ship fast, grow deep, touch grass occasionally."**

The Depth Protocol rewards personal growth, not just productivity. DepthOS is the experiential gateway into that philosophy.

---

## License

MIT - Build freely. Grow deeply.

---

## Credits

Built by **Brandon** ([@builtbyBrand0n](https://x.com/builtbyBrand0n))

Founder, Depth Protocol

*This is not financial advice. The Depth Protocol is a framework for mindful living, not a substitute for professional mental health support.*

---

**Boot it up. Explore the layers. Grow your depth.**
