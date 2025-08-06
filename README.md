# Aging Balance Report using Excel and Power Query

This report aims to consolidate data from two sources — SAP and Salesforce — into a single, comprehensive report that is cleaned and transformed using Power Query.

The structure and columns of this report are inspired by a real Aging Balance Report; however, all data used here is AI-generated and entirely fictitious.

![Recording Excel GIF](https://github.com/user-attachments/assets/b169deed-8ae8-456b-8634-020ae20a6097)

# Power BI Dashboard

<img width="1399" height="783" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/86e0cd77-6dbf-4fa6-a205-727a6e0c7621" />

# Steps in Power Query

Key steps in the Power Query process include:

Creating overdue buckets based on the number of days an item is overdue.
Grouping rows by account, ensuring that all numeric columns are logically summed.
Merging data from both sources (SAP and Salesforce) into a unified dataset.

<img width="300" height="461" alt="Power Query1" src="https://github.com/user-attachments/assets/c9cf81ed-23ce-4258-a6f9-905b885bef40" />

# File Reference

| Name                          | File  | Description                              |
| :-------------                | :-----| :-------------------------               |
| `Aging Balance Report.xlsx`   | `XLSX`| The finished Excel report                |
| `Sample SAP invoice data.csv` | `CSV` | Sample data based on a SAP report        |
| `Sample SF data.csv`          | `CSV` | Sample data based on a Salesforce report |
