# Financial Audit & Risk Model: P2P Fintech Ecosystem

## 📌 Project Overview
This repository contains a comprehensive financial and operational audit model for a decentralized P2P asset-exchange platform. The core objective of the project was to ingest raw transaction telemetry, perform data refactoring, segregate cash movements from accrual performance metrics, and reconstruct consolidated financial statements (**Cash Flow Statement** and **Income Statement / P&L**).

## 🛠️ Key Analytical Tasks Performed
1. **Data Refactoring & Rebranding:** Transformed raw, fragmented operational logs into a standardized corporate ledger with international fintech terminology.
2. **Tokenomics Validation:** Automated the conversion and liquidation tracing of internal platform tokens based on dual-rate conversion frameworks (Primary user issuance at 200:1 vs Operational settlements at 100:1).
3. **Anomaly & Fraud Detection:** Identified and adjusted telemetry flaws, including zero-coefficient anomalies in platform service fees and system overlay discrepancies.
4. **Financial Statement Reconstruction:** 
   * Formulated a **Cash Flow Statement** using the cash method to analyze platform liquidity and net fiat inflows.
   * Constructed an **Income Statement (P&L)** to assess true operational profitability, factoring in direct costs (Cost of Revenue), infrastructure payroll, and shareholder equity distribution.
5. **UI/UX Optimization:** Redesigned the spreadsheet architecture using the *Oswald* typography, custom pastel color-coding for financial alerts, proper padding, and standardized accounting number formats.

## 📊 Core Data Insights
* **Net Cash Flow:** The platform demonstrates robust liquidity with a positive net fiat inflow of **+1,705,777.65 RUB**, driven by solid user deposits.
* **Net Profit / (Loss):** Despite positive cash flow, the accrual P&L reveals a net operational loss of **-366,052.35 RUB**. 
* **Strategic Conclusion:** The net loss is driven by aggressive operational spending, administrative payroll, and immediate dividend distributions directly from working capital, while a significant portion of platform margins remains illiquid within the token float balances.

## 🗂️ Repository Structure
* `Project_Scope` — Executive summary, audit guidelines, and business logic.
* `Token_Operations` — Consolidated digital asset ledger and conversion rates.
* `Fiat_Ledger` — Multi-gateway transaction log (Crypto vs Card Processing) with automated accounting categorization.
* `Financial_Statements` — Automated executive dashboard mapping dynamic CF and P&L statements via `SUMIF`/`IF` logic.

## 💻 Tech Stack
* Google Sheets / MS Excel (Advanced logical formulas: `IF`, `SUMIFS`, `OR`, `IFNA`, multi-conditional array filters).
* Financial Data Modeling & Corporate Finance Architecture.
