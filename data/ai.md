# AI App Stacks

## Chat Pilot

**Use case:** AI chatbot with retrieval support
**Tools:** Next.js, Python FastAPI, PostgreSQL with pgvector, Vercel AI SDK
**Difficulty:** Intermediate

**Why this combo works**
- Separates frontend speed from backend orchestration
- Retrieval support makes the stack useful beyond toy demos
- Good balance between flexibility and developer experience

**Caveats**
- Model costs and latency need active monitoring
- Retrieval quality depends on chunking and evaluation

## Notebook to App

**Use case:** Turn an ML or data workflow into a lightweight demo app
**Tools:** Python, Streamlit, Hugging Face, Docker
**Difficulty:** Beginner

**Why this combo works**
- Very fast path from experiment to shareable interface
- Strong fit for demos, internal tools, and model previews
- Easy for contributors who are more data-focused than frontend-focused

**Caveats**
- Not ideal for highly custom product UX
- Can become messy if app logic grows too much
