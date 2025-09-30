<p align="center">
<img src="img/Banner-MS-AI-Tour-26.png" alt="decorative banner" width="1200"/>
</p>

# [Microsoft AI Tour 2026](https://aitour.microsoft.com)

## BRK462: Enable agentic AI apps with a unified data estate in Microsoft Fabric

If you will be delivering this session, check the [session-delivery-sources](./session-delivery-resources/) folder for slides, scripts, and other resources.

### Session Description

This session explores how organizations can enable agentic AI applications by unifying their data estate using Microsoft Fabric. Through the story of Zava, a regional DIY retailer, the session demonstrates how fragmented data systems can be modernized, integrated, and made AI-ready. Attendees will see practical demos covering data unification, transformation, governance, CI/CD for data products, and the integration of AI-powered experiences, all while maintaining robust security and compliance.


### 🧠 Learning Outcomes

By the end of this session, learners will be able to:

- Understand the challenges of fragmented data estates and the benefits of unification with Microsoft Fabric.
- Learn how to ingest, transform, and govern data using Fabric features like OneLake, shortcuts, and mirroring.
- Gain practical knowledge of implementing CI/CD for data products and analytics workflows in Fabric.
- Discover how to embed AI and Copilot capabilities for both technical and business users, including real-time analytics, natural language queries, and data agents.
- Recognize best practices for securing data and AI workloads in a unified platform.

### 💻 Technologies Used

1. Microsoft Fabric (including OneLake, Data Factory, Power BI, Real-Time Intelligence, Copilot, Data Agents, CI/CD integration)
1. Databricks (catalog mirroring with Fabric)
1. GitHub and Azure DevOps
1. Microsoft Teams and Copilot Studio

### 🎬 Demos

| # | Demo | Description | Git repository URL |
|---:|------|-------------|--------------------|
| 1 | Shortcuts transformations | See how you can access data from outside Fabric, and transform it without code. | https://github.com/microsoft/shortcut_transfroms-ai-tour-demos-fy26 |
| 2 | CI/CD Integration | Showcase a full CI / CD Setup with Fabric and Azure DevOps and GitHub Actions | https://github.com/cmaneu/fabric-ci-cd-demo |
| 3 | Real-Time Anomaly Detection | No-Code Anomaly detection on Realtime data | https://github.com/microsoft/anomaly-detection-ai-tour-demos-fy26- |
| 4 | AI Data Enrichment | Use AI Functions to enrich and analyze your data | https://github.com/microsoft/ai-in-fabric-ai-tour-demos-fy26 |
| 5 | PowerBI Copilot Experience |  | https://github.com/microsoft/ai-in-fabric-ai-tour-demos-fy26 |
| 6 | Databricks and Fabric Data Agents | Use data from Databricks inside a Copilot Studio-powered Data agent | https://github.com/cmaneu/databricks-fabric-data-agents |

### 🔗 Session Resources
| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| Lab - Securing a Microsoft Fabric Environment | https://github.com/cmaneu/WorkshopPowerBI/blob/main/Lab9%20-%20EN%20-%20Securing%20a%20Microsoft%20Fabric%20Environment.md | This workshop provides a step-by-step guide to securely deploying a Microsoft Fabric environment with Spark Notebooks, ensuring all access to resources like Azure Data Lake and Key Vault is restricted to an organization's internal network using Private Link, private endpoints, and disabled public internet access for maximum data protection and compliance. |
| Free Book - PySpark in Fabric | https://pyspark-fabric.maneu.net/ | A practical guide to Data Engineering tasks with PySpark in Microsoft Fabric |
| Sample - Open Mirroring | https://github.com/cmaneu/fabric-open-mirroring-sample | A complete sample about Microsoft Fabric Open mirroring feature. |

### 📚 Continued Learning Resources
| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| AI Tour 2026 Resource Center | https://aka.ms/AITour26-Resource-Center | Links to all repos for AI Tour 26 Sessions |
| Azure AI Foundry Community Discord | [![Microsoft Azure AI Foundry Discord](https://dcbadge.limes.pink/api/server/Pwpvf3TWaw)](https://discord.gg/Pwpvf3TWaw)| Connect with the Azure AI Foundry Community! |
| Learn at AI Tour | https://aka.ms/LearnAtAITour | Continue learning on Microsoft Learn |

### 🌐 Multi-Language Support

Additional Languages are coming soon.

## Content Owners

<table>
<tr>
    <td align="center"><a href="http://github.com/toolboc">
        <img src="https://github.com/toolboc.png" width="100px;" alt="Paul DeCarlo" /><br />
        <sub><b> Paul DeCarlo
        </b></sub></a>
        <br />
        <a href="https://github.com/toolboc" title="talk">📢</a> 
    </td>
    <td align="center"><a href="http://github.com/dikodev">
        <img src="https://github.com/dikodev.png" width="100px;" alt="Someleze Diko" /><br />
        <sub><b> Someleze Diko
        </b></sub></a>
        <br />
        <a href="https://github.com/dikodev" title="talk">📢</a> 
    </td>
    <td align="center"><a href="http://github.com/cmaneu">
        <img src="https://github.com/cmaneu.png" width="100px;" alt="Christopher MANEU""/><br />
        <sub><b> Christopher Maneu
        </b></sub></a>
        <br />
        <a href="https://github.com/cmaneu" title="talk">📢</a> 
    </td>
    <td align="center"><a href="http://github.com/iemejia">
        <img src="https://github.com/iemejia.png" width="100px;" alt="Ismaël Mejía""/><br />
        <sub><b> Ismaël Mejía </b></sub></a>
        <br />
        <a href="https://github.com/iemejia" title="talk">📢</a> 
    </td>
    <td align="center"><a href="http://github.com/Jcardif">
        <img src="https://github.com/Jcardif.png" width="100px;" alt="Josh Ndemenge" /><br />
        <sub><b> Josh Ndemenge </b></sub></a>
        <br />
        <a href="https://github.com/Jcardif" title="talk">📢</a> 
    </td>

</tr></table>

## Responsible AI 

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. Within Azure AI Foundry portal, the Content Safety service allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [Performance and Quality and Risk and Safety evaluators](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in). You also have the ability to create and evaluate with [custom evaluators](https://learn.microsoft.com/azure/ai-studio/how-to/develop/evaluate-sdk#custom-evaluators).

You can evaluate your AI application in your development environment using the [Azure AI Evaluation SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the azure ai evaluation sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Foundry portal ](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results).
