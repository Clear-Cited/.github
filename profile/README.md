<div align="center">

# Clear Cited

**Be the answer AI gives.**

AI search visibility (Answer Engine Optimization / Generative Engine Optimization) for B2B SaaS and developer tools.

[Website](https://clearcited.com) · [Free AI-visibility teardown](https://clearcited.com/free-teardown/) · [AI Visibility Index](https://clearcited.com/ai-visibility-index/)

</div>

---

When a buyer asks ChatGPT, Perplexity, Claude, Gemini, or Google AI for the best tool in your category, you're either **named and cited** — or a competitor is, and you never see the deal you lost.

Clear Cited measures **share-of-model** — how often each AI engine recommends you versus competitors — reproducibly (10+ runs per engine, with confidence intervals), then runs the full stack (SEO foundation, answer-first content, off-site authority) to improve it.

### Free & open source

Five tools, MIT-licensed, each archived on Zenodo with a DOI. They fit together:
find what a page is missing, fix it, then measure whether it moved.

**Measure**

- **[aeo-audit-lite](https://github.com/Clear-Cited/aeo-audit-lite)** — run a buyer prompt against an AI engine repeatedly and measure your *share of model* versus named competitors, with a Wilson 95% confidence interval. `pip install aeo-audit-lite`

**Diagnose**

- **[citation-ready](https://github.com/Clear-Cited/citation-ready)** — check whether a page carries the structural signals observed on content AI engines tend to cite. `pip install citation-ready`

**Fix**

- **[schema-for-ai](https://github.com/Clear-Cited/schema-for-ai)** — copy-paste JSON-LD templates tuned for AI extraction, plus a zero-dependency validator. `pip install schema-for-ai`
- **[schema-generator](https://github.com/Clear-Cited/schema-generator)** — build valid Organization / Product / FAQPage JSON-LD in your browser.
- **[llms-txt-generator](https://github.com/Clear-Cited/llms-txt-generator)** — generate a clean `llms.txt` for your site, in your browser.

**Also**

- **[measured-by-clear-cited](https://github.com/Clear-Cited/measured-by-clear-cited)** — the "Measured by Clear Cited" badge (SVG + embed). Brand assets, so **CC BY-ND 4.0**, not MIT — redistribute freely, but don't alter the mark. See [BRAND.md](https://github.com/Clear-Cited/measured-by-clear-cited/blob/main/BRAND.md).

### Open data

The Index is published as an open dataset — **4,497 measured AI answers** across nine B2B categories, **CC BY 4.0**.

- **Cite this** — [10.5281/zenodo.21612952](https://doi.org/10.5281/zenodo.21612952) (concept DOI, always resolves to the latest release)
- **Protocol** — [10.5281/zenodo.21614890](https://doi.org/10.5281/zenodo.21614890) · pre-registration at [osf.io/cd9q2](https://osf.io/cd9q2)
- **Mirrors** — [Kaggle](https://www.kaggle.com/datasets/clearcited/ai-visibility-index-which-products-ai-recommend) · [Hugging Face](https://huggingface.co/datasets/LoganAdams-ClearCited/Clear_Cited_AI_Visibility_Index)

Every repository here is also mirrored to **[Codeberg](https://codeberg.org/clear-cited)**, release tags included.

### Start here

→ **[Get a free AI-visibility teardown](https://clearcited.com/free-teardown/)** — your domain + a couple of competitors, a short video + one-pager back.

→ **[Browse the AI Visibility Index](https://clearcited.com/ai-visibility-index/)** — public leaderboards of which products AI engines actually recommend.
