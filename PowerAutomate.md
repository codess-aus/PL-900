# Demonstrate the capabilities of Power Automate (15-20%)

## Get a copy of the Flow for BackUp Purposes:
You should use the Export option to export the flow as a package. 
Your co-worker could then import this package and re-use the original version of the flow. 
You can also use the Save as option to make a new copy of this flow so your co-worker can work with the original version of the flow. 

You should not use the Rename option. This option is used to rename the existing flow, and you do not want to rename the flow because it is used by other processes. 
You should not use the Share option. This option is used for sharing an existing flow This task asks you to provide a copy of the flow so that it can be used by your co-worker. 

## Event-driven flow:
Use an EDF to check the arrival of a file in the FTP folder. You would build an event-driven flow so that whenever new files arrive in the FTP folder, it will trigger an action. 

## Template flow:
Use a Template Flow to move the files from the FTP folder to OneDrive. Once this flow is triggered by an event-driven flow, it will copy the files from the FTP folder to OneDrive. You already use the 
available templates flow to save time debugging and error handling. 

## Object detector. 
Object detectors are used to identify objects in an image. 

## Scheduled flow:
Use a SF type for a task that runs every two weeks. 
Scheduled flows can be used for recurrent tasks that run in a specific schedule, like sending a weekly report or sending a daily follow-up email. 
Scheduled flows are used in cases where you want to perform an action after a specified time like after an hour or once a day. 

## Automated Flow:
You should use an automated flow type for a task that runs when a new sales order is created. 
Automated flows are initiated to perform tasks after an event is triggered. 
You can create a flow that automatically starts when an event occurs in Dynamics 365, like when a new sales order is created. 
You should use an automated flow to automate setting up a reminder task. Once the ticket is marked completed, it will trigger an action that will set up a follow-up reminder after a week. 

## Button Flow:
You should use a button flow type for a task that runs on demand-based user input. 
You can automate repetitive tasks and execute them on demand with a button flow. 
For example, you may need to quickly send a message in Microsoft Teams to remind your team to join a daily meeting. 

## Business Process Flow: 
Business process flows can be used to configure a set of steps to be followed by users, resulting in a standard business process. 
For example, you might need a business process flow to handle customer service requests similarly. 
You should use business process flows for more complex processes that involve multiple company teams.
Business process flows are used with model-driven apps to create a guided experience.
Business process flows allow you to define a set of steps to be followed in a specific order. 

You should use a business process flow to ensure that customer representatives follow the same steps in the desired order every time they work with a customer. 
Business process flows allow you to define a set of steps that need to be followed in a specific order. 

This is a type of Power Automate flow that configures a set of steps to be followed by its users, resulting in a standard business process. For example, you might need a 
business process flow to similarly handle customer service requests. 


## Instant flow: 
Instant flows are used to automate tasks With the click Of a button. Once a button is clicked, it will trigger an action. 

## Approval Flow:
Approval flows are used for managing approval processes or automating approval systems like approving an inventory request or approving a leave request. 

The Approval flow will manage the generation of approval requests and process the acceptances and rejections. The approval requests will appear in emails, on mobile devices, and in Microsoft Teams, making it easy for managers to respond quickly and easily. 

Approval flows are used to manage tasks or process approvals.

## Approval: 
An approval is a type of action used when you need to have someone approve or reject some action during the workflow. 
For example - You need a project lead approval during this workflow to confirm that a task has been completed. 

You should not use an approval in any flow step. 
An approval is a type of action used when you need someone to approve or reject some action during the workflow. 

## Condition: 
Before sending an email to you, you should add a condition to check whether the project lead successfully approved the task. 
If the project lead confirmed that the task was completed, the flow can execute the test that sends an email to you. 
Otherwise, if the project lead rejected the task completion, you can perform the flow, like unmarking the task as done and notifying the PMO member. 

## Expression. 
You can use an expression in a condition's advanced mode to compare multiple values at once, like requiring an approval only for specific PMO members. 
You do not need to compare multiple values in the condition to determine whether the task was successfully approved or not. 

You should use an expression to merge the tweet user id and name in a single field. 
With an expression, you can concatenate information from multiple fields into a single field using the concat string function. 

You should use an expression to determine whether the customer is a promoter or a detractor. 
In Forms Pro, the NPS score is recorded as a number from O to 10, so you need to check the score and set it as either Detractor (0-6), Passive (7-8), or Promoter (9-10). 

You should use an expression to evaluate whether an associated hashtag is repeated a certain number of times. 
You can use expressions in conditions to compare two values or two arguments. 
You can use an expression to evaluate multiple values. 
In this case, you need to combine two expressions: one that checks for a specific hashtag and another that checks for the number of retweets for that specific hashtag 
You would combine these two expressions using an And clause. 


## Trigger. 
You can only use one trigger to run your workflow, and one is already configured to run when a PMO team member marks a task as complete. 

You should use a trigger to run the workflow every hour. 
You can use a scheduled trigger to run the workflow every hour or during another time interval, like every minute, for example. 

You should use a trigger to automatically process responses. The trigger listens for new responses, and when a response is received, it will execute your flow 

 Triggers are used to initiate an action, for example sending an email when a row is created. 

## Action:
You should use an action to retrieve the tweets mentioning your company's brand. 
You can use the search tweets actions from the Twitter connector to retrieve the latest tweets mentioning your company's brand. 
This will return a tweet list you can use in the next workflow steps. 

You should use an action to store the tweets into the Tweets entity. 
You can use the create a new record action from the Dataverse connector to save the tweet in the Tweets entity. 
This entity could be used later to perform the analysis of the stored tweets. 

You should use an action to send a survey to the customer. 
There are two actions for the Forms Pro connector: send a survey and create an invitation. 

Actions are used to perform tasks like sending an email
 
## Template. You can use a template to create a new workflow based on common built-in business scenarios. 

In Power Automate, pu can build a flow from scratch using more than four hundred connectors to automate a business process or •pu can use a template as a base and extend it to meet pur business needs. 

In Power Automate, you can use templates to create a flow based on a common business scenario, like saving Offce 365 email attachments to OneDrive for Business or receiving a push notification with updates from a blog. 

You can use a template and modify it to meet your needs. 

## Logic Apps:
Logic App is an Azure service that helps you to automate tasks, business processes, and workflows. Power Automate is built on top of Logic Apps and shares the same infrastructure and connectors. However, Logic Apps is focused on IT pro users. 

## CDM: 
CDM is a standard and extensible collection of schemas, including entities, attributes and relationships that represents business concepts and activities with well-defined semantics. It consists of a set of standardized, extensible data schemas published by Microsoft and its partners to facilitate data interoperability.

## Do-Until Loop:
You should use the Do Until loop to create a fixed number of tasks. The Do until will execute until the loop condition is true. 
You can use a count to restrict the number of times a Do until loop is run. 

# Apply To Each:
You should use the Apply to each loop to process of list of items. Apply to each will process each of the items retrieved in turn. 

#Switch:
Switch is a conditional that controls the execution path for actions in a flow. 

## Delay:
Delay pauses the flow until a condition is met. 

## Flow Checker:
You should use the Flow Checker to see any errors or potential issues with performance or stability. 
The Flow Checker finds errors in pur flow, spots potential performance issues, and spots reliability issues. 

You should use Flow Checker to check the flow for warning and errors. 
Flow Checker detects errors and warnings in your flow, like missing parameters in your actions or connections that are not configured. 
Flow Checker is always active during your flow design and when you save a flow that contains errors or warnings, Flow Checker opens automatically when you try to save the flow 

## Activity Utility:
The Activity utility gives you a summary of how many times each flow succeeded or failed. 
You can use the Activity utility to determine if a flow was executed properly or not.

## Test:
You should use the Test option to run a flow in the editor. When you edit a flow, you can click on the Test button and select a previous flow's data run to use. 
The test option allows pu to make changes to your flow and test the changes without having to re-create the situation that originally triggered the flow 

You should use the Test utility to run the flow with previously available or used data. 
You can test your flow with previous execution data to ensure that the flow produces the same outcome after it is modified. 
You should also use the Test utility to watch the flow execution when it is running. 
When you start a test, you can watch the flow execution and determine how long an action takes to execute and whether it contains errors. 


## View Action Outputs:
You should view the outputs from action steps when there is an error in a flow run. By examining the results of each step in your flow, you can determine why an expression is failing. 

## Resume option. 
Resume is an option for a classic workflow, not flow. 

## Submit option. 
Submit is used to publish your flow to the template gallery. 

## Export option. 
Export is used to copy the definition of the flow into a zip file for moving to a different environment, or a JSON file for converting into an Azure logic app.


