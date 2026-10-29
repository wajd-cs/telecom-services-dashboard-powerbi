<p align="center"><img src="images/dashboard.png" width="800" alt="Telecom Services Dashboard"></p>

<p align="center">
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black" alt="Power BI">
<img src="https://img.shields.io/badge/DAX-Measures-blue" alt="DAX">
<img src="https://img.shields.io/badge/Power%20Query-Data%20Cleaning-green" alt="Power Query">
<img src="https://img.shields.io/badge/Domain-Telecom-purple" alt="Domain">
<img src="https://img.shields.io/badge/Language-Arabic-orange" alt="Language">
</p>

## About Telecom Services Dashboard

Telecom Services Dashboard is an interactive Power BI report that analyzes the performance of a telecom company in a single page. It brings together revenue, billing and collection, customers, and customer-support data so that decision makers can quickly answer questions such as:

- Which branches and service types generate the most revenue?
- What is the collection rate, and how much is still unpaid or overdue?
- How are customers distributed across cities, and who are the top-billed customers?
- How satisfied are customers, how fast are complaints resolved, and which support channels are used most?

The dashboard is fully in Arabic and can be filtered by **city** and **customer type**.

## Key Metrics

The dashboard tracks the following KPIs:

- **Total Revenue**
- **Uncollected Amounts**
- **Active Customers**
- **Number of Complaints**
- **Satisfaction Rate**
- **Collection Rate**
- **Overdue & Unpaid Invoices**
- **Churn Rate**

## Visualizations

- Revenue by branch
- Revenue distribution by service type
- Average bill vs. average plan fee per plan
- Customers by city
- Top customers by billing
- Support requests by contact channel
- Request handling speed (average resolution time in hours over time)

## Data Model

The report is built on the following tables, connected through relationships in Power BI:

| Table | Description |
|---|---|
| Customers | Customer details: city, customer type, status |
| Usage & Billing | Invoices, revenue and payment status |
| Plans | Plans, service type and plan fees |
| Branches | Company branches |
| Complaints | Tickets, contact channel, resolution time and satisfaction |

## Tools & Skills

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) for building the report.
- [Power Query](https://learn.microsoft.com/power-query/) for cleaning and preparing the data.
- Data modeling and table relationships.
- [DAX](https://learn.microsoft.com/dax/) for calculating the KPIs.
- Interactive dashboard design in Arabic.

## Getting Started

Clone the repository and open the report with Power BI Desktop (free):

```bash
git clone https://github.com/wajd-cs/telecom-services-dashboard-powerbi.git
```

Then open `telecom_services_dashboard.pbix` in Power BI Desktop.

## Author

This project was built by **Wajd Alluhaibi** as part of her data analysis portfolio. Feel free to connect on [LinkedIn](https://www.linkedin.com/in/wajd-al-luhaibi-9194a1396) or check out more projects on [GitHub](https://github.com/wajd-cs).

## License

This project is shared for educational and portfolio purposes.
