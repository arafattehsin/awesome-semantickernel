# awesome-semantickernel
 Awesome list of tools and projects with the awesome semantic kernel framework

 > Curated list of tools and projects using semantic kernel.

Semantic kernel is an amazing framework to get LLM projects done in a matter of no time and the ecosystem is growing fast. Here is an attempt to keep track of the initiatives around semantic kernel.

Contributions welcome. Add links through pull requests or create an issue to start a discussion. Please read the [contribution guidelines](contribution.md) before contributing.

## Table of Contents

- [Awesome semantickernel ](#-awesome-semantickernel--)
  - [Table of Contents](#table-of-contents)
  - [Semantickernel Framework](#semantickernel-framework)
  - [Plugins](#plugins)
  - [Planners](#Planners)
  - [Personas](#Personas)
  - [Open Source Projects](#open-source-projects)
  - [Learn](#learn)
    - [Notebooks](#notebooks)
    - [Videos](#videos)
    - [Articles](#articles)
  - [Alternatives](#alternatives)
  - [Complement to this list](#complement-to-this-list)

## Semantickernel Framework
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel): the original  ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=social) [![Semantic Kernel Nuget package](https://img.shields.io/nuget/vpre/Microsoft.SemanticKernel?label=nuget%20Semantic%20Kernel)](https://www.nuget.org/packages/Microsoft.SemanticKernel/) 
- [Concepts](https://learn.microsoft.com/en-us/semantic-kernel/overview/): Semantic Kernel concepts doc 
- [Discord discussion](https://aka.ms/SKDiscord)
- [Semantic Kernel Blog](https://devblogs.microsoft.com/semantic-kernel/): The Official Semantic Kernel blog 
- [Semantic Kernel starter](https://github.com/microsoft/semantic-kernel-starters): Starter Projects for Semantic Kernel
- [VisualStudio Code Tool](https://marketplace.visualstudio.com/items?itemName=ms-semantic-kernel.semantic-kernel): Visual Code Studio Semantic Kernel Extension
- [OSSInsight.io](https://ossinsight.io/analyze/microsoft/semantic-kernel?vs=langchain-ai%2Flangchain#overview)
- [gosk](https://github.com/mfmayer/gosk) Go Semantic Kernel (gosk) adapts Microsoft's Semantic Kernel (C#, Python) to provide OpenAI API integration for Golang developers
- [Semantic Kernel vs LangChain](https://github.com/formulahendry/semantic-kernel-vs-langchain) Compare Semantic Kernel and LangChain
- [analassist-langchain-vs-microsoft-sk](https://github.com/calapsss/analassist-langchain-vs-microsoft-sk) AnalAssist - LangChain vs. Microsoft Semantic Kernel
- [Explore the Power of AI with SKPlayground](https://skplayground.dev/)
- [SK release](https://github.com/microsoft/semantic-kernel/releases) SK release notes
- [SK Extensibility Scenarios](https://github.com/matthewbolanos/sk-v1-proposal)  how to extend several Semantic Kernel interfaces and to use them in core scenarios.
- [Generative AI Learning for Beginners](https://microsoft.github.io/generative-ai-for-beginners/) A 12 Lesson course teaching everything you need to know to start building Generative AI applications
- [skUnit is a testing tool for SemanticKernel units, such as plugin functions and kernels](https://github.com/mehrandvd/skunit)

## Plugins
 modules that connect Semantic Kernel to different AI models or services, such as GPT-3, Azure Prompt Flow, or the Microsoft Graph
 Plugins are at the heart of unlocking more potential with your [Semantic Kernel](https://github.com/microsoft/semantic-kernel) applications. They allow you to connect to external data sources and give large language models tools to be able to interact with native functions and API services.


If you want to try out your plugins and you do not have a ChatGPT plus subscription or are off the waitlist, you can test this directly **for free** using the Semantic Kernel!

See [this tutorial doc](https://learn.microsoft.com/en-us/semantic-kernel/ai-orchestration/chatgpt-plugins) or watch the [video](https://youtu.be/W_xF8PcdT78) for how to get set up.

**Why:** Microsoft is standardizing around the [plugin architecture](https://learn.microsoft.com/en-us/semantic-kernel/ai-orchestration/plugins?tabs=Csharp) for all of its internal AI copilots
and encourage developers to use them for their own applications. This hackathon serves to jumpstart a larger plugin ecosystem that is valuable to the broader community.

**How:** Follow the getting started guides for creating a plugin
- **C#** - [(Video)](https://youtu.be/T7XLn11rpYI) | [(Repo) Semantic Kernel ChatGPT plugin starter](https://github.com/microsoft/semantic-kernel-starters/tree/main/sk-csharp-chatgpt-plugin)
- **Python** - [(Video)](https://youtu.be/_4HZCdd3OxI) | [(Repo) Semantic Kernel Python Flask (and plugin) Starter](https://github.com/microsoft/semantic-kernel-starters/tree/main/sk-python-flask)
- [SK Kernel Memory](https://github.com/microsoft/kernel-memory):Semantic Memory is an open-source library and service specializing in the efficient indexing of datasets through custom continuous data pipelines [![SemanticMemory Core Nuget package](https://img.shields.io/nuget/vpre/Microsoft.KernelMemory.Core?label=nuget%20KernelMemory%20Core)](https://www.nuget.org/packages/Microsoft.KernelMemory.Core/) [![SemanticMemory Client Nuget package](https://img.shields.io/nuget/vpre/Microsoft.KernelMemory.Client?label=nuget%20KernelMemory%20Client)](https://www.nuget.org/packages/Microsoft.KernelMemory.Client/) 
- [NL2EF](https://github.com/anthonypuppo/sk-nl2ef-plugin) A Semantic Kernel plugin designed to be a drop-in service that can expose an existing database to be queried via natural language
- [Packages, Examples and Demo code for Semantic Kernel](https://github.com/thinktecture/SemanticKernel) [![BlazorNavigationPlugin Nuget package](https://img.shields.io/nuget/vpre/Thinktecture.SemanticKernel.BlazorNavigationPlugin?label=nuget%20BlazorNavigationPlugin)](https://www.nuget.org/packages/Thinktecture.SemanticKernel.BlazorNavigationPlugin/)
- [sk-ethereumtx-plugin](https://github.com/sustia-llc/sk-ethereumtx-plugin) Semantic Kernel ChatGPT plugin for Ethereum Txs
- [Webscraper AIplugin](https://github.com/craigomatic/webscraper-aiplugin): AI Plugin that can be used to scrape useful information from a given URL
- [teams-bot-semantic-kernel](https://github.com/formulahendry/teams-bot-semantic-kernel) A Teams Bot app integrated with Semantic Kernel and its Microsoft Graph Plugin
- [EmbedElite marketplace](https://github.com/embedelite/sk-hackathon)This project is creating a plugin for the EmbedElite marketplace for the SK Hackathon. The Sementic Kernel plugin facilitates fetching ready-made premium context based on embeddings via an API
- [AssemblyAI plugins for Semantic Kernel](https://github.com/AssemblyAI/assemblyai-semantic-kernel) Transcribe audio using AssemblyAI with Semantic Kernel plugins. [![AssemblyAI.SemanticKernel Nuget package](https://img.shields.io/nuget/vpre/AssemblyAI.SemanticKernel?label=nuget%20AssemblyAI%20plugin)](https://www.nuget.org/packages/AssemblyAI.SemanticKernel/)
- [SemanticKernel.Connectors.Memory.SqlServer](https://github.com/kbeaugrand/SemanticKernel.Connectors.Memory.SqlServer) SQL Server connector for Semantic Kernel skills and semantic memory [![SQLServer connector Nuget package](https://img.shields.io/nuget/vpre/SemanticKernel.Connectors.Memory.SqlServer?label=nuget%20SqlServer%20connector)](https://www.nuget.org/packages/SemanticKernel.Connectors.Memory.SqlServer/)
- [semantic-kernel-LLamaSharp](https://github.com/SciSharp/LLamaSharp) use LLamaSharp to implement the Completion and Embedding interfaces of the semantic kernel [![LLamaSharp Nuget package](https://img.shields.io/nuget/vpre/LLamaSharp?label=nuget%20LLamaSharp)](https://www.nuget.org/packages/LLamaSharp/)
- [semantic-kernel-ERNIE-Bot](https://github.com/custouch/semantic-kernel-ERNIE-Bot): Semantic Kernel 集成文心千帆 [![ERNIE-Bot Nuget package](https://img.shields.io/nuget/vpre/ERNIE-Bot.SemanticKernel?label=nuget%20ERNIE-Bot)](https://www.nuget.org/packages/ERNIE-Bot.SemanticKernel/)
- [DashScope.net](https://github.com/custouch/DashScope.net) Semantic Kernel 集成 Aliyun DashScope灵积模型服务 SDK，通义千问SDK [![DashScope.Net Nuget package](https://img.shields.io/nuget/vpre/DashScope.SemanticKernel?label=nuget%20DashScope.Net)](https://www.nuget.org/packages/DashScope.SemanticKernel/)
- [SS.SemanticKernel.Extensions](https://github.com/chenrensong/SS.SemanticKernel.Extensions):  This extension enables you to generate text embeddings with a semantic-based kernel function. [![Semantic kernel extensions Nuget package](https://img.shields.io/nuget/vpre/SS.SemanticKernel.Extensions?label=nuget%20SemanticKernel%20Extensions)](https://www.nuget.org/packages/SS.SemanticKernel.Extensions/)
- [Semantic-Fleet ](https://github.com/MyIntelligenceAgency/semantic-fleet) Semantic-Fleet is a dedicated repository designed to extend the capabilities of Semantic Kernel. [![Oobabooga Connector Nuget package](https://img.shields.io/nuget/vpre/MyIA.SemanticKernel.Connectors.AI.Oobabooga?label=nuget%20Oobabooga%20Connector)](https://www.nuget.org/packages/MyIA.SemanticKernel.Connectors.AI.Oobabooga/) [![Multiconnector Nuget package](https://img.shields.io/nuget/vpre/MyIA.SemanticKernel.Connectors.AI.MultiConnector?label=nuget%20MultiConnector)](https://www.nuget.org/packages/MyIA.SemanticKernel.Connectors.AI.MultiConnector/)

- [Semantic Kernel - MongoDB Connector](https://github.com/kbeaugrand/SemanticKernel.Connectors.Memory.MongoDB) Atlas MongoDB connector for Semantic Kernel skills and semantic memory [![MongoDB Connector Nuget package](https://img.shields.io/nuget/vpre/SemanticKernel.Connectors.Memory.MongoDB?label=nuget%20MongoDB%20connector)](https://www.nuget.org/packages/SemanticKernel.Connectors.Memory.MongoDB/)
- [Faster & Smaller Single-File Search Engine for Vectors & Texts](https://github.com/unum-cloud/usearch) [![USearch Nuget package](https://img.shields.io/nuget/vpre/Cloud.Unum.USearch?label=nuget%20USearch)](https://www.nuget.org/packages/Cloud.Unum.USearch/)

- [Microsoft-Semantic-Kernel-Community-dotnet](https://github.com/Azure-AI-Community/Microsoft-Semantic-Kernel-Community-dotnet) [![AzureAI.Community.Microsoft.Semantic.Kernel.Speech](https://img.shields.io/nuget/vpre/AzureAI.Community.Microsoft.Semantic.Kernel.Speech?label=nuget%20SKPlugin%20Speech)](https://www.nuget.org/packages/AzureAI.Community.Microsoft.Semantic.Kernel.Speech#readme-body-tab) [![AzureAI.Community.OpenAI.Bot.Builder.Prompt](https://img.shields.io/nuget/vpre/AzureAI.Community.OpenAI.Bot.Builder.Prompt?label=nuget%20SKPlugin%20Builder%20Prompt)](https://www.nuget.org/packages/AzureAI.Community.OpenAI.Bot.Builder.Prompt) [![AzureAI.Community.Microsoft.Semantic.Kernel.Translation](https://img.shields.io/nuget/vpre/AzureAI.Community.Microsoft.Semantic.Kernel.Translation?label=nuget%20SKPlugin%20Translation)](https://www.nuget.org/packages/AzureAI.Community.Microsoft.Semantic.Kernel.Translation)  [![AzureAI.Community.Microsoft.Semantic.Kernel.PlugIn.Intent](https://img.shields.io/nuget/vpre/AzureAI.Community.Microsoft.Semantic.Kernel.PlugIn.Intent?label=nuget%20SKPlugin%20Intent)](https://www.nuget.org/packages/AzureAI.Community.Microsoft.Semantic.Kernel.PlugIn.Intent)  [![AzureAI.Community.Microsoft.Semantic.Kernel.PlugIn.Web.YouTube](https://img.shields.io/nuget/vpre/AzureAI.Community.Microsoft.Semantic.Kernel.PlugIn.Web.YouTube?label=nuget%20SKPlugin%20YouTube)](https://www.nuget.org/packages/AzureAI.Community.Microsoft.Semantic.Kernel.PlugIn.Web.YouTube)

- [sk-researcher](https://github.com/craigomatic/sk-researcher): Using Semantic Kernel to power a research agent that will work on your behalf to research a topic
- [worddoc-aiplugin](https://github.com/craigomatic/worddoc-aiplugin) AI Plugin that can be used to create and append to word documents
- [sk-plugin-sample](https://github.com/Jandev/sk-plugin-sample) Sample project to show how plugins can be used with Semantic Kernel
- [semantic-kernel-gradio](https://github.com/khcheung/semantic-kernel-gradio/) Using Gradio API for Semantic Kernel - TextEmbeddingGeneration
- [ServiceStack.AI](https://github.com/ServiceStack/ServiceStack/tree/main/ServiceStack/src/ServiceStack.AI) Speech-to-Text and ChatGPT providers to enable natural language features in .NET
- [MerkonVectorDB](https://github.com/Gravicode/MerkonVectorDB/)
- [bankcopilot-semantickernel-aiplugin](https://github.com/raffertyuy/bankcopilot-semantickernel-aiplugin) This is a Bank ChatGPT AI Plugin POC to observe how ChatGPT will perform with additional banking transaction skills
- [FreeMindLabs.SemanticKernel.Connectors.Elasticsearch](https://github.com/freemindlabsinc/FreeMindLabs.SemanticKernel) A Semantic Kernel connector to Elasticsearch. Use Elasticsearch as your vector database.
- [Postgres adapter for Kernel Memory](https://github.com/microsoft/kernel-memory-postgres)
- [Kernel Memory with SQLite](https://github.com/microsoft/kernel-memory-sqlite)This repository contains the SQLite adapter allowing to use Kernel Memory with SQLite
- [SemanticKernel.Connectors.Memory.SqlServer](https://github.com/kbeaugrand/SemanticKernel.Connectors.Memory.SqlServer)SQL Server connector for Semantic Kernel plugin and Kernel Memory
- [Plugin sample built using Semantic Kernel that summarises a given text from Bing Web Search.](https://github.com/vicperdana/sk-bingsummary-plugin)
- [Codeblaze.SemanticKernel](https://github.com/BLaZeKiLL/Codeblaze.SemanticKernel)
- [PaddleSharp.KernelMemory](https://github.com/xbotter/PaddleSharp.KernelMemory)Using PaddleSharp as an OCR engine in kernel memory.

## Planners
sequences of actions that Semantic Kernel can execute to achieve a goal, such as booking a flight or writing some content.
- [Introduction to Semantic Kernel Planners for Seamless Orchestration](https://medium.com/@akshaykokane09/empowering-ai-with-semantic-kernel-planners-for-seamless-orchestration-1c7ad35f2337)
- [Semantic Kernel Planner 101](https://blog.baeke.info/2023/06/01/semantic-kernel-planner-101/)
- [Using Planners in the SK Java Kernel](https://devblogs.microsoft.com/semantic-kernel/using-planners-in-the-sk-java-kernel/)

## Personas 
profiles that define the preferences and personality of Semantic Kernel, such as tone, style, and humor
- [SKPersona](https://github.com/anthonypuppo/skpersona) Demonstration of how to give Language Models (LLMs) a unique persona using part of speech tagging and logit bias
- [Semantic Kernel Personas: An Interview with SK Team Member Brian Krabach](https://devblogs.microsoft.com/semantic-kernel/semantic-kernel-personas-an-interview-with-sk-team-member-brian-krabach/)

## Open Source Projects
- [Copilot Chat Sample Application](https://github.com/microsoft/chat-copilot):This is an enriched intelligence app, with multiple dynamic components including command messages, user intent, and memories
- [ TypeChat.NET brings the ideas of TypeChat to .NET](https://github.com/microsoft/typechat.net) TypeChat.NET provides cross platform libraries that help you build natural language interfaces with language models using strong types, type validation and simple type safe programs (plans).
- [Conversational Speaker](https://github.com/microsoft/conversational-speaker): uses a Raspberry Pi (or desktop) to enable spoken conversation with OpenAI large language models. This implementation listens to speech, processes the conversation through the OpenAI service, and responds back.
- [SolidWorks-Copilot](https://github.com/weianweigan/SolidWorks-Copilot) : Your SolidWorks Copoilt based on LLM(ChatGPT) and semantical kernel
- [Email-Copilot](https://github.com/jogendrasinghgurjar/email-copilot): Email-copilot for Outlook aims to revolutionize email management by leveraging natural language processing to streamline drafting, responding, and organizing emails
- [A port of the Python example that answers questions about 2022 Winter Olympics](https://github.com/afederici75/SKWinterOlympics)
- [Fantasy Copilot](https://github.com/Richasy/FantasyCopilot): Fantasy Copilot integrates Open AI and Azure's AI services, dedicated to building a personal assistant tool with a large language model as the core and high scalability 
- [sk-ingest](https://github.com/craigomatic/sk-ingest): Small library to make it easier to BYO data for use with Semantic Kernel and LLMs 
- [sk-classifier](https://github.com/craigomatic/sk-classifier): This small sample project shows how to perform basic classification on a series on prompts, against a pre-defined series of classifications using Semantic Kernel
- [Using Semantic Kernel to Summarize Youtube Videos](https://github.com/RogerBarreto/sk-youtube-summarizer)
- [Elsa.SemanticKernel](https://github.com/rysweet/Elsa.SemanticKernel): SemanticKernel Activity Provider for Elsa Workflows
- [Write a blog using Semantic Kernel](https://github.com/devedium/WriteABlog)
- [op-semantic-kernel-demo](https://github.com/jackawatts/op-semantic-kernel-demo) Impersonating yourself with ChatGPT and Microsoft Semantic Kernel
- [Chat with your Enterprise Data: powered by Azure OpenAI/ChatGPT, Cognitive Search, and Bot Service](https://github.com/ronikurnia1/gpt-azure-botservice)
- [Semantic Kernel Sidecar](https://github.com/raykao/semantic-kernel-sidecar) About A prototype for an abstracted Sidecar Process that runs/abstracts Semantic Kernel via HTTP/gRPC
- [LangChain](https://github.com/tryAGI/LangChain): C# implementation of LangChain
- [semantic-kernel-ecom](https://github.com/alexcalabrese/semantic-kernel-ecom) AI-Powered eShopOnWeb E-commerce using Semantic Kernel
- [A Teams Bot app integrated with Semantic Kernel and its Microsoft Graph Plugin](https://github.com/formulahendry/teams-bot-semantic-kernel)
- [azure-openai-dev-skills-orchestrator](https://github.com/microsoft/azure-openai-dev-skills-orchestrator) Build a Virtual AI Dev Team using Semantic Kernel Skills
- [Semantic Kernel From Config](https://github.com/matthewbolanos/semantic-kernel-from-config) Provides an example of how you could extend Semantic Kernel to support config files for agents and plugins
- [GPTMeetingAgent](https://github.com/NetCoreApps/GPTMeetingAgent) A pattern for GPT Agent integration with ServiceStack services
- [SemanticKernel.PowerFx](https://github.com/jorisdg/SemanticKernel.PowerFx) Add low-code skills to Semantic Kernel using Power Fx
- [SemanticNativeFunctions](https://github.com/RobertEichenseer/OpenAI.SemanticNativeFunctions) Chaining native & semantic functions using MS Semantic Kernel
- [PowerPlatformCopilot](https://github.com/petrochuk/PowerPlatformCopilot) A .Net library which simplifies creation of Copilots/AI Assistants for Microsoft Power Platform with Azure OpenAI
- [Java Samples using Semantic Kernel](https://github.com/agoncal/agoncal-sample-semantic-kernel) These samples are used to test the Semantic Kernel with java
- [TextToVideo](https://github.com/Saby007/TextToVideo) This is an app to convert Text to Video using Azure Open AI and Dall-e in Python using Semantic Kernel.
- [ai-playground](https://github.com/karlgodtliebsen/ai-playground) This repository is for learning about AI - OpenAI and related using dotnet
- [LLM-Powered Wordle-Solver Agent](https://github.com/husainhz7/wordle-llm-solver) This is a Wordle-solving script powered by LLM (Large Language Model) and built using Semantic Kernel and PyAutoGUI.
- [MachineIntelligence-TextAnalytics-TPLDataFlows](https://github.com/bartczernicki/MachineIntelligence-TextAnalytics-TPLDataFlows) Machine Intelligence Text Analytics Enrichment implemented using Task Parallel Library Data Flow Pipelines
- [skonsole](https://github.com/lemillermicrosoft/skonsole) A Pull Request Skill example built on the Semantic Kernel
- [skonsole-generate-pr-description](https://github.com/mkarle/skonsole-generate-pr-description) A PR tool that uses Microsoft's Semantic Kernel and LLMs to generate PR descriptions
- [Retrieval Augmented Generation (RAG) using Azure Cognitive Search](https://github.com/MeshackMusundi/AzureCognitiveSearch-RAG)
- [dapr-chat-20230822](https://github.com/cwiederspan/dapr-chat-20230822) A Dapr-implemented OpenAI chat service demo
- [This application is a demo on how to setup an event driven architecture combining Dapr, Azure OpenAI and Azure Container Apps](https://github.com/pelithne/cngbg)
- [ParkPro](https://github.com/insaiyann/ParkPro) ParkPro aims to revolutionize parking services using Semantic kernel SDK
- [Java and OpenAI Hero Demos](https://github.com/microsoft/java-semantic-kernel-demos) This repository holds end-to-end demo applications that represent the concept of an Intelligent App, built in Java
- [Semantic Kernel in your application](https://github.com/Azure-For-Everyone/sk-hotelfiltering) we'll show you how to leverage Semantic Kernel into an existing application.
- [semantic_kernel_examples](https://github.com/rajib76/semantic_kernel_examples) This repo will contain the semantic kernel examples
- [sk-hotelfiltering](https://github.com/Azure-For-Everyone/sk-hotelfiltering) An example of how to use Semantic Kernel as part of a Hotel booking website for filtering hotels using natural language
- [SemanticKernelDemo](https://github.com/xuzeyu91/SemanticKernelDemo) 本项目主要介绍了SK的基本功能使用
- [EarthChat](https://github.com/239573049/EarthChat) 基于SignalR实现的Chat聊天，支持横向扩展，以便支撑百万用户同时在线聊天
- [semantic-kernel-semanticsearch](https://github.com/thinktecture-labs/semantic-kernel-semanticsearch) Question & Answer flow with C# & Semantic Kernel
- [sk-summarizer-pattern](https://github.com/msalemor/sk-summarizer-pattern) A summarizer implementation using Semantic Kernel
- [Quarkus Semantic Kernel](https://github.com/quarkiverse/quarkus-semantic-kernel) This extension eases the integration of Semantic Kernel for Java with Quarkus
- [semantic-kernel-bot-in-a-box](https://github.com/Azure/semantic-kernel-bot-in-a-box) Extensible Semantic Kernel Bot Solution Accelerator
- [LablabAutogen](https://github.com/Josephrp/LablabAutogen) A generalist agent that can go online and accomplish complex tasks using semantic-kernel and autogen
- [This is Local LLM Server for Semantic Kernel](https://github.com/kinfey/SemanticKernel-Local-LLM-Server) Local LLM Server for Semantic Kernel .NET Developer
- [A reference .NET application implementing an eCommerce web site using a services-based architecture](https://github.com/dotnet/eShop)
- [VectorSearchAiAssistant](https://github.com/Netizine/VectorSearchAiAssistant) Vector Search & AI Assistant for Azure Cosmos DB and Azure Cognitive Search
- [entirely with native functions in C# and am building out a console application with Spectre.Console](https://github.com/IntegerMan/BatComputer)
- [enmarcha](https://github.com/Encamina/enmarcha) Empower your applications with AI capabilities built on top of the Semantic Kernel, enabling more nuanced data interpretation.
- [minecraft-container-apps](https://github.com/cmendible/minecraft-container-apps)
- [AugmentR](https://github.com/bradygaster/AugmentR)Sample showing how to do Retrieval Augmented Generation using .NET Aspire, Semantic Kernel, and OpenAI.]
- [sk-v1-droneAssistant](https://github.com/elbruno/sk-v1-droneAssistant) Semantic Kernel V1 Assistant to control DJI Tello Drone
- [TerraMours实战项目，基于TerraMours框架实现的ChatGPT项目后端。实现用户登陆和基于SK的多语言模型聊天、基于chatgpt和SD的多模型图片生成等功能](https://github.com/TerraMours/TerraMours_Gpt_Api)
- [ENMARCHA — Your package to accelerate .NET projects](https://github.com/Encamina/enmarcha)
- [知识文档问答，用大模型与文档对话，提供Al分析、阅读、问答工具，助你快速了解文档内容](https://github.com/bianchenglequ/chat2KnowL)
- [SemanticKernel.Assistants](https://github.com/kbeaugrand/SemanticKernel.Assistants) It runs locally planners and plugins for the assistants
- [Sample showing how to do Retrieval Augmented Generation using .NET Aspire, Semantic Kernel, and OpenAI.](https://github.com/bradygaster/AugmentR)
- [Adventures in Semantic Kernel](https://github.com/HillPhelmuth/AdventuresInSemanticKernel) Learn about Semantic Kernel, Microsoft's AI orchestration library. Play with memories, models, plugins, and plans from various providers.
- [semantic-kernel-aiagent](https://github.com/xuzeyu91/semantic-kernel-aiagent) 基于.Net8+Blazor+SemanticKernel 打造的AI知识库/智能体
- [An example of how to use Semantic Kernel as part of a Hotel booking website for filtering hotels using natural language](https://github.com/Azure-For-Everyone/sk-hotelfiltering)
- [Kernel-Memory-Azure-Function-Implementation](https://github.com/Gpadh/Kernel-Memory-Azure-Function-Implementation)
  
## Learn

### Notebooks
- [A collection of C# notebooks to get you started with Semantic Kernel quickly](https://github.com/johnmaeda/SK-Recipes)
- [A collection of Python notebooks to get you started with Semantic Kernel quickly](https://github.com/alexchaomander/SK-Recipes)
- [Intelligent app workshop](https://github.com/Azure/intelligent-app-workshop): This is an envisioning workshop, based on Microsoft's Copilot stack, to rethink user experience, architecture, and app development by leveraging the intelligence of foundation models
- [Project Miyagi - Financial coach](https://github.com/Azure-Samples/miyagi): showcasing AI-first application architectures and generative AI capabilities with nascent design patterns to embed intelligence. A Hyper-personalized agent powered by SoTA foundation models and event-driven architecture
- [Tutorial: ChatGPT + Enterprise data with Semantic Kernel, OpenAI and Azure Cognitive Search](https://github.com/Azure-Samples/azure-search-openai-demo-csharp/)
- [Learn Azure OpenAI Service with .NET](https://github.com/kinfey/dotNETOAIBooks): This is a Azure OpenAI book for .NET Developer
- [MSFabricCopilotWorkshop](https://github.com/kinfey/MSFabricCopilotWorkshop) : Building Microsoft Fabric Copilot App Workshop
- [VSCodeEnterpriseCopilotWorkshop](https://github.com/kinfey/VSCodeEnterpriseCopilotWorkshop) Create Your Visual Studio Code Copilot Extension for Enterprise
- [Semantic Kernel OpenAPI Skill Sample Project](https://github.com/mbenachour/semantic-kernel-course) This is a sample project to demonstrate the Semantic Kernel OpenAPI skill. It consists of a clothing API, which is a Swagger API, and a Copilot chat app.
- [openai-sk-demos](https://github.com/msalemor/openai-sk-demos) Semantic Kernel Demos
- [SemanticKernelLearningLab](https://github.com/walidamro-msft/SemanticKernelLearningLab) This is a lab to learn Semantic Kernel and Azure Open AI Services
- [Semantic-Kernel-Workshop](https://github.com/jogendrasinghgurjar/Semantic-Kernel-Workshop)
- [semantic-kernel-quickstart](https://github.com/shuaihuadu/semantic-kernel-quickstar)
- [semantic-kernel-rag-chat](https://github.com/Azure-Samples/semantic-kernel-rag-chat) Tutorial for ChatGPT + Enterprise Data with Semantic Kernel, OpenAI, and Azure Cognitive Search
- [CookingKitchenSemanticKernelCourse](https://github.com/spavkov/CookingKitchenSemanticKernelCourse)
- [Hands-on Introduction to Semantic Kernel](https://github.com/ecdedios/hands-on-intro-semantic-kernel)
- [SKPlayground](https://github.com/brakmic/SKPlayground)
- [AdventuresInSemanticKernel](https://github.com/HillPhelmuth/AdventuresInSemanticKernel) Learn about Semantic Kernel, Microsoft's AI orchestration library. Play with memories, models, plugins, and plans from various providers 
- [understanding-semantic-kernel-with-heroes](https://github.com/0GiS0/understanding-semantic-kernel-with-heroes) Welcome to my own way to understand Semantic Kernel
- [OpenAI-Workshop](https://github.com/kierunb/OpenAI-Workshop)
- [Integrate OpenAI into Your Code with Semantic Kernel](https://github.com/feaselkl/Integrate-OpenAI-into-Your-Code-with-Semantic-Kernel)


### Videos
- [A Lightweight SDK for Integrating AI Models and Plugins](https://thedataexchange.media/semantic-kernel/amp/)
- [Introducing Semantic Kernel: Building AI-Based Apps](https://www.linkedin.com/learning/introducing-semantic-kernel-building-ai-based-apps)
- [Building Skills with Semantic Kernel](https://www.linkedin.com/learning/building-skills-with-semantic-kernel)
- [Kernel Basics, Semantic Skills, and Embeddings | Intro to Semantic Kernel](https://www.youtube.com/watch?v=dAiER2OCH58)
- [Building AI apps with Java and Semantic Kernel! | Intro to Semantic Kerne](https://www.youtube.com/watch?v=_l1R1f-YuoAl)
- [08.16.2023 - Semantic Kernel Office Hours](https://www.youtube.com/watch?v=XUyN2p-IkvE)
- [08.30.2023 - Semantic Kernel Office Hours](https://www.youtube.com/watch?v=m5ylH57Rq4Y)
- [09.06.2023 - Semantic Kernel Office Hours](https://www.youtube.com/watch?v=vPZXBedjuXg)
- [09.12.2023 - Semantic Kernel Office Hours (Asia-Pacific Region)](https://www.youtube.com/watch?v=hwVfie6Bnb8)
- [09.20.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=WD7q8S2T2yc)
- [09.26.2023 - Semantic Kernel Office Hours (Asia-Pacific Region)](https://www.youtube.com/watch?v=KQAzl5KQyfc)
- [10.04.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=p_vtK7bcxqc)
- [10.10.2023 - Semantic Kernel Office Hours (Asia-Pacific Region)](https://www.youtube.com/watch?v=_5ofwSOzPmI)
- [10.11.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=dXsjqmW_7Uw)
- [10.18.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=2q9IhHYWTP0)
- [10.25.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=1LQ7m3lPoBk)
- [11.01.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=-CYTBc0VDVk)
- [11.08.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=pWt6wmRt5Ho)
- [11.15.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=qtyJEg8kLdc)
- [11.21.2023 - Semantic Kernel Office Hours (Asia-Pacific Region)](https://www.youtube.com/watch?v=PloQIND1jrI)
- [11.29.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=JSca9mVUUJo)
- [12.06.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=xhPMbja-_KM)
- [12.13.2023 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=Qv7cNIgl3Z0)
- [12.19.2023 - Semantic Kernel Office Hours (Asia-Pacific Region)](https://www.youtube.com/watch?v=N82nMDq38r8)
- [01.10.2024 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=TLlVkfTmmyQ)
- [01.17.2024 - Semantic Kernel Office Hours (Asia-Pacific Region)](https://www.youtube.com/watch?v=slvt4TDeRHA)
- [01.17.2024 - Semantic Kernel Office Hours (US/Europe Region)](https://www.youtube.com/watch?v=MbIBpP38PSw)
- [Introduction to Semantic Kernel and Microsoft Fabric! (feat. Kinfey Lo)](https://www.youtube.com/watch?v=mCn0ie0z7EM)
- [How to create a basic planner](https://www.youtube.com/watch?v=kdelXPl4i88)
- [How to create a sequential planner using semantic kernel](https://www.youtube.com/watch?v=r-atDSeqLaI)
- [New POWERSHELL Planner](https://www.youtube.com/watch?v=91-_7z5tFV8)
- [A deeper dive on PromptFlow and Semantic Kernel (feat. Matthew Bolanos)](https://www.youtube.com/watch?v=-maOEleJ1PE)
- [Newest video on OpenAI Function calling in SK! Should make plans more stable and reliable](https://youtu.be/yAiKBRecNTQ)
- [Introduction to Semantic Memory (feat. Devis Lucato) | Semantic Kernel](https://www.youtube.com/watch?v=5JYW_uAxwYM)
- [RPG Assistant: Helping Forgetful Game Masters' with AI Driven World Management By Bruno Borges, John](https://www.youtube.com/watch?v=xGvOUmeSczE)
- [Semantic Kernel: AI orchestration for intelligent apps By Bruno Borges, John Oliver](https://www.youtube.com/watch?v=8s3ddZ_Z8zg)
- [Cooking with Semantic Kernel: Recipes for Building Chatbots, Agents, and more with LLMs (2023)](https://www.youtube.com/watch?v=AX8xM9YnV3k)
- [Cozy AI Kitchen – Episode 1](https://www.youtube.com/watch?v=6Jr6z_YvJhc)
- [Cozy AI Kitchen – Episode 2](https://youtu.be/TZ8wHF9iiuM?si=4bkN1tUj3WxCLtpG)
- [Cozy AI Kitchen – Episode 3](https://youtu.be/vEXTWilW_sU?si=1VeVE1psho_M53_E)
- [More reliable AI plans with the Handlebars Planner! | Intro to Semantic Kernel](https://www.youtube.com/watch?v=2VF6fUJ-HJw) 📢  New Handlebars Planner! Watch Teresa show off the latest handlebars planner in v1.0 of the Semantic Kernel which offers more customization and reliability for AI-generated plans!

### Articles
- [Empowering AI with Semantic Kernel Planners for Seamless Orchestration](https://medium.com/@akshaykokane09/empowering-ai-with-semantic-kernel-planners-for-seamless-orchestration-1c7ad35f2337)
- [Unleashing the Power of Semantic Kernel and Azure Cognitive Search: A Step-by-Step Guide to Building Your Own ChatGPT-like App with Internal Data! — Part 1](https://medium.com/@akshaykokane09/how-to-build-custom-chatgpt-with-semantic-kernel-and-azure-cognitive-search-ef899afba0b9)
- [Unleashing the Power of Semantic Kernel and Azure Cognitive Search: A Step-by-Step Guide to Building Your Own ChatGPT-like App with Internal Data!— Part 2](https://medium.com/@akshaykokane09/how-to-build-chatgpt-like-app-with-semantic-kernel-and-azure-cognitive-search-on-internal-data-814e4694decb)
- [Running Large Language Models locally – Your own ChatGPT-like AI in C#](https://blog.maartenballiauw.be/post/2023/06/15/running-large-language-models-locally-your-own-chatgpt-like-ai-in-csharp.html)
- [GUEST POST: Getting Started with Semantic Kernel for LangChain users](https://devblogs.microsoft.com/semantic-kernel/getting-started-with-semantic-kernel-for-langchain-users/)
- [Create Semantic Kernel code & skills to build AI-powered apps with .NET](https://labs.thinktecture.com/create-semantic-kernel-code-skills-to-build-ai-powered-apps-with-net/)
- [Using (Azure) Open AI Models with Semantic Kernel behind a reverse proxy](https://labs.thinktecture.com/using-azure-open-ai-models-with-semantic-kernel-behind-a-proxy/)
- [Semantic Kernel and Weaviate: Orchestrating interactions around LLMs with long-term memory](https://devblogs.microsoft.com/semantic-kernel/guest-post-semantic-kernel-and-weaviate-orchestrating-interactions-around-llms-with-long-term-memory/)
- [The Power of Persistent Memory with Semantic Kernel and Qdrant Vector Database](https://devblogs.microsoft.com/semantic-kernel/the-power-of-persistent-memory-with-semantic-kernel-and-qdrant-vector-database/)
- [Unlock the Power of Telemetry in Semantic Kernel SDK](https://devblogs.microsoft.com/semantic-kernel/unlock-the-power-of-telemetry-in-semantic-kernel-sdk/)
- [Track Your Token Usage and Costs with Semantic Kernel](https://devblogs.microsoft.com/semantic-kernel/track-your-token-usage-and-costs-with-semantic-kernel/)
- [A Pythonista's Intro to Semantic Kernel](https://towardsdatascience.com/a-pythonistas-intro-to-semantic-kernel-af5a1a39564d)
- [Ask .NET Rocks! questions with Semantic Kernel, GPT, and Chroma DB](https://www.assemblyai.com/blog/ask-dotnetrocks-questions-semantic-kernel/) Develop an application that answers questions about .NET Rocks! using Semantic Kernel, GPT models, Chroma DB, and AssemblyAI transcriptions.
- [Advanced Reasoning in Semantic Kernel – Build Autonomous Agents](https://tsmatz.wordpress.com/2023/06/08/semantic_kernel_reasoning_for_autonomous_agent/)
- [AI Orchestrator Beyond LangChain](https://mlnotes.substack.com/p/ai-orchestrator-beyond-langchain)
- [Searching an internal Knowledge Base with OpenAI and Azure Cognitive Search](https://developer.volocopter.com/p/searching-an-internal-knowledge-base-with-openai-and-azure-cognitive-search/)
- [Intro to Semantic Kernel – Part One](https://blog.brakmic.com/intro-to-semantic-kernel-part-one/)
- [Intro to Semantic Kernel – Part Two](https://blog.brakmic.com/intro-to-semantic-kernel-part-two/)
- [Intro to Semantic Kernel – Part Three](https://blog.brakmic.com/intro-to-semantic-kernel-part-three/)
- [Intro to Semantic Kernel – Part Four](https://blog.brakmic.com/intro-to-semantic-kernel-part-four/)
- [Intro to Semantic Kernel – Part Five](https://blog.brakmic.com/intro-to-semantic-kernel-part-five/)
- [Intro to Semantic Kernel – Addendum](https://blog.brakmic.com/intro-to-semantic-kernel-addendum/)
- [Introducing Semantic Kernel](https://thwanisithole.co.za/posts/introducing-semantic-kernel/)
- [Build your AI First Apps with Semantic Kernel](https://arafattehsin.com/build-your-ai-first-apps-with-semantic-kernel/)
- [Evaluate your LLM Prompt Chains with Promptflow + Semantic Kernel!](https://www.youtube.com/watch?v=BlOBjm761I0)
- [Getting Started with Semantic Kernel and C#](https://accessibleai.dev/post/introtosemantickernel/)
- [How to enhance your chatbot so it can retrieve data from multiple data sources & orchestrate its own plan with C# Semantic Kernel, planner & Azure OpenAI – part 1](https://jordanbeandev.com/how-to-build-your-own-chatbot-using-c-semantic-kernel-azure-openai-part-1/)
- [Semantic Kernel: The New Way to Create Artificial Intelligence Applications](https://medium.com/globant/semantic-kernel-the-new-way-to-create-artificial-intelligence-applications-7959d5fc90ca)
- [If you are a .NET Developer, you are an AI Developer! (with Semantic Kernel)](https://www.linkedin.com/pulse/you-net-developer-ai-semantic-kernel-jose-luis-latorre-hlh4e/)
- [Getting Started with Semantic Kernel and C#](https://accessibleai.dev/post/introtosemantickernel/)
- [Using Semantic Kernel with an open-source LLM](https://www.developerscantina.com/p/semantic-kernel-open-source-llms/)

## Complement to this list

- [Open LLMs](https://github.com/eugeneyan/open-llms): A list of open LLMs available for commercial use ![GitHub Repo stars](https://img.shields.io/github/stars/eugeneyan/open-llms?style=social)
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM): Awesome-LLM: a curated list of Large Language Model resources. ![GitHub Repo stars](https://img.shields.io/github/stars/Hannibal046/Awesome-LLM?style=social)
- [LLaMA Cult and More](https://github.com/shm007g/LLaMA-Cult-and-More): Keeping Track of Affordable LLMs, 🦙 Cult and More ![GitHub Repo stars](https://img.shields.io/github/stars/shm007g/LLaMA-Cult-and-More?style=social)

## Known Users


## Stargazers over time

[![Stargazers over time](https://starchart.cc/microsoft/semantic-kernel.svg)](https://starchart.cc/microsoft/semantic-kernel)


