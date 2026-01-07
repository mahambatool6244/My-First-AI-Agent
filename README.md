🤖 My First Autonomous AI Agent (n8n + Llama 3.1)
This project is a fully functional Autonomous AI Agent built using n8n. It doesn't just respond to text but can actively use tools to search the internet and generate creative visuals based on user prompts.

🚀 Key Features
Live Web Search: Integrated with Google Search and Wikipedia nodes to provide up-to-date information.

AI Image Generation: Uses Pollinations.ai API to create images directly from text descriptions.

Intelligent Reasoning: Powered by Llama 3.1 (via Groq) to understand user intent and select the appropriate tool.

Contextual Memory: Uses a Simple Memory node to remember past interactions for a natural conversation flow.

🛠️ Tools & Technologies
Automation: n8n

LLM Model: Llama 3.1-8b-instant (Groq)

APIs: Google Search API, Wikipedia API, Pollinations AI

📸 Workflow Preview
[Screen recording 2026-01-07 16.22.57.webm](https://github.com/user-attachments/assets/dda1a432-461a-433d-bf04-5f9124c317c0)
<img width="2398" height="1256" alt="Screenshot 2026-01-07 16 19 03" src="https://github.com/user-attachments/assets/f3d405cb-8188-4c36-9102-28bdf89c0277" />



⚙️ Setup Instructions
Import the provided .json file into your n8n instance.

Add your Groq API Key in the Chat Model node.

Configure your Google Search credentials.

Hit Execute and start chatting!
