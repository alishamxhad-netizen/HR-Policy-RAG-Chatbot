## Setup

1. Install uv:
   ```
   pip install uv
   ```
2. Create and activate a virtual environment:
   ```
   uv venv ragenv
   ragenv\Scripts\activate
   ```
3. Install dependencies:
   ```
   uv pip install -r requirements.txt
   ```
4. Create a `.env` file with:
   ```
   GROQ_API_KEY=...
   JINA_API_KEY=...
   QDRANT_URL=...
   QDRANT_API_KEY=...
   QDRANT_COLLECTION_NAME=hr_policy
   LANGSMITH_TRACING=false
   LANGSMITH_ENDPOINT=...
   LANGSMITH_API_KEY=...
   LANGSMITH_PROJECT=...
   ```

## Git basics

```
git add .
git commit -m "Some message"
git push
```
