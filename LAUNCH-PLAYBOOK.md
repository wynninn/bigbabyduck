# Big Baby Duck — Watermelon Worlds: Launch & Monetization Playbook

*Compiled 2026-07-18 from fresh web research (portals, COPPA, platform algorithms, clip strategy, realistic-outcome data). Sources cited inline where they matter.*

---

## The honest headline first

Short-form virality for indie games is a **free lottery ticket, not a plan**. The best-documented sustained conversion is ~1 wishlist per 1,000–2,000 views (Mortal Rite: 126M TikTok views → 61,749 wishlists), first videos from zero-follower accounts typically get **hundreds, not thousands, of views**, and organic reach for devlog content collapsed between 2024 and 2026. Every "how I went viral" post now carries its own outlier disclaimer.

**But this game has two real structural advantages:**
1. **Zero-friction play.** It's a link. Streamers and viewers can be playing in 5 seconds — no key, no download, no wishlist-and-wait. The strongest finding in creator-outreach research: "no demo, no video" — a live URL is the ultimate demo.
2. **A kid/family-safe cozy sandbox with genuinely clip-able chaos** (T-Rex chases, Melon Bob, kart races, a whole physics arcade world). Cozy + chaotic-moment is exactly the short-form format that travels.

Play the long game: ship free everywhere, build the duck as a character brand, let portals pay for traffic, and only go premium (Steam) if web numbers prove demand.

---

## ⚠️ One strategic warning: don't ride the "Watermelon Game" wave

Research verdict: leaning on Suika/"Watermelon Game" naming **hurts more than helps** in 2026.
- The Suika clone wave (hundreds of copycats, App Store removals, Apple's formal "clone app" policy since 2023, tightened Nov 2025) left lasting stigma; curated portals' **#1 rejection reason is perceived clone content** (CrazyGames devs report ~90% rejection rates).
- The discovery-arbitrage window for Suika-likes closed around 2024; what remains is mostly downside (clone-bucketing) without upside.
- No case study anywhere documents measurable gains from tagging a differently-themed game with #suikagame.

**What to do:** Foreground **"Big Baby Duck"** as the brand everywhere (page titles, thumbnails, account names). "Watermelon Worlds" as subtitle is fine — it's descriptive of *your* mechanic (collecting, not merging). Never use "Suika" anywhere. At most, one ironic caption-level watermelon tag on social posts; never in the product name or store metadata.

---

## Phase 1 — Ship it (this week, $0)

1. **itch.io** — zero approval process, single-file HTML supported (check "played in browser"), pay-what-you-want with $0 minimum enables tips from day one. This is the day-one home. (Realistic: 70th-percentile itch game = ~13K lifetime views; most earn <$100. It's a storefront + URL, not income.)
2. **GitHub Pages mirror** — free HTTPS + custom domain; this becomes the canonical shareable link. (Note: gray area once ads appear; fine while free. Avoid Vercel Hobby — it explicitly prohibits ads.)
3. **Before upload:** set the `og:url` / `og:image` TODO in `index.html` (1200×630 screenshot — take a Funland or T-Rex shot with the in-game 📸 Photo button), and buy a domain if you want one (~$12/yr, e.g. bigbabyduck.com).
4. **Press kit** — free at presskit.gg: factsheet, 6–12 clean 1080p screenshots (use Photo mode), a 60–90s **raw b-roll file with no music/text** (that's what creators actually cut from), transparent logo, contact email.

## Phase 2 — Seed the audience (weeks 1–4, $0)

**Reddit/Discord (in this order):**
- r/playmygame (built for self-promo)
- r/incremental_games Friday promo threads — best signal-to-noise for browser games
- r/WebGames (build a little account history first), r/IndieGaming, r/gamedev Feedback Friday
- Game Dev League Discord (42K+, weekly showcases), itch.io Discord "Share your work"

**Streamer/YouTuber cold outreach (the highest-EV free move):**
- Target **5K–250K subscriber** creators in kids/family/cozy/casual gaming; include non-English creators (less-crowded inboxes, documented outsized conversion).
- Skip Keymailer/Lurkit — they're Steam-key-centric; you have no keys, you have a link.
- Email = 3 sentences + a GIF/webm of a clip-worthy moment + the instant-play URL. Don't ask for wishlists/plugs (reads as paid promo).
- Realistic numbers (best documented campaigns): ~100 emails → single-digit-to-low-double-digit videos typical; top campaigns hit 30–73 videos. ~30% of creators who say yes actually follow through. Volume matters: 100–300 emails.
- **2-player mode is the pitch**: "play it with your kid / your chat on one keyboard, right now, in the browser."

## Phase 3 — Short-form clips (ongoing, $0, budget your morale)

**What the algorithms reward (2026):** completion/watch-through is the load-bearing signal on all three platforms (TikTok official; Mosseri on-record: watch time, likes, sends). YouTube Shorts now sharply favors videos <30 days old — recency means steady posting beats a back-catalog.

**The format that works for games:**
- **Cold-open on the moment. No intro, no logo, no context.** Hook lands in the first 1–3 seconds.
- One dramatic moment per clip beats montages: T-Rex chase with 30 ducklings trailing, Grinch stealing presents, Melon Bob popping in, bowling-strike in Funland, a photo-finish kart race, filling the whole floor piano.
- 10–30s clips for raw virality; test 45–90s "full run" content occasionally (platforms increasingly reward held attention).
- Design clips to **loop** (end frame ≈ start frame).
- Big bold caption text, keyword-heavy description ("cozy duck game you can play free in browser"), CTA on screen ≥3 seconds: **"free in your browser — link in bio"**.
- Trending audio still helps on TikTok (works even muted); your synth quacks are also an asset — original character sounds are a documented engagement lever.
- **Native re-edit per platform, never cross-post with watermarks** (watermarked reposts are excluded from recommendation surfaces on all three platforms; Instagram's April 2026 originality crackdown is account-level).
- **Be the visible human.** Every case study says personal/dev-voice accounts beat polished brand accounts. "Solo dad building a duck game my kid designed" (adjust to reality) is a stronger channel identity than a faceless game account.
- Cadence: post when you have a real moment (1–3/week sustainable); if something spikes, follow up within 24h — momentum-reactive beats calendar-driven.
- Expectations: most posts get 300–3,000 views. That's normal, not failure. A breakout is a low-probability event that can happen to a zero-follower account because each video is scored independently.

## Phase 4 — Portal money (months 1–3)

This is where browser games actually earn. In order:

| Portal | Deal | Realistic first-game money | Catch |
|---|---|---|---|
| **Poki** | 50/50 rev share on their traffic | **$500–$3,000/mo** (their own publisher-success lead's figure) | Hardest bar: <8MB initial download, 16:9 responsive, Poki SDK, Player Fit Test (25% of 500 testers play ≥3 min) |
| **CrazyGames** | Undisclosed base + **+50% for SDK+ads+2-mo exclusivity** | ~€1 per 1,000 plays anchor; tens–hundreds €/mo if it lands | SDK required for full launch; ~90% rejection rate, mostly clones — your originality is the asset |
| **CoolMathGames** | One-time license (industry range $500–$5K) | Best single payday + best audience fit (40M/mo, ages 8–18, classroom-approved) | Curated for "thinking games" — pitch the Funland puzzles/minigames angle |
| **Newgrounds** | Ad rev share, ~$50 threshold | Pocket change | Surrounding site content isn't kid-friendly — audience mismatch, skip or deprioritize |

Technical prep for portals (next dev session): an asset-size audit (we're a single ~250KB file + CDN Three.js — well under every limit, but Poki wants no third-party requests, so bundle Three.js locally), SDK integration points at the existing `startGame()`/`endGame()`/`travel()` seams, and a 16:9 letterbox check.

**Exclusivity caution:** CrazyGames' +50% boost requires 2-month launch exclusivity — that conflicts with launching everywhere at once. Decide: broad launch first (brand play) or CrazyGames-exclusive first (money play). Recommendation: broad free launch + itch first; add portals after the first outreach wave, taking the exclusivity boost only if CrazyGames traction looks strong.

## Phase 5 — Only if traction: premium tier

- **Steam** via Electron wrapper (not Tauri — Steamworks bindings are Electron-only): $100 recoupable fee, 4–6 week pipeline. Median indie Steam title earns ≤$4,000 lifetime — do this for the storefront legitimacy and wishlist flywheel only after web numbers prove demand.
- **Merch** (print-on-demand only, no upfront): documented case (Frog Detective) netted ~$4K AUD over 5 months *with an existing fanbase*. The duck needs fans first.
- **Ko-fi** link on the itch page from day one: costs nothing, 1–3% of an engaged audience tips.

---

## COPPA / kids-content rules (important, cheap to get right)

- **Right now you collect nothing** (no accounts, no analytics, no ads — localStorage bests are on-device and fine). That means effectively **zero COPPA compliance burden**. Keep it that way as long as possible.
- Cute aesthetic alone doesn't trigger COPPA — data collection does. The 2025 rule amendments (compliance deadline April 2026) expanded the "directed to children" test to include your *marketing*, so once you market to kids, treat the game as child-directed.
- **Never add**: Google Analytics (default config), personalized ads, accounts/emails — without doing the compliance work first.
- When monetizing with ads, prefer **CrazyGames Kids / Poki Kids** channels (kidSAFE/COPPA-certified ad stacks — they carry the compliance) over self-hosted AdSense (child-directed = contextual-only ads at roughly half CPM, configured yourself, liability yours).

---

## What shipped in the game today (v26)

- ⏱ **Speedrun timer** in HUD + **best-time records** — the streamer/replayability hook ("beat my time" is a content format)
- 📸 **Photo mode** (P key or button) — watermarked screenshots for social
- 🖼 **1080×1080 share card** on the end screen — auto-generated brag image with stats
- 📋 **Copy-brag button** — one-tap share text with challenge hook
- 💾 **Persistent stats** (best win, lifetime melons, runs) shown to returning players
- 🔇 **Mute toggle (M)** — streamer-friendly
- 🏷 **OG/meta tags + favicon** — links unfurl properly when shared (og:image TODO needs the hosted URL)
- 🧪 **`?debug` hook** (`window.__duck`) for automated QA — inert in normal play

## Suggested next dev sessions (priority order)

1. **Bundle Three.js locally** (removes CDN dependency; required by Poki, safer everywhere)
2. **Poki/CrazyGames SDK integration** behind a feature flag
3. **Mobile pass**: tap-to-move polish, bigger touch buttons, HUD density on small screens (tablet works today; phone is cramped)
4. **Daily challenge seed** (same melon layout for everyone each day) — the single strongest recurring-content/leaderboard hook for streamers and social
5. **Performance**: shadow-map cost is the big GPU line item; `InstancedMesh` for trees/buildings if low-end devices stutter
6. **Trailer**: 60–90s raw b-roll + 3 vertical 15s cuts from the clip list above
