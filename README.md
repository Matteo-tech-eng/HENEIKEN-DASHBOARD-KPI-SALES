FMCG Sales KPI Dashboard (Power BI)
A Power BI dashboard for tracking sales team & outlet performance against a
personal KPI framework used in FMCG route-to-market (RTC) operations.
All data in this project is synthetic/mock — no real company, employee, or
outlet data is used. This project is not affiliated with or endorsed by any
brand; it recreates a realistic FMCG KPI structure for portfolio purposes.
What it tracks
Sales Volume Performance — Total / Group AA / Group BB volume vs. target (HL)
Fundamental KPIs — %ASO (Active Selling Outlet), %Route Compliance, %Strike Rate,
SKU per Outlet, %PICOS
Call Performance — Actual Visit vs. Call Cap by employee
TouchPoint Mix — visit distribution by channel type (DIS, DIS-Lite, SEM, DOT)
Employee-level drill-through — outlet-by-outlet visit tracking, channel,
tier, AA/BB volume, pricing/SOS compliance, and PICOS status per employee
Pages
Page	Description
`Overview`	Team-level KPI summary with SR/DSM leaderboard and call performance chart
`Detail`	Drill-through view showing one employee's outlet-level visit and compliance data
Tech stack
Power BI Desktop (`.pbix`)
DAX for KPI calculations (volume vs. target, compliance %, strike rate, PICOS achievement)
Data model: dimension tables (Employee, Outlet, Territory, Product) + fact
tables (Visit, Order, PICOS)
Files
`Dashboard KPI_SaleRep_DSM.pbix` — full Power BI file (mock data)
`Overview.jpg` — overview page screenshot
`Detail DrillThrough.jpg` — employee drill-through screenshot
Notes
This dashboard was built to practice modeling and visualizing a real-world
FMCG KPI framework (fundamental KPIs + volume-based incentive structure)
commonly used to manage sales reps and district sales managers.
