---
layout: post
title: The Last Data Center
date: 2026-02-02
---

# The Last Data Center

Elon Musk recently announced that SpaceX had acquired xAI to build "orbital data centers" and "extend the light of consciousness to the stars."

Most people read this as Musk being Musk—grandiose language wrapped around a reasonable bet on space-based compute. The thesis seems straightforward: AI needs energy, terrestrial grids are constrained, the sun provides unlimited power, therefore put data centers in orbit.

That reading is wrong. Not because Musk isn't building orbital compute—he is. But because "data centers in space" is the cover story. The real play is underneath.

---

## The Physics Problem Everyone Ignores

The obvious challenge with orbital compute is thermal management. In vacuum, you can only dissipate heat through radiation. Stefan-Boltzmann is unforgiving: an H100 GPU running at 700W needs roughly 2 square meters of radiator surface just to reach thermal equilibrium. Scale that to a data center and you're launching as much radiator mass as compute mass.

Musk knows this. Google knows this—their Project Suncatcher paper names thermal management as the primary engineering challenge. So why is Musk betting billions on something that appears to violate basic physics?

Because he's not planning to run silicon in orbit. At least not for long.

---

## The Factory Thesis

Buried in SpaceX's recent activity is a program called Starfall. Bloomberg reported on it in July: uncrewed capsules launched via Starship to manufacture products in microgravity—pharmaceuticals, semiconductors, advanced materials—then return them to Earth.

Meanwhile, SpaceX is building a $280 million semiconductor packaging facility in Texas. FOPLP architecture, 700mm substrates, production starting 2026.

Meanwhile, Varda Space Industries—founded by a SpaceX veteran, backed by Founders Fund—has completed five orbital manufacturing missions, proven the economics of capsule reentry, and just raised $187 million.

Meanwhile, a startup called Flawless Photonics produced 5 kilometers of ZBLAN optical fiber on the ISS in two weeks. ZBLAN manufactured in microgravity has 10-100× lower signal loss than terrestrial silica fiber. It cannot be made properly on Earth—gravity causes crystallization defects during cooling.

Connect the dots:

**Phase 1:** Manufacture compute substrates in orbit—perfect silicon crystals, ZBLAN fiber for photonic interconnects, exotic semiconductors that phase-separate on Earth. Return them via Starfall. Package them in Texas.

**Phase 2:** Stop returning them. Deploy photonic compute directly into the Starlink constellation. Photonics doesn't have silicon's thermal problem. Radiation doesn't flip photons. The optical infrastructure for inter-satellite links already exists.

The "orbital data center" isn't about putting GPUs in space. It's about manufacturing a new class of compute substrate that only works if you have access to microgravity—and then running it in the one environment where it performs best.

---

## The Moat

If this is the play, the competitive implications are severe.

OpenAI, Anthropic, Google, Microsoft—they've collectively committed over a trillion dollars to terrestrial AI infrastructure. They have no launch capability. No orbital manufacturing program. No photonic compute stack.

To match Musk's position, they would need to:

1. Develop or acquire launch capability (5-10 year lag)
2. Build orbital manufacturing (no existing program outside SpaceX ecosystem)
3. Pivot to photonic compute architectures
4. Integrate all three into a coherent stack

By the time they could replicate this, SpaceX/xAI would be two generations ahead.

The moat isn't launch cost. It's manufacturing exclusivity for substrates that don't exist terrestrially.

---

## In The End

Everything I've described is a solution to a specific constraint: *how do you scale centralized compute when energy and thermal limits bind?*

Musk's answer: escape to space, where energy is unlimited and you can engineer around thermal limits with new substrates.

It's a brilliant answer. It might even work.

#### But it's an answer to the wrong question.
