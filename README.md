# Musfira AI Usage metrics API adds usage from tools like OpenCode - By Musfira AI

> Curated, written, and published by **Musfira AI**.

## Overview

The Copilot usage metrics API now provides a comprehensive view of model usage across a wider range of tools and environments. Previously, it only reported usage from the OpenAI API. Now, it includes tools like OpenCode, which are integral parts of many development workflows. This expansion is significant because it ensures that developers can understand how their projects are evolving and the impact of their decisions on the model's performance. For instance, if a developer frequently uses OpenCode for static code analysis, the API will show a clear picture of how frequently the model is being utilized for that specific purpose, helping them optimize their workflows and potentially improving the quality of the insights provided by the model.

**Source reference:** [https://github.blog/changelog/2026-10-23-usage-metrics-api-adds-usage-from-tools-like-opencode](https://github.blog/changelog/2026-10-23-usage-metrics-api-adds-usage-from-tools-like-opencode)
**Published:** 2026-10-27

## Key Features

- The Copilot usage metrics API now includes model usage from tools like OpenCode.
- It captures data from various development environments, including those outside of the typical CLI and web-based interfaces.
- This comprehensive view helps developers identify inefficiencies in their workflows, leading to better performance optimization.
- Developers can now track the model's usage in real-time, enabling them to make informed decisions based on usage patterns.
- The API also supports the visualization of usage trends, allowing developers to monitor the model's performance over time and identify improvements needed.

## Use Cases

A developer working on a project that heavily relies on OpenCode for static code analysis might experience significant benefits from this new feature. Prior to its implementation, the model's usage in this context was not tracked, leading to a lack of visibility into how often and how efficiently the model was being utilized. With the Copilot usage metrics API now reporting usage from OpenCode, the developer can now track the model's performance specifically for this tool, which is particularly important for projects requiring static code analysis. This real-time data has already led to the developer optimizing their workflows, reducing the time spent on rework and improving the overall quality of the static analysis done by the model.

## Quickstart

### Python

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

### n8n Workflow

Import `workflow.json` into your n8n instance via **Workflows > Import from File**.

### Local LLM (Ollama)

```bash
ollama pull llama3
ollama run llama3
```

To set up the Copilot usage metrics API and start tracking model usage, developers should first ensure that the API is integrated with their development environment. This involves configuring the API to track usage from all relevant tools, including those outside of the traditional CLI or web-based interfaces. Next, developers should set up the API to send data to a monitoring tool or dashboard. This can be done by configuring the API to forward data to a specific endpoint on the dashboard, which can then visualize and analyze usage trends. Finally, developers should regularly check the dashboard to ensure that the model's usage is being accurately tracked and to make necessary adjustments to their workflows based on the data provided.

## FAQ

To fully utilize the Copilot usage metrics API and gain insights into model usage, developers should ensure that their environments are configured to capture data from all relevant tools. This includes setting up the API to track usage from all development environments, including those outside of the traditional command-line interface. Additionally, developers should consider using the API to visualize usage trends and real-time data, which can provide immediate feedback on the model's performance and help identify areas for improvement. This setup can be achieved by integrating the API with a monitoring tool or dashboard, which can then provide comprehensive reports and visualizations of model usage across various tools and environments.

## Repository Structure

```
.
├── main.py
├── requirements.txt
├── workflow.json
├── ui/
│   └── index.html
└── README.md
```

## About Musfira AI

Musfira AI builds automation systems, AI agents, and YouTube automation pipelines for
creators and businesses across Pakistan and India.

- 🌐 Website: [https://musfiraai.com](https://musfiraai.com)
- ▶️ YouTube: [Automate With Musfira AI](https://www.youtube.com/@automatewithmusfiraai)
- 💼 LinkedIn: [https://www.linkedin.com/in/musfira-ai-b3218b39b](https://www.linkedin.com/in/musfira-ai-b3218b39b)
- 📸 Instagram: [https://instagram.com/musma_n55](https://instagram.com/musma_n55)
- 📍 Location: [Google Maps](https://share.google/kJchUsfQyABVLghSF)
- 💬 WhatsApp: [Chat with us](https://wa.me/923217358096)
- 📞 Call: [+923217358096](tel:+923217358096)

---

*This repository is part of Musfira AI's daily AI trend tracking series. Star ⭐ this repo
and follow the links above for daily updates on AI models, n8n workflows, and local LLM tools.*
