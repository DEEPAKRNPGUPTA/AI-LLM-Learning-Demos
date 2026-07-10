# 14 — RAG / Retrieval-Augmented Generation

A complete beginner-to-practical learning page for **RAG / Retrieval-Augmented Generation**.

This module explains why RAG exists, how it works internally, how documents become retrievable knowledge, how the LLM generates grounded answers, how RAG is evaluated, how it fails, and how practical/enterprise RAG systems are designed.

---

## Live Page

```text
https://deepakrnpgupta.github.io/AI-LLM-Learning-Demos/14-rag-retrieval-augmented-generation/
```

---

## Main File

```text
index.html
```

This is a single complete HTML page containing all RAG learning steps, demos, recap, and quiz.

---

## Topic Covered

```text
14 — RAG / Retrieval-Augmented Generation
```

---

## Learning Coverage

```text
Step 1 to Step 16
Part 1 to Part 18
Details 1 to 218
Demo 1 to Demo 8
Final Recap + Quiz
```

---

## Folder Structure

```text
AI-LLM-Learning-Demos
│
├── 14-rag-retrieval-augmented-generation
│   ├── index.html
│   └── README.md
```

---

## Complete Step Map

### Step 1 — Why RAG Exists

```text
1. What problem RAG solves
2. Why LLMs cannot know everything
3. Knowledge cutoff problem
4. Hallucination problem
5. Private/company data problem
6. Why fine-tuning is not always the answer
7. RAG vs normal prompting
8. RAG vs fine-tuning
9. RAG vs search engine
10. RAG in real enterprise use cases
```

### Step 2 — Basic RAG Idea

```text
11. Meaning of Retrieval-Augmented Generation
12. Simple RAG flow
13. User question → retrieve documents → send context to LLM → answer
14. Why retrieval comes before generation
15. What grounding means
16. What context injection means
17. What source-based answer means
18. Why RAG makes LLM more useful
```

### Step 3 — RAG Architecture

```text
19. High-level RAG architecture
20. User query
21. Query processing
22. Document store
23. Vector database
24. Embedding model
25. Retriever
26. Context builder
27. Prompt template
28. LLM
29. Answer generation
30. Citation/source display
31. Feedback loop
```

### Step 4 — Documents and Chunking

```text
32. What kind of data can be used in RAG
33. PDFs
34. Word documents
35. Web pages
36. Emails
37. SQL data
38. Logs
39. Policies
40. Product manuals
41. Support tickets
42. Training material
43. Code repositories
44. Enterprise knowledge base

45. What is chunking
46. Why we cannot send full documents to the LLM
47. Chunk size
48. Chunk overlap
49. Small chunks vs large chunks
50. Semantic chunking
51. Page-based chunking
52. Paragraph-based chunking
53. Heading-aware chunking
54. Sliding window chunking
55. Chunk metadata
56. Bad chunking problems
57. How chunking affects retrieval quality
```

### Step 5 — Embeddings and Vector Database

```text
58. Why embeddings are used in RAG
59. Document embeddings
60. Query embeddings
61. Meaning-based search
62. Similarity search
63. Cosine similarity intuition
64. Embedding model selection
65. OpenAI embeddings
66. Sentence transformers
67. Domain-specific embeddings
68. Embedding dimension
69. Embedding refresh
70. Why embedding quality matters

71. What is a vector database
72. Why normal SQL search is not enough
73. Vector index
74. Similarity search
75. Top-k retrieval
76. Approximate nearest neighbor search
77. Metadata filtering
78. Hybrid search
79. Popular vector databases
80. FAISS
81. Chroma
82. Pinecone
83. Weaviate
84. Qdrant
85. Milvus
86. Azure AI Search
87. KDB.AI
88. PostgreSQL pgvector
```

### Step 6 — Retrieval

```text
89. What retrieval means
90. Keyword search
91. Vector search
92. Hybrid retrieval
93. Top-k documents
94. Similarity score
95. Metadata filters
96. Query expansion
97. Query rewriting
98. Multi-query retrieval
99. Parent-child retrieval
100. Self-query retrieval
101. Recursive retrieval
102. Retrieval failure examples
```

### Step 7 — Context Building

```text
103. What happens after retrieval
104. Selecting useful chunks
105. Ranking retrieved chunks
106. Removing duplicates
107. Combining chunks
108. Respecting context window limit
109. Adding metadata
110. Adding source names
111. Creating final context
112. Context compression
113. Lost-in-the-middle problem
114. Context ordering
```

### Step 8 — Prompting in RAG

```text
115. RAG prompt template
116. System instruction
117. User question
118. Retrieved context
119. Answer rules
120. Citation instruction
121. Use only the provided context
122. Handling missing answers
123. Avoiding hallucination
124. Asking clarifying questions
125. Structured output in RAG
126. JSON output in RAG
```

### Step 9 — Generation

```text
127. How the LLM uses retrieved context
128. Grounded answer generation
129. Answer with citation
130. Answer with confidence
131. Answer with not-found response
132. Summarizing retrieved content
133. Comparing retrieved sources
134. Multi-document answer
135. Step-by-step answer
136. Enterprise-style answer
```

### Step 10 — RAG Evaluation

```text
137. Why RAG evaluation is difficult
138. Retrieval quality
139. Generation quality
140. Faithfulness
141. Relevance
142. Context precision
143. Context recall
144. Answer correctness
145. Hallucination rate
146. Source accuracy
147. Human evaluation
148. Golden question-answer set
149. RAGAS
150. TruLens
151. LangSmith evaluation
```

### Step 11 — RAG Failure Modes

```text
152. Wrong document retrieved
153. Right document not retrieved
154. Chunk too small
155. Chunk too large
156. Duplicate chunks
157. Old data retrieved
158. Bad OCR
159. Poor metadata
160. Ambiguous user query
161. LLM ignores context
162. LLM hallucinates
163. Source mismatch
164. Conflicting documents
165. Security leakage
```

### Step 12 — Advanced RAG

```text
166. Naive RAG
167. Advanced RAG
168. Modular RAG
169. Agentic RAG
170. Corrective RAG
171. Adaptive RAG
172. Graph RAG
173. Multi-hop RAG
174. SQL + Vector RAG
175. Knowledge graph + RAG
176. Re-ranking
177. Cross-encoder re-ranker
178. Query decomposition
179. Routing-based RAG
180. Tool-augmented RAG
```

### Step 13 — Enterprise RAG

```text
181. Enterprise document search
182. Access control
183. User permissions
184. Row-level security
185. Document-level security
186. Private data handling
187. PII protection
188. Audit logs
189. Versioning
190. Data freshness
191. Incremental indexing
192. RAG monitoring
193. Cost management
194. Latency management
195. Deployment architecture
```

### Step 14 — RAG vs Related Techniques

```text
196. RAG vs fine-tuning
197. RAG vs prompt engineering
198. RAG vs function calling
199. RAG vs agents
200. RAG vs semantic search
201. RAG vs traditional search
202. RAG vs knowledge graph
203. When to use RAG
204. When not to use RAG
```

### Step 15 — Practical RAG Pipeline

```text
205. Collect documents
206. Clean documents
207. Split documents
208. Create embeddings
209. Store in vector database
210. Receive user query
211. Embed query
212. Retrieve matching chunks
213. Build context
214. Send prompt to LLM
215. Generate answer
216. Show answer with sources
217. Log feedback
218. Improve retrieval
```

### Step 16 — Demos + Final Recap + Quiz

```text
Demo 1. Simple RAG Flow Visualizer
Demo 2. Chunking Simulator
Demo 3. Similarity Search Demo
Demo 4. RAG Prompt Builder
Demo 5. Hallucination vs Grounded Answer
Demo 6. Top-K Retrieval Demo
Demo 7. Metadata Filter Demo
Demo 8. RAG Failure Mode Demo

Final Recap
20 Quiz Questions
Answer Key
Completion Tracker
```

---

## Interactive Demos Included

### Demo 1 — Simple RAG Flow Visualizer

Shows the complete RAG journey:

```text
User Question
      ↓
Embedding
      ↓
Vector Search
      ↓
Retrieved Chunks
      ↓
Prompt Builder
      ↓
LLM Answer
      ↓
Sources
```

### Demo 2 — Chunking Simulator

Shows how a document is split into chunks using:

```text
Chunk size
Chunk overlap
```

Learning point:

```text
Small chunks may lose meaning.
Large chunks may include noise.
Overlap preserves boundary meaning.
```

### Demo 3 — Similarity Search Demo

Shows how a user question is compared with chunks using similarity scores.

Learning point:

```text
RAG retrieves by meaning, not only exact words.
```

### Demo 4 — RAG Prompt Builder

Shows how retrieved chunks become the final prompt.

Learning point:

```text
Retrieval gives evidence.
Prompting tells the LLM how to use the evidence.
```

### Demo 5 — Hallucination vs Grounded Answer

Compares an unsupported answer with a source-grounded answer.

Learning point:

```text
RAG reduces guessing by grounding the answer in retrieved context.
```

### Demo 6 — Top-K Retrieval Demo

Shows how changing Top-K changes the amount of context sent to the LLM.

Learning point:

```text
More context is not always better.
```

### Demo 7 — Metadata Filter Demo

Shows how filters such as department, year, document type, and region improve retrieval.

Learning point:

```text
Metadata filters improve accuracy, freshness, and security.
```

### Demo 8 — RAG Failure Mode Demo

Shows common RAG problems and fixes.

Learning point:

```text
RAG quality depends on the full pipeline, not just the LLM.
```

---

## Website Features

The final `index.html` includes:

```text
Single-page full RAG learning material
Sticky table of contents
Light/Dark mode
Compact/Full mode
Show/Hide TOC
Search support
Copy buttons for code blocks
Interactive demos
Final recap
Quiz and answer key
Responsive layout
```

---

## Git Commands

From the main project folder:

```bat
cd C:\GoogleDrive\TheAI\AI-LLM-Learning-Demos
```

Add files:

```bat
git add 14-rag-retrieval-augmented-generation/index.html
git add 14-rag-retrieval-augmented-generation/README.md
```

Commit:

```bat
git commit -m "Add RAG retrieval augmented generation learning module"
```

Push:

```bat
git push origin main
```

If your branch is `master`, use:

```bat
git push origin master
```

---

## GitHub Pages URL

After pushing, the page should be available at:

```text
https://deepakrnpgupta.github.io/AI-LLM-Learning-Demos/14-rag-retrieval-augmented-generation/
```

---

## Final Mental Model

```text
LLM = smart teacher
Documents = textbook/library
Retriever = librarian
Context builder = assistant who selects right pages
Prompt = exam instruction
Answer = explanation based on selected pages
Citation = page reference
Evaluation = checking whether answer and source are correct
```

---

## Summary

RAG is not only a prompt technique.

It is a full knowledge pipeline:

```text
Collect documents
Clean documents
Chunk documents
Create embeddings
Store in vector database
Retrieve relevant chunks
Build context
Prompt the LLM
Generate grounded answer
Show sources
Evaluate
Improve
```

The final lesson:

```text
A good RAG system answers from the right knowledge,
with the right sources,
under the right permissions,
and improves over time.
```
