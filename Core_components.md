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

A **default environment** is automatically created in each Power Platform tenant. Users are automatically added to the Maker role in the default environment. All users can create apps in the default environment. 

Flows do not need to be in the default environment to access Offce 365 services. All environments can access Offce 365. The default environment is used, for example, if you create a canvas app or a flow from within a SharePoint list.

Production, Sandbox or Trial environments: Users will need to be added to the environments of these types directly or via security groups. 

The **Environment Admin** role to administer an environment without a database. When there is no database in an environment, the Environment Admin role manages the environment and can add Environment Makers. If an environment has a Microsoft Dataverse database, security roles in the Dataverse database take over environment security. 

The **Environment Maker** role permits users to create apps in the environment. 

The **Basic User** role gives access to data in a Dataverse database. 

The **Power Platform admin** role is for creating environments. 

The **CDM** consists of a set of standardized schemas that can be used to build business applications and analytics. The CDM contains entities, attributes, relationships and importantly metadata. 

**Dataverse** is a database that implements the schemas in the CDM. The CDM is designed to be product agnostic. The CDM is already supported in the Dataverse, Dynamics 365, PowerApps, Power 81, and soon by Azure data services. 

The **Open Data Initiative**. The CDM is evolving as part of the Open Data Initiative, a jointly-developed vision by Microsoft, Adobe, and SAP. 

**Standard Entities** are the entities in a Dataverse database that have been created using the schemas in the CDM. 


### Common Data Model

**Common Data Model (CDM)** The CDM is a standard and extensible collection of schemas, including entities, attributes and relationships that represent business concepts and activities with well-defined semantics. It consists of a set of standardized, extensible data schemas published by Microsoft and partners that facilitate data interoperability.

### Microsoft Dataverse

Dataverse is used to store and manage data used by business applications. 
The data is stored within a set of entities. 
Dataverse uses the CDM to provide a set of standardized entities used by your applications. 

You can control access to data at organizational level when table ownership is set to organization owned. 
You can create a business rule to apply business logic and validation rules. 
You cannot change the ownership of a custom table. Once the custom table is created and ownership is set, you are not allowed to change the ownership. You need to create a new custom table in order to change table ownership. 

You should use a **table** to store all the return requests and their details as rows. You can use a table to model the return request details in columns and create relationships with other tables in Dataverse. Each return request is saved as a row in the table. 
You should use a **column** to generate a sequential numeric identifier for the return request. You can use a column with the AutoNumber type to generate a sequential nurneric identifier with an optional prefix like the current date. 
You should use a **relationship** to relate the return request with a sales order. You can use a One-to-many relationship to relate the return request with the corresponding row in the sales order table. 



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

### Unmanaged Solutions
You can only add existing compn)nents to an unmanaged solution. You cannot add or remove compnonents from a managed solution. 

To allow other app makers to make changes to your components including your app, you must export the solution as an unmanaged solution. 
The solution can then be imported into their environment and the compnonents can be changed. 

You have a new Power Platform environment You create an app and several other convnents, including tables, in the Power Apps Maker portal outside of a solution. To transport the components to another environment you must add the components to an unmanaged solution and export the solution. You can export an unmanaged solution to transport your components to another environment. 

### Managed Solutions
To prevent other app makers from making changes to your components including your app, you must export the solution as a managed solution. 
When a managed solution is imported, the solution cannot be edited.

You cannot add components to a managed solution or edit compnonents in a managed solution. You cannot export a managed solution.

### Triggers 
Triggers are supported by Power Automate only. You need a trigger to start a flow You can configure a time based trigger, which runs in a schedule, or an event based trigger, like receiving an email. 

You should use a trigger to cause your flow to run. Triggers are either event-based, for example a data change, time-based, for example recurrence every hour, or instant, for example an instant flow. The trigger causes the flow to start. Each connector defines the triggers it supports. When creating a flow, the first thing you define is the connector and its trigger. 


You should classify the When a blob is added or modified operation as a trigger. Triggers are operations that can start a Power Automate flow You can configure a time-based trigger, which runs in a schedule, or an event-based trigger, like receiving an email.

### Actions
Actions are supported by Power Apps and Power Automate. An action can be initiated by a trigger or by user input. An action executes functions that interact with your data source. For example, you can start an action to send an email in your workflow, or you can initiate an action to create a purchase order by clicking on the Submit button in your app. 

You should use actions to get items from your SharePoint list. Actions are operations performed on a connector. Connectors are either tabular or function-based. Each connector defines the actions it supports. With a tabular connector such a SharePoint list, there are actions that create, read, update and delete items as well as run a query to get a list of items. 

You should classify the Get blob content, Get blob metadata, and Create blob operations as actions. Actions are operations that are used to interact with a service by some function. You can use an action to send an email or create a blob in Azure Blob Storage. 

A **calculated column** is only re-calculated when the form is saved, not when a column is changed. Thus, the commission calculation will not be displayed immediately but when 
the form is auto-saved up to 30 seconds later.

A **Power automate flow** will only run when the form is saved, not when a column is changed. Also, Power Automate flows execute asynchronously, so the user will need to refresh the form to see the commission calculation. 

A **rollup column** aggregates values from the child rows in a relationship. Rollup columns are only re-calculated every hour. 

You cannot export the **Default Solution**. The Default Solution contains all compnonents in an environment. The export option is disabled when you select the Default 
Solution. 

You should not export the **Common Data Service Default Solution**. All metadata components, such as tables, created outside of a solution are automatically added to the Common Data Service Default Solution. However, apps are not added automatically to this solution. The Common Data Service Default Solution will not contain all the components that need to be exported. 

### Connectors
You should use the Dynamics 365 for Fin and Ops connector to update the sales order. You can use this connector to update an existing data record for a data entity in Dynamics 365 Finance and Operations. 

You should use a custom connector to request freight estimation. Power Automate offers more than two hundred built-in connectors for Microsoft and non-Microsoft products and services. If the service you want to integrate does not have a built-in connector, you can create and share a custom connector. 

You should use a custom connector to connect to a publicly available APL Custom connectors are created when there is no existing pre-built connector available. When defining a custom connector, you specify the triggers and actions by mapping onto the API functions. 

You do not need to create a custom connector to access an external data source. There are over 300 connectors that can be used to connect to data sources from Microsoft Offce 365, Dynamics 365, Azure, and third-party services. You only need to create a custom connector if there is no prebuilt connector. 

You should use a custom connector to connect to the external data source. You need to create a custom connector and provide API credentials so it can authenticate your connection if there is not one available.

You can build a custom connector for Power Automate and reuse the same connector for Power Apps. 
You can build a custom connector for the custom services once and use the same connector in Power Apps, Power Automate and Azure Logic App. 

You can build and use a custom connector without a certification from Microsoft. You can build and share a custom connector in your organization without a certification from Microsoft 

You cannot publish a custom connector as a public connector without a certification from Microsoft. You need to submit your custom connector to Microsoft to certify it before making it available to the public. 

SharePoint connectors are used to connect with SharePoint lists. 

**Logic apps** are used to automate tasks, workflows, and business processes. 

You should not use the Dynamics 365 Sales Insights connector. Dynamics 365 Sales Insights empowers sellers to deliver personalized engagement for customers using Al-driven insights. You cannot use this connector to update sales orders. 

You should not use a premium connector. Connectors can be standard, premium or custom. Premium and custom connectors require additional licensing. Offce 365 connectors such as SharePoint are standard connectors. 



You do not need to open inbound firewall ports to access an on-premises SQL server. Installing the on- premises data gateway enables on-premises databases to trigger flows and Power Apps to read and write data.


Example Power Platform solution: 
* The company needs to scan invoice data in Power Platform apps. 
* You need to use Al guilder to implement the solution. 
Which four actions should you perform in sequence? 

1. Build a form processing model in Al guilder. 
2. Train the model with invoice samples. 
3. Publish the model. 
4. use the model in Power Apps. 

You should build a form processing model in Al Builder. You can use different Al model types in Al guilder depending on your business needs. In this case, you should build a form processing Al model to extract information from the scanned invoices. 

You should train the model with invoice samples. The train step prepares a model that extracts the desired information. You should provide five invoices to train your model, selecting the fields that you need to extract the data from. 

You should then publish the model. After you train the model, you have to publish it to make it available for Power Apps or Power Automate. 

Finally, pu should use the model in Power Apps. You can use the form processor control component to scan the invoice and read the data that you need to extract. 

### AI Builder

You can perform sentiment analysis for tweets about your brand. You can use the prebuilt Sentiment analysis model of Al guilder to determine the sentiment for a tweet. 
You can categorize tweets as positive, negative, neutral, or mixed and take actions based on that analysis. 
This model can be implemented in a Power Automate flow to automate the tweet analysis. 

You can detect and tag your products in Instagram posts. You can use the object detection model to recognize pur products in images posted on Instagram after you train your model with images of your products. 

You can predict if a customer Will buy a product based on historical data. You can use the prediction model to analyze patterns in your historical data and predict an outcome for new data. This model can address business questions with available options, like yes or no, go or no go, pass or fail and true or false. 






