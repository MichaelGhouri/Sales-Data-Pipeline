# Sales Data Pipeline — n8n

An end-to-end **sales data automation pipeline** built with **n8n** to retrieve, transform, analyze, and generate reports from sales data.

## Workflow

```text
Get Sales Data
      ↓
Split Orders
      ↓
Calculate Order Totals
      ↓
      ├──→ Send Orders
      │
      └──→ Filter Delivered Orders
                    ↓
             Summarize by Region
                    ↓
             Update Field Names
                    ↓
              Send Analysis

Update Field Names
      ↓
Set Report Metadata
      ↓
Convert to CSV
      ↓
Send Final Report
```

## What It Does

* Retrieves sales data through a REST API
* Authenticates API requests using Header Auth
* Splits an orders array into individual records
* Calculates order totals dynamically
* Filters orders based on delivery status
* Generates regional sales summaries
* Aggregates processed data
* Generates a CSV report
* Sends processed data and reports through API endpoints

The workflow uses branching so the same sales data can support **operations, financial analysis, and management reporting**.

## Technologies

* **n8n**
* REST APIs
* HTTP Requests
* JSON
* Data Transformation
* Conditional Logic
* Data Aggregation
* CSV Generation

## Skills Demonstrated

**API Integration • Authentication • Data Transformation • Expressions • Branching • Filtering • Aggregation • File Generation • Workflow Automation**

## Workflow Preview

<img width="1296" height="424" alt="image" src="https://github.com/user-attachments/assets/2cfaf1c0-c4af-4639-9635-e7f2a109e4b9" />


## Author

**Michael Ghouri**
Software Engineering Graduate | AI & Automation Engineer

🔗 [GitHub](https://github.com/MichaelGhouri/Michael-Ghouri)
