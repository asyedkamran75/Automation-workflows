# Automation Workflows

This repository showcases automation and AI-agent workflows I've built using n8n, demonstrating practical applications of AI in business processes. Each project includes a ready-to-import workflow file along with an explanation of how it works.

## Projects

### 🤖 RAG Chatbot
An end-to-end AI-powered chatbot that retrieves relevant information from a custom knowledge base before generating a response, instead of relying only on the language model's general knowledge — resulting in more accurate, context-aware answers.

**File:** `rag-chatbot.json`
**Tech stack:** n8n, OpenAI, Pinecone (vector database), Replit (chatbot interface)

---

### 🎧 AI-Powered Customer Support Workflow
Automates customer support by combining a knowledge base with AI-generated responses, delivering efficient and context-aware replies directly through Gmail.

**File:** `customer-support-workflow.json`
**Tech stack:** n8n, OpenAI, Pinecone, Gmail

---

### 📋 AI-Powered Client Onboarding Workflow
Automates the client onboarding process — once a client submits a form, AI analyzes the information and automatically generates personalized emails such as a welcome message and terms & services.

**File:** `client-onboarding-workflow.json`
**Tech stack:** n8n, OpenAI, Gmail automation

---

### 💬 AI-Powered Slack Assistant
Connects Slack with AI to automate conversations and streamline team communication through intelligent, context-aware responses.

**File:** `slack-assistant.json`
**Tech stack:** n8n, OpenAI, Pinecone, Slack

---

### 🔗 Parent & Child Workflows
Demonstrates modular workflow design in n8n by splitting complex automation into reusable child workflows — keeping things clean, reusable across projects, and easier to debug and maintain.

**File:** `parent-workflow.json    
           child-workflow.json`
**Tech stack:** n8n, Execute Workflow node

---

### 🧾 AI-Powered Invoice Processing Workflow
Automatically detects new invoices in Google Drive, extracts data from PDFs, uses AI to identify key invoice information, stores structured data in Google Sheets, and sends an email notification — reducing manual data entry.

**File:** `invoice-processing-workflow.json`
**Tech stack:** n8n, Google Drive, PDF extraction, OpenAI, Google Sheets, Gmail

---

### 🗺️ Lead Generation Automation (Google Maps)
An end-to-end lead generation pipeline: scrapes Google Maps via Apify, extracts websites and domains, enriches leads with emails through an HTTP API, cleans the data, and stores everything automatically in Google Sheets.

**File:** `lead-gen-maps.json`
**Tech stack:** n8n, Google Sheets Trigger, Apify, HTTP API (email enrichment), Edit Fields

---

### 🎯 Candidate-Job Match Scorer
Fetches new job listings daily, compares each one against a resume using AI, and emails only the strong matches (80%+ score) — helping filter relevant opportunities automatically.

**File:** `candidate-job-match.json`
**Tech stack:** n8n, HTTP Request, Anthropic API, JavaScript (Code node), Email automation

---

### ✍️ AI-Powered LinkedIn Content Automation (Human-in-the-Loop)
A content workflow where AI and human decision-making work together: takes a content request via form, generates a LinkedIn post with AI, researches supporting info with Tavily, sends it for human approval, routes declined posts to a revision agent, and only publishes to LinkedIn after approval.

**File:** `linkedin-content-automation.json`
**Tech stack:** n8n, OpenAI, Tavily, Human-in-the-loop approval, LinkedIn API

---

### 📸 Instagram Lead Generation Automation
Turns a simple form submission (target location + business type) into a structured list of leads — scrapes Instagram profiles via Apify/Google scraping, processes the data with JavaScript, and stores results in Google Sheets.

**File:** `instagram-lead-gen.json`
**Tech stack:** n8n, Apify, JavaScript (Code node), Google Sheets
