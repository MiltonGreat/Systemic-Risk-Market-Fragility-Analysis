# Systemic-Risk-Market-Fragility-Analysis
## Overview
This project moves beyond traditional market forecasting to quantify systemic financial fragility by analyzing how volatility transmits across interrelated markets and how macroeconomic conditions amplify this transmission. Instead of predicting price movements, we measure the accumulation of systemic tension before it manifests in market crises.

**"The real danger is not the storm you see coming, but the fragility that accumulates silently before it breaks."**

## Key Insights from Analysis
<img width="1027" height="761" alt="Indexes" src="https://github.com/user-attachments/assets/80078bd3-760c-4701-b9be-c9ba1151beb3" />

### Current System Assessment
- Fragility Index: 0.252 (Low Fragility regime)
- System Status: ✅ Stable
- Primary Risk Driver: Network connectivity
- Analysis Period: 2016-04-14 to 2017-11-10

### Key Findings
- 51.6% of periods showed Low Fragility
- 48.3% showed Medium Fragility
- 0.2% showed High Fragility (critical warning)
- Maximum observed fragility: 0.828 (severe stress level)

### Dominant Risk Components
- Network Effects: 37.5% (volatility transmission)
- Correlation Strength: 34.2% (cross-market linkages)
- Macro Stress: 18.1% (economic conditions)
- Volatility: 10.6% (individual asset risk)

## Key Algorithms
- GARCH(1,1): Rolling volatility estimation
- Dynamic Correlation: Rolling window analysis
- Network Graphs: Correlation-based connectivity
- Composite Scoring: Min-max normalization and weighting
- Regime Classification: Threshold-based segmentation

## Interpreting the Results
**Fragility Index Scale**
- 0.0 - 0.4: 🟢 Low Fragility - Normal market conditions
- 0.4 - 0.7: 🟡 Medium Fragility - Elevated monitoring required
- 0.7 - 1.0: 🔴 High Fragility - Defensive measures recommended

## Risk Management Applications
- Portfolio Hedging: Increase protection during high fragility
- Leverage Management: Reduce exposure when system fragility rises
- Diversification Assessment: Monitor correlation breakdowns
- Liquidity Planning: Prepare for potential stress events

## Methodology Framework
### Tier 1: Multi-Asset Volatility Modeling
- GARCH Models: Capture volatility clustering across equities, credit, and currencies
- Rolling Correlations: Dynamic analysis of cross-market linkages
- Macro Integration: Synthetic economic data for regime detection

### Tier 2: Network Analysis
- Volatility Transmission: Network modeling of spillover effects
- Connectivity Metrics: Density, centrality, and clustering coefficients
- Systemic Hotspots: Identification of critical transmission nodes

### Tier 3: Composite Fragility Index
A weighted combination of four systemic risk dimensions:

- Volatility	(35%) Average GARCH volatility across assets
- Correlation	(30%) Strength of cross-market linkages
- Network (25%) Density of volatility transmission
- Macro Stress (10%) VIX and economic indicators

### Tier 4: Early Warning System
- Regime Detection: Low/Medium/High fragility thresholds
- Predictive Validation: Statistical testing of warning signals
- Economic Value: Strategy simulation for risk management

## Key Algorithms
- GARCH(1,1): Rolling volatility estimation
- Dynamic Correlation: Rolling window analysis
- Network Graphs: Correlation-based connectivity
- Composite Scoring: Min-max normalization and weighting
- Regime Classification: Threshold-based segmentation

## Visualization Dashboard

The analysis generates a comprehensive 10-panel dashboard showing:

- Systemic Fragility Index over time with regime thresholds
- Component Contributions to overall fragility
- Cross-Market Correlation dynamics
- Volatility Network density and connectivity
- Asset-Class Volatility comparisons
- Macroeconomic Stress indicators
- Fragility Regime distribution
- Recent Correlation structure
- Component Weighting methodology
- Early Warning signal performance

## Practical Applications

For Portfolio Managers

- Dynamic Asset Allocation: Adjust weights based on systemic conditions
- Hedging Strategy: Time protection purchases using fragility signals
- Risk Budgeting: Allocate risk capital according to regime

For Risk Officers

- Early Warning System: Monitor fragility for institutional risk
- Stress Testing: Identify vulnerable market conditions
- Liquidity Management: Prepare for correlation breakdowns

For Researchers

- Systemic Risk Measurement: Academic study of market fragility
- Network Analysis: Volatility transmission mechanisms
- Regime Detection: Statistical identification of market states

## Theoretical Foundation

This work builds on several key financial theories:

- Minsky's Financial Instability Hypothesis: Stability breeds instability
- Network Theory: Interconnectedness as systemic risk amplifier
- Regime Switching Models: Markets exist in distinct behavioral states
- Complexity Economics: Emergent behavior in adaptive systems

## Technical Implementation
**Data Sources**

- Primary: [Huge Stock Market Dataset from Kaggle](https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs)
- Coverage: ETFs and individual stocks (2010-2017)
- Synthetic Data: Credit spreads and currency indices for multi-asset analysis
