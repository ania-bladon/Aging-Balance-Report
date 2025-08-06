# Aging Balance Report using Excel and Power Query

This report aims to consolidate data from two sources — SAP and Salesforce — into a single, comprehensive report that is cleaned and transformed using Power Query.

The structure and columns of this report are inspired by a real Aging Balance Report; however, all data used here is AI-generated and entirely fictitious.

![Recording Excel GIF](https://github.com/user-attachments/assets/b169deed-8ae8-456b-8634-020ae20a6097)

# Steps in Power Query

Key steps in the Power Query process include:

Creating overdue buckets based on the number of days an item is overdue.
Grouping rows by account, ensuring that all numeric columns are logically summed.
Merging data from both sources (SAP and Salesforce) into a unified dataset.

<img width="294" height="453" alt="Power Query Steps Screenshot" src="https://github.com/user-attachments/assets/f167b521-b29c-49c1-9472-4da47d01bf16" />

# File Reference

| Name                          | File  | Description                              |
| :-------------                | :-----| :-------------------------               |
| `Aging Balance Report.xlsx`   | `XLSX`| The finished Excel report                |
| `Sample SAP invoice data.csv` | `CSV` | Sample data based on a SAP report        |
| `Sample SF data.csv`          | `CSV` | Sample data based on a Salesforce report |
