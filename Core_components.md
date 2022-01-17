## Identify the Core Components of Power Platform (15-20%)

### Business rules
You can create business rules and recommendations to apply logic and validations without writing code or creating plug-ins. Business rules provide a simple interface to implement and maintain fast-changing and commonly used rules.

Business rules defined for a table apply to both canvas apps and model-driven apps if the table is used in the app.

In a model-driven app to be used on mobile devices in a retail store. If you need to calculate the commission on a sale and the commission amount must be visible and 
updated immediately when the sales amount is entered. Then you can create a business rule to perform the calculation. 

A **calculated column** is only re-calculated when the form is saved, not when a column is changed. Thus, the commission calculation will not be displayed immediately but when 
the form is auto-saved up to 30 seconds later.

A **Power automate flow** will only run when the form is saved, not when a column is changed. Also, Power Automate flows execute asynchronously, so the user will need to refresh 
the form to see the commission calculation. 

A **rollup column** aggregates values from the child rows in a relationship. Rollup columns are only re-calculated every hour. 



