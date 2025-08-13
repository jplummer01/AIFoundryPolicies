Here's a formatted version of the text for your README.md file on GitHub:

---

# Disable Preview Items in AI Foundry

This guide explains how to disable current and future public preview items (such as Agents, Templates, Tracing, Healthcare Playground, and more) from AI Foundry by adding a specific tag to your Azure AI projects (Hub resource and AI Foundry resource) and Azure OpenAI Service.

## Steps to Disable Preview Items

1. **Enforce Tagging with Azure Policy**: You can enforce adding this tag `AZML_DISABLE_PREVIEW_FEATURE:TRUE` by adding the Azure Policy available in this repo.

## Applicable Services

- **Azure OpenAI Service**
- **Azure AI Hub Resource Projects**
- **Azure AI Foundry Resource Projects**

## Resource Types and Kinds

- **Type**: `Microsoft.CognitiveServices/accounts` - **Kind**: `OpenAI`
- **Type**: `Microsoft.MachineLearningServices/workspaces` - **Kind**: `Project`
- **Type**: `Microsoft.CognitiveServices/accounts/projects` - **Kind**: `AIServices`

## Visual Representation

In the image below, you can see the preview items listed in the left blade of AI Foundry projects:

Before Applying Tag : 
![Before Applying Tag](https://raw.githubusercontent.com/shivangvora39/AIFoundryPolicies/main/images/AIFoundryBeforeTag.jpg)

After Applying Tag : 
![After Appluing Tag](https://raw.githubusercontent.com/shivangvora39/AIFoundryPolicies/main/images/AIFoundryAfterTag.jpg)
