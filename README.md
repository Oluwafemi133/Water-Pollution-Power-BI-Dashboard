# Clean Water Impact: Linking Pollution, Treatment & Disease Burden (2000-2024)

Analysing contaminant & bacteria levels across water sources to guide intervention strategies.

**Tools:** Power BI, DAX, Data Modeling, Data Cleaning
**Dataset:** 3,000 water samples | 2000-2024 | Multiple countries

## Key Findings

**1. 95.1% of water tested is unsafe**
- Unsafe water had 2x the contaminant level of safe water (5.09 ppm vs 2.36 ppm)

**2. Treatment alone is not fixing it**
- Chlorination: 95.3% unsafe, 323 disease burden
- Boiling: 95.2% unsafe, 318 disease burden
- Filtration: 94.9% unsafe, 327 disease burden
- None: ~95% unsafe, 325 disease burden
- Insight: The problem is source contamination, not household treatment.

**3. Source type does not matter much**
- Well: 5.04 ppm, Spring: 4.99 ppm, River: 4.95 ppm, Lake: 4.94 ppm, Tap: 4.94 ppm, Pond: 4.85 ppm
- Difference is only 0.19 ppm - all sources are similarly polluted.

**4. Contaminant does not fully explain disease**
- Brazil had low contaminant (4.68 ppm) but highest disease burden (337.26)
- Suggests bacteria and access to clean water play a bigger role.

## Dashboard

### Page 1 - Overview
![Page 1](Page1.png)

### Page 2 - Treatment & Trends
![Page 2](Page2.png)

## Files
- `Clean_Water_Dashboard.pdf` - Full dashboard export
- `clean_water.csv` - Cleaned dataset

## What I Would Do Next
1. Validate the definition of "Unsafe" against WHO limits
2. Investigate why treatment shows no effect - was Unsafe measured before or after treatment?
3. Add bacteria count as a separate predictor for disease burden
