# UNITS///OS — Design: "The Collection Method"

> *You think you're a freelancer. You're a collection method.*

This document is the story bible and feature plan behind the 2026-09 rebuild. Everything here is implemented in `index.html` unless marked **(later)**.

---

## 1. The story

### Theme
Everyone in New Milos is being harvested. The agency harvests runners. Runners harvest each other. The grid harvests all of it. The only question the game asks is what you do the moment you can see the whole machine.

### The cast

| Who | What they want | What they're hiding |
|---|---|---|
| **SABLE** — your handler | To keep you working and alive | She wrote HavenCracker, got caught, and cut a deal: recruit runners, feed the agency their output. She's COMPLIANT to protect one person — Anatomical, her former partner. She genuinely likes you, which is the problem. |
| **cr4sh** — wire veteran, your friend | To get you through your first year | Nothing. He's exactly who he says he is. That's why the agency takes him in Act II. |
| **0RACLE** — a voice in your DMs | For you to see the grid before it closes your file | 0RACLE **is Anatomical.** The person who forked Sable's cracker and vanished has been inside the grid's audit layer for years, watching it watch everyone. |
| **V01D** — the wire's best runner | To pay off his own file | He's been selling your telemetry because the agency holds a review date on *him*. He is what you become if you keep your head down. |
| **Director Halloran** — New Milos Intelligence | A runner who'll work for the grid openly | Nothing. He's the only honest one. His offer is the SEIZE ending. |
| kr0nos · gr1mwald | Wire noise | — |

### Structure — 26 contracts, 5 interludes

**ACT I — THE FREE SHELF** *(m0 → m2b)* — learn the trade. Sable hands you work; cr4sh teaches you the wire. Ends with V01D booted and his confession: *"they have my file too. ask Sable what a review date is."*

**ACT II — THE COLLECTION METHOD** *(m5 → m6b)* — the jobs turn political. You meet 2FA (Meridian), the hot host (Ostrand), and then **cr4sh goes quiet mid-job** — his last DM is half a sentence and the log you pull shows his origin deep-probed from 6.0.0.1. Sable sends you for a manifest and tells you not to open it; 0RACLE tells you your name was in it. You pull Sable's own file: COMPLIANT, review date, and one line — *protected asset: ANATOMICAL, location unknown.* Then **Director Halloran writes to you directly** with an offer, and a test: delete a runner's file from an agency relay. The file is cr4sh's. Helping your friend means working for the enemy, once.

**ACT III — THE GRID** *(n4 → m7)* — 0RACLE reveals themselves as Anatomical. You find 6.0.0.1 in the Kowloon logs. You pull **your own file** and it has a review date 72 hours out — the top bar starts counting down. Sable finally speaks straight and asks you to fake her termination in the agency's own records (the record editor, used for the thing it was built for). Then NORAD. The terminal asks what to do with the killswitch, and this time each answer belongs to someone who asked you for it:

- **burn** — Anatomical's ask. No one is watched again. No one is paid, either.
- **seize** — Halloran's offer. The grid still watches. For you.
- **walk** — Sable's ask. Delete yourself and leave the machine humming.

**CODA — post-ending** *(m8 → m10)* — Blackwing. Then **find cr4sh**: a detention intake host, a trace, a decode, and one DM that says *"took you long enough."* Anatomical hands you PPOP as themselves. Finally Halloran, resolved by your ending: burn → you leak his file; seize → you demonstrate on his home node; walk → he sends you one line and closes your file for real.

### Interludes (read-only notes)
- **n1** 0RACLE — *you don't know who you work for* (after m2)
- **n2** SABLE — *ignore the noise* (after m4)
- **n3** V01D — *what a review date is* (after m2b) **new**
- **n4** 0RACLE — *I am Anatomical* (after m6b) **new**
- **n5** 0RACLE — *last warning before the core* (after m6c)

---

## 2. Collectibles — TAPES

Twelve `.tape` files hidden on story hosts. Never an objective. You find them by reading — `ls` shows them, `cat` plays them. Three sets of four:

| Set | Voice | Where |
|---|---|---|
| **HAVEN** | Sable's dev notes for HavenCracker, 2041–43 | early hosts |
| **WIRE** | cr4sh's old recordings from the first board | mid hosts |
| **FORK** | Anatomical's diary of the fork and the disappearance | late hosts |

The **Vault** window (dock: ▣) tracks them. Set rewards:
- any **4** → title **ARCHIVIST** shown on the wire
- **8** → **amber phosphor** CRT theme unlocked in Settings
- all **12** → *you read the source*: HavenCracker runs at +50% permanently, and Sable sends the last message she was never going to send

`tapes` in the terminal lists what you've found.

---

## 3. The shop — make every purchase felt

Every hardware line now prints its concrete effect the moment you buy it (*"crack on a tier-2 lock: 7.0s → 5.0s"*), and `rig` shows your whole build with real numbers.

### New hardware
| Item | Effect |
|---|---|
| **Gateway** L1→L3 (Burner → Shielded → Ghost) | Trace grace period 7s → 14s → 22s after