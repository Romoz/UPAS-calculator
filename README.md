# UPAS-calculator
# TAI-ÉCOSAFE UPAS v1.0
## Universal Plant Assessment System

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16901687.svg)](https://doi.org/10.5281/zenodo.16901687)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub release](https://img.shields.io/github/release/romanmozgovyi/TAI-ECOSAFE-UPAS.svg)](https://github.com/romanmozgovyi/TAI-ECOSAFE-UPAS/releases)

**Author:** Roman MOZGOVYI  
**Version:** 1.1  
**Date:** August 2025  
**License:** CC BY-NC-4.0

### 🎯 Overview

UPAS v1.1 is a comprehensive plant assessment methodology designed for scientifically-based classification of flora in urbanized ecosystems. The system integrates:

- **Risk Analysis (TAI)** - Toxicity, Animal danger, Invasiveness
- **Ecological Value (EVI)** - CO₂ absorption, Ecosystem services, Social value  
- **Economic Assessment (E_Score)** - ROI-based economic efficiency

### 🚀 Features

- ✅ Nine-level color classification system
- ✅ Luxembourg-specific modifiers
- ✅ Interactive web calculator
- ✅ 40+ validated plant species examples
- ✅ Economic impact assessment
- ✅ Scientific peer-review ready

### 📊 Quick Start

#### Web Calculator
Open `calculator/UPAS_v1.1.html` in your browser for interactive plant assessment.

#### Python Implementation
```python
from scripts.python.upas_calculator import UPASCalculator

calculator = UPASCalculator()
result = calculator.calculate(
    toxicity=0.0, 
    animal_danger=0.0, 
    invasiveness=0.5,
    co2_absorption=4.2, 
    ecosystem_services=4.5, 
    social_value=3.0
)
print(f"Category: {result.category}")  # GREEN
