# Factor Analysis of Information RIsk
A sample Python script for cybersecurity risk modeling using the PYFAIR library and Loss Distribution Approach. This script demonstrated multiple methods for quantifying risk as ranges.

PYFAIR Integration: Uses the PYFAIR library for Factor Analysis of Information Risk modeling with fallback to custom implementation
1. Loss Distribution Analysis: Fits multiple probability distributions (lognormal, gamma, exponential, Weibull) to loss data
2. Bow-tie Analysis: Models threat frequency, vulnerability, and control effectiveness
3. Monte Carlo Simulation: 10,000 iterations for robust statistical analysis

**Risk Quantification Methods:**

**FAIR Model:**
1. Loss Event Frequency (LEF) using PERT distributions
2. Primary/Secondary Loss Magnitude (PLM/SLM)
3. Annual Loss Expectancy (ALE) calculations


**_Loss Distribution Approach:_**
1. Multiple distribution fitting with AIC/BIC selection
2. Value at Risk (VaR) at 95% and 99% confidence levels
3. Conditional Value at Risk (CVaR) for tail risk assessment

_**Bow-tie Analysis:**_

1. Threat frequency modeling
2. Vulnerability probability assessment
3. Control effectiveness evaluation


_Output Ranges Include:_
1. Percentile Analysis: 5th, 10th, 25th, 75th, 90th, 95th, 99th percentiles
2. Risk Metrics: Mean, median, standard deviation, VaR, CVaR
3. Visual Analytics: Histograms, fitted distributions, comparative charts
4. Comprehensive Reports: Statistical summaries for decision-making

**_FAIR Model:_**
1. Loss Event Frequency (LEF) using PERT distributions
2. Primary/Secondary Loss Magnitude (PLM/SLM)
3. Annual Loss Expectancy (ALE) calculations

**_Alternative Approaches Incorporated:_**
1. PERT Distribution: More realistic than simple triangular distributions
2. Multiple Distribution Fitting: Finds best-fit distribution for your data
3. Control Effectiveness Modeling: Incorporates security control impact
4. Tail Risk Analysis: CVaR for extreme loss scenarios

The script provides two example scenarios (data breach and ransomware) and generates detailed reports with visualizations. You can easily adapt the parameters for your specific threat landscape and risk tolerance.

   
