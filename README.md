# BIAS PLAYGROUND
### Your Brain Is Lying To You — 44 Interactive Experiments

> *"You are about to be manipulated. Every experiment below is a real cognitive trap — the same ones used by advertisers, politicians, con artists, and pseudoscientists. You won't just learn about bias. You'll experience it, make the wrong call, and then see exactly why."*

**Bias Playground** is an interactive critical thinking resource built to expose the cognitive biases, statistical tricks, manipulation tactics, and social engineering patterns that shape decisions without people realizing it. You don't read about the trap. You walk into it — then see the mechanism.

Live demo: [bravowhiskybravo.github.io/bias-playground](https://bravowhiskybravo.github.io/bias-playground)

Part of the **BS-O-Tron Suite** → [BS-O-Tron 3000](https://bravowhiskybravo.github.io/bs-a-tron3000)

---

## Why This Exists

Most resources about cognitive bias describe the phenomenon and move on. This one makes you experience it. There's a meaningful difference between knowing that the Anchoring Effect exists and watching yourself guess higher after seeing a high random number — even knowing the number was arbitrary.

The same applies to scams, manipulation tactics, and statistical deception. Reading "urgency creates pressure to bypass critical thinking" is abstract. Clicking through a fake offer page with a countdown timer and seven annotated manipulation techniques firing simultaneously is concrete.

Understanding the pattern is the defense. You cannot be reliably manipulated by a technique you can name.

---

## What's Inside

### Section 1 — Cognitive Psychology Classics (7 experiments)
The foundational biases documented by Kahneman, Tversky, Forer, and others — now interactive.

- **Anchoring Effect** — Spin a random number, then estimate. Watch it contaminate your answer.
- **Gambler's Fallacy** — Build a streak of coin flips. Probability has no memory.
- **Availability Heuristic** — Which kills more: sharks or vending machines? Fear of the vivid distorts risk.
- **Framing Effect** — Same surgery, two framings. "90% survival" vs "10% mortality." Watch your gut react differently to identical data.
- **Conjunction Fallacy** — The Linda Problem. A specific story feels more probable than a general one. It can't be.
- **Sunk Cost Trap** — You're sick, the concert ticket is non-refundable. Walk through why the $80 is irrelevant.
- **Dunning-Kruger Visualizer** — Rate your confidence, take a quiz, see the gap between certainty and performance.

### Section 2 — How To Lie With Statistics (6 experiments)
Every trick from Darrell Huff's 1954 playbook, rendered interactive.

- **The Truncated Y-Axis** — Same data, two charts. One looks like a crisis. One looks flat.
- **Misleading Averages** — Mean vs median vs mode on a skewed salary dataset. Which would a company advertise?
- **Correlation ≠ Causation** — Nicolas Cage films vs pool drownings. r=0.67. Real correlation. Zero meaning.
- **Sample Size Illusion** — "4 out of 5 dentists" — how many dentists? The number always matters as much as the percentage.
- **Percent vs Percentage Points** — "Crime doubled" and "crime rose 1 percentage point" describe the same change.
- **Cherry Picking Visualizer** — Draw a trend line on partial data, then watch it collapse when hidden points are revealed.

### Section 3 — Magic & Mentalism (4 experiments)
The techniques behind stage magic and mentalism are engineered cognitive exploits. They work on everyone.

- **The Magician's Choice** — Pick a card. Either choice leads to the same outcome. Reveals the forcing mechanic.
- **Change Blindness** — A scene changes during a visual disruption. Most people miss it entirely.
- **The Illusion of Choice** — Four options engineered so one is almost always picked. Reveals the design.
- **Cold Reading Live** — One vague statement. You interpret it. Then see how many people it simultaneously described.

### Section 4 — Pseudoscience Mechanics (4 experiments)
The psychological infrastructure that makes pseudoscience feel credible — exposed from the inside.

- **Regression to the Mean** — Feel terrible, apply a remedy, feel better. Replay without the remedy. Same curve.
- **Cherry-Picked Testimonials** — Three glowing reviews shown first. Reveal all 13. The picture transforms.
- **The Placebo Mechanic** — Two identical supplements, one branded. Rate both. Reveal they're the same.
- **Unfalsifiable Claim Generator** — Try to disprove the claim. Every attempt is countered. That's the design.

### Section 5 — Bonus Round (5 experiments)
- **Spotlight Effect** — How many people will remember you walked in late? Far fewer than you think.
- **IKEA Effect** — You assembled it vs. it came pre-built. Price both. Labor creates irrational attachment.
- **Hindsight Bias** — "I knew it all along." You didn't. Hindsight rewrites memory of uncertainty.
- **Decoy Effect** — Add a clearly inferior third option and watch which of the original two wins.
- **Hot Hand Fallacy** — A player has made 5 shots in a row. Does that change the odds on shot 6?

### Section 6 — Don't Fall For It: Scams & Social Engineering (6 experiments)
- **Urgency & Scarcity Tactics** — A fully rendered fake offer page, annotated with 7 manipulation techniques.
- **Pretexting — The Social Engineering Playbook** — Branching scenario: an "IT technician" needs your credentials. Walk through the 4-phase attack pattern.
- **Vishing Script Deconstruction** — A realistic phone scam transcript, line by line. Click what looks suspicious. Reveal annotates every technique.
- **The Long Con — Pig Butchering Pattern** — Annotated 6-phase timeline from first contact to exit block.
- **Authority Exploitation + Phishing Spotter** — Real or scam? Classify three communications, then dissect URL anatomy.
- **Too-Good-To-Be-True Detector** — Tag red flags before the scanner runs. Three offer types cycling through.

### Section 7 — Don't Fall For It: General Manipulation Tactics (12 tactics)
Each tactic includes: definition, real-world example, recognition signals, response strategy, and a copy-paste script.

Gaslighting · Love Bombing · DARVO · Moving the Goalposts · Whataboutism · False Dichotomy · Intermittent Reinforcement · Foot-in-the-Door · Guilt Trip · Gish Gallop · Negging · Manufactured Consensus

### Section 8 — Defense Toolkit
- **Red Flag Checklist** — 32 interactive flags across communication, relationship, and debate contexts. Live risk score.
- **Countermeasures Library** — 6 response strategy cards with do/don't lists and copy-paste scripts for real situations.
- **Verification Habits** — Reference table: when someone claims X, verify by doing Y, red flag if Z. Plus the Pause Protocol.
- **Report & Resources** — FTC, FBI IC3, CISA, BBB Scam Tracker, HaveIBeenPwned, and guidance for if you've already been targeted.

---

## Features

- **44 experiments and tactics** across 8 sections — all in a single HTML file, no dependencies
- **Floating Pattern Reference Panel** — minimizable, lists all 22 manipulation patterns with one-line definitions
- **Progress tracker** — X of 44 completed, updates across all sections
- **Interactive throughout** — every experiment has an active decision phase before the reveal
- **Copy-paste defense scripts** — real language for real situations, one click to copy
- **Fully annotated reveals** — every trick named, every mechanism explained after you've experienced it
- **Cross-linked with BS-O-Tron 3000** — the suite's companion pseudoscience demonstration tool

---

## Running Locally

Single static HTML file. No build step, no dependencies.

```bash
git clone https://github.com/bravowhiskybravo/bias-playground.git
cd bias-playground
python -m http.server 8080
```

Open `http://localhost:8080` in your browser.

> **Note:** Use `http://localhost` not `file://` — the clipboard API requires a secure context.

---

## The BS-O-Tron Suite

| Project | What it does |
|---|---|
| [BS-O-Tron 3000](https://bravowhiskybravo.github.io/bs-a-tron3000) | Demonstrates how pseudoscience manufactures credibility |
| [Bias Playground](https://bravowhiskybravo.github.io/bias-playground) | Makes you experience cognitive bias firsthand, then explains the mechanism |

---

## References

- Kahneman, D. (2011). *Thinking, Fast and Slow.* Farrar, Straus and Giroux.
- Tversky, A. & Kahneman, D. (1974). Judgment under uncertainty. *Science, 185*(4157), 1124–1131.
- Forer, B.R. (1949). The fallacy of personal validation. *Journal of Abnormal Psychology, 44*(1), 118–123.
- Huff, D. (1954). *How to Lie with Statistics.* W.W. Norton & Company.
- Cialdini, R. (1984). *Influence: The Psychology of Persuasion.* Harper Business.
- Ariely, D. (2008). *Predictably Irrational.* Harper Collins.
- Norton, M., Mochon, D. & Ariely, D. (2011). The IKEA effect. *Journal of Consumer Psychology, 22*(3), 453–460.

---

## Disclaimer

All experiments are educational demonstrations. No personal data is collected or transmitted. Everything runs client-side in your browser.