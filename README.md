# LinkedIn Connections: Graph Analysis

A network analysis of LinkedIn connections for 126 Sitare University students. Cleaned LinkedIn exports are modeled as a graph for path analysis and insights.

## Objective

- Clean raw LinkedIn CSV/XLSX files to a uniform structure.
- Construct a graph where:
  - Each student file is a node.
  - Each connection (via First/Last Name, Company) forms edges.
- Generate adjacency lists (28,474 unique keys).
- Compute random and pruned paths between students.

## Data

- 126 LinkedIn exports (.csv/.xlsx), each listing: First Name, Last Name, Company.
- After cleaning, each file is a node, contents are edges.

## Key Analysis

- **Path Statistics:**  
  - Total unique keys: 28,474  
  - Computed stats (count, min/max/avg path length)  
- **Top Companies:**  
  - HCLTech: 1,200  
  - Sitare: 1,155  
- **Most Connected Student:**  
  - Rohit Malviya: 4,670 connections  
- **Common Surnames:**  
  - Kumar, Singh

---
