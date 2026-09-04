# UNITS///OS

**Elite Cybernetic Operatives. Will you take the opportunity?**

A CRT-terminal hacker sim set in New Milos City. You start with an empty deck — no tools, no botnet, no name — and work contracts through an anonymous agency uplink until you're standing in a grid that has been watching all of you the whole time.

Single self-contained HTML file. No build step, no dependencies, no networking of any kind — every host, trace and forum post is local fiction.

## Play

Open `index.html` in any modern browser. Progress saves to `localStorage`, scoped per browser, so every player keeps their own private run.

New to this kind of game? Type `hint` at any time and the terminal tells you the exact next command — or switch on **Guide Me** in Settings to get that after every command.

## The loop

```
getbrew stable                  install the package manager
brew install havencracker       pull a cracker off the free shelf
scan 196.4.55.120               probe a target
buybot fullz 5                  rent IPs — this is your route home
connect 196.4.55.120            the reverse-trace starts now
hc                              break the password
download ledger_q3.xls          take what you came for
sqlaudit                        open an audit session on the host
sq seelogs                      see what they logged about you
delete log all                  shred it
sq exit                         close the session
disconnect                      leave before the trace gets home
```

Going after someone on the wire — three different games depending on what they're hiding behind:

```
# Fullz chain — a guessing game. the decoder eliminates relays, you name the origin.
resolve kr0nos                  eliminate relays
nmap gui kr0nos                 hover the nodes for IPs, read the fingerprints
boot 210.161.245.60             call it. guess wrong and he'll say so publicly

# R00tKernel — a sequential siege. only the outermost relay on a line is reachable.
resolve gr1mwald                expose the frontier of each line
boot 168.166.13.99              drop it; the next one behind it steps up
                                (he patches replacements while you work)

# Amorphous — an obsidian mesh. no order, but every node is shelled.
resolve V01D                    strip shells — a good decoder strips several at once
boot 206.205.193.81 186.213.133.61     flood them together
```

Tear enough of someone's net down and **they start messaging you.** You can tell them where to go,
take the surrender for early rep, or demand tribute — but only if they're scared enough to pay.

## Features

- **20 story quests** across four acts, three endings, two post-ending endgame contracts
- **Named arsenal** — Brew, HavenCracker, HavenCracker Redux, HeavenCrackR, Mythos Blackwing
- **Decoders & the nmap GUI** — 1NetLynx, Parity, Parity Prime, Partisan Occulus, PPOP (VirtualEcholocation). `resolve` draws the target's botnet as a live topology; hover a node to expose its address. Your decoder greys out the relays it can *prove* are dead ends — whatever is still lit is a candidate, and picking the real one is your call, not the tool's. Better decoders leave you fewer candidates; the premium ones name the origin outright.
- **Botnets & monitors** — Fullz / Amorphous / R00tKernel, with MonitorMe, ObsidianGUI and KernelGuide
- **Booters & forum reputation** — resolve an origin by social engineering or decoding, then drop them
- **A living wire** — messenger DMs and a forum that escalates from idle chatter to outright panic as the story turns, then resolves after your ending
- **Freeplay gigs** — an endless job board between contracts
- **Getting past 2FA** — banks and socials roll a second factor. Look the account holder up with **InKobos**, wear a caller ID they trust, phone them, and they'll read you their own passkey; **EncryptR** forges the rolling token from it
- **The record editor** — some clients don't want a file stolen, they want a number changed. `edit` any record and a form opens: a grade, a debt balance, a follower count, a criminal disposition
- **Start your own thread** — ＋ new post on The Wire. Offer to boot people and see who volunteers (how they answer depends on your rank), shake the board for paid leads, or just ask what everyone's up to
- **iAliasFast** — `brew install ialiasfast`, then bind any command you're sick of typing: `ias add dl sql delete all`
- **Full CRT treatment** — curved glass, scanlines, chroma, rolling sync bar, generative ambient score

## Credits

Design & lore by **theliamladia**. Built with Claude Code.
