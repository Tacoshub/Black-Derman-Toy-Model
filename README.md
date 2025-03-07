# **Interest Rate Modeling: Lognormal Spot Rate Models**

## **Overview**

This repository presents a comprehensive study on **lognormal spot rate models**, with a particular focus on the **Black-Derman-Toy (BDT) model** and its extensions. The report explores key theoretical concepts, numerical methodologies, and empirical findings relevant to interest rate modeling. 

The main objectives of this work are:
- To examine the **properties and limitations** of lognormal spot rate models.
- To provide a **detailed calibration framework** for the Black-Derman-Toy model.
- To analyze the **Zero Black-Derman-Toy (ZBDT) model** in the context of zero-interest-rate policies (ZIRP).
- To address the **pricing challenges** of Eurodollar futures under lognormal models.
- To present a **correction approach** based on the Sandmann-Sondermann methodology.

The repository includes both theoretical derivations and numerical implementations in **Python**.

## **Contents**

### **Lognormal Spot Rate Models**
- Importance of spot rate models in bond pricing.
- Properties and limitations of lognormal short-rate models.
- Discussion of models including CIR, Hull-White, Dothan, and BDT.

### **The Black-Derman-Toy Model**
- Mathematical formulation of the BDT model.
- Link between continuous and discrete versions.
- Calibration methodology using a binomial tree approach.
- Numerical results and implementation details.

### **The Zero Black-Derman-Toy Model**
- Extension of the BDT model to accommodate zero interest rate policies (ZIRP).
- Structural modifications and probabilistic framework.
- Calibration procedure and empirical validation.
- Application to bond and option pricing.

### **Pricing of Eurodollar Futures**
- Theoretical instability in pricing under lognormal short-rate models.
- Analytical proof of explosive behavior in accumulation factors.
- Implications for arbitrage-free pricing of Eurodollar futures.
- The correction by Sandmann and Sondermann through effective rate modeling.

## **Implementation**

This repository includes **Python implementations** of the models discussed in the report. The numerical framework supports:
- **Calibration of the Black-Derman-Toy model** using market data.
- **Pricing of zero-coupon bonds and interest rate derivatives**.
- **Simulation of short-rate dynamics** under different modeling assumptions.
- **Application of the Sandmann-Sondermann correction** for stable Eurodollar futures pricing.

All implementations are structured for easy adaptation to new datasets and model parameters.

## **Results and Key Findings**

- The **Black-Derman-Toy binomial short-rate tree** was successfully calibrated using historical yield and volatility data.
- The **Zero Black-Derman-Toy model** effectively captures prolonged periods of low interest rates, making it well-suited for environments characterized by central bank interventions.
- The study confirms that **lognormal short-rate models can lead to unstable pricing of Eurodollar futures**, emphasizing the need for alternative modeling approaches.
- The **Sandmann-Sondermann correction** was validated as a viable solution, ensuring finite accumulation factors and stable derivative pricing.

## **Authors**
- Flavio Salvatore Boccia  
- Ludovico Costa  
- Alessandro Pigato  
- Lorenzo Tolomelli

## **References**

Below is a list of key references used in this project, covering foundational and advanced topics in interest rate modeling.

1. **Black, F., Derman, E., & Toy, W. (1990).**  
   *A One-Factor Model of Interest Rates and Its Application to Treasury Bond Options.*  
   The Journal of Fixed Income, 1(1), 2-8.  

2. **Black, F., & Karasinski, P. (1991).**  
   *Bond and Option Pricing when Short Rates are Lognormal.*  
   Financial Analysts Journal, 47(4), 52-59.  

3. **Sandmann, K., & Sondermann, D. (1993).**  
   *Log-Normal Interest Rate Models: Stability and Methodology.*  
   Mathematical Finance, 3(1), 1-15.  

4. **Hogan, S., & Weintraub, D. (1993).**  
   *Singularity and Explosive Behaviour in the Black-Derman-Toy Model.*  
   Journal of Financial Economics, 36(2), 123-140.  

5. **Krzyżanowski, G., Mordecki, E., & Sosa, A. (2020).**  
   *Zero Black-Derman-Toy Interest Rate Model.*  
   Risk Management, 22(4), 89-106.  

6. **Hull, J. C. (2017).**  
   *Options, Futures, and Other Derivatives (10th ed.).*  
   Pearson. ISBN: 978-0134472089.
