# 💎 Investment Analysis Dashboard - PRO Edition

> **Complete your IR materials in 30 seconds**  
> Free, Open-Source, 100% Browser-Based Financial Modeling Tool

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/koing999/HUB?style=social)](https://github.com/koing999/HUB)
[![Support](https://img.shields.io/badge/Support-KakaoPay-yellow.svg)](https://qr.kakaopay.com/Ej8t3tRhG)

[🌐 Live Demo](https://hub-999-rvi8.vercel.app/en/) | [📖 Documentation](./USAGE_GUIDE.md) | [🇰🇷 한국어](../ko/) | [💰 Support](https://qr.kakaopay.com/Ej8t3tRhG)

---

## 🚀 What Is This?

A **professional-grade investment analysis dashboard** that runs entirely in your browser. No backend, no installation, no learning curve. Just open and analyze.

Perfect for:
- 🎯 **Startup Founders** - Quick IR materials for investor meetings
- 💼 **Corporate Finance Teams** - Investment feasibility analysis
- 🎓 **MBA Students** - Financial modeling practice
- 📈 **Consultants** - Client presentation materials

---

## ✨ Key Features

### 🔥 Core Analytics
- **Automatic NPV/IRR Calculation** - Newton-Raphson method with 0.01% precision
- **Monte Carlo Simulation** - 1,000 iterations with P10/P50/P90 distribution
- **2-Way Sensitivity Analysis** - Revenue × WACC cross-analysis with heatmap
- **Scenario Comparison** - Conservative/Base/Optimistic side-by-side
- **Break-Even & Payback Period** - Automatic calculation from cumulative FCF

### 🧮 Advanced Tools
- **WACC Calculator** - Built-in CAPM, Beta adjustment (Hamada formula)
- **Industry Presets** - IT, Manufacturing, Retail, Healthcare, Construction
- **Terminal Value Methods** - Liquidation/Perpetual Growth/Exit Multiple
- **Revenue Generation** - Auto-generate by CAGR or upload Excel data

### 📊 Visualization & Export
- **Real-time Charts** - Interactive cash flow visualization (Chart.js)
- **Excel Export** - Complete FCF table + summary sheet
- **PDF Export** - One-click print with all charts and tables
- **Project Management** - Save/load multiple scenarios locally

---

## 🎯 Quick Start

### Option 1: Direct Use (Recommended)
1. **Visit Live Demo**: [https://hub-999-rvi8.vercel.app/en/](https://hub-999-rvi8.vercel.app/en/)
2. **Enter Data**: Initial investment, revenue projections
3. **Click Analyze**: Get NPV, IRR, and all metrics instantly
4. **Export**: Download as Excel or PDF

### Option 2: Local Use
1. **Download**: Clone or download this repository
   ```bash
   git clone https://github.com/koing999/HUB.git
   cd HUB/en
   ```
2. **Open**: Double-click `index.html` (no server required)
3. **Analyze**: Works offline, all calculations run locally

### Option 3: Deploy Your Own
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/koing999/HUB)

---

## 📖 How to Use

### 1. Basic Setup
- Enter **Initial Investment** ($M)
- Set **Analysis Period** (1-20 years)
- Input **Tax Rate** and **NWC Ratio**

### 2. Revenue Input
**Method A: Auto-Generate**
- Set Initial Revenue and CAGR %
- Click "Auto Generate"

**Method B: Upload Excel**
- Download template (click "Template" button)
- Fill in annual revenue data
- Upload completed file

### 3. WACC Configuration
**Quick Setup:**
- Select industry preset (IT/Manufacturing/Retail/etc.)

**Manual Calculation:**
- Enter Debt/Equity weights
- Calculate Cost of Equity via CAPM
- Auto-calculate WACC

### 4. Run Analysis
- Click **"Run Analysis"** button
- View NPV, IRR, Payback, Break-Even
- Explore interactive charts and tables

### 5. Advanced Features
- **Monte Carlo**: Click "Run Simulation" for risk analysis
- **Sensitivity**: Automatic 1-Way and 2-Way tables
- **Scenarios**: Compare Conservative/Base/Optimistic
- **Export**: Download Excel or print to PDF

---

## 🛠️ Technical Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Pure frontend, no backend required |
| **CSS3** (Tailwind) | Beautiful, responsive UI |
| **JavaScript** (ES6+) | Core calculation engine |
| **Chart.js** | Interactive data visualization |
| **SheetJS (XLSX)** | Excel import/export |
| **LocalStorage** | Project save/load |

**Dependencies**: All loaded via CDN, no npm install required

---

## 📊 Calculation Methodology

### NPV (Net Present Value)
```
NPV = Σ(FCFt / (1 + WACC)^t) - Initial Investment
```

### IRR (Internal Rate of Return)
- **Method**: Newton-Raphson iteration
- **Tolerance**: 0.0001 (0.01%)
- **Max Iterations**: 200
- **Range**: -99% to 500%

### FCF (Free Cash Flow)
```
FCF = NOPAT + Depreciation - ΔNWC - CapEx
```

### Terminal Value
```
TV = FCF × (1 + g) / (WACC - g)    [Perpetual Growth]
TV = EBITDA × Exit Multiple         [Exit Multiple]
TV = Liquidation Value              [Liquidation]
```

### Monte Carlo Simulation
- **Iterations**: 1,000
- **Variables**: Revenue (±20%), WACC (±10%)
- **Distribution**: Normal approximation
- **Output**: P10/P50/P90 percentiles

---

## 🎨 Screenshots

### Main Dashboard
![Dashboard](./screenshots/dashboard.png)

### Monte Carlo Simulation
![Monte Carlo](./screenshots/monte-carlo.png)

### 2-Way Sensitivity Analysis
![Sensitivity](./screenshots/sensitivity.png)

---

## 📋 Excel Template Format

### Revenue Data Sheet
| Year | Revenue ($M) |
|------|--------------|
| 1    | 100          |
| 2    | 120          |
| 3    | 145          |
| ...  | ...          |

**Tips:**
- Column A: Year (sequential)
- Column B: Revenue in millions
- Max 20 years supported
- Empty rows ignored

---

## 🆚 Comparison with Alternatives

| Feature | Our Dashboard | Excel | Crystal Ball | @RISK |
|---------|---------------|-------|--------------|-------|
| **Price** | FREE | ~$150/yr | $1,500/yr | $2,500/yr |
| **Installation** | None ✅ | Required | Required | Required |
| **Monte Carlo** | 1000 iter ✅ | Manual ⚠️ | Yes ✅ | Yes ✅ |
| **2-Way Sens.** | Auto ✅ | Manual ⚠️ | Yes ✅ | Yes ✅ |
| **Real-time** | Yes ✅ | No ❌ | No ❌ | No ❌ |
| **Learning** | 5 min ✅ | 2-3 hrs ⚠️ | 1-2 days ❌ | 1-2 days ❌ |
| **Open Source** | MIT ✅ | No ❌ | No ❌ | No ❌ |

---

## 🤝 Contributing

We welcome contributions! Here's how:

1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit** your changes
   ```bash
   git commit -m "Add amazing feature"
   ```
4. **Push** to the branch
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open** a Pull Request

### Areas for Contribution
- 🐛 Bug fixes
- ✨ New features (API integration, cloud save, etc.)
- 🌍 Translations (Spanish, French, German, etc.)
- 📚 Documentation improvements
- 🎨 UI/UX enhancements

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](../LICENSE) file for details.

**What this means:**
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use

**Just keep the copyright notice!**

---

## 🙏 Acknowledgments

- **Chart.js** - Beautiful charts
- **SheetJS** - Excel integration
- **Tailwind CSS** - UI framework
- **Font Awesome** - Icons

---

## 📧 Contact

**JoREDIN (조르딘)**
- 🐙 GitHub: [@koing999](https://github.com/koing999)
- 📧 Email: koing756@naver.com
- 💰 Support: [KakaoPay](https://qr.kakaopay.com/Ej8t3tRhG)

---

## 🌟 Star History

If you find this useful, please **⭐ star this repository** to support the project!

[![Star History Chart](https://api.star-history.com/svg?repos=koing999/HUB&type=Date)](https://star-history.com/#koing999/HUB&Date)

---

## 🔖 Version

**Current Version**: 1.0.0  
**Last Updated**: November 2024

---

## 📌 Roadmap

### v1.1 (Coming Soon)
- [ ] Cloud save/sync (Firebase)
- [ ] Multi-currency support
- [ ] Custom templates
- [ ] Collaboration features

### v1.2 (Future)
- [ ] API integration
- [ ] Real-time data feeds
- [ ] AI-powered forecasting
- [ ] Mobile app version

---

<div align="center">

**Made with ❤️ by JoREDIN**

[🚀 Try Now](https://hub-999-rvi8.vercel.app/en/) • [⭐ Star](https://github.com/koing999/HUB) • [🐛 Report Bug](https://github.com/koing999/HUB/issues) • [💡 Request Feature](https://github.com/koing999/HUB/issues)

</div>