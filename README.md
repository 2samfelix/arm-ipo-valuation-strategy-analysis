# Arm Holdings plc (NASDAQ: ARM) — IPO Valuation & Strategy Analysis

## 📄 Project Overview

This project is a full investment-banking-style analysis of **Arm Holdings' September 2023 IPO**, covering equity valuation at the offering, a forward-looking DCF cross-check, and the strategic read on how the market has re-rated the business since. It simulates how an analyst would approach a live deal — using real SEC filings, real valuation techniques, and a thesis question answered with actual numbers, not just described.

Key techniques used:

- Comparable Company Analysis (CCA) at the IPO pricing date
- IPO-date valuation range vs. actual offer price
- A **Valuation Evolution bridge** decomposing total shareholder return into EPS growth vs. P/E multiple expansion
- A **discounted cash flow (DCF)** cross-check, independent of both the IPO price and the market's subsequent re-rating
- Strategic risk assessment

---

## 🏗️ Project Structure

| File | Description |
|------|-------------|
| **Sam_Felix_Arm_IPO_Valuation_Strategy_Analysis.xlsx** | Complete model: historicals, IPO snapshot, CCA, IPO valuation, post-IPO performance with valuation-evolution bridge, DCF with sensitivity table, strategy & risks (11 tabs) |
| **Arm_IPO_Valuation_Strategy_Report.pdf** | Full written report — methodology, findings, valuation evolution, DCF, and final recommendation |
| **Arm_IPO_Executive_Summary.pdf** | One-page executive summary |
| **Arm_IPO_Valuation_Strategy_Deck.pptx** | Slide deck covering the transaction, CCA, valuation range, valuation evolution, and final verdict |

*(Source data: Arm's SEC filings — F-1/424B4 prospectus and FY2024–FY2026 Form 20-F — publicly available via [SEC EDGAR](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001973239&type=20-F).)*

---

## 🔍 Key Findings

- **Arm priced at ~18.7x FY2023 EV/Revenue, about 49% above the six-peer median of 12.6x.** The closest comp-based range was $43–$45 per ADS versus the $51 IPO price — an 11–15% premium, aggressive but defensible given Arm's recurring royalty model and near-100% gross margins.
- **Arm's 5.34x total shareholder return since IPO decomposes into 1.67x from EPS growth and 3.20x from P/E multiple expansion** — independently confirmed by a matching 3.11x expansion in EV/Revenue. Multiple re-rating contributed roughly twice as much to the stock's return as underlying earnings growth.
- **A DCF built entirely from today's actual fundamentals implies a fair value of ~$51.54 — almost exactly Arm's original $51.00 IPO price**, despite the stock trading at $272.21. Three independent methods (the 2023 CCA, the actual IPO transaction, and a 2026 fundamentals-only DCF) all cluster in the $43–$52 range, while the market prices Arm at roughly 5x that.
- **The original 11–15% IPO premium looks conservative in hindsight, not aggressive** — the market has re-rated Arm to a materially richer multiple than any fundamentals-based method, at IPO or today, would support on its own.

---

## 🛠️ Tools & Techniques Used

- Microsoft Excel (CCA, driver-based revenue forecasting, DCF with WACC/CAPM build, sensitivity tables, cross-sheet linked model)
- Financial statement analysis and comparable company analysis
- Discounted cash flow valuation with explicit limitations disclosure (beta reliability, assumption transparency)
- Return decomposition (EPS growth vs. multiple expansion)
- Professional report writing and structuring

---

## 🚀 How to Use

- Download the `.xlsx` to review the full model — every input is color-coded (blue = assumption/source-reported, black = formula, green = cross-sheet link), with sources cited directly next to each figure.
- The DCF tab's sensitivity table shows implied share price across a range of WACC and terminal growth assumptions — the highlighted row uses the model's live-computed WACC, not a static guess.
- Read the `.docx`/PDF report for the full narrative walkthrough, or the one-page PDF for a quick summary.
- This project is intended as a portfolio showcase for roles in:
  - Corporate Finance / FP&A
  - Financial Analyst
  - Investment Banking / Equity Research (foundational skills)

---

## ✍️ Author

Sam Felix
LinkedIn: [Sam Felix](https://www.linkedin.com/in/sam-felix-644b492b2/)
Email: 2samfelix@gmail.com

---

## 📢 Disclaimer

This project is for educational and personal portfolio purposes only. All historical financial data is sourced from Arm Holdings plc's official public filings (SEC EDGAR) and press releases. The author makes no claim of affiliation with Arm Holdings plc. Growth, margin, and DCF assumptions beyond reported historicals are the author's own estimates, clearly disclosed as such throughout the model — this is not investment advice.
