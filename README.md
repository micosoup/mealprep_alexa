# mealprep_alexa
CMSC389L
A simple meal prepper that utilizes Amazon Alexa.

The application consists of a DynamoDB database that stores all of the recipes. To interact with the database, I utilized Alexa Skills
to create an API that allows one to interact with Alexa and have a Lambda function receive the output from Alexa and input it
into DynamoDB. The recipes are scraped from BBC recipes and there are over 10,000 to choose from! 
