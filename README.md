# Euro-Area Banking Case Study III (2005–2023)

This repository contains the third case study on euro-area banking, analyzing the relationship between **monetary policy rates**, **lending volumes**, and **bank performance indicators**.  
The dataset covers monthly observations from **January 2005 to December 2023**, using sources from the **ECB Statistical Data Warehouse** and the **BankFocus Database**.

## Project Overview

The analysis investigates how ECB monetary policy influences banking outcomes by studying:  

- **Net Interest Margin (NIM)** and its relation to monetary policy rates.  
- **Impaired Loan Ratio (ILR)** and its dependence on time and policy conditions.  
- **Lending Volumes** for households and corporations, analyzed with pooled and fixed-effect regression models.  
- **Heterogeneity** across euro-area countries and across different time periods.  

The study employs econometric models in **R Studio**, with panel data techniques, t-tests, F-tests, and regressions using robust (Newey–West HAC) standard errors.

## Key Metrics

- **Net Interest Margin (NIM)**: Indicator of bank profitability from intermediation.  
- **Impaired Loan Ratio (ILR)**: Share of impaired assets relative to total assets, reflecting asset quality.  
- **Main Refinancing Operations Rate (MRO)**: Core ECB policy rate, central to the study’s regressions.  
- **Lending Volumes**: Loans issued to households and corporations across the euro area.  

## Results

- **Lending Volumes**:  
  - For corporations, pooled regressions and model selection tests suggest a **Fixed Effect Model** as most appropriate.  
  - For households, fixed-effect regressions confirm structural differences, with t-tests rejecting the null hypothesis of no effect.  

- **Net Interest Margin (NIM)**:  
  - Strong relationship with MRO rates, confirmed by regressions with Newey–West standard errors.  
  - Over time, NIM tracks monetary policy cycles, showing higher sensitivity during periods of rate adjustments.  

- **Impaired Loan Ratio (ILR)**:  
  - Quadratic regression indicates a **time-dependent pattern**, with significant declines after the 2010s banking reforms.  
  - Robust estimation confirms that asset quality improves in periods of accommodative policy and deteriorates under tighter conditions.  

- **Monetary Policy Transmission**:  
  - Splitting the sample into sub-periods (2005–2008, 2009–2014, 2015–2019, 2020–2023) reveals heterogeneous effects.  
  - Post-2020 data highlight how COVID-19 support policies temporarily boosted credit despite low interest rates.  

## Conclusion

The study demonstrates that:  
- ECB monetary policy rates (especially MRO) significantly shape both bank profitability (NIM) and asset quality (ILR).  
- Lending volumes to households and firms react differently, with corporate credit more elastic than household credit.  
- Long-term trends show convergence across euro-area countries, but significant heterogeneity remains across time periods.  
- Econometric evidence (F-tests, t-tests, fixed-effect models) confirms the importance of considering both **cross-country** and **time dynamics** in analyzing euro-area banking.  

## License

This project is licensed under the terms of the MIT License.  
