Project Name : Slack Project

This project is to create, join, rename, list and archive a Slack API channel, which is achieved by user using the Slack API methods. The project uses Get & Post HTTP request and responses. The project utilizes modular code which can be used inside different methods. 


Getting Started
Following steps are required to get started – 
1.	Create a Slack account with your email id.
2.	Create a work space in Slack
3.	Create a legacy token from https://api.slack.com/custom-integrations/legacy-tokens and use the token in the code to get authentication for creating slack channel


Prerequisites
1. Slack API Token 


Methods Used : Following methods are used in creating this project
1. channels.create
This method is used to create a new channel in Slack. The method URL is - https://slack.com/api/channels.create
2. channels.join
This method is used to join the recently created Slack channel. The method URL is - https://slack.com/api/channels.join
3. channels.rename
This method is used to rename the recently created Slack channel. The method URL is - https://slack.com/api/channels.rename
4. channels.list
This method is list the Slack channels. The method URL is - https://slack.com/api/channels.list
5. channels.archive
This method is used to join the archive the recently created Slack channel which was renamed. The method URL is - https://slack.com/api/channels.archive



Built With
1. Eclipse
2. RestAssured Package
