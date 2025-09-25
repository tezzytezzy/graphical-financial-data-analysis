# 🔍 Graph Query Language (GQL) Explorations
Welcome to my repository showcasing the use of [**Kusto Query Language (KQL)**](https://learn.microsoft.com/en-us/kusto/query/?view=microsoft-fabric) as GQL for advanced financial data analysis. This project demonstrates how graph-driven queries can uncover hidden patterns and relationships in financial datasets.

## 🎬 Teaser
![](https://github.com/tezzytezzy/graphical-financial-data-analysis/blob/main/sample.gif)  
*A snapshot of a financial network graph showing asset ownerships*

## 🎯 Objective  
The graphical presentations in this repository address key financial intelligence use cases:

- 💸 **Financial Fraud Detection**
- 🕵️‍♂️ **Anti-Money Laundering (AML) Analysis**
- 🔁 **Transaction Pattern Analysis**
- 📊 **Risk Assessment & Credit Scoring**
- 🚨 **Suspicious Activity Monitoring**
- 🌐 **Financial Network Analysis**

## 📂 Repository Structure

The repository is organized into two main folders:

### 📜 Scripts/

Contains KQL scripts for querying and analyzing transaction data:

- 🧮 `account-ownerships.kql`  
  *Identifies account ownerships by individuals and companies.*

- 🔁 `transactions.kql`  
  *Tracks transactions between individuals and companies.*

- 📈 `timelined-transactions.kql`  
  *Generates a time-pivoted chart of individual-to-individual transactions.*

### 🎥 Video Demos/

Includes video walkthroughs of the scripts in action:

- 📽️ `account-ownerships.mp4`  
- 📽️ `timelined-transactions.mp4`
  

## 🚀 Getting Started

To use the scripts, ensure you have access to a KQL-compatible environment (e.g., Azure Data Explorer). Simply open the desired `.kql` file and run the query.

## 🛠️ Tools Used

- [Kusto.Explorer Installation and UI](https://learn.microsoft.com/en-us/kusto/tools/kusto-explorer?view=microsoft-fabric)
- [Azure Data Explorer Documentation](https://learn.microsoft.com/en-us/azure/data-explorer/)
- [Help cluster](https://learn.microsoft.com/en-us/azure/data-explorer/web-ui-samples-query)

## 📚 References

- [Graph Semantics Overview – Kusto](https://learn.microsoft.com/en-us/kusto/query/graph-semantics-overview?view=microsoft-fabric)
- [Best Practices for KQL Graph Semantics](https://kql.how/query/graph-operators/graph-best-practices/)
- [Analytical Queries on Graph Data and Neural Networks with KQL in Microsoft Fabric and Azure Data Explorer (ADX)](https://blog.n-dimensions.de/en/articles/kql/kql_graph)
