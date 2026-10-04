# ✈️ Iteru Travel Automation Suite

**Submitted for:** 7th Global AI Hackathon (Hack-Nation)
**Track:** World Bank - Small AI for development (Track C: Tourism)

## 📌 Project Overview
Iteru Travel Automation Suite is a robust, multi-agent AI system designed to solve the most pressing operational bottlenecks in modern travel agencies. By combining deterministic automation with advanced generative AI, this suite eliminates manual data entry, monitors customer service quality in real-time, and generates instant marketing assets.

## 🤖 The Multi-Agent Architecture
This system is composed of four primary AI/Automation agents working in tandem:

1. **WhatsApp Monitor Agent (Customer Success):** 
   Monitors customer service chats to detect slow response times. It utilizes **Gemini AI** to analyze the context of the conversation, determine customer sentiment (e.g., urgent, angry, inquiring), and generate real-time summaries and suggested actions for supervisors.
   
2. **Hotel Scraper Agent (Market Intelligence):** 
   Automates the extraction of hotel pricing and availability from global aggregators (like Booking.com) and local B2B tourism platforms. It structures the data for immediate competitive analysis.
   
3. **Financial Reconciliation Agent (Automated Accounting):** 
   An automated workflow that intelligently matches internal booking records with external financial sheets, identifying discrepancies and ensuring accurate cash flow tracking without manual intervention.

4. **Marketing Content Generator (Generative AI):** 
   Takes basic travel offer details (destinations, prices) and uses Large Language Models to generate high-converting promotional prompts and corresponding marketing images, ready for social media publishing.

## 🛠️ Tech Stack
*   **Workflow Engine:** [n8n](https://n8n.io/)
*   **AI Models:** Gemini AI (LLM & Sentiment Analysis)
*   **Database / Backend:** Supabase

---

## ⚠️️ Important Security & NDA Notice for Judges
This project was built to interface with real B2B travel agency systems, live financial data, and private customer communications. 

Due to **strict Non-Disclosure Agreements (NDAs), data privacy laws, and security protocols**, the actual live environment, database credentials, API keys, and raw business data **cannot be shared in this public repository**. 

### What is included in this repository?
To allow judges to review the architectural complexity and logic of the system, we have included the **exported `.json` workflow files from n8n**. 

Judges can review these JSON files by importing them into any local or cloud n8n instance to examine the node structures, API calls (sanitized), and AI integration logic.

*Please refer to our **Demo Video** submitted via the hackathon portal to see the system operating live in a secure, mock-data environment.*