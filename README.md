# 📊 AlgoTest Trade Analyzer (Streamlit App)

This Streamlit app analyzes **AlgoTest `.clktrd` trade files** and provides:

- Total P&L
- Overall return %
- Trading duration (months / years)
- Equity curve
- Option holding periods
- Cash / underlying holding periods (FIFO-based)
- Full trade ledger view

---

## 🚀 Features

- Upload AlgoTest `.clktrd` file
- Enter total capital deployed
- Automatically calculates:
  - Strategy start & end date
  - Total trading duration
  - Overall returns
- Correct holding-period calculation:
  - Options → contract-based
  - Cash / underlying → FIFO matching
- Clean, investor-style dashboard

---

## 🛠 Installation

```bash
pip install -r requirements.txt
