# Demonstrate the capabilities of Power Apps (15-20%)

If you create a model-driven app and share the app with users but find users cannot access the app. You need to enable users to access the app by assigning a **security role** to the users. This is not the same as adding the users to a Security Group. **Security groups** are used in Power Platform to enable access to environments. They are not used to give access to individual apps. 

## Canvas app: 
Simple apps with a highly customizable user interface layout. A canvas app lets you have complete control over the app layout. It also allows you to drag and drop elements to a 
canvas and use expressions to specify simple logic. 

You should use a Power Apps canvas app to create a customized layout app for your company to schedule internal meetings in M365. A canvas app lets you choose the layout and add key business functionalities. 

You should use canvas apps for highly customizable layouts. Canvas apps provide full control over user interface and how screens can interact with each other. 

**Create a canvas app from data**: This creates an app with a browse, detail, and entry/edit screen using your data. 

**Create a canvas app from scratch**: You will need to develop all screens. This is not the quickest way to create an app. 

**Create an app from a template**: Template apps are used for specific scenarios like budgeting and employee management 

### Functions

Here are some common functions and an explanation of what they do:

* Filter - This function is often used with galleries or tables of data to narrow down the rows returned from your data source. You do this by specifying one or more columns in your data set to perform a logic test on, which will allow you to return data that falls in a certain date range, has a set value, or was created by the user for example.
* Match - This function allows you to check a value to see if it follows a given pattern. You can use this to check if the user entered a properly formatted email address and, if they did not, show them a warning that a valid email is required. This function serves well for conditional formatting.
* Distinct - This function allows you to return the unique values from a list of data, making it easier to build dynamic dropdowns that show users only the valid values for the given column.
* Math functions - Power Apps includes a range of math formulas for working with your data from the simple such as Sum or Average to the complex such as Atan and Sin to work with radians.


## Model-driven app 
Complex business process apps with simple user interfaces. Model-driven apps can automatically generate the application layout for your business data and processes stored 
in Microsoft Dataverse. You create a model-driven app by modelling the necessary business data your app needs to define a consistent business process. 

Model-driven app design is a component-focused approach to app development. Model-driven app design does not require code, and the apps you make can be simple or very complex. Unlike canvas app development, where the designer has complete control over app layout, much of the layout is determined for you with model-driven apps and largely designated by the components you add to the app.

Model-driven apps have three design phases:
* Model your business data
* Define your business processes
* Build the app

Model-driven apps let pu design critical business apps by allowing you to write complex business logic inside. 

Each table also contains four assets:
* Forms – Defining how users will see and interact with the data
* Views – A list view of the rows for each table
* Charts - Showing the data in a meaningful, visual representation
* Dashboards – Providing an insightful, graphical overview of the data

You should not use a model-driven app because you need to design an app with a customized layout. MDA design is mostly controlled by the business processes chosen.

Model-driven apps are created using the App Designer. You will choose the entities, dashboards, business process flows, forms, and other components that you want to make available in your app, and then the app will be created for you. This means you will need to spend more time understanding what your user needs than how it is going to look.

You can embed a canvas app in a model-driven app. You can design and create custom layouts using the canvas app designer and embed these apps in a model-driven app. An embedded canvas app includes rich data integration capabilities between the contextual data from the model-driven app form with the embedded canvas app. 

You should use Power BI to build reports in a model-driven app. You can embed Power BI reports to bring rich reporting and analytics to your model-driven app forms. This is an optional feature that you need to enable in your organization before using it. 

You can use one or more tables as a data source per model-driven app. You can use multiple tables, columns and relationships from Dataverse while designing your model-driven app. You are not limited to a single table per app. 

You should use model-driven apps for implementing complex business logic. Model-driven apps take care of the user interface part, so you only need to focus on business rules, forms, and views. 

You can add forms for tables to a model-driven app. When you add a table to a model-driven app, all forms are automatically added as table assets. 
You can add and remove forms from the app. 

You can also add business process flows to a model-driven app. Business process flows are associated with a table and can be included with, or excluded from, an app. 

You cannot add business rules to an app. Business rules are included automatically if the table or form they are associated with are added to the app, but you cannot add or remove business rules directly. 

You cannot add Power Automate cloud flows to a model-driven app. Power Automate cloud flows are not associated with user interface compn)nents that are part of an app.

### Business Logic
When incorporating business logic in your app, there are two primary options available. You can set Business Rules on your Microsoft Dataverse tables or you can build Business Process Flows.

With **Business Rules**, you will define behaviors at the data layer. This is great for setting conditions for when a field is required, setting a default value, or even showing or hiding a field based on criteria. An example could be a table for tracking expenses. You could have a column for type of travel and then build a business rule that dictates that if a user chooses automobile then the mileage field is required, else it is optional. This gives you the power to make sure you maintain data consistency in all scenarios.

**Business process flows** are used to guide users through using your app. These workflows can provide visuals on next steps based on the status of the data and facilitate other actions that you want to occur as the user uses the app. Business Process Flows let you bring automation to your app and make it more of a guided experience than just a place to enter data.


### Controls:

**Combo box control** This control allows you to display a list and search for items. The search is performed in the server so performance is not affected by very large data sources. 

**List box control**. This control displays all items from the list in the user screen. You cannot search for items with this control and the screen scroll size will expand significantly. 

You should use a list box control to allow the users to choose multiple predefined categories. This control displays a list of categories in which the user can select one or multiple items. 

You should use the List Box control to show all the information from a data source. To show the selected information, you need to edit the properties. 

A **Data Table control** shows information in a matrix format like rows and columns. 

You should use the **Add picture control** to allow taking full resolution photos and update them to a data source.

You should use an add picture control to upload a product picture from a mobile device. This control allows users to take pictures from their device or upload image files to update the product data source. 

**Drop down control**. This control can conserve the screen scroll size, displaying only the selected item. However, you cannot search for items with this control and all data 
sources are loaded at once, resulting in a potential low performance. 

These controls can be used to select a single item from a list You should allow the users to choose multiple predefined categories. 

**Radio control**. This control is best used with only a few items. You cannot search for items with this control and the screen scroll size Will expand significantly if you display more than two hundred items. 

These controls can be used to select a single item from a list You should allow the users to choose multiple predefined categories. 

**Form control** to create, view and edit records. If you add a display form control, the user can display the fields for a record. If you add an edit form control, the user can edit those fields, create a record, and save those changes to a data source. 

You should use the Edit form control to display, add, and update records. The edit form control can be used to edit the selected record or create a new record or for display purposes as well. 

**Gallery control** to display a list of records. A gallery control can filter, sort, search, and scroll through a set of records from a data source. 
You should use the Gallery control to show the image of an employee, their name, and department information. 

You should use a gallery control to show a list of manufactured products. This control type shows multiple records from a data source, like a product list. 

**Image control**: This control displays an image in the app. It does not upload a product picture. 

**Screen control**: This is a container for other controls and can have an image in the background. 

**Card control**. The card control is used within a form and handles the display and editing for a single field. 

**Button control**. Button controls allow the user to click and interact with the app. When selected, a button will perform an action. 

**Icon control**. Icon controls are similar to buttons. Icon controls allow the user to click and interact with the app. When selected, an icon will perform an action. 

**Shape control**. Shape controls are geometric shapes and symbols that can work in a similar manner to buttons. Shape controls allow the user to click and interact with the app. When selected, a shape will perform an action.

PCF controls are developed using Typescript and HTML and require developer skills to create and maintain. PCF controls are visual, re-usable compnonents that can be used by many apps. 


## Components

**Components** are re-usable controls built using the same skills as canvas apps. The skills required to create compnonents are the same as for creating canvas apps. 
Components are custom controls that can be re-used within an app. 

Components are re-usable controls built using the same skills as canvas apps. Changes made to components are automatically updated on apps using that component. The skills 
required to create compnonents are the same as for creating apps. 

**Component libraries** contain custom controls that can be reused across apps. Component libraries can be shared with other app makers. If a compnonent in a library is updated, the other app makers who are using the library are notified that there is an update available for the component. 

Power Apps Component Framework **(PCF) code component** are created by developers using Typescript and HTML. PCF controls are visual, re-usable compnonents that can be used in canvas and model-driven apps. 

**Text component** to display a simple message. This component displays a text message on your website. You can configure the text color, size and alignment. 

**Breadcrumb component** to allow users to establish where they are in the webpage hierarchy. 
This component uses the page navigation hierarchy to display the parent pages of the webpage. 
Users can navigate through the website using these breadcrumbs. 

**List component** to enumerate records in the Leads table. This component can render a list of rows stored in the Leads table without the need to write code. You can configure actions to interact with these rows, like adding a new row, viewing or editing details and deleting a row. 

**Form component** to receive user input and persist it in the Leads table. This component can render model-driven forms designed in the Dataverse table. You can configure the form component to insert new rows in the table, edit a row or a read-only form. 

**IFrame component** You can use this component to display an external website URL inside your webpage.

**Custom connectors** are used to connect to data sources where there is no pre-built connector. Custom connectors have no impact on the look and feel of the app.


## Dataverse 
To create a business process flow, you need to select a Dataverse table where the process Will be based. You cannot create a business process flow in an environment without 
a Dataverse database. 

You can use Dataverse to store business data used by your applications. The data is organized as tables. A table is a set of rows used to store data. 

Power Apps portals can only show data that is held in Microsoft Dataverse. Data in an Azure SQL database Will not be viewable in a portal. 

In Power App portals, all customer logins are associated with a contact row in Dataverse

## Power Apps Portal

You should use Power Apps portals to create a website for external customers. You can configure authentication so that customers can log in to the portal and view their data. 

You should not use a Power Apps portal. Power Apps portals are used for creating customer facing external websites.

You should use Power Apps portals for a customer facing website. Power Apps portals allow you to create a customer engagement website using pre-built templates.

## Data gateway. 
A data gateway works as a bridge to provide secure data transfer between on-premises data and Power Apps or other Power Platform services, like Power 81, Power Automate, Azure 
Analysis Services, and Azure Logic Apps. You need to install and configure the data gateway software on a machine in your on-premises network to access the data in your Oracle on-premises database. 

## Data source: 
You can use a data source to access external data stored in cloud services, like OneDrive for Business or SharePoint.

## AppSource: 
You can use AppSource to distribute and publish apps for Power Platform and Dynamics 365 to a broader audience.

## Portal Templates:
**Portal template**: A portal template is used when creating the portal site, and each template has a set of pre-configured web pages and other components.

### Starter portal template: 
The starter portal template is the only portal template that is available with a Microsoft Dataverse environment when you do not have any Dynamics 365 apps installed in your environment. The starter portal template is used when you choose the Portal from blank window 

### Customer self-service: 
These templates are only available when a Dynamics 365 app is installed in your Microsoft Dataverse environment.
Profile management can only be done through the customer or employee self-service portal.
You should not use a customer self-service portal. Customer self-service portals allow customers to access self-service knowledge, provide feedback, and open support cases.
Customer self-service portals allow customers to access self-service knowledge, provide feedback, and open support cases. You can use faceted search in this template by using filters based on the knowledge base contents. 

### Employee self-service:
These templates are only available when a Dynamics 365 app is installed in your Microsoft Dataverse environment.
Profile management can only be done through the customer or employee self-service portal.
In this portal template, employees can perform common tasks and manage contents and knowledge for internal audiences, like internal procedures. 
In this portal template, employees can perform common tasks and manage contents and knowledge for internal audiences. 
You can use faceted search in this template by using common filters based on the knowledge base contents. 

### Partner Portal:
These templates are only available when a Dynamics 365 app is installed in your Microsoft Dataverse environment.
Partners can share and maintain knowledge through the partner portal. 
The partner portal template allows partners to access a shared knowledge base. 
Partner portals are used by company partners, like resellers, distributors, and suppliers to collaborate and have real-time access to shared activities. 
Partner portals are used by company partners, like resellers, distributors, and suppliers to collaborate and have real-time access to shared activities. 
You cannot use faceted search in this template.

### Community Portal:
Customers can provide feedback and comments through the community portal. 
Community portal templates allow customers to interact with others as well as to provide feedback, comments, and ratings. 
Community portals allow interaction between customers and specialists using knowledge base articles, forums, and blogs. 
You cannot use faceted search in this template even if you have knowledge base articles in this portal. 

**Table lists** are used in Power Apps portals to define the Dataverse data displayed in the portal as a list of rows in a table. 

**Page templates** provide the means to create a consistent look and feel in the portal website. 
Page templates are built using ASP_NET pages, master pages, cascading style sheets (CSS), user controls, and server controls. 

**Content snippets** are small pieces of reusable content that can be placed within web templates. The header is a content snippet that •pu can edit and add logo and text that appears on each page in the portal. 

**Web pages**: A web page is an individual page in the portal website. A web page uses a page template to define its look and feel. 

**Webpage access rules** define which pages are visible to a web role. Users are associated with a web role. 
The webpage access control rules that are defined for a web role specify the pages a user can access when the user logs in and authenticates their user

**Website access permissions** define the editing permissions that a web role has in the front-end to change content such as content snippets. 
Website access permissions are not provided to ordinary users of the portal but to users to edit content contained in the portal pages. 

**Table permissions** define what access a web role has to individual Dataverse tables. Table permissions allow users to read, create, and update data rows in Dataverse from within a portal page. 

**Subarea**: A subarea contains the individual navigation items in a model-driven app that select tables and dashboards. 
You can add the table as a subarea

**Area: Areas are the top-level groups in a model-driven app navigation. 
You can only add groups to an area. 
You cannot add a table as an area.

**Assets**: Assets are the forms, views, charts, and dashboards for a table that are included in the model-driven app. 
You cannot not add a table as an asset.

**Groups**: Groups simply group navigation items under the group heading in the model-driven app navigation pane. 
You can only add subareas to a group. 
You cannot add the table as a group. 

**Views** define how a list of rows for a table are displayed in a model-driven app. 
A view defines the columns and their order, how the data is sorted, and includes a query to filter the data. 

**Forms** contain the columns for a table to allow a row from that table to be created and edited. 


**The sitemap** is the application-level navigation configuration for a model-driven app. 
Dashboards and tables are added to the sitemap and appear on the left-hand side of the model-driven web app. 

A **dashboard** contains components from multiple different tables. A dashboard can contain lists (views) and charts. 

## Dashboard. 

A dashboard is a Power BI compnonent that displays a single page with interactive visuals, text, and graphics. You can customize the dashboard interface layout, but you cannot interact with a dashboard as an application. 

## Power Automate Flow
You should not use a Power Automate flow Power Automate helps pu to automate workflows like approvals or repetitive tasks. 

Example:
Your IT department manages inventory using a SharePoint list. IT workers have access to the inventory on an intranet website. 
You need to create a mobile app through which users can initiate inventory requests. Users must also be able to manage their requests by using the SharePoint list. 
Which two actions should you perform to create the mobile app? Each correct answer presents part of the solution.

* You should create the mobile app using a Power Apps canvas app. Canvas app lets you customize the layout of your app. 
* You should also create a Power Apps form and connect it to the SharePoint list by using a connector. By connecting your form to SharePoint list, you can add/edit entries. 

You should not create a Power Apps model-driven app. Model-driven apps are used for Dataverse data. 
You should not create a Power Apps portal. Portal apps are used for external facing websites. 
