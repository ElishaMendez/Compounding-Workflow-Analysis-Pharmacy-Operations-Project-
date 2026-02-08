# Compounding Workflow Analysis (Pharmacy Operations Project)

# Background and Overview
Compounding pharmacy workflows are shaped by close coordination between multiple teams, primarily the compounding team responsible for production and the shipping schedule team responsible for managing delivery timelines. The shipping team also handled inbound and outbound calls related to order confirmations, delivery changes, and time-sensitive requests, which directly influenced daily workflow priorities.

This project analyzes workflow data created through this cross-team interaction to understand how scheduling decisions, communication volume, and production capacity align in practice. The analysis focuses on:

- Examining how batch scheduling and production timing impact daily workflow efficiency
- Identifying bottlenecks in high-volume products such as single ingredient and multi ingredient creams
- Evaluating how collaboration between the compounding team and shipping schedule team affects workflow balance
- Using data to recommend adjustments in production sequencing to reduce queue buildup and improve operational flow

<p>An interactive PowerBI dashboard can be downloaded <a href="https://raw.githubusercontent.com/ElishaMendez/Compounding-Workflow-Analysis-Pharmacy-Operations-Project-/main/Estimated%20Totals%20for%20Compounding%202025-2026.pbix" download>here.</a></p>

<p>Excel Dashboard and data sheet <a href="https://raw.githubusercontent.com/ElishaMendez/Compounding-Workflow-Analysis-Pharmacy-Operations-Project-/main/Estimated%20Totals%20for%20Compounding%202025-2026.xlsx" download>here.</a></p>

# Data Structure Overview
- **Primary Source:** Manual extraction from the pharmacy's compounding calendar system
- **Collection Period:** 2 months of operational data 
- **Update Frequency:** Daily entries logged in real-time as compounds were scheduled and completed
- **Data Validation:** Cross-referenced with shipping logs and batch records to ensure accuracy

# Executive Summary
### Overview of Findings
This project analyzed daily production patterns to create a more balanced workflow throughout the day. By examining batch volumes, queue buildup, and production timing, it became clear that certain products, including single ingredient creams and multi ingredient creams, were creating bottlenecks that caused the compounding calendar to fill up two weeks ahead of other products.

To address this, production output was adjusted by pushing and pulling higher volume products versus lower volume products throughout the day. This helped reduce bottlenecks, smooth the workflow, and improve overall efficiency. The analysis demonstrates how production-level data can guide better scheduling decisions and maintain a steadier daily operation without requiring additional resources.

Below is the overview page from my initial Excel dashboard & Power Bi dashboard. More examples are included throughout the report. The entire interactive dashboard can be downloaded <a href="[path/to/file.xlsx](https://github.com/ElishaMendez/Compounding-Pharmacy-Workflow-Analysis-Project/blob/main/Estimated%20Totals%20for%20Compounding%202025-2026.xlsx)" download>here.</a>

<div align="center">
  <img src="images/Excel Dashboard(Dark).JPG" alt="Description of image 1" height="900" width="480"/>
  <img src="images/PowerBi Version2.JPG" alt="Description of image 2" height="900" width="480"/>
</div>

# Insights Deep Dive
- **Front-Loaded Production Cycles**
Production consistently peaks on Mondays and declines through Friday due to cold-chain shipping constraints. Since temperature-sensitive medications cannot ship on Fridays, production is intentionally front-loaded to ensure all cold-chain orders are completed and shipped by 4:00 p.m. earlier in the week. This policy directly drives the weekly output trend.
- **Bulk Compounding and Batching Strategy**
Bulk compounding is strategically batched on Fridays when cold-chain shipping is unavailable, allowing the team to build inventory for bulk capsules and creams ahead of the following week. This allows time allocated to batching, cleaning, inventory checks, and preparation. This intentional reallocation improves early-week production efficiency and reduces pressure on high-volume days.
- **The Phone Call “Tug-of-War”**
Patient outreach occurs primarily between 9:00 a.m. and 1:00 p.m., competing directly with production scheduling activities. High inbound call volume delays outbound calls needed to finalize the compounding calendar. These delays create downstream impacts on daily readiness and overall productivity.

## Recommendations
- **Friday Prep Strategy:** My analysis shows Friday as our lowest production day due to cold-chain shipping constraints. I recommend restructuring it as a strategic prep day: (1) bulk compounding for half the day to build inventory for the following week, (2) dedicated outbound calls to fill the upcoming week's calendar and reduce Monday morning scheduling pressure, (3) deep clean and inventory audits to ensure all supplies are staged and ready, and (4) equipment setup and workspace preparation for Monday's high-volume production. This approach would help prevent maintenance interruptions during our peak days and ensure we start each week with a finalized schedule and fully stocked workspace.
- **Implement Peak-Hour Role Separation for Call Team:** During 9am-1pm, assign 2 staff to inbound calls only and 2 to outbound confirmations only, allowing uninterrupted calendar finalization by 10:30-11am (currently after 1pm). This enables production to start 2-3 hours earlier, reduces the 2-week calendar backlog for high-volume products, and requires zero additional headcount—simply protecting focused work time to unlock existing capacity.
- **Priority-Based Queue Scanning Protocol:** Standardize daily queue handling by scanning in order of complexity and risk: (1) hazardous medications first, (2) suspensions second, (3) creams third, (4) troches and suppositories last. This ensures time-consuming compounds requiring the hazard room are processed during peak staffing hours, reduces PPE change-over time by batching hazardous work, and creates a predictable workflow that prevents simple products from blocking complex ones—improving safety compliance and throughput without additional resources.
- **Supplies Readiness Audit:** Since Monday is our "Highest Production Day," we should implement a Friday afternoon checklist to ensure all bulk chemicals, capsule shells, and cream bases are fully stocked and staged. This prevents "out-of-stock" delays when we are at our maximum capacity.
