# Operations KPI
## Operational analytics using freight and traffic data

### Overview
This project builds a real operations KPI layer on container throughput data from the Port of Los Angeles.   Instead of using curated retail datasets, 
this project works with publicly available port throughput statistics to analyze supply-chain operations, congestion, and volume trends in a real logistical hub.

The emphasis is on:
- Data modeling
- SQL-driven KPI computation
- Imperfect operational data
- Decision-ready metrics
- Visualization in Power BI
  
### Business Problem

### Data Source
Port of Los Angeles – TEU Container Counts
Monthly and cumulative TEU (Twenty-Foot Equivalent Unit) figures for container throughput at the Port of Los Angeles. 

Key characteristics of the dataset:
- TEU counts by month and calendar/YTD totals
- Imported, exported, and empty container splits
- Annual historic TEU statistics available
- Publicly accessible CSV/JSON options for download

### Approach
- Data retrieval
- Data ingestion
- Schema design
- KPI computations
- Visualization
### Project Structure
sql/
  
  ddl/        → schema and table creation
  
  staging/    → raw data ingestion logic
  
  kpis/       → KPI and trend queries

reports/
  
  erd/        → schema diagrams
  
  insights/   → written observations and trends

powerbi/
  
  dashboards/ → visual dashboards and screenshots

### Insights

### Current Status

