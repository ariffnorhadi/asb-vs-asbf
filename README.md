# ASB Investment Calculator

A comprehensive web-based calculator to compare **Direct ASB Savings** vs **ASBF (ASB Financing) Strategy** for long-term investment planning.

## 🎯 Overview

This tool helps Malaysian investors analyze and compare two different approaches to ASB (Amanah Saham Bumiputera) investment strategies, providing detailed financial projections and ROI calculations over a 40-year period.

## ✨ Features

### 📊 Investment Analysis
- **Direct ASB Savings**: Traditional monthly investment approach
- **ASBF Strategy**: Leveraged investment using ASB financing
- **Side-by-side Comparison**: Real-time comparison of both strategies
- **ROI Calculations**: Detailed return on investment analysis

### 🎨 User Interface
- **Modern Design**: Clean, responsive interface built with Tailwind CSS
- **Real-time Updates**: Instant calculations as you modify parameters
- **Interactive Tables**: Detailed year-by-year breakdown
- **Visual Indicators**: Color-coded results and status updates

### 📈 Key Metrics
- Total investment amount
- Final portfolio value
- Net profit/loss
- Return on Investment (ROI)
- Strategy advantage percentage

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required - runs entirely in the browser

### Usage
1. Open `asb_vs_asbf.html` in your web browser
2. Adjust the investment parameters:
   - **Monthly Payment**: Your monthly investment amount
   - **ASB Return Rate**: Expected annual ASB dividend rate
   - **ASBF Interest Rate**: Loan interest rate for ASBF
   - **Loan Amount**: Initial ASBF loan amount
3. View real-time calculations and comparisons
4. Analyze detailed year-by-year projections

## 📋 Investment Parameters

| Parameter | Description | Default Value | Range |
|-----------|-------------|---------------|-------|
| Monthly Payment | Monthly investment amount | RM 867 | RM 100+ |
| ASB Return Rate | Annual ASB dividend rate | 5% | 1-15% |
| ASBF Interest Rate | Loan interest rate | 4.25% | 1-10% |
| Loan Amount | Initial ASBF loan | RM 200,000 | RM 50,000+ |

## 🧮 Calculation Methods

### Direct ASB Savings
Uses the future value of annuity formula:
```
FV = PMT × [((1+r)^n - 1) / r]
```
Where:
- PMT = Monthly payment
- r = Monthly interest rate
- n = Total number of months (40 years)

### ASBF Strategy
Calculates:
- ASB balance growth with annual dividends
- Loan balance reduction through monthly payments
- Net equity (ASB balance - remaining loan)

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup structure
- **Tailwind CSS**: Utility-first CSS framework
- **Vanilla JavaScript**: Pure JavaScript for calculations
- **Responsive Design**: Mobile-first approach

### Key Features
- **No Dependencies**: Runs entirely in the browser
- **Real-time Calculations**: Instant updates on parameter changes
- **Responsive Layout**: Works on all device sizes
- **Clean Code**: Well-structured and commented JavaScript

## 📱 Browser Compatibility

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

## 🤝 Contributing

This is a personal research project, but suggestions and improvements are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Ariff Norhadi**
- Software Engineer
- Investment Research Enthusiast
- AI-Powered Development

## 🔬 Research Background

As a software engineer exploring investment diversification strategies, this calculator was built to analyze and compare ASB investment approaches. The tool combines technical expertise with AI assistance to create a comprehensive solution for visualizing the long-term impact of different investment strategies.

## ⚠️ Disclaimer

This calculator is for educational and research purposes only. It provides estimates based on historical data and assumptions. Always consult with qualified financial advisors before making investment decisions. Past performance does not guarantee future results.

## 📞 Contact

For questions or suggestions about this project, please open an issue in the repository.

---

**Built with ❤️ and AI assistance for the Malaysian investment community**
