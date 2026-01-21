# N8N-workflows
# 🚀 n8n Automation Collection

A collection of professional n8n workflows for email processing, lead enrichment, and automated screenshot generation.

## 📂 Repository Structure
* **/PNG-By-MessageID**: Generates a PNG screenshot from a Gmail message HTML via Webhook.
* **/TG-Notifications-Clients**: Automated parser for Payment/Any Other emails with Telegram alerts.
* **/Lead-Enrichment**: Advanced lead scoring and enrichment pipeline (HubSpot/Google Sheets).

## 🛠️ Requirements & Setup
To use these workflows, you need:
1. **n8n Instance**: Self-hosted (recommended) or Cloud.
2. **Credentials**: You will need to configure your own:
    * [Google OAuth2](https://console.cloud.google.com/) (Gmail & Sheets API)
    * [Telegram Bot API](https://t.me/botfather)
    * [HubSpot Access Token](https://developers.hubspot.com/) (for Lead Enrichment)

## ⚠️ Self-Hosted vs Cloud
> [!IMPORTANT]
> Some workflows (like the PNG Screenshot generator) use the **Puppeteer** node. This requires a **Self-Hosted** n8n instance because it needs a browser installed in the environment. If you use n8n Cloud, check their documentation for compatible alternatives or custom Docker images.

---
