<a name="start-building"></a>
<br>
<p align="center">
<img src="img/banner-build-26.png" alt="Microsoft Build 2026" width="1200"/>
</p>

# [Microsoft Build 2026](https://build.microsoft.com)

## BRK252: From observability to ROI for AI agents on any framework

Nondeterministic, multi-agent systems break traditional monitoring. As agents reach production, observability must be built in—not added after failures. This session covers modern agent observability: cross-framework tracing and evals, rigorous inner-loop practices, evolving context-specific evals, and always-on signals that connect behavior to business outcomes to measure value, cost, and ROI.

| |
|:---:|
| [ ![Thumbnail](./img/BRK252-thumbnail.jpg) ](https://build.microsoft.com/en-US/sessions/brk252)|


| | |
|:---------|:------------|
| [Watch the Session Replay](https://aka.ms/build26/BRK252/youtube) | BRK252: From observability to ROI for AI agents on any framework|
| [Complete the Hands-On Lab](https://github.com/microsoft/Build26-LAB540-observe-optimize-and-protect-your-hosted-agents-in-microsoft-foundry) | LAB540: Observe, optimize and protect your hosted agents in Microsoft Foundry |
| [Read The Dev Blog Post](https://devblogs.microsoft.com/foundry/build-2026-from-observability-to-roi-for-ai-agents-on-any-framework/) | Build 2026: From observability to ROI for AI agents on any framework |
| [Download The Session Slides](https://medius.microsoft.com/video/asset/PPT/bc75ad49-f354-49ee-a449-69cb12bcf5fb?referrer=Microsoft+Build-%2Fen-US%2Fsessions%2Fbrk252&mhid=build&uid=1768245294609build26-1756141269010001LleM) | BRK252 "Download Slides" Link From Session Page |
| | |

<br/>

## Session Overview

**Reliable AI Agent development needs observability**. Agents are inherently non-deterministic, creating new challenges in reliability and consistency for developers and operators. Delivering trustworthy solutions requires a unified end-to-end observability platform that can help you understand and optimize the cost, health and behavior of agents in real time.

![Overview](./img/BRK252-focus.png)

In this session, you will walk through the end-to-end agent devops lifecycle with a focus on using observability tools and workflows to go from prototype to production. You will get started with out-of-the-box observabilty (plan-code-test-release) - then fast forward to production (monitor, analyze, optimize) and learn to hill climb with confidence using the new Foundry Optimizer capability -- **with live demos at each step** that show you how to:

 - observe any agent, on any framework - with tracing and evals
 - get code-first observability - with skills-based guided experiences
 - optimize for scale - with Foundry Optimizer to do your hill climbing
 - prove the value of your product - with Agent ROI using portal and API


![Ops](./img/BRK252-agent-devops-roi.png)

<br/>

## Learning Outcomes


By the end of this session you will be able to:
- Apply cross-framework tracing and evaluation techniques to gain visibility into nondeterministic, multi-agent systems
- Establish rigorous inner-loop practices that build observability into agents before they reach production
- Design and evolve context-specific evals that keep pace with changing agent behavior and requirements
- Connect always-on production signals to business outcomes to measure agent value, cost, and ROI
- Optimize for scale with a unified end-to-end observability capabilities

<br/>

## Keep Learning with Copilot

> _Try these prompts in GitHub Copilot Chat to explore topics in more detail. Open a new chat session in Visual Studio Code (`Ctrl+Alt+I` on Windows/Linux, `Cmd+Shift+I` on Mac) and use a prompt below as a starting point - or write your own! 💡 Tip: connect the [Microsoft Learn MCP Server](#-microsoft-learn-mcp-server) first to ground responses in official docs.

| Topic | Prompt |
|:---|:---|
| **Distributed tracing in Microsoft Foundry** | Walk me through how to enable distributed tracing for an AI agent in Microsoft Foundry, including how to view thread results and spans across tools and model calls. Reference [Trace and observe AI agents in Microsoft Foundry](https://learn.microsoft.com/azure/foundry-classic/how-to/develop/trace-agents-sdk) and [Observability in the Agent Framework](https://learn.microsoft.com/agent-framework/agents/observability) |
| **Cross-framework observability**| Explain the core observability capabilities in Microsoft Foundry and how they cover the three stages of the AI application lifecycle (ideate, build, operate) for multi-agent systems. Ground your answer in [Observability in generative AI](https://learn.microsoft.com/azure/foundry/concepts/observability).|
| **Evals from inner loop to production**| Show me how to run cloud evaluations with the Microsoft Foundry SDK and connect trace data to evaluation results so I can evolve context-specific evals as my agent changes. Use [Run evaluations in the cloud by using the Microsoft Foundry SDK](https://learn.microsoft.com/azure/foundry/how-to/develop/cloud-evaluation) as the source. |
| *Connecting observability to ROI**| How do I use the Agent Monitoring Dashboard and fleet-wide monitoring in Microsoft Foundry together with cost optimization to measure agent value, cost, and ROI in production? Reference [Monitor agents with the Agent Monitoring Dashboard](https://learn.microsoft.com/azure/foundry/observability/how-to/how-to-monitor-agents-dashboard), [Monitor agent health and performance across your fleet](https://learn.microsoft.com/azure/foundry/control-plane/monitoring-across-fleet), and [Optimize model cost and performance](https://learn.microsoft.com/azure/foundry/control-plane/how-to-optimize-cost-performance). |
| | |

<br/>


## Technologies Used

1. [Microsoft Foundry](https://learn.microsoft.com/azure/foundry/agents/overview) — the unified platform for building, deploying, and managing AI agents
1. [Microsoft Foundry Control Plane](https://learn.microsoft.com/azure/foundry/control-plane/overview) — manage and monitor agent fleets at scale across environments
1. [Microsoft Foundry Observability](https://learn.microsoft.com/azure/foundry/concepts/observability) — tracing, evaluations, and monitoring across the agent lifecycle

<br/>

## Related Resources

| Resource | Description |
|:---|:---|
| [Microsoft Foundry Agent Service](https://learn.microsoft.com/azure/foundry/agents/overview) | Build, deploy, and manage AI agents on Microsoft Foundry |
| [Microsoft Agent Framework](https://learn.microsoft.com/agent-framework/overview/) | Open framework for building single- and multi-agent systems across .NET and Python |
| [Microsoft Agent Framework Workflows](https://learn.microsoft.com/agent-framework/workflows/) | Orchestrate multi-agent workflows with durable, observable execution |
| [Observability in generative AI](https://learn.microsoft.com/azure/foundry/concepts/observability) | Core observability capabilities across the ideate, build, and operate stages |
| [Trace and observe AI agents in Microsoft Foundry](https://learn.microsoft.com/azure/foundry-classic/how-to/develop/trace-agents-sdk) | Enable distributed tracing for agents and inspect spans in the Foundry portal |
| [Agent Framework observability](https://learn.microsoft.com/agent-framework/agents/observability) | OpenTelemetry-based tracing and logging for agents across frameworks |
| [Run cloud evaluations with the Foundry SDK](https://learn.microsoft.com/azure/foundry/how-to/develop/cloud-evaluation) | Run continuous, context-specific evals tied to trace data |
| [View evaluation results in the Foundry portal](https://learn.microsoft.com/azure/foundry/how-to/evaluate-results) | Compare runs and track quality, safety, and performance over time |
| [Monitor agents with the Agent Monitoring Dashboard](https://learn.microsoft.com/azure/foundry/observability/how-to/how-to-monitor-agents-dashboard) | Always-on production signals for a single agent |
| [Monitor agent health across your fleet](https://learn.microsoft.com/azure/foundry/control-plane/monitoring-across-fleet) | Cross-agent monitoring for production operations |
| [Optimize model cost and performance](https://learn.microsoft.com/azure/foundry/control-plane/how-to-optimize-cost-performance) | Connect observability signals to cost and ROI decisions |
| [Plan and manage costs for Microsoft Foundry](https://learn.microsoft.com/azure/foundry/concepts/manage-costs) | Budgeting and cost monitoring for Foundry workloads |
| [https://aka.ms/build26-next-steps](https://aka.ms/build26-next-steps) | Explore lab and session repos to further your learning from Microsoft Build |

<br/>

### 🌟 Microsoft Learn MCP Server

The Microsoft Learn MCP Server gives your AI agent direct access to Microsoft's official documentation — grounded, up-to-date answers about the products and services covered in this session.

**VS Code** — One click installation: 

[![Install in VS Code](https://img.shields.io/badge/VS_Code-Install_Microsoft_Learn_MCP-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://vscode.dev/redirect/mcp/install?name=microsoft-learn&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Flearn.microsoft.com%2Fapi%2Fmcp%22%7D)


**GitHub Copilot CLI** — Run this to install the Learn MCP Server as a plugin:
```
/plugin install microsoftdocs/mcp
```

For more info, other clients, and to post questions, visit the [Learn MCP Server repo](https://aka.ms/learnmcp).

## Content Owners

<table>
<tr>
    <td align="center"><a href="https://github.com/skohlmeier123">
        <img src="https://github.com/skohlmeier123.png" width="100px;" alt="Sebastian Kohlmeier"/><br />
        <sub><b>Sebastian Kohlmeier</b></sub></a><br />
            <a href="https://github.com/skohlmeier123" title="talk">📢</a>
    </td>
    <td align="center"><a href="https://github.com/fubaduba">
        <img src="https://github.com/fubaduba.png" width="100px;" alt="Filisha Shah"/><br />
        <sub><b>Filisha Shah</b></sub></a><br />
            <a href="https://github.com/fubaduba" title="talk">📢</a>
    </td>
    <td align="center"><a href="https://github.com/vbhadauria">
        <img src="https://github.com/vbhadauria.png" width="100px;" alt="Vivek Bhadauria"/><br />
        <sub><b>Vivek Bhadauria</b></sub></a><br />
            <a href="https://github.com/vbhadauria" title="talk">📢</a>
    </td>
</tr></table>

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreements](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
