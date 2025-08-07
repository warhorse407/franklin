# Franklin AI Middleware

Franklin is a privacy-first, local-aware AI assistant. It acts as a middleware layer that combines local tools with OpenAI’s GPT-4o or TinyLlama fallback for hybrid intelligence.

## Features
- Read files and logs
- Summarize folders and notes
- Respond in natural language
- Local fallback with TinyLlama via Ollama
- Web UI + FastAPI backend
- Built-in test suite

## Quickstart

```bash
git clone https://github.com/warhorse407/franklin.git
cd franklin
docker compose -f docker-compose/docker-compose.yml up
```

## License
Franklin is licensed under the [Prosperity Public License 3.0.0](https://polyformproject.org/licenses/prosperity/3.0.0/).  
You may use it freely for non-commercial purposes.  
To use it commercially, contact the author at [franklinai.project@gmail.com](mailto:franklinai.project@gmail.com).

---

> 🔧 *This is a proof-of-concept project. Use at your own risk.*
