# Week 3 - Data Reporting & Analysis

### Reading
- [Learning Tableau](https://learning.oreilly.com/library/view/learning-tableau-2022/9781801072328/) Ch. 1 & 2
- https://learn.microsoft.com/en-us/training/modules/get-data/

### Watch
- https://www.tableau.com/learn/training

### Learning Outcomes
 - What is data reporting
 - Key tools for reporting

### What is Data Reporting?

Often know as `business intelligence (BI)` reporting, this is the process of generating reports or analyses, usually to assist business decision-making.

Reports can be tabular, summarizing the underlying data, or graphical. The process of generating graphical reports is called `data visualization`.

Reporting is largely independent of how data is stored (e.g. text files, spreadsheets, relational DB's, etc.)

BI reporting is an essential business function for more companies.

Historically much BI reporting depended on relational databases and often complex SQL queries. 

Recently, software tools have emerged that allow employees with limited technical skill to perform sophisticated data analysis.

### Key Data Reporting Tools

Many commercial and open-source tools exist for data reporting and it's not feasible to cover all of them here. A few more prominent tools are:

- [SAP Crystal Reports](https://www.sap.com/products/technology-platform/crystal-reports.html)
- [Microsoft SRSS](https://learn.microsoft.com/en-us/sql/reporting-services/tools/reporting-services-tools?view=sql-server-ver16)
- [Microsoft Power BI](https://powerbi.microsoft.com/en-us/what-is-power-bi/)
- [Tableau](https://www.tableau.com/why-tableau/what-is-tableau)

### Working with Tableau

- A **sheet** is a single data visualization, such as a bar chart or a line graph. Since sheet is also a generic term for any tab, we’ll often refer to a sheet as a view because it is a single view of the data.
- A **dashboard** is a presentation of any number of related views and other elements (such as text or images) arranged together as a cohesive whole to communicate a message to an audience. Dashboards are often designed to be interactive.
- A **story** is a collection of dashboards or single views that have been arranged to communicate a narrative from the data. Stories may also be interactive.

- **Measures** are values that are aggregated. For example, they are summed, averaged, or counted, or the result is the minimum or maximum value.
- **Dimensions** are values that determine the level of detail at which measures are aggregated. You can think of them as slicing the measures or creating groups into which the measures fit. The combination of dimensions used in the view defines the view’s basic level of detail.

**Relationaships** define SQL joins on related tables