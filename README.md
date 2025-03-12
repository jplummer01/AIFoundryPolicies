Here's a formatted version of the text for your README.md file on GitHub:

---

# Disable Preview Items in AI Foundry

This guide explains how to disable current and future public preview items (such as Agents, Templates, Tracing, Healthcare Playground, and more) from AI Foundry by adding a specific tag to your Azure AI projects and Azure OpenAI Service.

## Steps to Disable Preview Items

1. **Enforce Tagging with Azure Policy**: You can enforce adding this tag `AZML_DISABLE_PREVIEW_FEATURE:TRUE` by adding the Azure Policy available in this repo.

## Applicable Services

- **Azure OpenAI Service**
- **Azure AI Project**

## Resource Types and Kinds

- **Type**: `Microsoft.CognitiveServices/accounts` - **Kind**: `OpenAI`
- **Type**: `Microsoft.MachineLearningServices/workspaces` - **Kind**: `Project`

## Visual Representation

In the image below, you can see the preview items listed in the left blade of AI Foundry projects:

*An external link was removed to protect your privacy.* 
Once the tag is applied to the Azure AI Project, the preview items will no longer be visible:

*An external link was removed to protect your privacy.* 
---

Please replace `path_to_image` with the actual path to your images. Let me know if you need any further assistance!
