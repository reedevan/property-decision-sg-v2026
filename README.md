# Property Decision Singapore v2026 - home-buying decision tool 2026

> **A Singapore home-buying planner for affordability checks, loan-limit analysis, and property-type comparisons, refreshed with live data and released for 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/reedevan/property-decision-sg-v2026?style=flat-square)](https://github.com/reedevan/property-decision-sg-v2026)

---

<p align="center">
  <a href="https://reedevan.github.io/property-decision-sg-v2026/">
    <img src="https://img.shields.io/badge/Download-Property%20Decision%20Singapore%20Latest-brightgreen?style=for-the-badge" alt="Download Property Decision Singapore">
  </a>
</p>

> **[Direct Download - Property Decision Singapore v2026](https://reedevan.github.io/property-decision-sg-v2026/)**

---

[Download Latest Build](https://reedevan.github.io/property-decision-sg-v2026/)

---

## What Property Decision Singapore Does

Property Decision Singapore is a browser-based decision aid for people evaluating home purchases in Singapore. It combines affordability estimates, mortgage capacity checks, and property comparisons so you can assess different choices in a single dashboard. The tool covers key loan constraints including TDSR, MSR, and LTV, while also estimating downpayment and stamp duty.

It is especially helpful when you want to see how cash available, financing rules, and property category affect your options across HDB, condo, and landed homes. The dashboard also provides segment and land bid analysis, plus live refreshes from public sources for more up-to-date comparisons.

---

## Highlights

- Singapore home-buying affordability and loan calculator
- TDSR, MSR, and LTV evaluation for financing review
- Analysis of maximum loan tenure and the age-65 LTV cliff
- Estimation of cash downpayment and stamp duty
- Comparison of cash and mortgage scenarios
- HDB, condo, and landed scorecards for side-by-side review
- Segment and land bid analysis for market and site context
- Live refresh from public data sources
- Dashboard interface for fast scenario assessment
- Support for GitHub Pages deployment

---

## Setup

1. Clone or download the repository:
   - `git clone https://github.com/reedevan/property-decision-sg-v2026.git
2. Open the project folder:
   - `cd sg-property-decision`
3. Start the app by opening the main HTML file in a browser, or use any static web server if you want a local preview.

If you are using the hosted version, you can also open the deployment link directly in your browser.

---

## How to Use It

Open the dashboard, enter your purchase assumptions, and review the resulting affordability and borrowing limits.

A typical flow looks like this:

1. Choose the property category you want to assess, such as HDB, condo, or landed.
2. Review the affordability output and financing checks.
3. Compare estimated downpayment, mortgage, and stamp duty figures.
4. Examine the TDSR, MSR, and LTV results for that scenario.
5. Look at the max loan tenure and age-65 cliff effect.
6. Use the segment or land bid context when deciding between locations.

This tool is meant for decision support and learning, so it works best as a comparison reference rather than a final recommendation.

---

## Configuration Notes

Most configuration lives inside the web application or within the static files that drive the dashboard. If you are running your own copy locally, inspect the main HTML file and related scripts for default scenarios, refresh behavior, and layout settings.

Example structure:

```text
/index.html
/assets/
/data/
/scripts/
```

If you publish a custom build, make sure any public source URLs or site paths are updated to fit your hosting environment.

---

## Requirements

- A web browser that supports modern HTML and JavaScript
- Internet access for live refreshes from public sources
- Static hosting support if you want to deploy it with GitHub Pages
- Enough local storage for browser state and cached data, if used

---

## FAQ

**Is this only for Singapore properties?**  
Yes. The calculations and comparison paths are focused on Singapore home-buying scenarios.

**Does it include financing checks?**  
Yes. It covers affordability, TDSR, MSR, LTV, loan tenure, and related comparisons.

**Can I compare different property types?**  
Yes. The dashboard offers HDB, condo, and landed scorecard-style comparisons.

**Where is the data sourced from?**  
The dashboard refreshes from public sources as part of its workflow.

**How do I customize or update it?**  
Edit the web app files and redeploy your version, especially if you want to change scenarios, data sources, or the interface.

**What should I do if something fails to load?**  
Check the browser console, confirm the files are in place, and verify that the public data endpoints can be reached.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
