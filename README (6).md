<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Welcome to the Lex Chatbot series!

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-ai-lex)

**Author:** SHIVARAMAN RAMAKRISHNAN  
**Email:** shivaraman.r02@gmail.com

---

## I'm Building an AI Chatbot on Amazon Lex!

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex_ba6d42ae)

---

## The Project

I am trying to build a bot to show my technical AI skills to potential employers and I need some hands on experience using AWS services beyond just theoritical knowledge 

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex_a1b2c3d4)

---

## Hold me accountable!

I will build a bot

### What is AI in chatbots?

AI-powered chatbots use a set of key principles and AI technologies that help is appear more user friendly like NLP, Genrative AI and Speech recognition

### How does Amazon Lex simplify chatbot development?

Building chatbots traditionally requires hours and hours of work put into feeding models data on how converstaions usually flow, how accents differ and many other things. Amazon Lex eliminates most of the complexity and makes it in hours.

---

## Excited to share my progress - build a chatbot with me!

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex_ba6d42ae)

---
<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Chatbot with Amazon Lex

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-ai-lex1)

**Author:** SHIVARAMAN RAMAKRISHNAN  
**Email:** shivaraman.r02@gmail.com

---

## Build a Chatbot with Amazon Lex

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex1_505be5b8)

---

## Introducing Today's Project!

### What is Amazon Lex?

Amazon Lex is a aws service that helps us build chat bot by cutting down the hours spend on training the bot.

### How I used Amazon Lex in this project

Services I used were the lex builder and played around with intents, responses and fallback intent

### One thing I didn't expect was...

It is interesting

### This project took me...

It took me around 40 mins

---

## Setting up a Lex chatbot

I created my chatbot from scratch with Amazon Lex. Setting it up took me couple of minutes

While creating my chatbot, I also created a role with basic permissions because it needs the permission to call other AWS services on our behalf

In terms of the intent classification confidence score, I kept the default value of 0.40. This means that bit needs to understand atleast 40% of what the user is saying before responding back

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex1_97dc2351)

---

## Intents

Intents are user goals the bot needs to understand and meet

I created my first intent, WelcomeIntent, to welcome any new user

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex1_505be5b8)

---

## FallbackIntent

I launched and tested my chatbot, which could respond successfully if I enter hi, hello, hiya etc

My chatbot returned the error message 'Intent FallbackIntent is fulfilled' when I entered how are you This error message occurred because it was not one of the trained phrases.

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex1_505be5b8)

---

## Configuring FallbackIntent

FallbackIntent is a default intent in every chatbot that gets triggered when the chatbot has a low intent score that is it does not understand what the user is trying to say. Its like an error message for un-answerable queries.

I wanted to configure FallbackIntent to get a clear concise response that can help the user phrase his query in a better way to help the bot understand

---

## Variations

To configure FallbackIntent, I inputed some sample texts to print out in case of errors

I also added variations! What this means for an end user is they get different responses so that it doesnt appear monotonic.

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex1_c4fc89af)

---

## Initial Responses

---

---

<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Add Custom Slots to a Lex Chatbot

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-ai-lex2)

**Author:** SHIVARAMAN RAMAKRISHNAN  
**Email:** shivaraman.r02@gmail.com

---

## Add Custom Slots to a Lex Chatbot

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex2_c4fc89af)

---

## Introducing Today's Project!

In today's project, I used Amazon Lex to create chatbot and created the checkbalance intent by using slots to take the account types and data of birth to output the balance

### What is Amazon Lex?

Amazon Lex is an AWS service that helps build chatbots by minimising the time spent working on it and making it work across all other services

### One thing I didn't expect in this project was...

it was straightforward

### This project took me...

This project took me an hour

---

## Slots

Slots are fill in the blanks that the bot needs to complete the users request.

By adding custom slots in utterances, my chatbot's users can have the account type pre classfied

In this project, I created a custom slot type to make sure the banker bot accepts the same

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex2_97dc2351)

---

## Connecting slots with intents

This slot type has restricted slot values, which means that it compares to few select values and cross checks if the input matches that

checkbalance intent allows the bot to take in the users account type and DOB to cross check and output the balance

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex2_c4fc89af)

---

## Slot values in utterances

I included slot values in some of the utterances (i.e. user inputs) by using teh curly brackets {} and mentiomning the slot value.

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex2_505be5b8)

---

## Handling failures in slot values

---

---

<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Connect Amazon Lex with Lambda

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-ai-lex3)

**Author:** SHIVARAMAN RAMAKRISHNAN  
**Email:** shivaraman.r02@gmail.com

---

## Connect Amazon Lex with Lambda

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex3_505be5b8)

---

## Introducing Today's Project!

### What is Amazon Lex?

Amazon Lex is useful because it makes building chatbots easier and the cross functionality with other AWS services makes it even better

### How I used Amazon Lex in this project

In today's project, I used Amazon Lex to build the chatbot, welcome intent, fallback intent, checkbalance intent which links with a lambda function generate random balance values

### One thing I didn't expect in this project was...

It was great

### This project took me...

This project took me an hour

---

## AWS Lambda Functions

AWS Lambda is a service that lets you run code in the cloud without needing to manage any computers/servers - Lambda will manage them for you.

Lambda runs your code only when needed and scales automatically, from a few requests per day to thousands 

When someone asks about their account balance to your chatbot, Lex will ask your Lambda function to run this code, which will pick a random number to pretend it's the balance.


![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex3_97dc2351)

---

## Chatbot Alias

Think of an alias in Amazon Lex as a pointer for a specific version of your bot.
So when you're connecting Lex with other AWS services or your custom applications, those external resources will connect to an alias

TestBotAlias is a default version of your bot that's made for testing or development.

This is the playground version of your bot that you'll use to make sure everything works smoothly before rolling out changes!

To connect Lambda with my BankerBot, I visited my bot's TestBotAlias and updated the language settings by selecting the lambda function i created

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex3_c4fc89af)

---

## Code Hooks

Code hooks help you connect your chatbot to custom Lambda functions for doing specific tasks during a conversation.

They're used to handle more complex actions that the basic chatbot setup can't do on its own, like checking data from a database or making decisions based on past conversations.

I could find code hooks at the fulfillment section of the checkbalance intent

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex3_505be5b9)

---

## The final result!

I've set up my chatbot to trigger Lambda and return a random dollar figure when the checkbalance intent gets fulfilled

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex3_505be5b8)

---

## Customizing the Lambda function

---

---

<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Save User Info with a Lex Chatbot

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-ai-lex4)

**Author:** SHIVARAMAN RAMAKRISHNAN  
**Email:** shivaraman.r02@gmail.com

---

## Save User Info with a Lex Chatbot

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex4_505be5b8)

---

## Introducing Today's Project!

### What is Amazon Lex?

Amazon Lex is useful as it makes building chatbots easier

### How I used Amazon Lex in this project

In today's project, I used Amazon Lex to build a intent called followupcheckbalance that uses the input of prev entered DOB and gives balances of other accounts for that user without the need to re enter DOB

### One thing I didn't expect in this project was...

It was great

### This project took me...

This project took me 30 mins

---

## Context Tags

Context tags in Amazon Lex are used to store and check for specific information across different parts of a conversation. They help save the user from having to repeat certain information

Output - This tells the chatbot to remember certain details after an intent is finished.

Input - Checks if specific details are already available before an intent activates.

I created a context tag called contextCheckBalance. This context tag was created in the intent check balance. This tag stores information about the DOB

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex4_97dc2351)

---

## FollowUpCheckBalance

I created a new intent called FollowupCheckBalance. The purpose of this intent is to recheck the balance of another account of the same user without needing to ask for the DOB again

This intent is connected to the previous intent I made, CheckBalance, because the DOB output from that intent is the input for this intent

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex4_12345678)

---

## Input Context Tag

I created an input context, contextCheckBalance, that accesses the outputt tag from my previous intent that saved the DOB

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex4_c4fc89af)

---

## The final result!

To see the context tags and followup intent in action, I first asked for my savings balance and inputted my DOB. Then i asked for my checking balance and in an Instant i got the other balance and for further follow up i asked for credit too

If I had gone straight to trying to trigger FollowUpCheckBalance without setting up any context, i would received an error as the followup intent needs input from checkbalance intent

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex4_505be5b8)

---

## Managing context expiry

---

---

<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Set Up Multiple Slots in a Lex Chatbot

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-ai-lex5)

**Author:** SHIVARAMAN RAMAKRISHNAN  
**Email:** shivaraman.r02@gmail.com

---

## Build a Chatbot with Multiple Slots

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex5_67890123)

---

## Introducing Today's Project!

### What is Amazon Lex?

Amazon Lex is an incredible service of AWS that makes creating and automating AI chatbots super simple

### How I used Amazon Lex in this project

In today's project, I used Amazon Lex to create a bot that welcomes the user, takes in their inputs to check for checking balances across various accounts using DOB and also lets us transfer funds between them. We also tried cloud formation.

### One thing I didn't expect in this project was...

no issues

### This project took me...

This project took me  40 mins

---

## TransferFunds

An intent I created for my chatbot was TransferFunds, which lets the user transfer money between two of their accounts by using sourceacc and targetacc slots and a transferamount slot which saves the amount of money transfered

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex5_67890123)

---

## Using multiple slots

For this intent, I had to use the same slot type twice. This is because both the source account type and target account type fall under the 3 account types we had given and are essentially the same

I also learnt how to create confirmation prompts, which are prompts which typically repeat back information for the user to confirm. e.g. "Are you sure you want to do x?" If the user confirms the intent, the bot fulfills the intent

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex5_97dc2351)

---

## Exploring Lex features

Lex also has a special conversation flow feature that shows every step in a conversation in a logical, chronological order.

You could also set up your intent using a visual builder! A visual builder is a visual representation of the intent you have just built in a flow chart manner which is also interactive

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex5_12345678)

---

## AWS CloudFormation

AWS CloudFormation is a service that gives you an easy way to create and set up AWS resources.

It's an infrastructure as code service

use a file that describes all the resources you want to create and their dependencies as code. Then, you can use that template to create, update, and delete the entire stack of resources you described, instead of managing your resources individually

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex5_c4fc89af)

---

## The final result!

Re-building my bot with CloudFormation took me 15 mins


happening because the permissions in the AWS Lambda function are a little funky, so it's not passing the values back to your chatbot

![Image](http://learn.nextwork.org/motivated_lavender_quiet_boto/uploads/aws-ai-lex5_505be5b8)

---

## Using the visual builder

---

---

