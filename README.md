# Quantitative Portfolio Analysis & Optimization

## Overview
A comprehensive portfolio optimization project applying Modern Portfolio Theory (MPT) to construct two distinct investment strategies: a direct equity portfolio and a mutual fund portfolio. The project demonstrates quantitative finance principles, statistical analysis, and risk-return optimization techniques to maximize Sharpe ratios through data-driven asset allocation.

## 🎯 Objective
To construct optimal portfolios that maximize risk-adjusted returns using mathematical optimization, moving beyond naive equal-weighting strategies to achieve superior performance through statistical analysis of historical data.

## 📊 Project Structure

### Dual Portfolio Strategy
- **Equity Portfolio**: 4 individual stocks across diverse sectors
- **Mutual Fund Portfolio**: 4 professionally managed funds with varied strategies

### Methodology Framework
1. **Fundamental Analysis**: Comprehensive evaluation of each investment vehicle
2. **Statistical Modeling**: Historical return analysis and covariance calculation
3. **Optimization**: Sharpe ratio maximization using Excel Solver
4. **Validation**: Backtesting with recent market data

## 🏢 Investment Universe

### Equity Portfolio
| Company | Sector | Market Cap | Key Rationale |
|---------|--------|------------|---------------|
| **HDFC Bank** | Banking | ₹15.2L Cr | Market leadership, superior asset quality |
| **Divi's Laboratories** | Pharmaceuticals | ₹1.8L Cr | Global API dominance, regulatory compliance |
| **Bharat Dynamics** | Defense | ₹72K Cr | Defense indigenization beneficiary |
| **Jubilant FoodWorks** | QSR/Food Services | ₹47K Cr | Dominant pizza market position |

### Mutual Fund Portfolio
| Fund | Category | Strategy | AUM Focus |
|------|----------|----------|-----------|
| **Parag Parikh Flexi Cap** | Multi-cap | Value + International exposure | Core holding |
| **DSP Healthcare** | Sectoral | Healthcare/Pharma focused | Thematic play |
| **Mirae Asset NYSE FANG+ ETF** | International | US Tech giants | Growth/Tactical |
| **Tata Banking & Financial Services** | Sectoral | BFSI proxy | Economic growth play |

## 🔬 Technical Methodology

### Statistical Analysis
- **Covariance Matrix Calculation**: Quantified inter-asset correlations
- **Risk-Return Profiling**: Analyzed historical volatility and returns
- **Sharpe Ratio Optimization**: Maximized (Return - Risk-free rate) / Volatility

### Optimization Process
```
1. Data Collection → Daily price data (252+ trading days)
2. Return Calculation → Daily returns matrix
3. Covariance Analysis → Risk relationship mapping
4. Constraint Setting → Weights sum to 1, no short selling
5. Solver Optimization → Maximum Sharpe ratio objective
6. Weight Allocation → Optimal portfolio composition
```

## 📈 Key Results

### Equity Portfolio Performance
- **Equal Weight Baseline**: Sharpe Ratio 2.09, Return 49.49%, Volatility 20.76%
- **Optimized Portfolio**: Sharpe Ratio 2.28, Return 54.01%, Volatility 21.04%
- **Improvement**: 9.1% enhancement in risk-adjusted returns

#### Optimal Allocation
- Divi's Laboratories: 36.90%
- Jubilant FoodWorks: 28.73%
- HDFC Bank: 21.59%
- Bharat Dynamics: 12.77%

### Mutual Fund Portfolio Performance
- **Equal Weight Baseline**: Sharpe Ratio 1.23, Return 23.26%, Volatility 14.01%
- **Optimized Portfolio**: Sharpe Ratio 1.28, Return 25.83%, Volatility 15.48%
- **Improvement**: 4.1% enhancement in risk-adjusted returns

#### Optimal Allocation
- Parag Parikh Flexi Cap: 41.68%
- Mirae Asset NYSE FANG+: 37.65%
- DSP Healthcare: 15.64%
- Tata Banking & Financial: 5.03%

## 🔍 Key Insights

### Portfolio Construction Learnings
- **Diversification Benefits**: Mathematical optimization revealed non-intuitive weight allocations
- **Risk-Return Tradeoffs**: Higher-returning assets didn't always receive highest weights due to correlation effects
- **Sector Concentration**: Defensive sectors (banking) balanced growth sectors (pharma, defense)

### Validation Results
- Backtesting confirmed theoretical optimization improvements
- Short-term performance exceeded long-term projections (characteristic of favorable market conditions)
- Model assumptions (i.i.d. returns) held reasonably well in testing period

## ⚠️ Limitations & Assumptions

### Model Limitations
- **Historical Bias**: Past performance doesn't guarantee future results
- **Market Regime Changes**: Fixed covariance assumes stable market relationships
- **Transaction Costs**: Real-world implementation costs not considered
- **Liquidity Constraints**: Assumes perfect divisibility and liquidity

### Methodological Assumptions
- Daily returns are independently and identically distributed
- Risk-free rate remains constant
- No leverage or short selling constraints
- Static optimization (no rebalancing strategy)

## 🛠️ Tools & Technologies
- **Excel**: Primary analysis platform with Solver optimization
- **Statistical Functions**: Covariance, correlation, and performance calculations
- **Financial Modeling**: DCF valuation, ratio analysis, peer comparisons
- **Data Sources**: Historical market data, financial statements

## 📁 File Structure
```
📁 Portfolio-Optimization-Project/
├── 📄 README.md
├── 📊 Portfolio-analysis.xlsx
│   ├── 📋 Landing Page
│   ├── 📈 Stock Equal Weights
│   ├── 📈 Stocks Optimized Weights  
│   ├── 📈 Stock Backtesting
│   ├── 📈 MF Equal/Optimized/Backtesting
│   └── 📋 Individual Company Analysis Sheets
└── 📄 Report-on-portfolio-analysis.pdf
```


## 🔗 Applications
This methodology framework can be extended to:
- **Asset Management**: Professional portfolio construction
- **Risk Management**: Quantitative risk assessment
- **Financial Planning**: Individual investment optimization
- **Research**: Academic finance and behavioral studies

## 📝 Future Enhancements
- Dynamic rebalancing strategies
- Multi-period optimization models
- Alternative risk measures (VaR, CVaR)
- Machine learning integration for return prediction
- ESG factor incorporation

## Sources of Data
- https://www.screener.in/
- https://www.bloomberg.com/

---

**Note**: This project demonstrates academic application of quantitative finance principles. All investment analysis is for educational purposes and should not be considered as investment advice.
