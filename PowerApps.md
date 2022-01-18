# Demonstrate the capabilities of Power Apps (15-20%)

If you create a model-driven app and share the app with users but find users cannot access the app. You need to enable users to access the app by assigning a **security role** to the users. This is not the same as adding the users to a Security Group. **Security groups** are used in Power Platform to enable access to environments. They are not used to give access to individual apps. 

## Canvas app: 
Simple apps with a highly customizable user interface layout. A canvas app lets you have complete control over the app layout. It also allows you to drag and drop elements to a 
canvas and use expressions to specify simple logic. 

You should use a Power Apps canvas app to create a customized layout app for your company to schedule internal meetings in M365. A canvas app lets you choose the layout and add key business functionalities. 

You should use canvas apps for highly customizable layouts. Canvas apps provide full control over user interface and how screens can interact with each other. 

**Combo box control** This control allows you to display a list and search for items. The search is performed in the server so performance is not affected by very large data sources. 

**List box control**. This control displays all items from the list in the user screen. You cannot search for items with this control and the screen scroll size will expand significantly. 

**Drop down control**. This control can conserve the screen scroll size, displaying only the selected item. However, you cannot search for items with this control and all data 
sources are loaded at once, resulting in a potential low performance. 

**Radio control**. This control is best used with only a few items. You cannot search for items with this control and the screen scroll size Will expand significantly if you display more than two hundred items. 



## Model-driven app 
Complex business process apps with simple user interfaces. Model-driven apps can automatically generate the application layout for your business data and processes stored 
in Microsoft Dataverse. You create a model-driven app by modelling the necessary business data your app needs to define a consistent business process. 

Model-driven apps let pu design critical business apps by allowing you to write complex business logic inside. 

You should not use a model-driven app because you need to design an app with a customized layout. 

You can embed a canvas app in a model-driven app. You can design and create custom layouts using the canvas app designer and embed these apps in a model-driven app. An embedded canvas app includes rich data integration capabilities between the contextual data from the model-driven app form with the embedded canvas app. 

You should use Power BI to build reports in a model-driven app. You can embed Power BI reports to bring rich reporting and analytics to your model-driven app forms. This is an optional feature that you need to enable in your organization before using it. 

You can use one or more tables as a data source per model-driven app. You can use multiple tables, columns and relationships from Dataverse while designing your model-driven app. You are not limited to a single table per app. 

You should use model-driven apps for implementing complex business logic. Model-driven apps take care of the user interface part, so you only need to focus on business rules, forms, and views. 




## Power Automate Flow
You should not use a Power Automate flow Power Automate helps pu to automate workflows like approvals or repetitive tasks. 

## Power Apps Portal

You should not use a Power Apps portal. Power Apps portals are used for creating customer facing external websites.

You should use Power Apps portals for a customer facing website. Power Apps portals allow you to create a customer engagement website using pre-built templates.

## Dashboard. 

A dashboard is a Power BI compnonent that displays a single page with interactive visuals, text, and graphics. You can customize the dashboard interface layout, but you cannot interact with a dashboard as an application. 
