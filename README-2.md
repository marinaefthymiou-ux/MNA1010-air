# AirStrategist

**An airline business model simulator for higher education.**
© 2026 Prof Marina Efthymiou. Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).
DOI: [10.5281/zenodo.22309151](https://doi.org/10.5281/zenodo.22309151)

Students take over a start-up airline based at **Geneva (GVA)** with €30 million and eight quarters (two years) to prove that their chosen business model works. They pick one of two archetypes, a **Low-Cost Carrier (LCC)** or a **Full-Service Network Carrier (FSNC)**, and make quarterly decisions on network, alliance, routes, aircraft, cabin configuration, per-cabin fares and frequency, while shocks (fuel spike, ATC strike, recession, price war, pandemic) arrive on a schedule fixed by a scenario seed.

A live **strategic coherence** score measures how well every decision fits the model chosen; a board review at the end grades the run A to F. The teaching point is that an airline is a system of choices that must fit together: the market punishes carriers that are *stuck in the middle*, even when each individual choice looked reasonable.

## Play

**→ [Launch AirStrategist](https://YOUR-USERNAME.github.io/airstrategist/)**

Nothing to install; runs in any modern browser (Chrome, Edge, Firefox, Safari). Works offline once loaded. Nothing a student enters is sent anywhere.

## Data and realism

Demand, competitor seats and fares, aircraft economics, cabin configurations, block times, airport charges and general costs are drawn from an airline-planning dataset for five European airports, nine aircraft types and six competitor airlines, with real quarterly demand by cabin. Items not in the dataset (feed uplifts, hub complexity cost, coherence penalties, shock magnitudes) are modelled and marked as assumptions in the source.

## Features

- Two coherent business models with model-specific coherence rules.
- Four routes from Geneva: London Heathrow, Paris CDG, Amsterdam, Alicante.
- Real per-route, per-cabin demand and competitor fares.
- Full unit-economics reporting: load factor, spill, yield, ASK, RPK, CASK, RASK, break-even load factor.
- Live strategic coherence score with plain-language findings each quarter.
- Five scenario shocks with model-specific board coaching.
- Deterministic **scenario seed** so every group faces the same scenario and results are comparable.
- Instructional briefing on the two models and a searchable 39-term glossary, with dotted-underline tooltips throughout.
- **Two exports**: a full HTML report reproducing every decision, ledger, shock and boardroom comment (prints cleanly to PDF, with a subtle authorship watermark); and a CSV of every number for AI-assisted analysis.

## For instructors

The repository ships with the simulator only. The full teaching pack (instructor handbook, student user guide, group assignment brief, assessment rubric, 11-week teaching plan and workshop slides) accompanies the tool separately and is available to instructors on request.

To tune the simulator, all parameters sit in `CONFIG`, `MODELS` and `SHOCKS` near the top of the script in `index.html` and are documented in the comment block above them.

## For students

Read the "Understand the two models first" briefing on the start screen before you choose. Use the scenario seed your lecturer gives you. Export the HTML report before you close the tab; nothing is saved automatically.

## Licence

AirStrategist is released under the **Creative Commons Attribution-NonCommercial 4.0 International Licence** (CC BY-NC 4.0). In plain English:

- **You may** share and adapt the work, including translating it, forking it, or building on it for your own teaching.
- **You must** give appropriate credit (see "How to cite" below), provide a link to the licence, and indicate if changes were made.
- **You may not** use the work for commercial purposes without written permission from the author.

The full licence text is in [`LICENSE`](LICENSE) and at https://creativecommons.org/licenses/by-nc/4.0/legalcode.

For commercial licensing, translations or use outside education, please contact the author.

## How to cite

Please cite AirStrategist in any use, publication or reuse. GitHub renders a "Cite this repository" button based on the `CITATION.cff` file. Pre-formatted citations:

**APA**
Efthymiou, M. (2026). *AirStrategist: an airline business model simulator* (Version 1.0) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.22309151

**Harvard**
Efthymiou, M., 2026. *AirStrategist: an airline business model simulator*. Version 1.0. Zenodo. https://doi.org/10.5281/zenodo.22309151

**Vancouver**
Efthymiou M. AirStrategist: an airline business model simulator. Version 1.0. Zenodo; 2026. Available from: https://doi.org/10.5281/zenodo.22309151

## Author

**Prof Marina Efthymiou**, Dublin City University, DCU Business School
Email: marina.efthymiou@dcu.ie
ORCID: [0000-0001-8611-5973](https://orcid.org/0000-0001-8611-5973)
DOI: [10.5281/zenodo.22309151](https://doi.org/10.5281/zenodo.22309151)

## Version history

- **1.0** (September 2026): first public release. Geneva base, eight quarters, two models, full instructional layer, HTML and CSV exports.
