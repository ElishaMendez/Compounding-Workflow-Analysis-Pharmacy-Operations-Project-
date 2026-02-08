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
- Collection Period: 2 months of operational data 
- Update Frequency: Daily entries logged in real-time as compounds were scheduled and completed
- Data Validation: Cross-referenced with shipping logs and batch records to ensure accuracy

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
- Front-Loaded Production Cycles
Production consistently peaks on Mondays and declines through Friday due to cold-chain shipping constraints. Since temperature-sensitive medications cannot ship on Fridays, production is intentionally front-loaded to ensure all cold-chain orders are completed and shipped by 4:00 p.m. earlier in the week. This policy directly drives the weekly output trend.
- Bulk Compounding and Batching Strategy
Bulk compounding is strategically batched on Fridays when cold-chain shipping is unavailable, allowing the team to build inventory for bulk capsules and creams ahead of the following week. This allows time allocated to batching, cleaning, inventory checks, and preparation. This intentional reallocation improves early-week production efficiency and reduces pressure on high-volume days.
- The Phone Call “Tug-of-War”
Patient outreach occurs primarily between 9:00 a.m. and 1:00 p.m., competing directly with production scheduling activities. High inbound call volume delays outbound calls needed to finalize the compounding calendar. These delays create downstream impacts on daily readiness and overall productivity.

## Recommendations
- Optimize the "Friday Gap": Since Friday is our lowest production day due to shipping constraints, we should officially designate it as "Deep Clean & Inventory Day." Using this low-volume window for maintenance ensures we don't have to stop production during the high-volume Monday rush.
- Pre-Batching Non-Cold Items: To further ease the Monday peak, we could look into identifying non-cold items that have a long shelf life and moving their production specifically to Thursdays or Fridays. This would "shave the peak" off Monday and create a more balanced workflow.
- Hazardous Block Scheduling: On Mondays, when volume is at its highest, we should implement strict "Hazardous Only" time blocks. This prevents technicians from having to switch back and forth between HZ and Non-HZ compounds during our busiest hours, saving precious time on PPE transitions.
- Supplies Readiness Audit: Since Monday is our "Highest Production Day," we should implement a Friday afternoon checklist to ensure all bulk chemicals, capsule shells, and cream bases are fully stocked and staged. This prevents "out-of-stock" delays when we are at our maximum capacity.
