# Demonstrate the capabilities of Power Virtual Agents (10-15%)

## Topics: 

In Power Virtual Agents, a topic defines how a chatbot conversation plays out. You can author topics by customizing provided templates, create new topics from scratch, or get suggestions from existing help sites.

A topic has trigger phrases—these are phrases, keywords, or questions that a user is likely to type that is related to a specific issue—and conversation nodes—these are what you use to define how a chatbot should respond and what it should do.

The AI uses natural language understanding to parse what a customer actually types and find the most appropriate trigger phrase or node.

For example, a user might type "Open hours" into your chatbot—the AI will be able to match that to the Store hours topic and begin a conversation that asks which store the customer is interested in, and then display the hours the store is open.

You can see how the chatbot conversation works in practice by testing it in the Test chatbot pane. This lets you fine-tune the topic until you are ready to deploy it without having to exit the Power Virtual Agents portal.

A topic has trigger phrases and actions. 
A topic allows your bot to have natural conversations. 
The more conversations you add to your bot, the more intelligent it will be.

Topics are used to control the conversation path and flow Topics do not identify email addresses. 

You need to set the topic status to on. You can check the topic status. If a topic status is set to off, it Will not trigger, so if trigger phrases are used in a bot conversation, it will not answer. 

You also need to add trigger phrases to the topic. You can check the topic trigger phrases. If a topic has no trigger phrases, it Will not trigger from a bot conversation. 

## Trigger phrases: 
Add trigger phrases to your topics. This way, topics are more likely to trigger a conversation. 

You should *ask a question* or *show a message* to gain more information and provide relevant information. 

## Message Nodes:
You should use a message node to provide event details. With this option, you can add a node to show a message to provide event details. 

## Question Nodes:
You should use a question node to get age confirmations. With this option, you can add a node to ask a question to get age confirmations. 

## Action Nodes:
You should use an action node to send a confirmation email. With this option, you can add a node to call to action to send an email confirmation. 

## Condition Nodes:
You can add a condition node to divert a conversation to different paths. 

You can use the bot in Microsoft Teams, Facebook, and Slack to enhance social engagement. By adding a bot to your Teams or Slack channel, Facebook page users can interact with the bot, ask questions, and get replies from the bot.

Each time you want to update your bot, you [Publish](https://docs.microsoft.com/en-us/power-virtual-agents/publication-fundamentals-publish-channels) it again from within the Power Virtual Agents app itself. Publishing your bot will update the bot across all the channels where you've inserted or connected your bot.

Entities
A big part of chatbot conversations in Power Virtual Agents is natural language understanding, which is the ability for the AI to understand a user's intent. For example, natural language understanding is involved when a user might say "I tried to use my gift card but it doesn't work" and the chatbot is able to route the user to the topic related to gift cards not working—even if that exact phrase isn't listed as a trigger phrase.

One fundamental aspect of natural language understanding is to identify entities in a user dialog. An entity can be viewed as an information unit that represents a certain type of a real-world subject, like a phone number, zip code, city, or even a person's name.

Prebuilt entities
Out of the box, Power Virtual Agents comes with a set of prebuilt entities, which represent the most commonly used information in real-world dialogs, such as age, colors, numbers, and names.

With the knowledge granted by entities, a chatbot can smartly recognize the relevant information from a user input and save it for later use.

Custom entities
The prebuilt entities cover commonly used information types, but on some occasions, such as when building a chatbot that serves a specific purpose, you will need to teach the chatbot's language understanding model some domain-specific knowledge.

Actions
You can enable your chatbot to perform an action by calling a Microsoft Power Automate flow. Flows can help you automate activities or call backend systems. For example, you can use flows with end-user authentication to retrieve information about a user after they sign in.

You can call flows from within topics, as a discrete Call an action node. You can utilize flows that have already been created in your Power Apps environment, or you can create a flow from within the Power Virtual Agents authoring canvas.

## Entitites:
Entities represent information such as people, places, and things. 
Power Virtual Agents have prebuilt entities for common information such as age, numbers, and personal information including email addresses. 

You do not need to use custom entities since email addresses are one of the prebuilt entities in Power Virtual Agents. 

**Variables** are used to store responses so you can reuse them later in the conversion. 

Example:
You need to create a registration bot that collects user names and email addresses to send out confirmation emails. 

You should perform the following actions in order: 
1. Create a new topic. 
2. Add trigger phrases for the topic. 
3. Add questions for the username and email. 
4. Add Call an action and configure the Send email action. 

Additionally, youu can configure email actions in Power Automate: 
* In Power Automate, add input parameters for the username and email. 
* Add the Send email action. 
* Configure the recipient, subject, and email body. 
* In Power Virtual Agents in Call action, map Power Automate input parameters to variables. 
* Test your registration bot, 

## Summary report: 
The Summary report allows you to monitor overall engagement, resolution, and escalation rate. 

## Customer Satisfaction report: 
The Customer Satisfaction report allows you to monitor customer engagement and the resolution and escalation rate for each topic. 

## Session report. 
The Session report allows •pu to download session transcripts. 

## Topics report. 
The Topics report only allows you to monitor the engagement, resolution, and escalation rate for a specific topic. To see overall bot performance, you can check the 
Summary report. 

## Topic Checker:
You should use Topic Checker to check a question node. The Topic Checker option displays errors in your topic. 

#Test Your Bot:
You should use Test your bot to check transfers to agent nodes. The Test your bot option allows you to interact with a bot and debug how your bot is moving between topics. 
You should use Test your bot to show a list of available cities. The Test your bot option allows you to interact with your bot When a specific conversation path hits, the option will show you a list of available cities. 

## Flow Checker:
The Flow Checker is used to check your Power Automate flows.
