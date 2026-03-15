┌──────────────────────────────────────────────────────────────────────┐
│                         CLIENT LAYER                                 │
│   React Native (iOS/Android)  ·  Next.js Web Dashboard              │
│   Tailwind CSS  ·  Framer Motion  ·  MapboxGL                       │
├──────────────────────────────────────────────────────────────────────┤
│                        API GATEWAY                                   │
│   FastAPI (Python 3.11+)  ·  GraphQL (Strawberry)                   │
│   WebSocket channels for real-time alerts                            │
├────────────────┬─────────────────┬───────────────────────────────────┤
│  MATCHING      │  SCHEDULING     │  SAFETY & MONITORING              │
│  ENGINE        │  OPTIMIZER      │  PIPELINE                         │
│                │                 │                                    │
│  Sentence      │  OR-Tools /     │  Prophet / Isolation Forest       │
│  Transformers  │  CP-SAT Solver  │  Time-series anomaly detection    │
│  Collaborative │  Integer LP     │  Health-sensor ingestion          │
│  Filtering     │  Google Maps    │  Alert routing (Twilio/SNS)       │
│  GeoHash       │  Distance       │                                    │
│  Indexing      │  Matrix API     │                                    │
├────────────────┴─────────────────┴───────────────────────────────────┤
│                   CONVERSATIONAL AI LAYER                            │
│   On-device LLM (Ollama / llama.cpp)  ·  OpenAI API (fallback)     │
│   Prompt templates  ·  RAG over visit history                        │
├──────────────────────────────────────────────────────────────────────┤
│                       DATA & INFRA                                   │
│   PostgreSQL 16  ·  Redis (caching/queues)  ·  Pinecone (vectors)   │
│   Celery + RabbitMQ (async tasks)  ·  Docker  ·  Kubernetes         │
│   Terraform  ·  GitHub Actions CI/CD                                 │
│   Checkr API (background checks)  ·  Stripe (payments)              │
└──────────────────────────────────────────────────────────────────────┘