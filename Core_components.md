## Identify the Core Components of Power Platform (15-20%)

### Business rules
You can create business rules and recommendations to apply logic and validations without writing code or creating plug-ins. Business rules provide a simple interface to implement and maintain fast-changing and commonly used rules.

Business rules defined for a table apply to both canvas apps and model-driven apps if the table is used in the app.

In a model-driven app to be used on mobile devices in a retail store. If you need to calculate the commission on a sale and the commission amount must be visible and 
updated immediately when the sales amount is entered. Then you can create a business rule to perform the calculation. 

You should use a **business rule** to validate data in Dataverse tables consistently between different apps. You can apply business rules to enable or hide columns, validate data, and show error messages without having to write code. A business rule can be composed of multiple conditions, involving multiple columns and tables. Business rules can be applied to the table level, ensuring that every app that uses this table complies with the rules. 

### Environments

You should use **environments** to separate apps that use development or production data. An environment manages and shares •pur business data, apps, and flows. Environments also serve as containers that separate apps that may have different security requirements or target audiences, like development and production environments that use different data. 

You do not need to configure at least one Microsoft Dataverse database in each environment. You can create an environment without a Dataverse database, and create it in the future if necessary. 
You can create an environment in different regions on the same tenant to meet compliance requirements. When you create an environment, you need to select a region to provision this environment. All internal Power Platform resources are provisioned in this region, respecting the region's boundary requirements. 
You can configure different roles for a user in different environments. You can assign the Environment Admin or the Environment Maker role for a user in each environment. For example, you can create two environments named Test and Production. In the Test environment you can assign the Environment Admin role for User A, and in the Production environment, you can assign the Environment Maker role for User A.


### Common Data Model

**Common Data Model (CDM)** The CDM is a standard and extensible collection of schemas, including entities, attributes and relationships that represent business concepts and activities with well-defined semantics. It consists of a set of standardized, extensible data schemas published by Microsoft and partners that facilitate data interoperability.

### Microsoft Dataverse

Dataverse is used to store and manage data used by business applications. 
The data is stored within a set of entities. 
Dataverse uses the CDM to provide a set of standardized entities used by your applications. 

You can control access to data at organizational level when table ownership is set to organization owned. 
You can create a business rule to apply business logic and validation rules. 
You cannot change the ownership of a custom table. Once the custom table is created and ownership is set, you are not allowed to change the ownership. You need to create a new custom table in order to change table ownership. 


### Dynamics 365 Business Central. 

This is an end-to-end solution for finance, sales, services, and operations for small and mid-sized companies. 

### Business process flow 
This is a type of Power Automate flow that configures a set of steps to be followed by users, resulting in a standard business process. 
For example, you might need a business process flow to handle customer service requests similarly. 
You should use a **business process flow** to ensure that users input data and perform tasks in a specific order. 
In a business process flow you can define a set of stages and steps to be followed and what information a user needs to insert in order to advance to the next process step. 

### Model Driven Apps

You can validate data and show error messages, set column values, enable or disable columns, and create business recommendations when pu are developing a model-driven app. You can use all actions available in business rules when you are developing a model-driven app. 

You cannot create a business rule on a table to show or hide specific columns for canvas apps. You can create a business rule on a table to show or hide specific columns for only model-driven apps. 

### Canvas Apps

You can validate data, show error messages, and set column values when you are developing a canvas app. Canvas apps can use almost all business rules actions, except show or hide columns, enable or disable columns, and create business recommendations.

You can create business rules on tables to validate data and show error messages for both canvas and model-driven apps. 

You can create a business rule on a table to set or clear specific column values for both canvas and model-driven apps. 



A **calculated column** is only re-calculated when the form is saved, not when a column is changed. Thus, the commission calculation will not be displayed immediately but when 
the form is auto-saved up to 30 seconds later.

A **Power automate flow** will only run when the form is saved, not when a column is changed. Also, Power Automate flows execute asynchronously, so the user will need to refresh the form to see the commission calculation. 

A **rollup column** aggregates values from the child rows in a relationship. Rollup columns are only re-calculated every hour. 















