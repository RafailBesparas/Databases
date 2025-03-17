# Factory-Database-System
A relational database system with automated triggers, foreign keys, and stored procedures is proposed to improve these processes, resulting in increased productivity and reduced costs.

1. Executive Summary
This project aims to design and implement a relational database system for a factory that streamlines the production, maintenance, and inventory management processes. The system will include key features such as foreign keys for relational integrity, triggers for automation, and stored procedures to automate repetitive tasks. The goal is to improve operational efficiency, reduce downtime, and optimize resource management.

2. Business Problem
The factory currently faces challenges in managing its production, machine maintenance, and inventory processes:

Inefficient production tracking: Production records are maintained manually, leading to discrepancies and delays.
Frequent machine downtime: Maintenance records are not centralized, resulting in delayed repairs and production halts.
Poor inventory management: Inventory levels are either overstocked or insufficient due to inaccurate records, causing delays in production or wastage of resources.
These issues increase operational costs, reduce productivity, and negatively affect the factory's profitability.

3. Proposed Solution
The proposed relational database system will:

Centralize production data: Track product types, production output, and timelines using an automated system.
Automate machine maintenance: Triggers will ensure that machine maintenance schedules are automatically updated, and alerts are sent when maintenance is due.
Optimize inventory management: Real-time tracking of raw materials and finished products, with alerts for low inventory levels.
This database will be highly relational, with foreign keys ensuring referential integrity across the system, triggers to automate updates, and stored procedures to automate tasks such as maintenance scheduling and inventory reporting.

4. Project Scope
The project will focus on:

Database design: Tables for employees, machines, production, inventory, and maintenance.
Automation features: Implementing triggers for inventory updates and machine status changes.
Stored procedures: Automating production reports, inventory replenishment, and maintenance scheduling.

5. Key Features
Foreign Keys: Ensure that all relationships (e.g., between machines and maintenance tasks) are consistently enforced.
Triggers: Automate the updating of machine statuses and inventory levels when certain conditions are met.
Stored Procedures: Automate complex tasks such as generating monthly reports, restocking inventory, and assigning maintenance tasks.

7. Benefits
Reduced Downtime: Automated maintenance schedules will reduce machine downtime by ensuring timely repairs.
Increased Efficiency: Production and inventory tracking will be automated, minimizing human errors and ensuring accuracy.
Cost Savings: Optimized inventory levels and reduced operational disruptions will lower costs and increase overall profitability.

9. Risks and Mitigations
Data Integrity Risks: Foreign keys will ensure that data integrity is maintained, and relationships are enforced.
Automation Failures: Triggers and stored procedures will be tested rigorously to ensure they function correctly under all conditions.

11. Conclusion
Implementing this relational database system will significantly enhance the factory’s operations, reduce manual work, and improve resource management. The automation of key processes such as maintenance and inventory control will lead to lower costs, higher efficiency, and ultimately, greater profitability.
