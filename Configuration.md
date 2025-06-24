# ⚙️ Configuration Guide

This document explains how to set up environment variables, API keys, and configuration files for the **Sustainable Smart City Assistant** project.

---

## 📦 1. Environment Variables (`.env` file)

Create a `.env` file in the **root directory** of your project.

> ⚠️ Do not commit this file to GitHub — it contains sensitive API keys.

### ✅ Sample `.env` Format:
```env
WATSONX_API_KEY=your_ibm_watsonx_api_key
WATSONX_PROJECT_ID=your_ibm_watsonx_project_id

PINECONE_API_KEY=your_pinecone_api_key
PINECONE_ENV=your_pinecone_environment
PINECONE_INDEX=your_vector_index_name
