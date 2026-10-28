# Ivan Šimić

**Trading systems developer.** I build the execution and analytics infrastructure I use to trade, then turn it into products other traders can run.

Electrical engineer by training. Intraday FX and gold by practice. Most of what I build exists because I needed it first and nothing on the market did the job.

---

### What I'm building

**[Kriteria](https://kriteria.app)** — a multi-user trading journal and analytics platform. TradingView alerts arrive by webhook, get reconstructed into complete trades, and come back as per-user performance analytics: R-multiple distributions, MFE/MAE, profit factor, expectancy, drawdown, and setup funnels broken down by configuration.

It also runs things most journals don't:

- **Break-even simulation** — replays historical trades against alternative stop-management rules using recorded trade-path data, so the counterfactual is measured rather than guessed
- **SL optimizer** — sweeps stop-loss factors across the full trade set and reports total R, profit factor and max drawdown per setting, flagging parameter regions that are statistically unstable
- **News module** — scheduled high-impact calendar plus a live headline feed, polled on a killzone-aware schedule and used for trade tagging and pre-session briefings
- **Telegram integration** — per-user bot, trade notifications, owner-locked controls

**Expert Advisor (MT5)** — automates indicator signals through to prop-firm and broker accounts, with execution tracked back into Kriteria so EA fills can be compared against what the indicator intended.

**Indicator suite (Pine Script v6)** — intraday liquidity and session-based volatility logic for FX, metals and indices.

---

### Elsewhere

- **On-chain research tooling** across EVM chains — token and contract analysis
- **Cairo / Starknet** — NFT marketplace development

---

### Stack

**Languages** Python · TypeScript · Pine Script · SQL · Cairo
**Frontend** React · Tailwind
**Backend** Supabase · PostgreSQL · Edge functions · Webhooks · REST
**Platforms** TradingView · MetaTrader 5 · Telegram Bot API
**Tooling** JetBrains IDEs · Git

I develop heavily with AI assistance — **Claude Code** and **Lovable** are core to how I ship. I treat them as leverage on an engineering process, not a replacement for one: I still own the architecture, the data model and the correctness of what goes out.

---

### A note on this profile

Most of my repositories are private. The trading logic behind the indicator suite and the EA is the product, so the source stays closed.

What's public here is documentation: architecture notes, data flow, and case studies on how these systems are built and why. The live product is at **[kriteria.app](https://kriteria.app)** — a running system is better evidence than a repository anyway.

Code available on request or under NDA.

---

📍 Split, Croatia · Open to remote and relocation
🔗 [LinkedIn](https://www.linkedin.com/in/ivan-simic/) · [kriteria.app](https://kriteria.app)
