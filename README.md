# PANW Objection Handling Simulator

A browser-based training tool for practicing sales objection handling across the Palo Alto Networks product suite. You pick the product, the type of objection, and the difficulty level — it drops you into a conversation with an AI playing a skeptical customer. When you're done, it grades your performance and tells you exactly where you lost ground.

## Why I built this

Onboarding reps to a product suite as broad as PANW's takes time, and the hardest part isn't product knowledge — it's developing the instinct to handle pushback in real time. Role-playing with a manager helps, but it's hard to schedule and easy to go easy on people. I wanted something that could be pulled up before a call, used to drill a specific scenario, and give honest feedback without any social softening.

## How to use it

```
1. Clone or download the repo
2. Open index.html in Chrome or Edge
```

Pick a product, an objection type, and how hard you want the customer to push back. The simulation runs as a live conversation — type your responses or use the microphone. When you're ready for feedback, hit **End Session** and get a full coaching report with scores, specific gaps, and model responses for the moments you could have handled better.

## What's covered

**Products:** NGFW, Prisma Access, Prisma Cloud, Cortex XDR, Cortex XSIAM, Cortex XSOAR, AI Security

**Objection types:** Price/budget, existing vendor, complexity, trust/maturity, feature gaps, timing, ROI, platform vs. best-of-breed

**Difficulty levels:** IT Manager (Junior), IT Director (Mid), CISO/CTO (Senior)

## How it works

Runs entirely in the browser. No backend, no server, no install. The AI plays the customer persona and evaluates the full conversation at the end. Cost is roughly **$0.05–$0.10 per session** using `claude-sonnet-4-6`.

Voice features use the browser's built-in Web Speech API — the customer can speak their responses aloud, and you can respond by voice. Microphone input works in Chrome and Edge.
