# JanMitra AI

### AI-Powered Civic Governance & Public Service Intelligence

JanMitra AI is a prototype civic-tech platform designed to demonstrate how Generative AI can help transform citizen requests into structured, prioritized, and actionable insights for public-service management.

The platform combines citizen request processing, AI-assisted classification and prioritization, analytics, and an interactive dashboard into a single workflow.

> **Prototype:** JanMitra AI uses synthetic demonstration data and is not connected to any government system or live public-service infrastructure.

---

## ✨ What JanMitra AI Does

JanMitra AI demonstrates a workflow where:

**Citizen Request → AI Analysis → Categorization → Priority Assessment → Actionable Insight → Dashboard**

The prototype can:

- 📝 Process citizen service requests
- 🤖 Use Google Gemini for AI-assisted analysis
- 🏷️ Categorize incoming requests
- 🚨 Identify and prioritize important requests
- 📊 Visualize civic-service activity through an interactive dashboard
- 🗺️ Present regional and district-level information
- 💡 Generate actionable insights from citizen-request data
- 🌐 Support a multilingual civic-service experience
- 🧪 Run in Demo Mode without an API key

---

## 🎯 Problem

Large volumes of citizen requests can make it difficult for public-service teams to quickly identify:

- Which issues require immediate attention
- What categories of problems are increasing
- Which regions are generating more requests
- What patterns exist across citizen complaints
- Where administrative attention may be required

JanMitra AI explores how an AI-assisted workflow could help organize this information into a more understandable and actionable format.

---

## 🧠 AI Workflow

```text
Citizen Request
       ↓
Request Processing
       ↓
Gemini AI Analysis
       ↓
Category + Priority
       ↓
Actionable Insight
       ↓
Civic Dashboard

The application can also operate without Gemini through a deterministic rule-based Demo Mode, allowing the prototype to remain functional without an API key.

## 🖥️ Dashboard

The dashboard provides a visual overview of the civic-service data, including:

Request volumes
Request categories
Priority distribution
Regional information
AI-generated insights
Civic-service trends

The interface uses a modern glassmorphism-inspired design with subtle animations and interactive components.

## 🛠️ Technology Stack
Frontend
HTML
CSS
JavaScript
Responsive interactive dashboard
Backend
Node.js
Express.js
AI
Google Gemini API
Server-side Gemini integration
Deployment
Docker
Cloud Run compatible architecture
Data
Synthetic demonstration data

## 🔐 Security

Gemini API credentials are kept server-side.

The browser communicates with backend /api/* endpoints rather than directly exposing the Gemini API key.

API keys should be provided through environment variables and should never be committed to the repository.

## 🚀 Running Locally

1. Clone the repository
git clone https://github.com/Mudassir-25/janmitra-ai.git
cd janmitra-ai
2. Install dependencies
npm install
3. Configure Gemini

Create a .env file:

GEMINI_API_KEY=your_api_key_here
4. Start the application
npm start

Open:

http://localhost:8080
Demo Mode

If no GEMINI_API_KEY is provided, JanMitra AI automatically runs in a labelled Demo Mode using deterministic rule-based analysis.

## ☁️ Deployment

The application is designed to be compatible with container-based deployment such as Google Cloud Run.

Example:

gcloud run deploy janmitra-ai \
  --source . \
  --set-env-vars GEMINI_API_KEY=...

For production deployments, use a secure secret-management solution rather than placing credentials directly in deployment commands.

## 📁 Project Structure

janmitra-ai/
├── public/
│   └── index.html
├── server.js
├── package.json
├── package-lock.json
├── Dockerfile
├── .env.example
├── .gitignore
└── README.md

## ⚠️ Prototype Disclaimer

JanMitra AI is an experimental prototype created to demonstrate an AI-assisted civic governance workflow.

It uses synthetic data and does not represent or connect to any real government database, department, citizen registry, or public-service system.

AI-generated outputs are demonstrations and should not be treated as official government decisions or recommendations.

## 🌱 Future Possibilities

If developed beyond the prototype, the concept could explore:

Integration with authenticated civic-service platforms
More advanced regional analytics
Multilingual citizen interaction
Human-in-the-loop administrative workflows
Service-level monitoring
Historical trend analysis
Role-based dashboards
Secure government data integrations
Explainable AI-assisted prioritization

## 📄 License

This project is provided as a prototype for educational, demonstration, and portfolio purposes.


