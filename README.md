# ioops
**It's a metric used to measure the number of requests a system receives and processes per second.**

**EFFICIENT MANAGEMENT OF DISK THROUGHPUT IN DISTRIBUTED ARCHITECTURES**
* Author: 
* Published In : 
* Publication Date:
* E-ISSN:
* Impact Factor:
* Link:

**Abstract**:\
This paper investigates the impact of disk throughput on distributed systems like etcd, which rely on State Machine Replication (SMR) for consistency and fault tolerance. As node count increases, disk throughput declines due to the overhead of log replication and synchronization. The performance bottleneck, especially under high data mutation rates, significantly affects system responsiveness and reliability. To address this, the paper proposes optimizing disk throughput using a Write-Ahead Log (WAL) algorithm. The WAL approach improves data durability and replication efficiency, enhancing overall system performance.

**Key Contributions:** 
* **Algorithm Development** \
  Designed and optimized Write Ahaed Log disk throughput to improve input out operations.
* **Performance Comparison** \
  Conducted bench marking between State Machine Replication disk throughput and Write Ahead Log disk throughput.
* **Reserach Leadership**
  Led the research and technical implementation , focusing on advancing distributed database through algorithm innovation.

**Relevance & Real-World Impact**
* **Kubernetes infrastructure optimization:**\
    Enhances distributed key-value store performance by improving input and output operations.
* **Query Processing Improvement:** \
    need to add here
* **Academic Recognition :** \
    need to add here
* **Educational Impact:** \
    need to add here

**Experimental Results (Summary)**

| Cluster Size (Nodes) | SMR Disk Throughput (MB/s)| WAL Disk Throughput (MB/s) | Improvement (%) |
| ---------------------| ------------------------- | -------------------------- | ----------------|
| 3                    | 400                       | 800                        | 100.0           |
| 5                    | 375                       | 850                        | 126.7           |
| 7                    | 350                       | 900                        | 157.1           |
| 9                    | 325                       | 950                        | 192.3           |
| 11                   | 300                       | 1000                       | 233.3           |

**Citation**
* **OPTIMIZING INPUT OUT OPERATIONS BY IMPROVING THE DISK THROUGHPUT.**
*   Naveen Srikanth Pasupuleti
*   International Journal of
*   E-ISSN- 

**License**
* This reserach is shared for a academic and reserach purposes. For commercial use, please contact the author.

**Resources**
* IJFMR Site please 

**Author Contact** 
  * LinkedIn| Email:
