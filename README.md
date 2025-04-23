# Supplier-Evaluation-Dashboard
This repository has a Power BI dashboard that analyzes supplier performance by evaluating categories like vendors, plants, materials, and defect types. It provides insights into underperforming suppliers, downtime impact, and financial losses, helping manufacturers optimize procurement, and reduce operational inefficiencies.
![image](https://github.com/user-attachments/assets/e9d29d11-2ba2-4ce8-8e05-baaa89766c67)

DASHBOARD INSIGHT

Homepage
![Screenshot 2025-04-19 103225](https://github.com/user-attachments/assets/4036509f-c311-44a7-834b-945099eda465)

Overview page
![Screenshot 2025-04-19 103245](https://github.com/user-attachments/assets/962191b8-c01f-40bc-8347-e504350527cf)

- Rising Defects and Costs: Defective materials surged to 2.6 billion units (123% increase), causing over 215,000 hours of downtime and $2.16 million in losses, highlighting a major hit to efficiency and cost.

- Trend Insights: Downtime peaks in September across both years suggest possible seasonal or vendor-related issues, with a toggle feature offering flexible views of defect and downtime trends.

- Performance Hotspots: Key underperformers—like vendor Yombu and the Hingham plant—are flagged for targeted audits and quality improvement, helping prioritize corrective actions.


Vendor page
![Screenshot 2025-04-19 103304](https://github.com/user-attachments/assets/55345601-3ab8-42d0-9f82-c5e49946a590)

- This section identifies underperforming vendors with the highest defective material supply. A "Top N" toggle enables users to view defect quantities by vendor in either ascending or descending order. To assess the impact more clearly, a risk analysis was conducted, classifying vendors into high, medium, or low risk based on downtime hours: If downtime > 800 hours then High-risk, if downtime ≥ 400hours ≤ 800hours, then Medium risk, if downtime < 400 hours, then low risk.

Plant Performance and tooltip
![Screenshot 2025-04-22 001458](https://github.com/user-attachments/assets/69e7e5ab-c61e-4936-bcfd-b0e575810839)

- This dashboard highlights significant disparities in defect quantities across the company's plants, using interactive tooltips to provide deeper insights and trend visibility. According to the data, Enterprise Manufaturers Ltd., operates 30 plants across various locations in the United States.

Material Performance
![Screenshot 2025-04-19 103339](https://github.com/user-attachments/assets/8bfce17f-d392-42b2-887a-d02fc94ebd8f)
- From the charts, raw materials and corrugate stand out as the material types causing the most downtime, with 66,000 and 51,000 hours respectively. When it comes to defects, not certified and bad seams are the top culprits, making up a large chunk of the lost production time.
- In terms of category, mechanical and logistics issues are having the biggest impact. October saw the worst performance for both, with mechanical materials causing over 12,000 hours of downtime and logistics over 6,000 hours.

Downtime Impact
![Screenshot 2025-04-22 122113](https://github.com/user-attachments/assets/b325b37c-6030-42d3-81d5-9c9de3a4f251)
This dashboard highlights the financial impact of downtime (assuming a downtime cost of $10/hr) for Enterprise Manufacturers Ltd., broken down by month and day of the week. March and October stand out as the months with the highest downtime costs.

RECOMMENDATION 

Enterprise Manufacturers Ltd. should focus quality audits on high-risk areas such as materials from vendors with frequent defects or plants with repeated performance issues—especially during peak downtime. Materials like raw inputs and corrugates require stricter inspections or re-sourcing. It is also critical to start tracking actual downtime costs, including labor, machine idle time, and lost revenue, to create a more precise cost model that informs supplier evaluations and justifies investments in quality improvements. Implementing a centralized Power BI dashboard as a live procurement tracker will allow for monthly updates, faster risk responses, and standardized vendor review processes across all plants.

CONCLUSION

This project highlights the value of business intelligence tools like Power BI in turning raw data into actionable insights. For Enterprise Manufacturers Ltd., a centralized system is essential to monitor vendor performance, reduce inefficiencies, and improve decision-making. The findings clearly show the need for a formal procurement system that promotes consistent evaluations and enhances production quality company-wide.

Read full project analysis: https://medium.com/@rofiat.razaq/from-chaos-to-clarity-how-power-bi-transformed-supplier-quality-for-a-manufacturing-giant-3f092b5461d3





