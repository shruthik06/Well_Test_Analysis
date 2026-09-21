# Well_Test_Analysis
# Pressure Drawdown Testing with Python

## 📌 Project Overview

This project demonstrates the analysis of a **pressure drawdown test** using Python to identify the **Infinite-Acting Radial Flow (IARF)** regime and estimate the **natural absolute permeability** of a reservoir.

Pressure transient analysis is an important reservoir-engineering technique used to understand reservoir behavior from pressure and production data.

In this project, pressure-time data is processed using Python, followed by:

- Pressure-drop calculation
- Time and pressure-difference calculation
- Pressure-derivative analysis
- Log-log diagnostic plotting
- Identification of the Infinite-Acting Radial Flow (IARF) regime
- Semi-log pressure-time analysis
- Straight-line regression
- Reservoir permeability estimation

The estimated reservoir permeability from the analysis is approximately:

**7.31 mD**

---

## 🎯 Objectives

The main objectives of this project are:

1. Load and process pressure drawdown test data.
2. Calculate pressure drop from initial and flowing pressure.
3. Calculate time and pressure differences between consecutive measurements.
4. Generate a log-log diagnostic plot.
5. Identify the Infinite-Acting Radial Flow (IARF) region.
6. Perform conventional semi-log analysis.
7. Determine the slope of the semi-log straight-line region.
8. Estimate the natural absolute permeability of the reservoir using the pressure-transient equation.
9. Demonstrate how Python can be used to automate reservoir-engineering calculations and visualization.

---

# 🛢️ Problem Statement

A pressure drawdown test is performed by producing a reservoir at a specified flow rate and recording the corresponding bottom-hole flowing pressure as a function of time.

The pressure response is analyzed to identify the flow regime and estimate reservoir properties.

For this project, the pressure-time data is analyzed to identify the **Infinite-Acting Radial Flow (IARF)** regime.

Once the IARF region is identified, a conventional semi-log plot is used to obtain the straight-line slope required for permeability estimation.

---

# 📊 Input Data

The following reservoir and well parameters are used in the analysis:

| Parameter | Value | Unit |
|---|---:|---|
| Flow rate, `q` | 250 | stb/d |
| Production time, `tp` | 460 | hr |
| Initial pressure, `Pi` | 4412 | psia |
| Formation thickness, `h` | 69 | ft |
| Porosity, `φ` | 3.9 | % |
| Total compressibility, `ct` | 17 × 10⁻⁶ | psi⁻¹ |
| Formation volume factor, `B` | 1.136 | rb/stb |
| Viscosity, `μ` | 0.8 | cp |
| Wellbore radius, `rw` | 0.198 | ft |

---

# 📁 Dataset

The pressure-time data is provided in an Excel file:

```text
WTA.xlsx
