﻿# QnA Maker

**Important**: The QnA Maker service will retire on the 31st of March, 2025. A newer version of the question and answering capability is now available as part of Azure Cognitive Service for Language.
For question-and-answer capabilities within the Cognitive Services, see _question answering_. Starting 1st October, 2022 you won’t be able to create new QnA Maker resources. 
For information on migrating existing QnA Maker knowledge bases to question answering, consult the migration guide.
For an updated version of this sample that uses question answering, see the [CustomQABot sample](../12.customQABot).


Bot Framework v4 QnA Maker bot sample: This bot has been created using [Bot Framework](https://dev.botframework.com), it shows how to create a bot that uses the [QnA Maker Cognitive AI](https://www.qnamaker.ai) service.

The [QnA Maker Service](https://www.qnamaker.ai) enables you to build, train, and publish a simple question and answer bot based on FAQ URLs, structured documents, or editorial content in minutes. In this sample, we demonstrate how to use the QnA Maker service to answer questions based on a FAQ text file used as input.


## Prerequisites

This samples **requires** prerequisites in order to run.

### Overview

- This bot uses [QnA Maker Service](https://www.qnamaker.ai), an AI based cognitive service, to implement simple Question and Answer conversational patterns.

- [.NET SDK](https://dotnet.microsoft.com/download) version 6.0

  ```bash
  # determine dotnet version
  dotnet --version
  ```

### Create a QnAMaker Application to enable QnA Knowledge Bases

QnA knowledge base setup and application configuration steps can be found [here](https://aka.ms/qna-instructions).

## To try this sample

- Clone the repository

    ```bash
    git clone https://github.com/Microsoft/botbuilder-samples.git
    ```

- Run the bot from a terminal or from Visual Studio:

  A) From a terminal, navigate to `samples/csharp_dotnetcore/11.qnamaker`

  ```bash
  # run the bot
  dotnet run
  ```

  B) Or from Visual Studio

  - Launch Visual Studio
  - File -> Open -> Project/Solution
  - Navigate to `samples/csharp_dotnetcore/11.qnamaker` folder
  - Select `QnABot.csproj` file
  - Press `F5` to run the project

## Testing the bot using Bot Framework Emulator

[Bot Framework Emulator](https://github.com/microsoft/botframework-emulator) is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

- Install the latest Bot Framework Emulator from [here](https://github.com/Microsoft/BotFramework-Emulator/releases)

### Connect to the bot using Bot Framework Emulator

- Launch Bot Framework Emulator
- File -> Open Bot
- Enter a Bot URL of `http://localhost:3978/api/messages`

## Interacting with the bot

QnA Maker enables you to power a question and answer service from your semi-structured content.

One of the basic requirements in writing your own bot is to seed it with questions and answers. In many cases, the questions and answers already exist in content like FAQ URLs/documents, product manuals, etc. With QnA Maker, users can query your application in a natural, conversational manner. QnA Maker uses machine learning to extract relevant question-answer pairs from your content. It also uses powerful matching and ranking algorithms to provide the best possible match between the user query and the questions.

## Deploy the bot to Azure

To learn more about deploying a bot to Azure, see [Deploy your bot to Azure](https://aka.ms/azuredeployment) for a complete list of deployment instructions.

## Further reading

- [Bot Framework Documentation](https://docs.botframework.com)
- [Bot Basics](https://docs.microsoft.com/azure/bot-service/bot-builder-basics?view=azure-bot-service-4.0)
- [QnA Maker Documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/qnamaker/overview/overview)
- [Activity processing](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-activity-processing?view=azure-bot-service-4.0)
- [Azure Bot Service Introduction](https://docs.microsoft.com/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0)
- [Azure Bot Service Documentation](https://docs.microsoft.com/azure/bot-service/?view=azure-bot-service-4.0)
- [.NET Core CLI tools](https://docs.microsoft.com/en-us/dotnet/core/tools/?tabs=netcore2x)
- [Azure CLI](https://docs.microsoft.com/cli/azure/?view=azure-cli-latest)
- [QnA Maker CLI](https://github.com/Microsoft/botbuilder-tools/tree/master/packages/QnAMaker)
- [Azure Portal](https://portal.azure.com)
- [Channels and Bot Connector Service](https://docs.microsoft.com/en-us/azure/bot-service/bot-concepts?view=azure-bot-service-4.0)
