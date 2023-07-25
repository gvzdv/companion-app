# AI Companion App (based on [AI Getting Started template by a16z](https://github.com/a16z-infra/companion-app))

[Live Demo](https://ai-bro-5oxslodcwq-uc.a.run.app/)

<img width="1182" alt="App Screenshot" src="https://github.com/gvzdv/companion-app/blob/main/public/bro.png">

Runs on ChatGPT. 

## Stack

- Auth: [Clerk](https://clerk.com/)
- App logic: [Next.js](https://nextjs.org/)
- VectorDB: [Pinecone](https://www.pinecone.io/) / [Supabase pgvector](https://supabase.com/docs/guides/database/extensions/pgvector)
- LLM orchestration: [Langchain.js](https://js.langchain.com/docs/)
- Text model: [OpenAI](https://platform.openai.com/docs/models), [Replicate (Vicuna13b)](https://replicate.com/replicate/vicuna-13b)
- Text streaming: [ai sdk](https://github.com/vercel-labs/ai)
- Conversation history: [Upstash](https://upstash.com/)
- Deployment: [Google Cloud Run](https://cloud.google.com/run/)
