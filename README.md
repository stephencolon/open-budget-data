# Open Budget Data
Source: [City of Philadelphia Budget Office of Budget and Program Evaluation](http://www.phila.gov/finance/units-BudgetProgram.html)

Please refer to FAQ section of the [Open Budget Application](http://cityofphiladelphia.github.io/open-budget) for information about the data. Note that in the application, `Class` is referred to as `Expense Type`.

Summary
--------------------------
Submitted on an annual basis, the operating budget is comprised of a consolidated budget of all the operating obligations of the City and presented by the Mayor to City Council for approval.  



Details
-----------------

| Attribute | Details |
| ---------- |--------------|
| Title | City Budget |
| Department | Office of Budget and Program Evaluation |
| Contact Name | Rebecca Rhynhart |
| Contact E-mail | Rebecca.Rhynhart@phila.gov |
| Contents | A proposal of future costs for the next fiscal year presented by the Mayor to City Council for approval. |
| Purpose | This data is useful for preparing and monitoring the annual operating budget for the City, providing periodic projections of the year end fund balance for the operating funds for the City. |
| Date Range | FY 2015 to FY 2016 |
| Format | CSV |
| Data Hygiene | 5 - Very High |
| Data Accuracy | 5 - Very High |
| Frequency	| Annually |
| Last Updated	| 3/5/2015 |


Field Descriptions
--------------------------

|Field|Description of Field|Type of Field|
|:----|:-------------------|:------------|
|Fiscal Year|The financial period for which the operating budget is relevant.|Text|
|Fund|An independent fiscal and accounting entity with a self-balancing set of accounts recording cash and/or other resources, together with all related liabilities, obligations, reserves and equities.|Text|
|Department|A division within city government responsible for carrying on specific activities or attaining certain objectives|Number|
|Class ID|Numeric identifier for expense class.|Number|
|Class|Expense category determined by the manner in which the monies are used.|Text|
|Total|Sum of each unique budget item by Fund, Department, and Class.|Currency|
