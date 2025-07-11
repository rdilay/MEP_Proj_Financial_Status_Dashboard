# 📊 Construction Cost & Profitability Analysis (Jul 2017 – Sep 2019)

Analyzing budget, cost, contract value, and profitability across the construction lifecycle using Excel and Tableau.

**🔗 Interactive Dashboard:** 👉 [Explore the live Tableau version here.](https://public.tableau.com/views/MEP_Proj_Financial_Status_Dashboard_09-2019/Proj_Final?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<img width="1199" height="1199" alt="Proj_Final" src="https://github.com/user-attachments/assets/1e410aed-6e14-4be2-a9f2-2f7ab1217ec0" />

## 📌 Key Metrics and Dimensions
- **Contract Value:** Original contract amount awarded by the client
- **Expected Variations:** Expected to be approved change order amounts to be added
- **Total Contract Value:** Sum of original contract + expected variations
- **Budget:** Baseline project budget (cost planning)
- **Variation Budget:** Budget allocated for expected variations
- **Total Budget:** Sum of baseline budget and variation budget
- **Actual Cost to Date:** All real monthly expenses logged from site (staff, labor, materials, subcontractors, etc.)
- **Cost-to-Completion:** Forecast of remaining costs based on the remaining works at site
- **Cost at Completion (EAC):** Total expected cost of the project (actual + remaining)
- **Profit / Margin Forecast:** Difference between Total Contract Value and Cost at Completion

## 📈 Summary of Insights
### 🧾 Contract vs. Budget vs. Cost:
- As of Sep. 2019, the actual cost incurred is AED 142.62M, which means the project has already consumed 97% of the total budget—with ongoing works and cost-to-completion of AED 139K still ahead.
- This highlights a narrow margin and signals potential budget overrun if variation orders are not approved and recovered in time. With the cost creeping close to the total budget, and just AED 4.5M remaining in budget buffer, strict cost control and rapid claim validation are essential.

### 💸 Cash Flow Trends:
- From Jul 2017 to Jul 2018, the project experienced consistent negative monthly cash flow throughout the early and mid-phases of construction. For example, in the first three months, the actual costs totaled AED 1.4M, but the cumulative client payments were only AED 803K, resulting in a funding gap of nearly AED 600K.
- This pattern continued as actual costs ramped up, but client payments lagged behind—due to milestone-based billing and the delay in claiming high-value equipment that had been procured but not yet installed.
- By July 2018, the cumulative actual cost reached AED 39.14M, while cumulative paid claims totaled only AED 31.45M, resulting in the project’s highest funding gap of AED 7.69M.
- The cash flow only began to stabilize by April 2019, as the project team started claiming and recovering previously deferred high-ticket items. However, the sustained gap highlights a risk of project-level financing strain, and reinforces the importance of:
  - Accurate cash flow forecasting
  - Early variation claim approval

### 📊 Forecast Accuracy:
- As of September 2019, the projected cost-to-completion was estimated at AED 139K, bringing the Cost at Completion to AED 142.77M.
- This is AED 4.36M below the total project budget of AED 147.13M, resulting in a positive variance of approximately 3%. This reflects a strong overall forecasting performance, indicating that the project team maintained effective control over cost trends and future projections throughout the build.
- The forecast showed minimal remaining cost pressure in most categories, such as Subcontractor (AED 360K) and Site Admin (AED 26K). A notable item is the negative cost-to-complete of AED -1.39M in Materials_HVAC, driven by over-issued items such as ductworks and accessories, which were planned to be returned to the main warehouse. This accurate recognition of field conditions and material reconciliation helped ensure the reliability of the final forecast.
- Overall, this level of forecast precision demonstrates the project team's ability to make informed financial decisions based on real-time data, with built-in accountability for over-issued or recoverable resources.

### 💰 Expected Profit:
- Based on the final Cost at Completion of AED 142.77M and a Total Contract Value of AED 216.74M, the project is forecast to yield an expected profit of:

  ✅ AED 73.98M

- This represents a profit margin of approximately 34.1%, which is well within the healthy range for complex construction projects. It reflects strong management of direct costs and effective variation handling — even without factoring in unapproved change orders or late-stage claims.
- Maintaining this margin will depend on tight closeout practices and ensuring no unplanned scope creep occurs beyond the current forecast window.

## ✅ Recommendations and Next Steps
### Refine Variation Management Workflow:
- Continue optimizing the variation claim process by prioritizing faster approval cycles and improving the visibility of variation impacts on projected margins. Regular reviews of variation recovery against incurred costs are recommended.

### Monitor Cash Flow Lag More Closely:
- Maintain monthly tracking of actual cost vs. paid claims, and flag funding gaps exceeding predefined thresholds. This will help project leadership proactively manage working capital needs as the project closes out.

### Strengthen Forecasting Accuracy at Closeout Stage:
- With the remaining cost-to-completion now minimal, tighten forecast inputs to include late adjustments such as material returns, final subcontractor invoices, and unresolved site issues to ensure final costs are well-aligned with reality.

### Perform Material Reconciliation Finalization:
- Ensure all over-issued materials (like GI ducts and accessories) are either returned or reallocated to avoid cost misstatement. Coordinate closely with site and warehouse teams during project demobilization.

### Use Dashboard as Historical Reference for Post-Mortem:
- Leverage the full dashboard history to conduct a project closeout review and lessons-learned session. Patterns in early underbilling, material flow, and forecast accuracy can inform planning and risk controls in future projects.

## 🛠 Tools Used
- Excel: Data transformation and time series calculation
- Tableau: Interactive dashboard and cost trend visualizations
- GitHub: Project repository and documentation
