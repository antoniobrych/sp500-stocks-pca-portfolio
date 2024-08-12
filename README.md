# Principal Component Analysis (PCA) for SP500 Portfolio Construction

## Project Overview

This project explores the construction of a U.S. stock portfolio using Singular Value Decomposition (SVD) of the daily return matrix of the SP500 components, followed by Principal Component Analysis (PCA). The portfolio's performance was compared against the benchmark, represented by the Invesco SP 500 Equal Weight ETF (SP500 EW).

## Objectives

- Perform Singular Value Decomposition (SVD) on the daily return matrix of SP500 components.
- Apply Principal Component Analysis (PCA) to determine the weights for each asset in the portfolio.
- Construct a portfolio using the weights derived from the first principal component (PC-1).
- Compare the portfolio's performance with the SP500 Equal Weight benchmark (SP500 EW).

## Methodology

1. **Data Collection**: 
   - Daily returns of all SP500 components were obtained and organized into a return matrix.

2. **Singular Value Decomposition (SVD)**:
   - The return matrix was decomposed using SVD to understand the underlying structure of the data.

3. **Principal Component Analysis (PCA)**:
   - PCA was applied to extract the principal components. The first principal component (PC-1) was used to determine the portfolio weights.

4. **Portfolio Construction**:
   - A portfolio was constructed using the weights derived from PC-1.

5. **Performance Evaluation**:
   - The portfolio's performance was evaluated against the SP500 EW benchmark through historical simulations across various time windows.

## Results

The strategy generated a portfolio that outperformed the benchmark in historical simulations over multiple time periods. The literature provides reasons supporting such results, including the reduction of dimensionality and emphasis on the most significant sources of variance in the returns.

## Conclusion

This project demonstrates the potential of PCA in creating a well-performing investment strategy. By focusing on the first principal component, the strategy effectively captured the dominant trends in the SP500 returns, leading to superior performance compared to the equal-weighted benchmark.

## Future Work

- **Risk Management**: Implement risk management techniques to enhance portfolio robustness, test with other assets such as bonds and commodities.
- **Optimization**: Explore other dimensionality reduction techniques and optimization methods.
- **Real-time Application**: Apply the strategy in a real-time trading environment to assess its practical viability.


- Relevant literature and resources that support the methodology and findings of this project.

