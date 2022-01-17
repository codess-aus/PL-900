## Identify the Core Components of Power Platform (15-20%)

### Business rules
You can create business rules and recommendations to apply logic and validations without writing code or creating plug-ins. Business rules provide a simple interface to implement and maintain fast-changing and commonly used rules.

Business rules defined for a table apply to both canvas apps and model-driven apps if the table is used in the app.

In a model-driven app to be used on mobile devices in a retail store. If you need to calculate the commission on a sale and the commission amount must be visible and 
updated immediately when the sales amount is entered. Then you can create a business rule to perform the calculation. 

You should use a **business rule** to validate data in Dataverse tables consistently between different apps. You can apply business rules to enable or hide columns, validate data, and show error messages without having to write code. A business rule can be composed of multiple conditions, involving multiple columns and tables. Business rules can be applied to the table level, ensuring that every app that uses this table complies with the rules. 

### Environments

You should use **environments** to separate apps that use development or production data. An environment manages and shares •pur business data, apps, and flows. Environments also serve as containers that separate apps that may have different security requirements or target audiences, like development and production environments that use different data. 

### Common Data Model

**Common Data Model (CDM)** The CDM is a standard and extensible collection of schemas, including entities, attributes and relationships that represent business concepts and activities with well-defined semantics. It consists of a set of standardized, extensible data schemas published by Microsoft and partners that facilitate data interoperability.

### Model Driven Apps

You can validate data and show error messages, set column values, enable or disable columns, and create business recommendations when pu are developing a model-driven app. You can use all actions available in business rules when you are developing a model-driven app. 

### Canvas Apps

You can validate data, show error messages, and set column values when you are developing a canvas app. Canvas apps can use almost all business rules actions, except show or hide columns, enable or disable columns, and create business recommendations.



A **calculated column** is only re-calculated when the form is saved, not when a column is changed. Thus, the commission calculation will not be displayed immediately but when 
the form is auto-saved up to 30 seconds later.

A **Power automate flow** will only run when the form is saved, not when a column is changed. Also, Power Automate flows execute asynchronously, so the user will need to refresh the form to see the commission calculation. 

A **rollup column** aggregates values from the child rows in a relationship. Rollup columns are only re-calculated every hour. 


You should use a **business process flow** to ensure that users input data and perform tasks in a specific order. 
In a business process flow you can define a set of stages and steps to be followed and what information a user needs to insert in order to advance to the next process step. 












