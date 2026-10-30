# What should a kilolitre of water cost in Bengaluru?

A question-by-question answer to the true price of piped water in Bengaluru, built by [Urvara](https://urvara.life).

- **Read it:** https://vinaybale-collab.github.io/blrwaterprice/
- **The answer (FY2026-27, ₹ per kilolitre billed):** households pay about ₹21; BWSSB spends about ₹61 to run the system today; supplying it, replacing the pipes and plants, and cleaning and returning the sewage costs about ₹113; counting the river, its wildlife, the farms, the forests and the carbon, about ₹208.
- **Every number is editable.** The [assumptions page](https://vinaybale-collab.github.io/blrwaterprice/assumptions.html) lists each one with its sources and range.
- **The model** is in `downloads/bengaluru-water-price-model.xlsx`, with live formulas, and in `assets/app.js`.

## Pages

| Page | What it holds |
|---|---|
| `index.html` | The main question, the staircase from ₹21 to the full cost, and twelve sub-questions with their working |
| `assumptions.html` | All 91 assumptions, editable, with reasons, ranges and sources |
| `sources.html` | Every source, grouped by where it is used |
| `method.html` | How the model works, how it was reviewed, and what data is missing |

It is a static site with no build step. Open `index.html` in a browser, or serve the folder.
