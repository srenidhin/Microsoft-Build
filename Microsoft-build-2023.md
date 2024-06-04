# Day 1

## Imagine Cup 

Imagine Cup is an annual competition sponsored and hosted by Microsoft Corp. which brings together student developers worldwide to help resolve some of the world’s toughest challenges. Teams :

**Tawi (Winner)** : Replace hearing aids with Android app to help kids communicate cost effectively with Speech to Text.

**CS-M** : Android app which works with special device which has a stethoscope in one end and 3.5mm jack on the other end. The app reports 6 types of heart conditions which is more than smartwatches, ECG and Oximeter.

**Eupnea** : Gamified App which detects Tuberculosis through AI coupled with a cough test, An end-to-end solution from Diagnosis to cure cost effectively.

## Opening Keynote

> "Computer is the bicycle for the brain, AI is the Steam engine"

### Codespaces & DevBox

GitHub Codespaces is a configurable development environment that's hosted in the cloud. It is a virtual machine that can be operated through your browser or through VSCode, allowing developers to get to work instantly. The Dev env can be stored on cloud for each user on the desired repo. 

Devbox is similar to Codespaces but for Azure Repos.

### Microsoft Copilot

Integrate ChatGPT into every application possible to reduce mind-numbing tasks and do tasks that are rewarding as a developer thereby increasing efficiency and joy in working. 

**GitHub Copilot** : Extension which mimics pair programming. Helps like Intellisense and Also uses NLP to suggest code from user request.

**Windows Copilot** : Controls lot of native apps. Ex: Timer, Viewport, Launch apps and many more.

**Bing Copilot** : ChatGPT is integrated into bing to improve searches. provides more control to developers on how the response are to be framed. provides citations for sources. 

**Plugins for Copilot** : Allows ChatGPT to fetch data from our applications thereby provide a seamless experience to users from query to solution. Ex: Buy groceries.

**Microsoft 365 Copilot** : This is pretty next level. I would recommend anyone who uses Word, Excel, PowerBi to take a good look at this. It can go through documents and comprehend it. It also has few legal plugins that can be utilized to write up contracts and agreements. Tracks website changes, So our kanban boards can be managed in teams with copilots help. Creates Microsoft graphs by comprehending the data from PowerBi.

## Azure AI Studio

Azure AI Studio is a new capability within the Azure OpenAI Service that lets customers combine a model like OpenAI’s ChatGPT or GPT-4 with their own data which will not be used to train Microsoft's Model which means our data & trained model is private to us. It is designed to help developers build their own AI copilots. It contains Azure Machine Learning Studio which is a GUI-based integrated development environment for constructing and operationalizing Machine Learning workflow.

### Azure AI Safety

Azure AI Content Safety is a content moderation platform which handles potentially offensive, risky, or undesirable content using content moderation ML models. Using this we can test models that were created and trained using our data.

### Microsoft Fabric

Microsoft Fabric is an all-in-one analytics solution for enterprises that covers everything from data movement to data science, Real-Time Analytics, and business intelligence. It offers a comprehensive suite of services, including data lake, data engineering, and data integration, all in one place. 

> "Better technology and more growth to improve lives all around the world"

## The Era of the AI Copilot

Copilots are application using Modern AI with conversational interface assisting our Cognitive tasks. 

### Interview with Greg Brockman, President & Co-founder of OpenAI

Greg talks about the founding days of OpenAI where the created WebGPT and hired contractors to test it and provide feedback which was not great but not bad either. Later they worked on it more and had GPT-3 which only worked with a certain set of instructions, He further mentions about the struggles they had to go through to one-up GPT-3 to create GPT-4 to his pleasant surprise GPT-4 was able to hold the context of the conversation unlike GPT-3. He also loves the idea of how plug-ins can extend the functionality of all AI's. For the future. He wants to extract every bit of potential from GPT-4 before we revolutionize AI by adding vision capabilities and reducing costs of GPT-4. 

> "Find new ways which would enhance AI to improve quality of life in your respective fields" - Greg Brockman

### Plug-ins

Foundation models are powerful and will gain more power but for the near future they can't do everything on their own. Plug-ins are a way for developers to achieve the end goal of AI with the existing foundation models. With Plug-ins AI can now access APIs, Use external information, perform new computations and act on-behalf of the user.

### Anatomy of a Copilot

Focus on the product not on the infra. In this case, the foundation models. Create great experiences with existing models. Depending on what works and what doesn't, there are multiple levels on the AI which can be configured to suit our purposes. For ex: Plugins can be made to work just from the front end of AI. If that doesn't work, there is a more definitive layer where we can make AI suit our needs like prompt & response filtering, Metaprompt, grounding and the way plugins interact. Safety is a key feature with AI as we don't want the AI to throw out sentences with negative impact. Azure has taken care of it with their strong foundational models and Azure AI safety. He proceeds to show an awesome demo of how AI can be used to create an ad post for a podcast. It uses the podcast voice data, finds guests in the podcast, looks up guest on the internet, creates a blurb, creates an image with DALL-E 2.0 and then posts it to social media automatically after a confirmation from user.

## Next-gen AI for developers with Microsoft Cloud

Revolutionize apps with AI and app development platforms like VSCode, Visual Studio with AI. Github already has Github Copilot

### Github Copilot X 

New update to run it on GPT-4. Helps with Chat, Auto pull requests and Automatic test generation. Followed by a demo of Copilot X featuring NLP code suggestion and syntax fixes and early access to Copilot X

**Create a Plug-in demo & Plug-in build to deploy demo**

### Azure OpenAI Services

Azure OpenAI Service is a cloud-based platform that allows developers to easily integrate state-of-the-art AI models into their applications. Azure OpenAI Service gives customers advanced language AI with OpenAI GPT-3, Codex, and DALL-E models with the security and enterprise promise of Azure. Azure OpenAI Service provides REST API access to OpenAI’s powerful language models including the GPT-3, Codex and Embeddings model series.

**Create your first private Copilot demo**

### Prompt-flow AI

Azure Prompt Flow is a powerful feature within Azure Machine Learning (AzureML) that streamlines the development, evaluation, and continuous integration and deployment (CI/CD) of prompt engineering projects. With prompt flow, we can quickly create prompt workflows that connect to various language models and data sources. This allows for building intelligent applications and assessing the quality of our workflows to choose the best prompt for our case.

### Responsible AI

They talk about how AI needs to be kept in check with regards to the tone, vocabulary and responses that are used to help the user.

### Azure AI Supercomputer

They showcase their new in-house developed AI warehouse the size of 45 football stadiums and explain their new tech like NVidia hopper based GPUs and infinity cables and how it help maximize scalability and performance. They also talk about sustainability within their 120 Data warehouses in 60+ countries and how they plan on being 100% sustainable by 2025.

### Nvidia Omniverse Cloud

Create digital twins of robots and live simulations to truly recreate a plant in virtual world. Also helps is optimizing layout and simulating robots

**Great demo of Copilot leveraging Microsoft Graphs to visualize data through PowerBi with the help of Microsoft Fabric**

## Developer Experience

**Demo for Github CoPilot on Github, Visual Studio 2022**

**Demo for DevBox**

### Azure Load testing

Azure Load Testing is a fully managed load-testing service that enables us to generate high-scale load. The service simulates traffic for our applications, regardless of where they’re hosted. We can use it to optimize application performance, scalability, or capacity. During the load test, the service collects the following resource metrics and displays them in a dashboard: Client-side metrics give you details reported by the test engine. These details include the number of virtual users and Server-side metrics provide information about our Azure application.

# Day 2

## Opening Note

Allow AI to reduce workload which grants developers the time they need to innovate.

### Microsoft 365 Copilot

We can use the Copilot chat in Teams to catch up on outlook mail. It can go through graphs, calendar and Microsoft Dataverse to retrieve data and present it to us when we need it. Plugins for this copilot using different connectors is also possible. Lastly a demo on how to create a 365 copilot plugin.

### Microsoft Graph

Microsoft Graph is the gateway to data and intelligence in Microsoft 365. It provides a unified programmability model that you can use to access the tremendous amount of data in Microsoft 365, Windows, and Enterprise Mobility + Security. Microsoft Graph exposes REST APIs and client libraries to access data on the following Microsoft cloud services: Microsoft 365 core services: Bookings, Calendar, Delve, Excel, Microsoft 365 compliance eDiscovery, Microsoft Search, OneDrive, OneNote, Outlook/Exchange, People (Outlook contacts), Planner, SharePoint, Teams, To Do, Viva Insights

**Demo of 365 copilot with Graph and Sematic index**

**Demo of 365 Copilot with MS Word**

**SAP Success factor links with 365 Copilot in word**

### Microsoft Syntex Plugin

Microsoft Syntex plugins for Copilot brings content management skills to M365 experiences. It analyses and presents valuable data 

## Developer Success

Help IT teams to deploy apps to developer hardware, Use company license for automatic activation. Provide a suitable enviornment for developers in the IDE. Also, Helps developers reach customers through consistent app store. License management and revenue management for apps sold through app store.

### Microsoft Mesh

Microsoft's answer to Meta's Metaverse and their version of VR office enviroment. Avatar, Positional Audio with VR experience.

### Microsoft Windows 11

Recap of copilot features from Day 1. In windows 11, UI/ UX development for CoPilot and the 3 different ways we can integrate AI with native apps. New Experiences of WhatsApp in windows 11. New features of Windows 11 :

    1.DevHome
    2.DevDrive
    3.Dashboard
    4.Compress to multiple formats including tar.gz
    5.End non responding task from task bar
    6.Windows terminal can split into multiple tabs
    7.Github copilot X integrated with terminal
    8.new Widgets, Pin widget in board and new layouts for board
    9.App restore
    10.Windows Subsystem for Android
    11.Ads for apps in Microsoft Store
    12.AI feedback of Apps from reviews
    13.Windows AI Library
    14.ONNX Runtime
    15.Camo
    16.Olive toolchain
    17.Nvidia NPU & GPU
    18.ORT-Web
    19.Luminar Neo

## Great Seminar by Steven Bathiche

He talks about how people how interacted with computers and how we need to design new apps with AI in mind and the ways to integrate seamlessly the AI and our app in the UI. The future of programming would be pragmatic and piloted 

**Hands-On session on DevHome**

*That's it from Microsoft Build 2023*
