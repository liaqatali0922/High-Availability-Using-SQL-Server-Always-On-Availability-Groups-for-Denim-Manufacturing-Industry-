This project implements a high availability and disaster recovery solution using SQL Server 
Always On Availability Groups (AG) for a Garment Manufacturing (Denim) enterprise system. 

The solution ensures: 
1. Continuous database availability  
2. Automatic failover  
3. Data redundancy across nodes  
4. Zero/minimal downtime for production systems
   
This Invloves three nodes configutation in which are working in sync mode and one is for disaster recovery and working in asynch mode.

Problem Statement 
In denim manufacturing environments: 
1.  Production runs 24/7  
2.  System downtime causes financial loss and production delays  
3.  Single SQL Server instances create single point of failure  
4.  Reporting and operational load affects performance
   
A highly available, fault-tolerant system is required. 

Solution 
Implemented: 
1. Windows Server Failover Cluster (WSFC) 
2. SQL Server Always On Availability Groups 
3. Multi-node synchronous & asynchronous replication 
