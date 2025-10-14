# AI Powered Email Automation Workflow:
Built an intelligent Gmail automation system using n8n, Gmail API, and OpenAI to auto-draft, review, and approve email replies, reducing manual effort through human-in-the-loop workflow automation.


## 🚀 Features

-  **Automatic Email Drafting:** Uses OpenAI to generate smart responses to incoming emails.  
-  **Human-in-the-loop Approval:** Allows users to review, edit, or reject AI responses before sending.  
-  **Seamless Gmail Integration:** Connected through the Gmail API with OAuth2 authentication.  
-  **Workflow Automation:** Entire process orchestrated via n8n’s node-based automation engine.  
-  **Dynamic Decision System:** Webhook-driven approval and edit actions with instant feedback.  

## 🏗️ Tech Stack

- **n8n** — Workflow automation platform  
- **OpenAI GPT API** — For AI-generated email replies  
- **Gmail API** — To fetch, draft, and send emails  
- **Webhook / Express Server** — For edit, approve, and reject interactions  
- **Node.js** — For backend support and hosting  



## 🧭 Workflow Overview

1. **Trigger:** Gmail Trigger node detects a new incoming email.  
2. **AI Draft:** Message content is sent to OpenAI for generating a suggested reply.  
3. **Human Review:** Reviewer receives options to _Approve_, _Edit_, or _Reject_ the AI draft.  
4. **Webhook Form:** If _Edit_ is selected, an editable form allows message modification.  
5. **Send Email:** Approved or edited message is sent automatically through Gmail API.  


