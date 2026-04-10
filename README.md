# MengLinMaker
Building systems on top of **messy real-world data**.
I focus on:
- Data pipelines with observability to detect poorly processed data.
- Local-first analytical UX for interactive data exploration.
- Developer tools to catch issues during development.

## ✍️ [Writing](https://medium.com/@menglinmaker)
I write about **things that broke, tradeoffs, and what didn’t work**:
- Serverless GPU vs CPU inference for ML workloads.
- Iterating on a data pipeline from concept to production.

## 🤝 Open source
- Won a 1000 USD open source bounty ([SolidHack 2024](https://opencollective.com/solid/projects/solidhack-2024/expenses/226889)) for a UI component contribution.
- Currently contributing [external Docker image support](https://github.com/anomalyco/sst/pull/6359) to SST.
- Added dependency highlighting to the [Skott](https://github.com/antoine-coulon/skott/pull/180) dependency visualiser.

## 🚀 Selected work

### 🏠 [NewHomie](https://github.com/New-Homie/new-homie) — real estate analytics
Analytics platform for finding a place to live in Australia:
- Transforming messy scraped property data to help users compare properties across different buying strategies.
- Observable pipeline with fault tolerance on AWS (OpenTelemetry + LGTM).
- Local-first dashboard as code (DuckDB WASM).
- In production since October 2025.

### 🎹 [Musidi](https://www.musidi.org/) - on-demand piano transcription
Serverless ML piano audio to MIDI converter:
- [Highly parallel AWS Lambda architecture](https://medium.com/aws-tip/piano-transcription-saas-on-aws-ed73ac9c51d)
- Explores tradeoffs between CPU/GPU inference and parallel processing strategies.
- In production since April 2024.

### 🧩 [eslint-plugin-runtime-compat](https://github.com/MengLinMaker/eslint-plugin-runtime-compat)
ESLint plugin for detecting runtime compatibility issues:
- Catches runtime incompatibilities statically before they reach production.
- Built for server-side libraries that need compatibility across runtimes.

## Note
Most projects are iterative and evolve through real-world usage and constraints.
I optimise for learning through real-world projects.
