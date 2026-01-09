# Student Performance Analysis Report

## Executive Summary

Analysis of **395 student records** exploring factors influencing mathematics performance (G3 final grades). This report presents key insights through univariate and bivariate visualizations.

**Dataset**: UCI Student Performance Dataset | **Source**: student-mat.csv | **Attributes**: 33 variables

---

## 1. Student Profile Distribution

### Age & Education Background

| | |
|---|---|
| ![Age Distribution](Univariate%20Analysis/AgeDist.png) | ![Mother's Education](Univariate%20Analysis/MeduDist.png) |
| ![Father's Education](Univariate%20Analysis/FeduDist.png) | ![Internet Access](Univariate%20Analysis/Internet.png) |

---

## 2. Academic Performance Overview

### Final Grade Distribution & Pass/Fail Outcomes

| | |
|---|---|
| ![G3 Distribution](Univariate%20Analysis/G3Hist.png) | ![Pass/Fail Ratio](Univariate%20Analysis/Passfail.png) |

---

## 3. Key Findings: What Drives Performance?

### Previous Performance → Final Grade
![G2 vs G3](Bivariate%20Analysis/G2%20vs%20G3.png)

**Insight**: Strongest predictor of success. Previous grades highly correlate with final performance.

---

### Study Time → Academic Success
| | |
|---|---|
| ![Study Time vs Grade](Bivariate%20Analysis/Studytime%20vs.%20G3.png) | ![Study Time vs Pass](Bivariate%20Analysis/Studytime%20vs%20Pass%28avg%29.png) |

**Insight**: More study hours = higher grades and better pass rates.

---

### Attendance Impact
![Absences vs Grade](Bivariate%20Analysis/G3%20vs%20Absence.png)

**Insight**: Higher absenteeism strongly correlates with lower grades.

---

## 4. Family & Support Systems

### Family Support & Parental Education Effects

| | |
|---|---|
| ![Family Support](Bivariate%20Analysis/Famsup%20vs%20G3.png) | ![Parental Education](Bivariate%20Analysis/parentEdu%20vs%20Pass.png) |

**Insight**: Family support and educated parents significantly improve outcomes.

---

## 5. Social & Health Factors

### Lifestyle Balance

| | |
|---|---|
| ![Romantic Relationships](Bivariate%20Analysis/G3%20vs%20Romantic.png) | ![Free Time](Bivariate%20Analysis/Freetime%28Avg%29%20vs%20Pass.png) |
| ![Social Outings](Bivariate%20Analysis/goout%28avg%29%20vs%20Pass.png) | ![Health Status](Bivariate%20Analysis/G3%20vs%20health.png) |

**Insight**: Moderate social engagement optimizes performance; balance is key.

---

### Digital Access & Lifestyle

| | |
|---|---|
| ![Internet Access](Bivariate%20Analysis/G3%20vs%20Internet.png) | ![Alcohol Consumption](Bivariate%20Analysis/WalcDalc.png) |

**Insight**: Internet access aids academic work. Alcohol consumption shows varied patterns weekdays vs weekends.

---

## Summary: Performance Drivers

| Factor | Impact | Priority |
|--------|--------|----------|
| **Previous Grades (G2)** | Strongest | **⭐⭐⭐** |
| **Study Time** | Strong | **⭐⭐⭐** |
| **Attendance** | Strong | **⭐⭐⭐** |
| **Family Support** | Moderate | **⭐⭐** |
| **Parental Education** | Moderate | **⭐⭐** |
| **Health Status** | Moderate | **⭐⭐** |

---

## Actionable Recommendations

1. **Monitor G1 & G2 grades** → Early warning system for at-risk students
2. **Improve attendance** → Implement tracking & intervention programs
3. **Encourage study time** → Provide study spaces & time management support
4. **Strengthen family engagement** → Family support programs & communication
5. **Promote healthy balance** → Well-being initiatives for optimal performance

---

**Tools Used**: Python | Pandas | Altair | Statistical Analysis  
**Data Source**: UCI Machine Learning Repository | School Year 2011-2012  
**Last Updated**: January 2026
