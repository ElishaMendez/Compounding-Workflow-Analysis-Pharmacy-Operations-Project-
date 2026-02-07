## Compounding Workflow Efficiency Analysis (Pharmacy Operations Project)
This is my own excel project on analyzing workflow for a compounding pharmacy

I created a dynamic dashboard visualization in Excel using Pivot Tables, slicers, and interactive charts to optimize our compounding pharmacy workflow. The data was manually input from the compounding calendar, which we used to schedule our workflow with patients. This allowed for better trend analysis and real-time decision-making to improve efficiency. Additionally, I utilized Power BI to enhance data visualization, providing clearer insights for decision-making

Tools: Excel, Data Cleaning, Trend Analysis, Capacity Planning

## What I Learned
- How to capture and structure operational pharmacy data to support decision-making
- Identifying and quantifying bottlenecks using Excel-based analysis
- Recognizing how compound categories differ in prep time, hazard level, and scheduling load
- Translating real-world workflow patterns into actionable operational insights

## Impact & Value
- This analysis provided to my pharmacy manager and director with clear visibility into daily production constraints and highlighted where capacity must be expanded before the pharmacy can scale. The project also lays the groundwork for:
- A capacity-based scheduling model
- Better distribution of workload among compound types
- Identified phone call management as a critical bottleneck, consuming an estimated 6-8 hours of daily production capacity and delaying next-day scheduling by an average of 1-2 hours

## Data Structure Overview
- Primary Source: Manual extraction from the pharmacy's compounding calendar system
- Collection Period: 2 months of operational data 
- Update Frequency: Daily entries logged in real-time as compounds were scheduled and completed
- Data Validation: Cross-referenced with shipping logs and batch records to ensure accuracy

### Executive Summary
## Overview of Findings
Data shows a "Monday bottleneck, Friday gap" pattern where Monday hits 150% capacity from cold-chain shipping limits and bulk prep scheduling, while Friday drops to 45% utilization. Phone calls take 6-8 hours daily, and technicians assigned by compound type can't flex during spikes. My analysis led to discussions about shifting toward single-ingredient creams and bulk suspensions for efficiency. When hazardous suspensions spiked, we reallocated time from bulk prep to accommodate them.

Below is the overview page from my initial Excel dashboard & Power Bi dashboard. More examples are included throughout the report. The entire interactive dashboard can be downloaded <a href="[path/to/file.xlsx](https://github.com/ElishaMendez/Compounding-Pharmacy-Workflow-Analysis-Project/blob/main/Estimated%20Totals%20for%20Compounding%202025-2026.xlsx)" download>here-></a>

<div align="center">
  <img src="images/Excel Dashboard(Dark).JPG" alt="Description of image 1" height="900" width="500"/>
  <img src="images/PowerBi Version2.JPG" alt="Description of image 2" height="900" width="500"/>
</div>

## Insights Deep Dive
- Front-Loaded Production Cycles: Our Production Trend shows a heavy peak on Mondays with a steady decline toward Friday. This isn't just a random trend; it’s driven by our shipping policy. Since we can't ship cold products on Fridays (to help preserve the expiration date of medications), we intentionally front-load our schedule to ensure all temperature-sensitive orders out the door each day by 4:00p.m. and no shipping on cold chain items on Friday.
- Bulk Compounding Strategy: The high volume phone calls on Mondays and Tuesdays also reflects our "Bulk Prep" strategy. We prioritize compounding large batches of Bulk Capsules and Creams early in the week to facilitate the individual prescription volume we expect over the following days. 
- The Friday "Drop-Off": The sharp dip on Fridays in the dashboard highlights a shift in focus. With cold-shipping off the table, Friday becomes more of a "cleaning and prep" day for the following week rather than a high-output production day.
- The "Phone Call Tug-of-War": One of the biggest challenges identified is Phone Call Complexity. There is a constant struggle to balance inbound patient inquiries with the outbound calls needed to "fill" the compounding calendar. When the team is tied up on the phones, it creates a delay in finalizing the production schedule and getting prepped for the next day, which causes a ripple effect on daily productivity.

## Recommendations
- Optimize the "Friday Gap": Since Friday is our lowest production day due to shipping constraints, we should officially designate it as "Deep Clean & Inventory Day." Using this low-volume window for maintenance ensures we don't have to stop production during the high-volume Monday rush.
- Pre-Batching Non-Cold Items: To further ease the Monday peak, we could look into identifying non-cold items that have a long shelf life and moving their production specifically to Thursdays or Fridays. This would "shave the peak" off Monday and create a more balanced workflow.
- Hazardous Block Scheduling: On Mondays, when volume is at its highest, we should implement strict "Hazardous Only" time blocks. This prevents technicians from having to switch back and forth between HZ and Non-HZ compounds during our busiest hours, saving precious time on PPE transitions.
- Supplies Readiness Audit: Since Monday is our "Highest Production Day," we should implement a Friday afternoon checklist to ensure all bulk chemicals, capsule shells, and cream bases are fully stocked and staged. This prevents "out-of-stock" delays when we are at our maximum capacity.
