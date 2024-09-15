# Cloud Data Stacks

**Data Engineers** must consider multiple factors when choosing a stack for a cloud project.


## Key questions need to be asked when designing cloud architecture

### Who is the end user and What outputs are needed?
- The who could be a Data Analyst who simply needs to be able to query data in a cloud data warehouse.
- A business stakeholder who needs to view Business Intelligence dashboards that update in real time.
- The endpoint may not be a person at all, the endpoint may be an API that serves data to other data pipelines or external systems.

### What types of data will be used and where do they come from?
- Data sources can be varied and complex.
- Example: A retail store (Information about sales both from an e-commerce website and physical retail stores)
- Inventory (Information such as in-hand, store, in-transit, return and distribution centres inventories)
- Sales and product information, employees working in customer service from their customers and social media mentions.
- Different types of data will be stored in different systems, pulling it all together can be a huge task.

### How much data comes from each source? 
- Understanding the volume of data coming from each source.

### How quickly does it need to move end-to-end? 
- How quickly it needs to get to its end users.
- Will help engineers determine the exact tools they need to use and the performance level of hardware needed.
- High-performance systems can get very expensive.

### How often does it need to refresh?
- Daily, Weekly, Monthly, Quarterly, Yearly, etc

### What is the budget for the project? 
- As an Analyst and Data Scientist, you'll often be responsible for helping Data Engineers understand the user's needs.

### Does the project add enough value to justify the cost?
- While engineers and analysts could make every Business Intelligence dashboard update in real-time.
- They need to think critically about whether or not that's necessary to achieve the goal.
- The more data that's getting moved and analyzed, and the faster it moves, the more expensive the project gets.
- A lot of money can be wasted by using state of art tools for projects that only need simple and cheap solutions


