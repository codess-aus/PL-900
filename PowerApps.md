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

Power Apps Component Framework **(PCF) code component** are created by developers using Typescript and HTML. PCF controls are visual, re-usable compnonents that can be used in canvas and model-driven apps. 

PCF controls are developed using Typescript and HTML and require developer skills to create and maintain. PCF controls are visual, re-usable compnonents that can be used by many apps. 


**Components** are re-usable controls built using the same skills as canvas apps. The skills required to create compnonents are the same as for creating canvas apps. 
Components are custom controls that can be re-used within an app. 

Components are re-usable controls built using the same skills as canvas apps. Changes made to components are automatically updated on apps using that component. The skills 
required to create compnonents are the same as for creating apps. 

**Component libraries** contain custom controls that can be reused across apps. Component libraries can be shared with other app makers. If a compnonent in a library is updated, the other app makers who are using the library are notified that there is an update available for the component. 

**Custom connectors** are used to connect to data sources where there is no pre-built connector. Custom connectors have no impact on the look and feel of the app.


## Model-driven app 
Complex business process apps with simple user interfaces. Model-driven apps can automatically generate the application layout for your business data and processes stored 
in Microsoft Dataverse. You create a model-driven app by modelling the necessary business data your app needs to define a consistent business process. 

Model-driven apps let pu design critical business apps by allowing you to write complex business logic inside. 

You should not use a model-driven app because you need to design an app with a customized layout. 

You can embed a canvas app in a model-driven app. You can design and create custom layouts using the canvas app designer and embed these apps in a model-driven app. An embedded canvas app includes rich data integration capabilities between the contextual data from the model-driven app form with the embedded canvas app. 

You should use Power BI to build reports in a model-driven app. You can embed Power BI reports to bring rich reporting and analytics to your model-driven app forms. This is an optional feature that you need to enable in your organization before using it. 

You can use one or more tables as a data source per model-driven app. You can use multiple tables, columns and relationships from Dataverse while designing your model-driven app. You are not limited to a single table per app. 

You should use model-driven apps for implementing complex business logic. Model-driven apps take care of the user interface part, so you only need to focus on business rules, forms, and views. 

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

## Starter portal template: The starter portal template is the only portal template that is available with a Microsoft Dataverse environment when you do not have any Dynamics 365 apps installed in your environment. The starter portal template is used when you choose the Portal from blank window 

## Customer self-service, employee self-service, or partner portal template: These templates are only available when a Dynamics 365 app is installed in your Microsoft Dataverse environment.

## Dashboard. 

A dashboard is a Power BI compnonent that displays a single page with interactive visuals, text, and graphics. You can customize the dashboard interface layout, but you cannot interact with a dashboard as an application. 

## Power Automate Flow
You should not use a Power Automate flow Power Automate helps pu to automate workflows like approvals or repetitive tasks. 
