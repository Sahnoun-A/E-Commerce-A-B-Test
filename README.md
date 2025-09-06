# E-Commerce A/B Test: Variant B vs Control A

## 1. Project Objective
Assess whether Variant B improves user-level conversion rate relative to Control A.

## 2. Primary Metric
Conversion Rate (CR) = # unique users with converted = 1 ÷ # unique exposed users.

## 3. Experimental Design
User-level randomization, first exposure decides group; fixed-horizon analysis post test window.

## 4. Statistical Settings
- Significance (alpha): 0.05
- Power: 0.8
- MDE (relative): 5.00%
- Alternative (test direction): smaller

## 5. Results
- n(A) = 145232, n(B) = 145352
- CR(A) = 12.03%, CR(B) = 11.88%
- Absolute lift = -0.145 pp
- Relative lift = -1.21%
- z-statistic = -1.2084
- p-value = 0.113450
- 95% CI (absolute) = [-0.381 pp, 0.090 pp]

## 6. Decision
Do NOT ship (retain A)

## 7. Recommendation
Retain Control A. Iterate on the variant; target a more impactful change, pre-register a realistic MDE, and ensure planned sample size is achieved.

## 9. Resources
- 🗃 [**GitHub Repo**](https://github.com/Sahnoun-A/E-Commerce-A-B-Test)
- 📘 [**Kaggle Notebook**](https://www.kaggle.com/code/abdelkabirsahnoun/a-b-testing)
