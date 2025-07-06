#  Differential Equations – Assignment 3  
### 🧪 Predicting the Age of the Earth using Uranium Dating

**Submitted by:**  
- Mansoob-e-Zahra  
- Aimen Eman

---

##  Objective

The aim of this project is to estimate the **age of the Earth** using **Uranium Dating**.  
This scientific method relies on the **radioactive decay of uranium isotopes** (U-238 and U-235) into their **stable lead products** (Pb-206 and Pb-207).  
By calculating the ratios of these isotopes, we can estimate how much time has passed since the rocks (and Earth) first formed.

---

##  Scientific Principles

### Radioactive Decay

Radioactive elements decay over time into stable isotopes following an **exponential law**:

N(t) = N₀ * e^(-λt)


Where:
- `N(t)` = Remaining quantity at time `t`  
- `N₀` = Initial quantity  
- `λ` = Decay constant  
- `t` = Time elapsed

---

###  Half-life

The half-life is the time required for **half of the radioactive substance** to decay. It is related to the decay constant by:
λ = ln(2) / half-life

---

##  Code Explanation

###  Importing Libraries
- `numpy`: For numerical calculations  
- `matplotlib.pyplot`: For plotting graphs

###  Defining Constants
Half-lives of uranium isotopes:
- U-238: **4.468 billion years**
- U-235: **0.704 billion years**

Decay constants are calculated from these half-lives.

###  Simulating Radioactive Decay
- Time simulated from 0 to 5 billion years
- Decay modeled using the exponential decay formula

### 📈 Plotting Decay Curves
- Graphs plotted to show decay of U-238 and U-235  
- Helps visualize remaining parent isotope over time

---

##  Age Estimation Using Pb/U Ratios

Example isotope ratios:
- Pb-206 / U-238 = **0.85**
- Pb-207 / U-235 = **1.65**

Using the rearranged decay formula:

- Estimated Age (U-238): **~4.31 billion years**  
- Estimated Age (U-235): **~4.55 billion years**

---

##  Basic Error Analysis

Assuming ±5% uncertainty in the isotope ratios:

- U-238 Age Range: **4.13 – 4.48 billion years**  
- U-235 Age Range: **4.38 – 4.73 billion years**

---

##  Results

The decay simulations and ratio-based calculations support the conclusion that the Earth's age is between **4.3 and 4.6 billion years**, consistent with scientific consensus.

---

##  Conclusion

Using uranium dating:
- The Earth's age is estimated to be between **4.3 and 4.6 billion years**
- Dual use of **U-238 and U-235 decay chains** increases result reliability
- Simple error analysis improves confidence in the result range

---

##  Future Scope

- Incorporate other radiometric dating methods (e.g., **Thorium-Lead**, **Potassium-Argon**)  
- Analyze **real geological data** from meteorites or Earth's oldest rocks for improved precision  

