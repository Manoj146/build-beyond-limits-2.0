Problem Statement No: 66
project name : Valkey_for_ai
Team Details : Manoj,Vedanth,Sai,Jaya Krishna
Github username : Manoj146
LinkedIn Profile: https://www.linkedin.com/in/manoj-pachipulusu-a51873258/
GitHub Project Repository: https://github.com/Manoj146/valkey-for-ai.git
Problem statement:Build or extend AI-powered applications showcasing Valkey's vector search, semantic caching, and agent memory capabilities.
Project description: 
An AI-powered chat assistant that combines **Valkey's semantic vector caching** with **Breeth's intent-aware memory** to deliver fast, personalized responses.

Approach:
- **Valkey** — Caches answers using HNSW vector search. Similar questions hit the cache instantly, skipping the LLM entirely.
- **Breeth** — Stores the *why* behind every conversation. Extracts intent, entities, and cognitive patterns to personalize future responses.
- **OpenRouter** — Powers the LLM, called only on a cache miss.
- **React + FastAPI** — Clean chat UI with live cache stats and a memory explorer.

Tech stack and tools used: 
Valkey , Breeth AI , OpenRouter , FastAPI , React

