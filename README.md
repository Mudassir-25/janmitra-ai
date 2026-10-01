# JanMitra AI
Prototype — synthetic demonstration data. Not connected to any government system.

Run: `npm install && GEMINI_API_KEY=... npm start` → http://localhost:8080
No key? App runs in labelled Demo Mode (deterministic rule-based analysis).
Cloud Run: `gcloud run deploy janmitra-ai --source . --set-env-vars GEMINI_API_KEY=...` (prefer Secret Manager).
Key stays server-side; browser only calls /api/*.
