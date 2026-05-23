# Applied AI Engineer Roadmap
*From early developer → intermediate → production-grade engineer*

## Layer 1 — Software Engineering Foundations

### 1. Python Engineering
**Goal:** Build reliable, maintainable, production-grade Python systems.

#### Core Topics
- Python syntax and idioms
- Object-oriented design
- Functional programming principles
- Type annotations and static typing
- Asynchronous programming and concurrency
- Exception and error handling
- Structured logging
- Environment and dependency management
- Unit testing and integration testing

#### Recommended Tools
- Python
- Pytest
- Pydantic
- uv
- Ruff

### 2. Git & Engineering Workflow
**Goal:** Apply consistent source control practices and collaborate effectively.

#### Core Topics
- Commit hygiene
- Branching strategies
- Pull request workflows
- Merge conflicts and rebasing
- Semantic commits
- Code review best practices

#### Recommended Tools
- Git
- GitHub

### 3. Project Structure
**Goal:** Organize code and configuration for scalability and clarity.

#### Core Topics
- Logical project structure
- Separation of concerns
- Configuration management
- Environment-specific settings
- Dependency injection
- Reusable and modular components

### 4. Software Architecture
**Goal:** Choose patterns that support scalability, reliability, and maintainability.

#### Core Topics
- Monolith vs. microservices
- API-first architecture
- Event-driven systems
- Domain boundaries and bounded contexts
- Scalability and performance planning
- Maintainability and technical debt management

## Layer 2 — Backend Engineering

### 5. API Development
**Goal:** Build robust backend services with modern web API design.

#### Core Topics
- REST API design
- Request/response lifecycle
- Validation and schema enforcement
- Authentication and authorization
- Middleware patterns
- Rate limiting and throttling
- Background tasks and asynchronous workflows
- WebSockets and real-time communication

#### Recommended Tools
- FastAPI

### 6. Database Fundamentals
**Goal:** Model data effectively and manage persistence with confidence.

#### Core Topics
- SQL fundamentals
- NoSQL fundamentals
- Schema design and normalization
- Indexing strategies
- Transactions and concurrency control
- Query optimization

### 7. Caching & Queues
**Goal:** Improve performance and reliability with caching and asynchronous processing.

#### Core Topics
- Caching strategies
- Background job processing
- Event queues and task pipelines
- Pub/Sub patterns

#### Recommended Tools
- Redis

## Layer 3 — AI Engineering Core

### 8. LLM Engineering
**Goal:** Build language-model applications that are predictable and useful.

#### Core Topics
- Prompt engineering
- System prompts and instruction design
- Structured outputs
- Function calling and tool integration
- Context window optimization
- Token efficiency
- Model selection and evaluation

#### Providers
- OpenAI
- Anthropic
- Google

### 9. Embeddings
**Goal:** Use semantic representations to improve search and retrieval.

#### Core Topics
- Text embeddings
- Similarity search
- Semantic retrieval
- Embedding evaluation

### 10. RAG Systems
**Goal:** Build retrieval-augmented generation pipelines for grounded AI responses.

#### Core Topics
- Document ingestion
- Chunking and vectorization
- Retrieval pipeline design
- Re-ranking and filtering
- Evaluation and quality control
- Hallucination reduction

### 11. Vector Databases
**Goal:** Manage large-scale similarity search with efficient indexing.

#### Core Topics
- Indexing strategies
- Similarity search algorithms
- Metadata filtering
- Hybrid search

#### Recommended Tools
- Pinecone
- Weaviate
- FAISS

## Layer 4 — Agentic AI

### 12. Agents
**Goal:** Create autonomous workflows with planning, reasoning, and tools.

#### Core Topics
- Tool orchestration
- Task planning
- Memory management
- Multi-step reasoning
- Automated execution

### 13. MCP (Model Context Protocol)
**Goal:** Implement standardized interoperability for AI systems.

#### Core Topics
- Tool registration
- Resource sharing
- Protocol communication
- Secure tool access

### 14. SDKs / ADKs
**Goal:** Use and build SDKs for AI applications and integrations.

#### Core Topics
- SDK usage patterns
- Wrapper development
- Agent development kits
- Tool integration

#### Recommended Frameworks
- LangChain
- LlamaIndex

## Layer 5 — Cloud & Infrastructure

### 15. Docker
**Goal:** Containerize applications for consistent deployment.

#### Core Topics
- Dockerfile authoring
- Image creation and optimization
- Containers and runtime behavior
- Volumes and networking
- Multi-stage builds

#### Recommended Tool
- Docker

### 16. Cloud Platforms
**Goal:** Deploy and operate AI services on cloud infrastructure.

#### Focus
- Google Cloud

#### Core Services
- Compute
- Cloud Run
- GKE
- Compute Engine
- Cloud Storage
- Security and IAM
- Secret Manager
- Pub/Sub
- Cloud Logging
- Cloud Monitoring
- Vertex AI

### 17. Databases on Cloud
**Goal:** Use managed cloud databases for production workloads.

#### Core Topics
- Firestore
- Cloud SQL
- BigQuery

#### Recommended Tools
- Cloud Firestore

### 18. Infrastructure as Code
**Goal:** Manage infrastructure declaratively and repeatably.

#### Core Topics
- Provisioning best practices
- State management
- Reusable modules
- Environment separation

#### Recommended Tools
- Terraform

### 19. Artifact Management
**Goal:** Version and distribute deployable assets securely.

#### Core Topics
- Container image management
- Package registries
- Model versioning

#### Recommended Tools
- Artifact Registry

## Layer 6 — Frontend for AI Engineers

### 20. Basic Frontend Knowledge
**Goal:** Build simple interfaces for AI applications.

#### Core Topics
- HTML fundamentals
- CSS basics
- JavaScript essentials
- React fundamentals

#### Recommended Tools
- React

### 21. Python UI
**Goal:** Create rapid AI demos and internal tools.

#### Core Topics
- Internal demos
- Rapid prototyping
- Model-driven interfaces

#### Recommended Tools
- Streamlit
- Gradio

## Layer 7 — AI Developer Productivity

### 22. AI Coding Assistants
**Goal:** Leverage AI tools for faster, higher-quality development.

#### Core Topics
- IDE prompting
- Code generation
- Refactoring
- Debugging support
- Test generation
- Documentation generation

#### Recommended Tools
- GitHub Copilot
- Gemini Code Assist
- Cursor

### 23. Local vs Cloud AI Coding
**Goal:** Compare tradeoffs between local and cloud AI development.

#### Cloud Models
- Pros: stronger reasoning, higher performance
- Cons: enterprise data concerns

#### Local Models
- Pros: better privacy and control
- Cons: hardware limitations, smaller context windows

#### Recommended Tools
- Ollama
- LM Studio

### 24. Enterprise Security for AI Usage
**Goal:** Protect data, ensure governance, and reduce risk.

#### Core Topics
- Data leakage prevention
- Prompt injection mitigation
- Source code privacy
- API key protection
- Model governance
- Audit trails
- Private and on-prem deployments

## Suggested Learning Path

### Phase 1 — Build a strong foundation
- Python engineering
- Git workflow
- Project structure
- FastAPI
- Docker

### Phase 2 — Deliver value quickly
- LLM engineering
- RAG systems
- Vector databases
- AI coding assistants

### Phase 3 — Become production ready
- Google Cloud
- Firestore
- CI/CD
- Terraform

### Phase 4 — Grow into a strategic engineer
- Agents
- MCP
- Architecture
- Security and governance
