# Tracker Sample Planner

How many respondents do you need per wave to see a real move in a brand tracker? Enter the score you expect, the smallest move you need to see and what you can afford, and get the sample you need before you commission the wave.

Open `index.html` in any browser. No build step, no dependencies, no network calls.

- **Verdict:** `you can see it` or `you can't see it`, from your affordable sample against the sample needed.
- **Shows:** respondents needed per wave, the smallest move your sample can see, cost per wave (optional cost per respondent), the margin of error on one score, a table of what each size of move costs to see, and a table of what each sample size can see.
- **Calculation:** n per wave = (z + zb)^2 x (p1(1 - p1) + p2(1 - p2)) / move^2 x design effect. Confidence tightens with the Sidak correction when you scan more than one metric.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

Assumes a simple random sample and covers sampling noise only. A changed panel, question wording or field month can move a score by more than this. Companion to tracker-wave-check, which reads the waves once you have them.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
