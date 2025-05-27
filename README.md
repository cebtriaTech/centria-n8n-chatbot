# Centria n8n Chatbot Starter

This repo is ready to deploy on Railway using Docker.

## Includes:
- Dockerfile
- Chatbot workflow (OpenRouter)
- PostgreSQL Q&A cache

## To Deploy:
1. Upload this repo to GitHub
2. Go to Railway → New Project → Deploy from GitHub
3. Choose Docker
4. Add environment variables:
   - N8N_BASIC_AUTH_USER = admin
   - N8N_BASIC_AUTH_PASSWORD = your_password
   - N8N_PORT = 5678
   - N8N_HOST = 0.0.0.0
   - WEBHOOK_URL = https://your-app.up.railway.app
   - N8N_PROTOCOL = https
