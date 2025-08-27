📞 AI Calling Agent with n8n + Retell AI

This project showcases an AI-powered calling agent built with n8n and Retell AI. The agent automatically calls leads from a Google Spreadsheet, conducts live conversations, generates a summary of each call, and then sends the summary via email as well as appends it to the same spreadsheet.

🔹 Features

📞 Automated Calls – Calls leads directly using Retell AI.

🤖 Conversational AI – Engages in two-way conversations with leads.

📝 Call Summarization – Generates concise summaries of conversations.

📧 Email Integration – Sends call summaries to your email inbox.

📊 Spreadsheet Updates – Appends the summary into a dedicated column in Google Sheets.

🔄 End-to-End Automation – Entire process managed through n8n workflows.

🔹 Tech Stack

n8n
 – Workflow automation

Retell AI
 – AI calling agent

Google Sheets
 – Lead storage & call logs

Email Service (SMTP / Gmail / Outlook) – For sending call summaries

🔹 How It Works

Trigger Node (Google Sheets) – Reads leads from the spreadsheet.

Retell AI Node (HTTP Request) – Initiates a phone call with the lead.

Summarization (Gemini / GPT) – Summarizes the call conversation.

Email Node – Sends the summary to a configured email address.

Google Sheets Update Node – Appends the summary into the spreadsheet’s “Summary” column.

🔹 Example Use Cases

Sales & lead nurturing via automated calls.

Appointment confirmation with summary records.

Customer support follow-ups with logged conversations.

Feedback collection with AI summaries.

🔹 Getting Started

Clone this repository.

Import the n8n workflow JSON into your n8n instance.

Add credentials for:

Google Sheets

Retell AI API

Email Service

Configure the spreadsheet with lead details (Name, Phone Number, etc.).

Run the workflow and let the AI agent handle calls + summaries 🚀.

🔹 Future Improvements

Multi-language calling support.

CRM integration (HubSpot, Salesforce, Zoho).

Advanced AI summaries with sentiment analysis.

Voice customization for better personalization.

⚡ With this automation, businesses can save time, scale lead engagement, and maintain structured records of every conversation.
