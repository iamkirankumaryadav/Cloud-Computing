# **Cloud Architecture**

### **Computer**

1. **Compute:** The Central Processing Unit (CPU) fetches, decodes, and executes instructions from programs and applications.
2. **Storage:** Used to store data and files, the Hard Drive is used for long-term storage, while RAM is used for short-term storage.
3. **Network:** The Network Interface Card allows you to connect and communicate with external servers, networks, and the internet.
4. **Software:** Using what we interact with our computers OS + UI (Mac, Windows, Linux), Applications (Files, Browsers, Utility tools)

### **On-Premise Servers**
- Servers are monitorless computers used to power on-premise networks.
- Local computers submit a query to the server's database and the server processes the query and returns the data to your computer.
- Servers are ideal places to store databases as compared to a local personal computer.
- Servers have increased computing power, and greater storage capacity, and can be accessed by multiple users at a same time.
- Servers have the same components as personal computers but tend to be physically larger and more powerful.
- Servers entail expensive investments in physical space and hardware (racks, wires, blades, ACs, cooling equipment, etc)
- Requires specialized talent to set up, configure, maintain, and service over time to keep it safe and secure.
- Additional investment is needed to ensure data is backed up and performance remains high.

### **Cloud Data Centers and Networks**
- With the cloud, the company pay for access to a fraction of the network's resources and can increase or decrease that fraction.
- As a user (Data Analyst, Data Scientist, Data Engineer) you will not feel any difference using an on-prem server and a cloud.
- As a user you will submit the query to the cloud database, the servers process the query and return data to your machine.
- Cloud servers are still just networks of servers, but at an extreme scale.
- A cloud data centre will look like a massive data warehouse full of computing equipment that has large cooling towers.
- Dozens of data centres are located across the globe which connects the cloud database to your local machine.
- Companies like Amazon, Microsoft, and Google have a global distribution of cloud data centres that enable fast, high-performing connections worldwide and provide redundancy in the case of natural or political disasters.

### **Cloud Security**
- No data is ever completely secure, whether on-premise or in the cloud.
- One of the downsides about the cloud is the fact that all of this data is accessible via the internet.
- Cloud data is at risk of a data breach, just like other data.
- But cloud systems also have robust security measures in place, as well as some of the world's best team prevents breaches.

### **Cloud Security Measures**
1. Multi-factor authentication
2. Data encryption and firewalls
3. Threat response teams
4. Continuous monitoring
5. Data backup and disaster recovery
6. Physical security forces onsite

## **Components of Cloud**

- Cloud Data Centres house massive amounts of computing, storage, and network components.
- Cost can be optimized by choosing the appropriate computing and storage options for the tasks in hand.
- Google Drive, Microsoft Drive, and Apple iCloud provide features to upload their data to the cloud instead of storing it in a phone or laptop.

### **Storage**
- Cloud storage solutions range from traditional Hard Disk Drives (HDD) to Solid State Disk Drives (SDD), and can be scaled on demand.
- Standard HDD: Traditional storage for non-critical, backup, and infrequently access files (Old computers and laptops | Slow and laggy)
- Standard SDD: Ideal for development, testing, and light web or application use (New laptops and computers | Fast and smooth)
- Premium SDD: Critical for production, analytics, high-performance applications (Content Creators, Corporate laptops, Aeronautics and Medical Labs)

### **How data can be stored?**
1. Flat files: 
- Static data stored on a local machine or cloud drive, used for a quick ad hoc analysis, sometimes archived due to infrequent usage.
- Example: CSV, Excel, XML, JSON, Parquet, etc.

2. Database: 
- Collection of related tables stored in a DBMS, used for collecting and managing data for a single application or company/business.
- Capturing sales, and transactional records on a real-time e-commerce website.
- Usually optimized for **Online Transactional Processing (OLTP)** (Built to receive and store data efficiently)
- Example: Google Cloud SQL, Amazon RDS, Azure SQL Database, etc.

3. Data Warehouse
- A database or collection of data sourced from multiple databases.
- Structured to support analytics needs and optimized for **Online Analytical Processing (OLAP)**
- Example: Amazon Redshift, Google BigQuery, Azure Synapse Analytics, Snowflake, Databricks, etc

4. Data Lake
- A repository of structured and unstructured data typically stored in a raw, unprocessed state.
- Data is typically extracted from the lake and transformed for specific purposes (ML or AI)
- Example: AWS S3, Azure Data Lake, Google Cloud Storage, etc

6. Data Lake House (Hybrid of Data Warehouse and Data Lake)

**You'll most likely be told which systems to use, and you'll need to know how to write SQL queries to extract the data.**

### **Compute**

Cloud computing resources come in three primary variations, as our processing units get more powerful they also get more expensive.

1. **Central Processing Units (CPU)**
- Sufficient for most data analysis tasks, even heavy data processing.
- You can ask for a single CPU or a machine with multiple CPUs powering your data processing.
- Some of the shelf cores even have 64 CPUs that can be dedicated to a single task.

2. **Graphics Processing Units (GPU)**
- Best for ML models and intensive parallel data processing.
- Frequently used in image processing, video editing, graphic design, ML and AI operations.

3. **Tensor Processing Units (TPU)**
- Reserved for large-scale workloads and cloud-based ML model training and fine-tuning.
- TPU computing is the most expensive.

### **Virtualization**
- Create virtual versions of physical computing resources (AWS Workspace, Microsoft Windows 365 Cloud PC, etc)
- Virtualization enables the massive scalability of the cloud.
- A single piece of physical hardware can be partitioned to serve multiple tasks and users.
- Multiple pieces of hardware can be pooled together to serve a single task and user.
- Example: If a cloud server had an HDD that was 300GB, but I only needed 100GB of storage.
- Virtualization would allow that provider to split off 100GB for me and sell the 200GB to somebody else.
- This means I only have to pay for what I need and also allow cloud service providers to sell the remaining with others.
- We can rent small fractions of physical resources, and we can also gain access to massive amounts of computing power.
- By pulling multiple physical resources together into a single virtual machine that can tackle very large tasks.

### **Cost Control**
- Cloud bills for the largest companies can run into the billions annually.
- Shut down unused resources. Stop requesting the reserved resources if you're not using them.
- Optimize query efficiency. Use show columns to fetch metadata details instead of fetching tables with records.
- Every single query is going to incur a cost in terms of computing.
- So making queries as efficient as possible is going to help reduce the cost of your cloud bill.
- Avoid using premium resources unless needed.
- Consult with IT Data Admin or Data Engineers to ensure you're following best practices.
- IT Data Admin will notice the high costs if you're using a lot of resources.

## **Type of Cloud Services**

### 1. **Infrastructure as a Service (IaaS)**
- Provides cloud access to raw compute (processor), storage (HDD, SDD), and networking resources.
- Users are required to setup their computing environments.
- These raw resources don't come with any software installed at all. Including OS (Mac OS, Windows, Linux)
- This allows for a high degree of customization, but also means that only IT expert tends to work at this level.
- Most data professionals, including Data Engineers, start working with the cloud at the PaaS (Platform as a Service) level.
- Example: AWS, Google Cloud, Azure.

### 2. **Platform as a Service (PaaS)**
- Provides pre-configured environments, cloud hardware and operating systems.
- User can develop data pipelines and set up databases and coding environments.
- Allows user to quickly start downloading the rewquired applications or start building applications.
- Setup data pipelines, and create the analytical environments where Analysts and Data Scientists performs their daily work.
- Primary workspace of Data Professionals (Data Engineers, Data Scientists, Data Analyst, Business Analyst, ML Engineers)
- Example: AWS, Google Cloud, Microsoft Azure, Snowflake, Databricks with high performance data warehousing, ML and AI software.
- Provides specialized tools and services for Data Professionals.
- PaaS offerings are built on top of IaaS.

### 3. **Software as a Service (SaaS)**
- The final layer of the cloud and most familiar to the general public.
- Fully developed software applications that users pay to access.
- Wide range of applications, from data analytics tools to consumer gaming apps.
- They typically use IaaS hardware and PaaS environments in their backend.
- But end users take a SaaS as is rather than have any ability to customize it.
- Types of users of SaaS products are general publics (Productivity Tools, Analytics Tools, Games, Utility Tools)
- SaaS is generally downloaded as an application in a phone or laptop or can be used as a web on the browsers.
- Examples: Google Workspace, Microsoft 365, Apple iWork, SAP, Salesforce, Atlassian, ServiceNow, Wrike, Gemini App, ChatGPT App, etc. 

## **Type of Cloud Infrastructures**

### 1. **Private Cloud**
- Fully dedicated to a single organization.
- Dedicated resources offer the best performance.
- Easier to be compliant with control over the infrastructure.
- Applicable rules governing the storage and handling of sensitive data.
- Access to data is limited to your organization with strict security measures.
- Example: Corporate, Healtcare, Finance, etc.
- Cons: High initial investment and fixed cost. Requires dedicated IT staff to manage, maintain and sevice the infrastructure.

### 2. **Public Cloud**
- Cloud resources hosted by third parties to shared across many organizations.
- Low initial investments and a pay-as-you-go model.
- Infrastructure managed by the cloud provider.
- Can easily adjust the services and resources based on demand.
- The pool of resources available from the public cloud providers is much larger than private cloud systems.
- Solutions might not meet specific compliance requirements.
- Shared resources can lead to potential vulnerabilities. Public cloud providers serve many organizations.
- There are incereased security risks and shared storage might not be compliance for some types of sensitive data.
- Major public cloud providers have matured and developed offerings tailored to specific popular industries and organizations.

### 3. **Hybrid Cloud**
- A combination of Private Cloud and Public Cloud infrastrutures, with protocols exchange data between systems.
- Allows business to manage their workloads based on their needs.
- Can implement cost effective measures by optimizing usage.
- Can easily adjust resources on public cloud if necessary.
- Sensitive data can be stored in the private cloud.
- Example: A hospital may keep its patient's medical records stored in the private cloud, but leverage the public cloud for supply chain.
- It won't be as cheap as a public cloud, it does allow companies to lower its cost and increase its scalability as compared to private.
- This makes the system more complex overall, but it's often worth it for organizations.

From the perspective of a data professional, the choice of Private vs Public vs Hybrid will rarely impact your day at work.
