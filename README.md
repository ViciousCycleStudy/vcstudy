# Dataset for ASPLOS 2023 Submission "Vicious Cycles in Distributed Systems"

The file [ASPLOS 23 Dataset.ods](<ASPLOS 23 Dataset.ods>) contains 24 vicious cycles from 14 open source systems studied in our paper.

Each line in the spreadsheet represents one vicious cycle case collected in our study (e.g., CASSANDRA-13441). Each column represents one characteristic of the vicious cycle. For example, "Failure recovery" in column B represents whether a vicious cycle happen in the failure recovery stage or not.

An "X" in the cell indicates that a vicious cycle have the corresponding characteristic. For example, an "X" in cell F5 indicates that the vicious cycle "CASSANDRA-13441" happens in the "System startup" stage. An "X" in cell P11 indicates that the vicious cycle "HDFS-12914" is triggered by a "Heavy workload".
