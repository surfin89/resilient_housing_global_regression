# Appendix: Specification Curve Analysis (SCA) Robustness Report

This report summarizes the stability of key theoretical constructs across all calculated specifications, differentiated by Dependent Variable (DV).

## Analysis for Dependent Variable: VULN_DEFAULT_ROBUSTNESS
| Theoretical Construct | Variable | Models (N) | Median β | Sign Consistency | Sig. Rate (p<0.05) |
| :--- | :--- | :---: | :---: | :---: | :---: |
| Structural Barrier | Poverty Gap ($4.20/day) | **42** | -0.0071 | 100.0% | 64.3% |
| Learning Effect | Earthquake Count (Log) | **18** | 0.0542 | 100.0% | 50.0% |
| Institutional Spec. | Building Quality Index | **9** | 0.0102 | 100.0% | 22.2% |
| Governance Paradox | Gov. Effectiveness × Storm | **2** | -0.0732 | 100.0% | 100.0% |
| Leapfrogging (Storm) | Poverty × Storm | **2** | 0.0025 | 100.0% | 0.0% |
| Leapfrogging (Flood) | Poverty × Flood | **2** | -0.0006 | 50.0% | 100.0% |

## Analysis for Dependent Variable: VULN_DEFAULT_ROBUST_ONLY
| Theoretical Construct | Variable | Models (N) | Median β | Sign Consistency | Sig. Rate (p<0.05) |
| :--- | :--- | :---: | :---: | :---: | :---: |
| Structural Barrier | Poverty Gap ($4.20/day) | **42** | -0.0032 | 100.0% | 16.7% |
| Learning Effect | Earthquake Count (Log) | **18** | 0.0425 | 100.0% | 50.0% |
| Institutional Spec. | Building Quality Index | **9** | 0.0093 | 100.0% | 33.3% |
| Governance Paradox | Gov. Effectiveness × Storm | **2** | -0.0683 | 100.0% | 100.0% |
| Leapfrogging (Storm) | Poverty × Storm | **2** | 0.0021 | 100.0% | 50.0% |
| Leapfrogging (Flood) | Poverty × Flood | **2** | 0.0017 | 100.0% | 50.0% |

## Key Findings Across Specifications
1. **Sign Stability:** High 'Sign Consistency' (near 100%) indicates that the direction of the effect is independent of control variable choice.
2. **Significance Rate:** Variables with lower significance rates but high sign consistency suggest the effect exists but may be underpowered in certain sub-specifications.
3. **DV Sensitivity:** Comparison between DVs reveals whether the 'Leapfrogging' effect is stronger for specific performance metrics.
