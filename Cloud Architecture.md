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

1. Central Processing Units (CPU)
- Sufficient for most data analysis tasks, even heavy data processing.
- You can ask for a single CPU or a machine with multiple CPUs powering your data processing.
- Some of the shelf cores even have 64 CPUs that can be dedicated to a single task.

2. Graphic Processing Units (GPU)
- Best for ML models and intensive parallel data processing.
- Frequently used in image processing, video editing, graphic design, ML and AI operations.

3. Tensor Processing Units (TPU)
- Reserved for large-scale workloads and cloud-based ML model training and fine-tuning.
- TPU computing is the most expensive.

### **Virtualization**
- Create virtual versions of physical computing resources (AWS Workspace, Microsoft Windows 365 Cloud PC, etc)
- A single piece of hardware can be partitioned to server multiple tasks and users.
- Multiple pieces of hardware can be pooled together to serve a single task and user.
