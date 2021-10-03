## Welcome to your voice demo assistant 

This demo was created to demonstrate the 
- capabilities of azure communication services 
- BotframeWork Composer with
- BotframeWork Telephony Channel installed.

# Prerequisites: 
- a Azure subscription with a billing adress in US or configured direct routing to get a telefonnumber 
- a installed and running Botframework Composer Client with the following packages:
    - Bot.Builder.Community.Components.Dialogs.Input
    - Microsoft.Bot.Builder.Adapters.Twilio
    - Microsoft.Bot.Components.Telephony

# HowTo
- clone this repository to your botframework composer and create all needed ressources on azure with botframework composers wizard.
- build, deploy, enjoy

# Functionality
- voice only assistant
- ability to transfer a call to a hardcoded phonenumber (trigger - "i want to speak to a human)
- detect DTMF (as an example - trigger "identification please")
- basic help
- basic QnA

# setup Azure Communication Services
- [setup ACS for Azure Bot](https://docs.microsoft.com/en-us/azure/communication-services/quickstarts/telephony-sms/get-phone-number?pivots=platform-azp)
- [Setup and use telephony channel](https://github.com/microsoft/botframework-telephony/blob/main/README.md)

