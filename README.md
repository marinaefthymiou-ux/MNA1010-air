# MNA1010 Air

**An airline business model simulator for the MNA1010 module.**
Created by Prof Marina Efthymiou, September 2026.

Students take over a start-up airline based at **Geneva (GVA)** with €30 million and eight quarters (two years) to prove that their chosen business model works. They pick one of two archetypes — a **Low-Cost Carrier (LCC)** or a **Full-Service Network Carrier (FSNC)** — and make quarterly decisions on network, alliance, routes, aircraft, cabin configuration, per-cabin fares and frequency, while shocks (fuel spike, ATC strike, recession, price war, pandemic) arrive on a schedule fixed by a scenario seed.

A live **strategic coherence** score measures how well every decision fits the model chosen; a board review at the end grades the run A–F. The teaching point is that an airline is a system of choices that must fit together — the market punishes carriers that are *stuck in the middle*, even when each individual choice looked reasonable.

## Play the simulator

**→ [Launch MNA1010 Air](https://YOUR-USERNAME.github.io/mna1010-air/)**

Nothing to install; runs in any modern browser (Chrome, Edge, Firefox, Safari). Works offline once loaded. Nothing a student enters is sent anywhere.

## Data and realism

Demand, competitor seats and fares, aircraft economics, cabin configurations, block times, airport charges and general costs are drawn from the MNA1010 *Business Case University Challenge 24* dataset — five airports, nine aircraft types, six competitor airlines, real quarterly demand by cabin. Items that are not in the workbook (feed uplifts, hub complexity cost, coherence penalties, shock magnitudes) are modelled and marked as assumptions in the source file.

## Features

- Two coherent business models with model-specific coherence rules.
- Four routes from Geneva: London Heathrow, Paris CDG, Amsterdam, Alicante.
- Real per-route, per-cabin demand and competitor fares.
- Full unit-economics reporting: load factor, spill, yield, ASK, RPK, CASK, RASK, break-even load factor.
- Live strategic coherence score with plain-language findings each quarter.
- Five scenario shocks with model-specific board coaching.
- Deterministic **scenario seed** so every group faces the same scenario and results are comparable.
- Instructional briefing on the two models and a searchable 39-term glossary, with dotted-underline tooltips throughout.
- **Two exports**: a full HTML report reproducing every decision, ledger, shock and boardroom comment (prints cleanly to PDF); and a CSV of every number for AI-assisted analysis.

## For instructors

The repository ships with the simulator only. The full teaching pack — instructor handbook, student user guide, group assignment brief and assessment rubric — is distributed to MNA1010 staff and students through the module’s VLE.

To tune the simulator, all parameters sit in `CONFIG`, `MODELS` and `SHOCKS` near the top of the script in `index.html` and are documented in the comment block above them.

## For students

Read the "Understand the two models first" briefing on the start screen before you choose. Use the scenario seed your lecturer gives you. Export the HTML report before you close the tab — nothing is saved automatically.

## Credit and citation

Created by **Prof Marina Efthymiou**, September 2026, for the MNA1010 module.
Please cite as: *Efthymiou, M. (2026). MNA1010 Air — airline business model simulator. MNA1010 module.*

## Licence

All rights reserved. Provided for educational use within the MNA1010 module. For use outside the module, please contact the author.
