# Fixed Income Pricing Notebooks

This repository contains a collection of Jupyter notebooks that cover various topics in financial engineering. The notebooks provide interactive examples and implementations of different financial models and pricing techniques.

## Notebooks

### 1. Defaultable Bonds and CDS

This notebook provides an interactive approach to pricing Defaultable Bonds and Credit Default Swaps (CDS) using the Hazard rate model.

- **File:** [Defaultable bonds and CDS.ipynb](Term%20structure%20and%20Credit%20Derivatives/Defaultable%20bonds%20and%20CDS.ipynb)
- **Topics Covered:**
  - Hazard Rate Model
  - Survival Probability
  - Pricing Defaultable Bonds
  - Pricing Credit Default Swaps (CDS)
  - Optimization of Hazard Rates and CDS Spreads

### 2. Fixed Income Pricing Lattice

This notebook demonstrates the use of binomial trees for pricing various fixed income instruments, including Zero-Coupon Bonds (ZCB), futures, forwards, swaps, and swaptions.

- **File:** [Fixed_income_pricing_lattice.ipynb](Term%20structure%20and%20Credit%20Derivatives/Fixed_income_pricing_lattice.ipynb)
- **Topics Covered:**
  - Building Binomial Trees
  - Term Structure of Interest Rates
  - Pricing ZCB Options
  - Pricing Futures and Forwards
  - Pricing Swaps and Swaptions

### 3. BDT Model

This notebook implements the Black-Derman-Toy (BDT) model for term structure modeling using a binomial lattice approach. It includes functions for building the BDT term structure, calculating bond prices, and optimizing interest rates.

- **File:** [BDT model.ipynb](Term%20structure%20and%20Credit%20Derivatives/BDT%20model.ipynb)
- **Topics Covered:**
  - Building BDT Term Structure
  - Elementary Prices Lattice
  - Bond Pricing using BDT Model
  - Optimization of Interest Rates

## Getting Started

To run these notebooks, you will need to have Jupyter Notebook installed along with the necessary Python libraries. You can install the required libraries using the following command:

```sh
pip install numpy pandas scipy matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/keshav0801/financial-engineering-notebooks.git
   ```
2. Navigate to the repository directory:
   ```sh
   cd Fixed-income-pricing
   ```
3. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. Open the desired notebook from the Jupyter interface and run the cells to see the examples and results.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
