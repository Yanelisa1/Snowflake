# Snowflake
WHAT IS SNOWFLAKE?
It is divided into three parts:
1. Cloud Oriented
Snowflake's software is purposely built for the cloud.All snowflake infrastructure runs on the cloud in either AWS, GCP or Azure andThey make use of Cloud's elasticity,scalability,high-availability,cost efficiency
 and durability.
2. Data Platform
As part of Data Warehouse snowflake handles Structured and Relational data using ANSI Standard SQL.It also supports ACID compilant transactions and Data is stored in databases,schemas and tables.
As part of Data Lake snowflake handles scalable storage and compute,Schema does not need to be defined upfront and Native processing of semi-structured data formats.
As part of Data engineering Snowflake provides features like COPY INTO and Snowpipe,Separate compute clusters,supports tasks and Streams and ensures all data encrypted at rest and intransit.
As part of Data science you can remove data management roadblocks with centralized storage.
As part of Data sharing snowflake offers Secure data sharing,Data exchange BI with the snowflake partner ecosystem tools.
As part of Data Applications snowflake simplifies connectivity with connectors and drivers,supports UDFs and stored procedures including External UDFs and explore preview features such as snowpark.
3.Saas(Software as a Service)
No management of hardware,Transparent updates and patches,Subscription payment,Ease of access and Automatic optimisation.

SNOWFLAKE ARCHITECTURE
It is designed for scalability,perfomance and simplicity.It decouples storage,compute and management services.
Key Components:
1.Storage Layer
Snowflake utilizes the object storage layer provided by the underlying cloud platform such as Amazon S3, Azure Blob Storage, or Google Cloud Storage for durable and scalable storage of data.
Data loaded into snowflake is organized by databases, schemas and accessible primarly as tables.
Both structured and semi-structured data files can loaded and stored.
Snowflake stores data in a columnar format, where each column is stored separately.
Micro-partitions it is the data that is loaded or inserted also partitioned into snowflake.
2.Query Processing Layer
It consist of Virtual Warehouses that execute the processing tasks required to return results for most SQL statements.
A Virtual Warehouse is a named abstraction for a cluster of a cloud-based compute instances that snowflake manage.
Virtual warehouses can be created or removed instantly
3. Service Layer
It is a collection of highly available and scalable services that coordinate activities such as authentication and query optimization across all snowflake accounts.
Services managed by this layer include: 
1. Authentication & Access Control
2. Infrastructure Management
3. Transaction Management
4. Metadata Management
5. Query parsing and optimisation and 
6. Security

KEY FEATURES AND CAPABILITIES OF SNOWFLAKE
Separation of Compute and storage:Unique architecture that decouples storage and compute resources,allowing independent scaling for each other.
Automatic Scaling:Snowflake dynamically adjust computing resources to match workload demands,ensuring optimal perfomance without manual intervention.
Multi-cluster Shared Architecture:Allows multiple compute clusters to access the same data simultaneously,enabling high concurrecy without resource contention
Data Sharing:Secure and controlled sharing of live data bettween snowflake accounts and organizations
Zero-Copy Cloning:Provides the ability to create instant,virtual copies of data without physically duplicating it.
Security and Governance:End-to-end encryption,granular access cont


 







   


   
