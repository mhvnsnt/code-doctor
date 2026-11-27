# HANDOFF — Code Doctor

**Last updated: 2026-11-27 (America/Chicago).**
**Repo:** `mhvnsnt/code-doctor` (PUBLIC), default branch `main`.
**Purpose of this file:** any agent that picks up work here reads this FIRST, then the linked docs. It states what we've done, where we're at, and what we're working toward — so the owner can say "go to this repo, pick up the work" and you just know. Update this file in the same PR whenever the state changes (add, don't delete).

## 1. What this repo is

Code Doctor: fixed-price fixes for broken AI-built apps. The offer is simple — someone's AI-built app is broken, Code Doctor fixes it for a fixed price. This repo holds the working method and the service docs.

**Honest state note:** this file records only what the repo itself shows. The live offer details — current pricing, intake flow, what is live right now — are NOT recorded here. Before quoting anything to anyone, read the README and the working method statement in the repo. Do not invent prices or promises.

## 2. Where we're at

### DONE
- **Landing page takes email leads (2026-11-27).** `index.html` on GitHub Pages now has a Book a fix form that opens a mailto to the documented owner address (`fmmg.mars@gmail.com`). Fiverr buttons stay in the page but stay hidden until a real `https://` gig URL replaces the `FIVERR_GIG_URL` / `FIVERR_PREMIUM_URL` placeholders. No Stripe key, Cash App cashtag, or Ko-fi URL was documented in the repos, so none was invented or wired. Prices on the page are unchanged.
- **PULL-IN-FIRST LAW (2026-11-27, PR #7 merged).** Owner order of Nov 27 is in AGENTS.md.
- **Working method statement (2026-10-27, commits 688a78e / b97faca).** The method for how fixes are done is written down in the repo.
- **Anti-clobber laws (2026-10-17, PR #3 merged, c67845a).** Owner law from the DXMMII 54k-file wipe: never clobber, never overwrite working files — add, don't delete. These laws apply here and everywhere.

### IN PROGRESS
- **Pre-made parts first rule (open PR #5).** Docs PR adding the owner's 2026-11-20 rule to AGENTS.md. Open, not merged.

### BLOCKED
- **Card / instant checkout is not live.** There is still no documented Stripe key, Stripe payment link, Cash App cashtag, or Ko-fi URL. Leads go by email until the owner provides one of those. Fiverr stays hidden until a real gig URL exists.
- **Nothing else blocked.** Historical note: the repo was quiet from 2026-10-27 until the Nov 27 lead-form work. If other client work exists, it lives elsewhere; say so plainly rather than assuming.

## 3. What we're working toward

**The goal:** a working, money-making fix service — fixed-price fixes for broken AI-built apps, done by the documented method, with each fix landed cleanly and the client able to see the result. Money-first: the next real dollar outranks the next build.

**The bar:** the method statement is the method — follow it, don't improvise a new one per fix. Anti-clobber always: a fix never wipes the client's working files. Proof is the fixed app running, verified by own eyes.

## 4. Standing rules that apply here

- **Branch → PR → merge, always.** Never push to main directly. Add-only, zero-conflict PRs, no force pushes.
- **Checkpoint-and-save law:** CHECKPOINT.md first, update after every step; the repo is the save; resume, never restart.
- **No-temp-storage law:** nothing in /tmp or any wipeable location, ever. Everything goes straight into the repo or a durable folder the second it exists.
- **No-gaps / solve-it law:** a gap or block is never the end of the work — route-switch until it's done or every reasonable route is exhausted with exact errors recorded.
- **Anti-clobber laws (owner, 2026-10-17):** add, don't delete; never overwrite working files. Born from the DXMMII 54k-file wipe.
- **Pre-made parts first (owner, 2026-11-20):** pull working parts before building anything from scratch.
- **Never invent prices or promises.** If the README doesn't state it, the answer is "not recorded here," not a guess.
- **Sign-in standing approval:** Google/Gmail (fmmg.mars@gmail.com) and GitHub (mhvnsnt) are blanket-approved forever. Never ask him to do sign-in steps himself.

## 5. Key files and paths

| What | Where |
|---|---|
| Working method statement | Method statement docs in repo (commits 2026-10-27) |
| Anti-clobber laws | Laws landed with PR #3 |
| Public landing page | `index.html` (GitHub Pages: https://mhvnsnt.github.io/code-doctor/) |
| Open PRs | #5 Add PRE-MADE PARTS FIRST rule to AGENTS.md |

## 6. Open decisions needing the owner

- **PR #5 (pre-made parts first rule):** merge, or hold? His call if it needs one — it is a docs rule he already ordered elsewhere.
- **Payment link:** a real Stripe payment link, Cash App cashtag, or Ko-fi URL, if he wants checkout on the page instead of email-then-invoice.
- **Fiverr gig URL:** paste a real `https://` gig URL over `FIVERR_GIG_URL` / `FIVERR_PREMIUM_URL` in `index.html` and the buttons will unhide.
- **What is live right now (2026-11-27):** the public page takes email leads at fmmg.mars@gmail.com and lists the existing Express/Premium prices. Instant checkout and Fiverr are not live. Do not invent other prices or promises.

## 7. How to pick up

1. Read this HANDOFF.md first, then the README and the working method statement in the repo.
2. Check what other agents are already doing before starting anything (never start a duplicate session).
3. Resume from the stated next step — the landing page now takes email leads; PR #5 is still open. Never restart, never re-derive finished work.
4. Land work branch → PR → merge, add-only. Stage finished work to the repo as it lands.
5. Update this HANDOFF.md in the same PR when the state changes. Never invent prices, promises, or client work that isn't in the repo.
