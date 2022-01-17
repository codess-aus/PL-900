## Demonstrate the capabilities of Power BI (15-20%)

Power Bl can connect to and auto refresh from Microsoft Dataverse. 
Power Bl can connect to, auto refresh, and use DirectQuery with Azure SQL Data Warehouse. 
Power Bl can connect to Dynamics 365 Customer Insights and bring in its data such as customer details, roles, locations, and key performance indicators (KPls). 
Power Bl can create visualizations from Microsoft Dataverse audit logs, but these visualizations will be limited because the audit data available does not include the field or value changes, only whether a record has been changed.

In Power BI, you can connect to many different types of data sources, then shape the data to meet your needs into a dataset. 
A Power Bl report has one or more pages of visualizations. All of the visualizations in a report must come from a single dataset 
Power Bl can extract tabular data directly from a website URL and other public data sources and combine this data with your own data.

## Power BI Desktop 
Use Power BI Desktop to create reports and connect them to SharePoint lists. 
You should use Power BI Desktop to perform tasks like creating reports, calculating columns and configuring security settings. 
Power BI Desktop is a complete tool that creates reports, visualizations and data modelling. 

You should use Power Desktop to shape and combine data. Power BI Desktop allows you to share links to different data sources and to shape and model the data before publishing the model to Power BI Service. 

Uuse either Power BI Desktop or Power BI Service to configure a cross-report drillthrough report. You can use the cross-report drillthrough feature to connect related reports. 

You can connect with SQL Server, Hadoop File (HDFS) and Excel data sources from Power 81 Desktop. 
Power Bl Desktop supports all data sources available in Power Some data sources require a prerequisite installed on your machine, for example, the SQL Server data source requires .NET Framework. 


## Power BI Service 

You can connect with SQL Server and Excel data sources from Power BI Service. Almost all data sources available for Power BI can be used in Power BI Service, except the HDFS data source. Some data sources may require a data gateway to connect with on-premises data.

Use Power BI Service to create a new workspace to share reports and dashboards within your organization or with specific people in a cloud environment. 

Use [Power BI Service](https://app.powerbi.com) to publish the report and share it within your organization or with specific people. 
With Power BI Service you can create your reports in the cloud environment. 

You should use Power BI Service to perform tasks like configuring sharing and security settings and creating reports. 
Power BI Service is primarily used to share, publish and collaborate within pur organization, but it also includes limited data modelling capabilities.

You should use Power Service to create dashboards. You can create visualizations and reports in both Power Bl Desktop and Power Service, but you can only create and share dashboards in Power BI service. 

Use Power AI Service to create a dashboard. A dashboard is a visualization of one or multiple reports that are published in the same workspace. 

## Power Query:
You should use Power Query to connect to and transform data. Although you can use many components in Power BI to connect and retrieve data, all the tools use Power Query for data cleansing and data transformation. 

Power Query allows you to connect to data sources and perform complex transformations

## Power BI Mobile App
Power BI Mobile App is used to access your report hosted in Power BI Service. 

You should not use Power BI Mobile. Power BI Mobile is used to display Power 81 reports and dashboards. 

You could also publish the report as an app to your co-workers. You can create a Power app to bundle dashboards and regn)rts and publish these as apps to your whole organization or to specific people or groups, for example to your co-workers. You can also publish the app to a broader audience, like your entire company.

## Dashboard. 
Dashboard is a collection of visuals from a Power BI report hosted in Power AI Service. 

In Power al, pu can create a dashboard that displays your company s most important Key Performance Indicators (KPls) in a single page by using interactive visuals, text, and graphics called tiles. Each tile can use information from a single dataset, but a dashboard can use multiple tiles which can show information from multiple datasets.

Dashboards contain visualizations from your reports. You can share dashboards with other users. 

You should recommend a dashboard to display the company's KPls 
A dashboard is a single page with interactive visuals, text, and graphics called tiles. 
A tile's contents comes from one or more reports and one or more datasets. 
Because the dashboard is composed of only one page, you should include only the most important information, like the KPls used to monitor business performance. 

You should recommend a dashboard to configure alerts when a specific threshold target is met With a dashboard, the managers can configure a data alert on the tiles that they are most interested in. For example, a sales manager can configure an alert when the total sales are above the expected. Data alerts are available only for the user who created them. 

You cannot apply filters to a dashboard. 

**Comment feature**. This feature allows you to collaborate with others and the @mentions feature allows you to grab the attention of your colleagues. 

**Spotlight feature**. This feature simply highlights the selected visual on your display. 

**Export the data feature**. Exporting the data 

**Subscribe feature**. This feature will email you a snapshot of the dashboard for the frequency you select. 

Dashboards are created in the Power BI Service, not in Power BI Desktop. In Power BI Service, you add visualizations from your reports to dashboards.

You should use a dashboard to distribute a single page containing content from multiple datasets. A dashboard is a single page that can contain visualizations from different reports and different datasets. 
Dashboards are shared to distribute them to other users so that they can consume the content. 

## Report
You should recommend a report to analyze sales charts filtered by region. A report is composed of one or more visuals that represent different findings and insights from a single dataset. A report can have multiple tabs to better explore the information on a dataset. 
You can apply filters, slices, and highlights to discover specific data or patterns, like filtering sales for a specific region. 

The Report view contains one or more pages where you add and edit your visualizations. 

You should use a report to distribute multiple pages containing content from a single dataset. A report can have multiple pages containing visualizations from a single dataset. Reports are shared to distribute them to other users so that they can consume the content 

You can export data from a visualization in the report. You can export the summarized data used to build the visualization and the underlying data behind the visualization as CSV or Excel files. 

You cannot access multiple datasets in the same report. Power Bl reports are based on a single dataset with capabilities to interact with your visualizations, like applying filters and slices and exporting the data. 

You cannot see the underlying data behind a visualization without exporting it You can see the summarized data in a report visualization using the Show as Table option. To see the underlying data behind a visualization, you need to export it first.


## Model
You should use the Model view to show a visual view of all the entities from your data sources. 
The model view (also known as the Relationships view) contains all entities, columns, and relationships in a graphical view. 
You can edit relationships, change their direction and cardinality, and create new relationships as necessary. 
Relationships are important for visualizations because they allow data to be grouped, aggregated and linked. 

## Data
The Data view contains tables and columns in the right hand pane, with the data records in the main pane, allowing you to inspect your data after it has been loaded into the model. 

## Workspace
Workspaces are containers for data models, reports, and dashboards in the Power BI service. When you publish from Power BI Desktop to Power BI service, you select a workspace to hold your analytics.

You should use a workspace to collaborate with others to create and edit content. A workspace is a collection of datasets, reports, and dashboards. 

You should create a new Power BI workspace and invite your co-workers. Workspaces are designed to collaborate with your co-workers to create and share dashboards, reports, and paginated reports. You can assign workspace roles to individuals or user groups and grant access to the report. 

## Button or Bookmark
Use Buttons or Bookmarks to provide a menu to users so they can go directly to a specific page. 
You can enable actions on buttons or bookmark buttons and provide a URL or snapshot bookmark of your report to directly go to that specific page. 

## What-If Parameter
Use a What-if parameter to interact with visuals by providing an input value. For example, you could the see the impact of an increase of sales on the total sales value. 

## Slicer Visual
Use a Slicer Visual to provide users the ability to select specific products from a report and see analysis based on those products or categories. 

You can use slicers to display common filters on the report canvas for easier access. You can use the Location field in a slicer after you create the calculated column. 


## Calculated Column
Create a calculated column to concatenate the City and State fields into a single field named Location. You can use a calculated column to concatenate text values from different columns and create a single field that could be used in your visualizations as rows, axis, and legends. 
Calculated columns are new columns created using DAX language from data already in the data model. 
You should use a calculated column to combine the city and state columns in a table into a new column. 
The calculated column would concatenate the two columns and create a new combined column. 

## Column quality 
Column quality allows you to analyze valid, error, or empty values for all columns in a single view. 

## Column distribution  
Column distribution allows you to show distinct values for all columns in a single view 

## Column profile. 
Column profile allows you to analyze value distribution along with empty or error values for the selected column. 
Use Column profile option to check empty, error, or distinct values. Column profile allows you to analyze value distribution along with empty, error, or distinct values for a selected column. 

## Custom column 
The custom column option allows you to create a new column from Power Query editor either using an example or by providing a column formula. 


## Measure
Measures are used for aggregated calculations such as Key Performance Indicators (KPls)

Measures are automatically created by Power BI if it detects a field as numeric. You can use measures with aggregate functions, like sum, average, and median to build your 
visualizations. Measures created automatically by Power BI are identified by the symbol on the left side of the fields list and are generally used in your visualizations as a value. 

Measures are aggregations of KPls created from the data in your model. You Will use measures in your visualizations and can use the date table. 

* You should use a measure to calculate your company's aggregated sales. You can define a measure using a DAX expression. 
* You should use a measure to calculate your company's yearly increase in revenue. You can use a built-in Quick measure to show year-over-year change, or you can create a measure by writing DAX to calculate the year-over-year change. 

## Custom Measure
Custom measures can be used to aggregate data like but custom measures are created by you and are identified by a calculator icon in the fields list. 

## Dataset
You should not use a dataset. You can share datasets with other workspaces so that others can create visualizations using your dataset. Only the dataset will be shared not the associated reports and dashboards.

Datasets in a classic workspace can only be used in that workspace, and dashboards and reports in this workspace could not use datasets in other workspaces. This 
dataset cannot be shared outside the Main workspace. 

You can use datasets in the same workspace with a classic or the new workspace experience. 

In the new workspace experience you can share datasets across multiple workspaces. Datasets can also be certified in the endorsement settings. Certified datasets can then 
be used in a workspace that is also using the new experience. 

A dataset is a set of data that is ready for visualization. 

## Gateway

A gateway allows you to connect with on-premises data sources and communicate with cloud services like Power Bl and Power Apps. 


You should use a SharePoint folder data source to be able to connect to a SharePoint site. using a SharePoint folder data source allows you to connect to the files available in that directory. 


## Workspace
A workspace acts as a placeholder to share and collaborate with reports and dashboards.

## Date Table. 
Although Power BI automatically identifies columns that represent dates, and then creates date hierarchies, it is better to specify which date field you want to use as a date table, or even create a new table using the Calendar DAX function. You should create a relationship from the date table to the Order table. 

## Filter
Filters are used to interact with reports and visualizations in Power BI

You should use the (free) Power BI license to create Power BI Desktop reports. Power BI Desktop allows users to create reports without signing into a Power BI account. 

You should use the Power BI (Pro) license to publish and share reports through Power BI Service. Users need to have a Power BI (Pro) license in order to publish and share Power BI content. 

You should use the Power BI (Embedded) license to integrate your Power BI reports and dashboard into your company website. Power BI Embedded is a subscription offered through Azure. 

The Power BI (Premium) license allows you to run your reports and dashboards in a dedicated resource capacity. 

Example: Your company uses D365 Business Central, you want a quick report on Sales:

You should use the **Dynamics 365 Business Central Sales app from AppSource**. This is a pre-built app that you can connect to your Dynamics 365 instance to show default reports. 

You should not use Dynamics 365 (Online) Connector. This would let you connect to your Dynamics 365 instance and build a report, but that would take time, and you need to produce the report quickly. 

You should not use Dynamics 365 Business Central Connector. This would let you connect to your Dynamics 365 instance and build a report, but that would take time, and you need to produce the report quickly. 

You should not use the Microsoft Dataverse Connector. This would let you connect to Dataverse, where all underlying data is stored for your Dynamics 365 instance. It would be very time-consuming to get the required data and build a report. 

