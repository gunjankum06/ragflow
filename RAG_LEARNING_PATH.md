# RAGFlow - Learning Path to Master RAG Development

<div align="center">
<a href="https://demo.ragflow.io/">
<img
src="https://github.com/infiniflow/ragflow/raw/main/web/src/assets/logo-with-text.svg" width="520" alt="ragflow logo">
</a>
</div>

## 📚 Master RAG Development Roadmap (Updated for 2026)

This learning path will help you become proficient in RAG (Retrieval-Augmented Generation) development using RAGFlow and modern AI techniques.

### **Level 1: Foundations (Weeks 1-2)**

#### 📖 Core Concepts to Learn
- **What is RAG?** — Understanding retrieval-augmented generation fundamentals
  - Traditional LLMs vs. RAG systems
  - When to use RAG vs. fine-tuning
  - Key advantages and limitations

- **Document Processing** — How to extract and structure knowledge
  - Document parsing (PDF, DOCX, HTML, etc.)
  - Text chunking strategies
  - Metadata extraction

- **Embeddings & Vector Search** 
  - Understanding embeddings (word2vec, transformers)
  - Vector databases (Elasticsearch, Milvus, Infinity)
  - Semantic search vs. keyword search

#### 🛠️ Hands-On Tasks
1. Install RAGFlow using Docker
2. Explore the RAGFlow UI with sample documents
3. Upload a PDF and observe the chunking visualization
4. Test queries against your first knowledge base
5. Review the citation and grounding features

**Resources:**
- [RAGFlow Official Docs](https://ragflow.io/docs/dev/)
- [Understanding RAG Architecture](https://ragflow.io/basics/what-is-rag)
- [RAGFlow Chunking Strategy](https://ragflow.io/docs/dev/chunking)

---

### **Level 2: RAG Architecture Deep Dive (Weeks 3-4)**

#### 🏗️ System Architecture Understanding
- **RAGFlow Architecture** — Core components
  - Deep Doc Engine (document understanding)
  - Context Engine (knowledge assembly)
  - Embedding & Reranking modules
  - LLM integration layer

- **Retrieval Strategies**
  - Multiple recall (BM25, semantic similarity, vector search)
  - Hybrid search approaches
  - Fused re-ranking
  - Query expansion

- **Knowledge Base Organization**
  - Knowledge graphs
  - Hierarchical chunking
  - Template-based organization
  - Multi-model support

#### 🛠️ Hands-On Tasks
1. Explore RAGFlow configuration files (`service_conf.yaml`)
2. Set up multiple LLM providers (OpenAI, local models via Ollama)
3. Test different chunking templates
4. Run advanced retrieval benchmarks
5. Analyze retrieval metrics (precision, recall, MRR)

**Repository Exploration:**
- Study `deepdoc/` — Document parsing engine
- Review `rag/` — Core RAG pipeline
- Examine `chunks/` — Chunking strategies
- Understand `retriever/` — Retrieval implementations

---

### **Level 3: Building with RAGFlow (Weeks 5-7)**

#### 🎯 Practical Application Development

**Project 1: Knowledge Base Q&A System**
- Upload domain-specific documents (research papers, technical docs, manuals)
- Configure embedding models
- Build a custom question-answering interface
- Measure accuracy and citation quality
- Implement feedback loops

```bash
# Quick start
cd ragflow/docker
docker compose up -d
# Access at http://localhost
```

**Project 2: Multi-Source Knowledge Integration**
- Connect data sources (Confluence, S3, Google Drive, Discord)
- Orchestrate data synchronization pipelines
- Handle real-time updates
- Manage knowledge conflicts

**Project 3: Agent-Based Workflow**
- Build autonomous agents using RAGFlow's agent templates
- Combine retrieval with tool execution
- Implement memory for multi-turn conversations
- Create agentic workflows with MCP integration

#### 💻 Code-Level Integration
- RAGFlow API integration (Python/JavaScript)
- Custom chunking strategies
- Reranking implementations
- LLM integration patterns

---

### **Level 4: Advanced Topics (Weeks 8-10)**

#### 🚀 Production-Grade RAG Systems

**Advanced Retrieval**
- Graph-based RAG (knowledge graphs)
- Hybrid retrieval with cross-encoders
- Active learning for knowledge refinement
- Contextual retrieval

**Optimization & Performance**
- Vector database optimization
- Caching strategies
- Batch processing
- Latency reduction

**Evaluation & Metrics**
- RAGAS evaluation framework
- Custom evaluation metrics
- A/B testing retrieval strategies
- Grounding and faithfulness metrics

**Multi-Modal RAG**
- Image understanding in PDFs
- Cross-modal retrieval
- Document layout understanding
- Tables and structured data extraction

#### 🛠️ Hands-On Tasks
1. Build a production RAG pipeline with proper monitoring
2. Implement custom re-ranking models
3. Create evaluation benchmarks for your domain
4. Deploy RAGFlow in a cloud environment (AWS, GCP, Azure)
5. Set up CI/CD for knowledge base updates

---

### **Level 5: Mastery & Specialization (Weeks 11-12)**

#### 🎓 Become a RAG Expert

**Choose Your Specialization:**

1. **Enterprise RAG**
   - Multi-tenant architectures
   - Security and compliance (SOC2, HIPAA)
   - Scale optimization for millions of documents
   - Cost optimization strategies

2. **Agentic AI Development**
   - Advanced agent orchestration
   - Tool composition strategies
   - Memory management patterns
   - Workflow automation

3. **Domain-Specific RAG**
   - Legal document processing
   - Medical/scientific paper analysis
   - Technical documentation systems
   - Code understanding and retrieval

4. **RAG Research & Innovation**
   - Latest RAG techniques (GraphRAG, LightRAG)
   - Novel evaluation methods
   - Contributing to open-source
   - Publishing research

#### 🔬 Research & Experimentation
- Implement GraphRAG concepts in RAGFlow
- Develop novel chunking strategies
- Create domain-specific embedding models
- Contribute improvements to RAGFlow

---

## 📊 Learning Checkpoints

### ✅ Level 1 Mastery Indicators
- [ ] Can explain RAG fundamentals to others
- [ ] Successfully uploaded and queried a knowledge base
- [ ] Understand document chunking strategies
- [ ] Know basic embedding concepts

### ✅ Level 2 Mastery Indicators
- [ ] Can describe RAGFlow's architecture in detail
- [ ] Configured multiple LLM providers
- [ ] Optimized retrieval performance
- [ ] Analyzed and interpreted metrics

### ✅ Level 3 Mastery Indicators
- [ ] Built 3+ RAG applications
- [ ] Integrated RAGFlow with external systems
- [ ] Created autonomous agents
- [ ] Handled real-world data sources

### ✅ Level 4 Mastery Indicators
- [ ] Deployed production RAG system
- [ ] Implemented advanced optimization techniques
- [ ] Created comprehensive evaluation framework
- [ ] Handled multi-modal documents

### ✅ Level 5 Mastery Indicators
- [ ] Specialized in chosen domain
- [ ] Contributed to RAGFlow/RAG community
- [ ] Mentoring others in RAG development
- [ ] Publishing novel RAG techniques

---

## 🔗 Essential Learning Resources

### Official Documentation
- [RAGFlow Docs](https://ragflow.io/docs/dev/)
- [RAGFlow GitHub](https://github.com/infiniflow/ragflow)
- [RAGFlow Community](https://discord.gg/NjYzJD3GM3)

### Complementary Technologies to Learn
- **Vector Databases**: Milvus, Infinity, Pinecone, Weaviate
- **LLM Frameworks**: LangChain, LlamaIndex, Semantic Kernel
- **Evaluation**: RAGAS, Trulens, DeepEval
- **Embeddings**: Sentence Transformers, OpenAI Ada, Jina

### Recommended Reading
- "Retrieval-Augmented Generation for Large Language Models" (Research)
- "Building Production RAG Systems" (Tutorials)
- RAGFlow Blog & Case Studies
- Latest AI/LLM research papers

### Practice Datasets
- Wikipedia extracts
- arXiv papers
- Technical documentation
- Domain-specific datasets (legal, medical, financial)

---

## 🎯 Project Ideas to Apply Your Knowledge

### Beginner Projects
1. Legal document Q&A system
2. Medical research paper assistant
3. Technical documentation bot
4. FAQ automation system

### Intermediate Projects
1. Multi-source knowledge fusion system
2. Real-time data pipeline with dynamic updates
3. Custom domain-specific search engine
4. Research paper analysis assistant

### Advanced Projects
1. Enterprise knowledge management system
2. Multi-modal document understanding platform
3. Graph-based knowledge reasoning system
4. Autonomous research agent

---

## 🤝 Community & Contribution

After mastering RAG:
- **Join the community**: [Discord](https://discord.gg/NjYzJD3GM3)
- **Share your projects**: GitHub discussions
- **Contribute to RAGFlow**: [Contributing Guidelines](https://ragflow.io/docs/dev/contributing)
- **Publish your learnings**: Blog posts, tutorials, papers

---

## 💡 What is RAGFlow?

[RAGFlow](https://ragflow.io/) is a
leading open-source Retrieval-Augmented Generation
([RAG](https://ragflow.io/basics/what-is-rag)) engine that fuses cutting-edge RAG with Agent capabilities to create
a superior context layer for LLMs. It offers a streamlined RAG workflow
adaptable to enterprises of any scale. Powered by a converged [context
engine](https://ragflow.io/basics/what-is-agent-context-engine) and pre-built agent templates,
RAGFlow enables developers to transform complex data into high-fidelity,
production-ready AI systems with exceptional efficiency and precision.

---

## Additional Sections
For the rest of the original README content (Demo, Key Features, Get Started, etc.), refer to the [original RAGFlow repository](https://github.com/infiniflow/ragflow).
