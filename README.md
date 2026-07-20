<div align="center">

# hey, I'm Sash 👋

**Seharish Fatima** — developer, self-directed learner, founder of [NOCTAVENT](#)

Karachi, Pakistan 🇵🇰 · building things, breaking things, then actually fixing them

</div>

---

### the short version

I come from a data science background, I tutor O/A-Level Maths and CS on the side, and I build a lot of small, complete things instead of a few big unfinished ones. Every project below started life as an old repo — some working, most quietly broken — and got audited, benchmarked against real data, and rebuilt until the numbers held up.

That's the actual theme of this profile. Not "10 apps." Ten *audits*.

### how I actually work

Every repo pinned here went through the same process before I called it done:

1. **Read the old code like it's guilty until proven innocent.** A churn model that scored 0.001 MAE on training data isn't good — it memorized the answer key.
2. **Verify against real data, not vibes.** If a claim can be tested, I test it, before I ship it.
3. **Delete the fake stuff.** Five hardcoded rows pretending to be a 141-sample NASA dataset. A JavaScript UI that never actually called the C++ engine it was supposedly demoing. Gone.
4. **Ship it somewhere real.** Streamlit Cloud, GitHub Pages, WebAssembly — whatever the project actually needs, not whatever's easiest.

If you read one repo's README, you'll see a "the crime scene this repo used to be" section. That's not a bit. That's the actual diff between v1 and v2.

---

## 🚀 the apps

### algorithms & systems

| project | what it does | stack |
|---|---|---|
| **[ScheduleSavvy](https://github.com/Seharish-Fatima/ScheduleSavvy)** · [live](https://schedulesavvy.streamlit.app) | Clash-free timetable generator for FAST-NUCES students — backtracking scheduler over real course data, Excel parsing, section-alias normalization | Python, Streamlit |
| **[TaskForge](https://github.com/Seharish-Fatima/TaskForge)** · [live](https://seharish-fatima.github.io/TaskForge/) | A priority task scheduler whose engine — max-heap, hash map, undo/redo stacks — is real C++ compiled to WebAssembly and running in your browser tab. The JS only draws. | C++17, Emscripten/Embind, WASM |
| **[Superposed](https://github.com/Seharish-Fatima/Superposed)** · [live](https://seharish-fatima.github.io/Superposed/) | Quantum chess with *actual* superposition — ghosts that block, captures that trigger real measurement, and an expectiminimax AI that reasons over collapse probabilities instead of pretending the physics is decorative | Python, pygame, pygbag/WASM |

### machine learning

| project | what it does | stack |
|---|---|---|
| **[FlightRisk](https://github.com/Seharish-Fatima/FlightRisk)** · [live](https://flightrisk.streamlit.app) | End-to-end churn prediction — live-trained gradient boosting, ROC/calibration validation, and a threshold lab that turns "accuracy" into an actual retention-budget decision | Python, scikit-learn, Streamlit |
| **[PCA Fraud Detector](https://github.com/Seharish-Fatima/PCA-Fraud-Detector)** · [live](https://pcafrauddetector.streamlit.app) | Unsupervised anomaly detection on the ULB credit card dataset — PCA-based fraud scoring in a SOC-terminal dashboard | Python, scikit-learn, Streamlit |
| **[FairCheck](https://github.com/Seharish-Fatima/FairCheck)** · [live](https://faircheck-ml.streamlit.app) | An ML fairness auditor with an aware-vs-blind intervention toggle — watch Disparate Impact move in real time, and see the one case where "just remove the sensitive column" *doesn't* actually fix anything | Python, scikit-learn, Streamlit |
| **[Burnout Detector](https://github.com/Seharish-Fatima/Burnout-Detector)** · live: add link once deployed | A transparent, weighted burnout screener — every driver's contribution is visible, deliberately not a black-box model, because a mental-health tool should show its work | Python, Streamlit |

### data & science

| project | what it does | stack |
|---|---|---|
| **[Netflix Decoded](https://github.com/Seharish-Fatima/Netflix-Decoded)** · [live](https://netflix-decoded.streamlit.app) | A five-act data story on the Netflix catalog — myth-checking "Netflix pivoted to TV," the international content bet, and the real math behind the one-season-cancellation meme | Python, pandas, Streamlit |
| **[Waveform](https://github.com/Seharish-Fatima/Waveform)** · [live](https://waveform.streamlit.app) | The pandemic read as a time series — wave detection, growth/doubling-time analysis, a falling case-fatality curve, and a forensics tab on the WHO data's own reporting collapse | Python, scipy, Streamlit |
| **[Orbital](https://github.com/Seharish-Fatima/Orbital)** · [live](https://orbital-osdr.streamlit.app) | Built for NASA Space Apps 2024 — reads OSDR space-biology metadata and auto-generates the mission's graphical abstract, then answers the actual question: did spaceflight damage the tissue? (Spoiler: statistically, no.) | Python, pandas, SVG generation, Streamlit |

---

### the pattern, if you're skimming

Every rebuild fixed a specific kind of lie: fake data standing in for real data, a metric that doesn't match the task, silent crashes nobody caught because nobody ran it against real inputs. The fix was always the same instinct — verify first, ship second.

<div align="center">

*building toward AI/CS grad study — debugging my way there, one repo at a time.*

</div>
