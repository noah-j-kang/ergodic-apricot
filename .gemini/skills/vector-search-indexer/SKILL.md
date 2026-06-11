---
name: vector-search-indexer
description: Scaffolds high-performance backend code connecting FastAPI with local vector search indices (HNSWlib) and relational backends. Triggered when writing endpoints, search logic, or database wrappers.
---

# Core Mandates
- Write all backend code using FastAPI with explicit asynchronous structural patterns (`async/await`).
- Use `hnswlib` for handling sub-linear approximate nearest neighbor (ANN) searches over multi-dimensional landscape arrays.
- Enforce strict data validation using Pydantic v2 schemas.
- Ensure the separation of concerns: relational metadata queries route via the Supabase client, while geometric similarity operations route via the HNSW index.
- Provide clear error boundary handling for out-of-bounds vector dimensions or missing data entries.
- Output code cleanly formatted without extraneous explanations or markdown wrappers.