#  B2B SaaS Business Intelligence & Portfolio Optimization Report

### 📄 Executive Project Overview
This data science project transforms `9,994 raw transactional records` from a fictitious B2B SaaS enterprise into an actionable corporate growth strategy. Historically, the company pursued a aggressive "revenue-at-all-costs" philosophy, scaling top-line sales without translating those gains into bottom-line earnings. 
This analysis identifies structural leaks in pricing policies, customer retention, and regional allocations, providing data-driven solutions to recover trailing profit margins.


### 🔍 Core Analytical Discoveries

#### 1. Descriptive: The Stagnant Profit Traps
The Revenue-Profit Divergence: While annual gross sales surged by `+20.62%` ($733,912.00) in 2023, net profits lagged behind at `+14.41%` ($93,522.00). 
Margin Compression: The overall company profit margin peaked in 2022 at `13.43%` before dropping down to `12.74%` in 2023, proving that high sales volume was actively eroding baseline efficiency.
Macro Concentration Risks: `EMEA` stands out as the primary volume driver ($1.04M sales, $147K profit). However, the `APJ region` is in a severe operational crunch, yielding a weak `2.77% profit margin` ($11.5K profit out of $415K sales).

#### 2. Diagnostic: The Poisonous Discount Thresholds
The 20% Break-Even Wall: Protecting full pricing integrity delivers an optimal `29.5% profit margin`. Applying promotional discounts up to 20% safely preserves positive returns.
The Toxic Zone (≥30%): The exact tipping point occurs at the 30% discount threshold, where margins instantly drop to `-10.1%`. At extreme 80% pricing discounts, margins plummet to `-180.0%`.
SKU Leaks: A targeted diagnostic sample isolates the largest corporate losses to just two high-volume software products: “Big Ol Database” and “ContactMatcher” when attached to discounts ranging from 50% to 80%.

#### 3. Predictive: Churn Vulnerability & Portfolio Health
Strong Structural Core: The active customer database remains highly resilient, with `84 accounts completely active and engaged`, 8 flagged for attention, and `7 accounts sitting in critical churn territory`.
Lapse Exposure: The high-risk client cohort accounts for massive historical footprints, led by Nestle` ($23,194.64 lifetime spend, 117 days inactive) and HSBC Holdings` ($22,703.84 lifetime spend, 61 days inactive). `Citigroup` shows a permanent lapse signal at 239 days inactive.


###  Prescriptive Strategic Mandates

1. Implement an Automated CRM Pricing Shield: Enforce a hard ceiling in the CRM. Restrict standard sales representatives from applying any discount above 20%. Any promotional overrides above this cutoff must automatically route to regional VPs for approval.
2. Transition from Price Cutting to Value Bundling: Based on Market Basket Analysis, eliminate standalone pricing discounts for late-stage Q4 contracts. Instead, protect full software contract value by bundling complementary product add-ons or free onboarding seats.
3. Restructure Sales Incentives to Protect Profit Margins: Shift sales compensation structures away from gross contract value (Sales volume) and tie commissions directly to contract profitability (Net Profit margin) to align sales behavior with bottom-line health.
4. Deploy Immediate CS Outreach to Slipping Accounts: Direct the Customer Success team to launch proactive retention campaigns for *Nestle* and *HSBC Holdings* to secure $45K+ in threatened renewal value before permanent churn happens.


###  Technical Deliverables Generated
Strategic Visual Elements: Multi-axis Seaborn line plots, sorted stacked bar charts with custom boundary labels, and outlier-highlighting customer value scatter plots.
Automated Stakeholder Workbook: A dynamic, multi-tab Excel document (`SaaS_Business_Intelligence_Report.xlsx`) built with a navy corporate style, auto-fit boundaries, and accounting formats for automated report generation.
