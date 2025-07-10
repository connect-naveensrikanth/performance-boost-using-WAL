# Efficient Management of Disk Throughput in Distributed Architectures
* Author: Naveen Srikanth Pasupuleti
* Published In : International Journal of Intelligent Systems and Applications in Engineering (IJISAE)
* Publication Date: Feb 2021
* E-ISSN: 2147-6799
* Impact Factor: 
* Link: [Read the paper](https://ijisae.org/index.php/IJISAE/article/view/7608/6625)
---
## 📌 **Abstract**:
This paper investigates the impact of disk throughput on distributed systems like etcd, which rely on State Machine Replication (SMR) for consistency and fault tolerance. As node count increases, disk throughput declines due to the overhead of log replication and synchronization. The performance bottleneck, especially under high data mutation rates, significantly affects system responsiveness and reliability. To address this, the paper proposes optimizing disk throughput using a Write-Ahead Log (WAL) algorithm. The WAL approach improves data durability and replication efficiency, enhancing overall system performance.

**IOOPS**:\
Input/output (I/O) operations are the fundamental way computers receive data and send results.

**Key Contributions:** 
* **Algorithm Development** \
  Designed and optimized Write Ahead Log disk throughput to improve input out operations.
* **Performance Comparison** \
  Conducted bench marking between State Machine Replication disk throughput and Write Ahead Log disk throughput.
* **Research Leadership**
  Led the research and technical implementation , focusing on advancing distributed database through algorithm innovation.

**Relevance & Real-World Impact**
* **WAL-based storage optimization:**\
Improves write-heavy workload performance in distributed systems by leveraging efficient sequential write operations, resulting in enhanced disk throughput and scalable performance as the number of nodes increases.

* **Query processing improvement:**\
Minimizes read-write contention and supports rapid data recovery, enabling faster and more predictable query execution during peak loads and cluster transitions.

* **Resource management:**\
Maximizes disk I/O utilization and reduces unnecessary write amplification, ensuring better use of system resources in environments with high data ingestion rates.

* **Failure recovery:**\
Supports rapid recovery and data integrity through durable write logging, reducing recovery time objectives (RTO) and ensuring consistency after node crashes or unexpected shutdowns.

* **Replication efficiency:**\
Facilitates consistent replication by preserving write order and reducing state divergence across replicas, making it well-suited for distributed databases and fault-tolerant architectures.

* **Academic Recognition :** \
    Covered in academic publications and technical literature addressing enhancements in DNS resolution and efficiency optimization within ETCD systems.
* **Educational Impact:** \
    Embedded in academic initiatives, contributing to ongoing scholarly exploration of workload automation and performance optimization in cloud-native environments.

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
*   International Journal of Intelligent Systems and Applications in Engineering
*   E-ISSN-2147-6799

**License**
* This research is shared for academic and research purposes. For commercial use, please contact the author.

**Resources**
* [IJISAE Website](https://ijisae.org/index.php/IJISAE)

**Author Contact** 
  * LinkedIn: https://www.linkedin.com/in/naveensrikanth  |  Email: connect.naveensrikanth@gmail.com
