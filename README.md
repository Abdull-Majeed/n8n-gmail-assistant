# n8n-gmail-assistant
This n8n workflow connects Telegram with Gmail and Google Gemini AI to automate email summarization and professional email replies using AI. Users can send text or voice messages via Telegram, and the workflow will summarize unread emails or help compose and send new emails—all powered by Google Gemini.

##  Features

- **Telegram Integration:** Trigger actions from Telegram messages (text or voice).
- **Voice Transcription:** Automatically transcribes voice messages using Google Gemini.
- **AI Summarization:** Summarizes unread Gmail messages in a concise, professional format.
- **AI Email Writing:** Compose and send professional emails directly from Telegram.
- **Customizable Prompts:** Easily adjust AI instructions for your needs.

---

##  Setup Instructions

1. **Import the Workflow**
   - Download the `my-workflow.json` file from this repository.
   - In your n8n editor, click **Import** and select the JSON file.

2. **Configure Credentials**
   - Set up the following credentials in n8n:
     - **Telegram API** (for Telegram Trigger and Send nodes)
     - **Gmail OAuth2** (for Gmail nodes)
     - **Google Gemini (PaLM) API** (for AI nodes)
     
3. **Update Placeholders**
   - Replace any placeholder values (e.g., chat IDs, webhook URLs) with your own.

---

##  Required Credentials

| Service         | Credential Name         | Usage                        |
|-----------------|------------------------|------------------------------|
| Telegram        | Telegram API           | Triggers and sends messages  |
| Gmail           | Gmail OAuth2           | Reads and sends emails       |
| Google Gemini   | Google Gemini (PaLM)   | AI transcription & chat      |

---

##  Usage

- **Summarize Emails:**  
  Send a text or voice message in Telegram to trigger email summarization. The workflow will reply with a summary of your unread emails.

- **Send Emails:**  
  Use the provided Telegram commands to compose and send professional emails via Gmail, with AI assistance.

---

##  Contributing

Feel free to open issues or submit pull requests to improve this workflow!

---

How to use:

 - Replace my-workflow.json with your actual file name if different.
 - Edit the description and features to match your workflow’s specifics.
 - Add or remove sections as needed.
