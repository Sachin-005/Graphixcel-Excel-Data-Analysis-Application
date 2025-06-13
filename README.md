# 🚀 Graphixcel: Excel Data Analysis Application

**Graphixcel** is a Django-based web application designed to import, analyze, and visualize Excel data with ease. Whether you're crunching numbers or exploring trends, Graphixcel makes data analysis intuitive and interactive.

---

## ✨ Features

- **Excel file import**: Upload `.xlsx` or `.xls` files directly.
- **Automated data parsing**: Clean, organize, and store data in your Django database.
- **Dynamic analysis**: Compute common summaries (e.g., totals, means, frequencies).
- **Visual outputs**: Generate charts (bar, line, pie, scatter) for insightful reporting.
- **Export options**: Download analyzed data or charts for sharing.

---

## 🚧 Getting Started

### Requirements

- Python 3.10+
- Django 4.x
- `pandas`, `openpyxl`, `matplotlib` (or `plotly`), and other dependencies listed in `requirements.txt`

### Installation

```bash
git clone https://github.com/Sachin-005/Graphixcel-Excel-Data-Analysis-Application.git
cd Graphixcel-Excel-Data-Analysis-Application
python -m venv venv
source venv/bin/activate    # or `venv\Scripts\activate` on Windows
pip install -r requirements.txt
