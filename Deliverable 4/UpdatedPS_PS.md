## **1.1 Updated Problem Statement**

In our initial approach, we aimed to develop a comprehensive Farm Management System encompassing all aspects of farm operations—crop management, worker scheduling, rotation planning, and resource tracking. However, this scope proved overly ambitious given our current time and resource constraints.

After re-evaluating the project and receiving feedback, we realized the importance of narrowing our focus to specific areas where digital solutions could offer immediate and measurable value. We now aim to concentrate on three interconnected areas of the farm management process:

* **Crop Rotation Management**: Addressing the lack of a structured system for planning and tracking rotation cycles, which is essential for maintaining soil health and optimizing crop yield.
* **Worker Task Management**: Improving the assignment and tracking of daily tasks performed by farm workers to ensure accountability and efficient operations.
* **Harvest Inventory Tracking**: Introducing a system to log and manage harvested crop quantities for better oversight and future planning.

Currently, many small to medium-sized farms still rely on paper-based or Excel-driven systems, which make it difficult to track crop progress, inventory, and worker performance effectively. This results in issues such as:

* **Soil degradation** due to poor rotation tracking
* **Low task transparency**, leading to inefficiencies in daily operations
* **Untracked or misreported harvest yields**, affecting sales and long-term planning
* **Delayed reporting**, leaving stakeholders without timely insights

Our revised problem statement focuses on solving these specific issues with a scalable and targeted solution.

---

## **1.2 Proposed Solution**

The revised Agricultural Management System will focus specifically on **Crop Rotation Management**, **Worker Task Tracking**, and **Harvest Inventory Logging**, three essential features that together improve operational efficiency and long-term sustainability.

### **1. Crop Rotation Management**

We will provide a digital module that allows farm managers and workers to:

* Assign crops to specific fields with historical tracking
* Prevent overuse of soil by identifying repeat crop patterns
* Input soil test data to guide rotation decisions 
* Instruct the user that if The NPK ratio is to high or low, should use fertilizer or its perfect for planting.
* Receive alerts if the same crop is selected consecutively for a given plot

This feature will help reduce the risk of soil nutrient depletion and increase long-term yield through better planning.

###  **2. Worker Task Management**

The system will include a simple interface where farm workers and managers can:

* Log daily tasks (e.g., watering, harvesting)
* Task should be derived from the Field details (i.e., crop irrigation having intervals of 3 days, or when fertilizer is needed)
* Record task completion status and time spent
* Assign tasks to individuals or teams
* Generate reports on workforce activity and productivity

This will enhance task accountability and allow for better use of human resources on the farm.

### **3. Harvest Inventory Management**

To help farms monitor their yield, we will introduce an inventory tracking module that allows users to:

* Log harvested quantities by crop type, date, and field
* Track storage status (e.g., quantity in storage, sold, spoiled)
* Generate simple reports showing yield trends and storage capacity
* Export harvest logs for external stakeholders or market tracking

This module will ensure that harvested crops are recorded consistently, aiding both operational decisions and stakeholder reporting.

### Implementation Notes

* The system will be web-based with mobile-friendly forms for data entry.
* Real-time data access will be facilitated via cloud database (e.g., Firebase).
* The MVP will focus on manual data input with well-structured interfaces.

