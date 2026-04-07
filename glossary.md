# AI Glossary of Terms<!-- omit from toc -->

> *Building a glossary for something as fast-moving as AI is a bit like trying to organize a library while the building is still being constructed.*
> 
> *It’s easy for things to get messy, so maintaining this glossary is guarded and assisted by [Copilot instructions](.github/instructions/glossary-instructions.md).*

**Index**
- [A](#a)
  - [Agent Loop](#agent-loop)
  - [Agentic AI](#agentic-ai)
  - [Artificial General Intelligence (AGI)](#artificial-general-intelligence-agi)
  - [Artificial Superintelligence (ASI)](#artificial-superintelligence-asi)
  - [Autonomous Agent](#autonomous-agent)
- [F](#f)
  - [Fine-tuning](#fine-tuning)
- [G](#g)
  - [Goal Decomposition](#goal-decomposition)
- [L](#l)
  - [Large Language Model (LLM)](#large-language-model-llm)
  - [Large Reasoning Models](#large-reasoning-models)
- [M](#m)
  - [Mixture of Experts (MoE)](#mixture-of-experts-moe)
  - [Model Context Protocol (MCP)](#model-context-protocol-mcp)
- [P](#p)
  - [Prompt Injection](#prompt-injection)
- [R](#r)
  - [Retrieval-Augmented Generation (RAG)](#retrieval-augmented-generation-rag)
- [S](#s)
  - [Source Citations](#source-citations)
- [T](#t)
  - [Tool Use](#tool-use)
- [V](#v)
  - [Vector Database](#vector-database)
  - [Vector Embedding](#vector-embedding)


## A

### Agent Loop
*Agent Loop* is the repeating cycle an [*Autonomous Agent*](#autonomous-agent) uses to finish a task: notice what is happening, decide what to do, act, and check the result.

> *See also:* [OODA loop (Wikipedia)](https://en.wikipedia.org/wiki/OODA_loop)

### Agentic AI
*Agentic AI* describes AI systems built around [*Autonomous Agents*](#autonomous-agent) that can pursue goals across many steps with limited human guidance. They make decisions along the way and use [*Tool Use*](#tool-use) to do real actions.

> *See also:* [Agentic AI (Wikipedia)](https://en.wikipedia.org/wiki/Agentic_AI)

### Artificial General Intelligence (AGI)
*Artificial General Intelligence (AGI)* is a theoretical type of AI that could handle most thinking tasks at about human level across many fields.

> *See also:* [Artificial general intelligence (Wikipedia)](https://en.wikipedia.org/wiki/Artificial_general_intelligence)

### Artificial Superintelligence (ASI)
*Artificial Superintelligence (ASI)* is a hypothetical form of AI that would perform better than humans at almost every thinking task.

> *See also:* [Superintelligence (Wikipedia)](https://en.wikipedia.org/wiki/Superintelligence)

### Autonomous Agent
*Autonomous Agent* is an AI system that can plan and carry out actions toward a goal with little step-by-step human instruction. It often uses [*Goal Decomposition*](#goal-decomposition) to break big goals into smaller tasks.

> *See also:* [Intelligent agent (Wikipedia)](https://en.wikipedia.org/wiki/Intelligent_agent)

## F

### Fine-tuning
*Fine-tuning* is extra training on an already trained model so it performs better for one specific task or topic.

> *See also:* [Fine-tuning (deep learning) (Wikipedia)](https://en.wikipedia.org/wiki/Fine-tuning_(deep_learning))

## G

### Goal Decomposition
*Goal Decomposition* is the process of breaking a big goal into smaller, ordered tasks that can be done step by step.

> *See also:* [Task analysis (Wikipedia)](https://en.wikipedia.org/wiki/Task_analysis)

## L

### Large Language Model (LLM)
*Large Language Model (LLM)* is an AI model trained on a lot of text so it can understand and produce human-like language.

> *See also:* [Large language model (Wikipedia)](https://en.wikipedia.org/wiki/Large_language_model)

### Large Reasoning Models
*Large Reasoning Models* are [*Large Language Models (LLMs)*](#large-language-model-llm) tuned to solve harder problems by doing extra reasoning work before giving a final answer.

> *See also:* [Chain-of-thought prompting (Wikipedia)](https://en.wikipedia.org/wiki/Chain-of-thought_prompting)

## M

### Mixture of Experts (MoE)
*Mixture of Experts (MoE)* is a model design where only a few specialized parts are used for each request, which can make the model faster and cheaper to run.

> *See also:* [Mixture of experts (Wikipedia)](https://en.wikipedia.org/wiki/Mixture_of_experts)

### Model Context Protocol (MCP)
*Model Context Protocol (MCP)* is a standard way for AI systems to connect to outside tools and data sources. It enables consistent [*Tool Use*](#tool-use) so one assistant can work with many integrations in the same way.

> *See also:* [Communication protocol (Wikipedia)](https://en.wikipedia.org/wiki/Communication_protocol)

## P

### Prompt Injection
*Prompt Injection* is a security attack where hidden instructions in input try to make an AI system ignore its intended rules.

> *See also:* [Prompt injection (Wikipedia)](https://en.wikipedia.org/wiki/Prompt_injection)

## R

### Retrieval-Augmented Generation (RAG)
*Retrieval-Augmented Generation (RAG)* is a method where a model first looks up relevant documents, often through a [*Vector Database*](#vector-database), and then uses that information to produce a more grounded answer.

> *See also:* [Retrieval-augmented generation (Wikipedia)](https://en.wikipedia.org/wiki/Retrieval-augmented_generation)

## S

### Source Citations
*Source Citations* are references that show which source passages an AI answer is based on, so people can check whether a claim is supported.

> *See also:* [Citation (Wikipedia)](https://en.wikipedia.org/wiki/Citation)

## T

### Tool Use
*Tool Use* is the ability of an AI system to call external tools, such as APIs, databases, or scripts, to take actions beyond text generation.

> *See also:* [Application programming interface (Wikipedia)](https://en.wikipedia.org/wiki/API)

## V

### Vector Database
*Vector Database* is a database built for storing and searching [*Vector Embeddings*](#vector-embedding), so systems can find content by meaning instead of exact keyword matches.

> *See also:* [Vector database (Wikipedia)](https://en.wikipedia.org/wiki/Vector_database)

### Vector Embedding
*Vector Embedding* is a numeric representation of text, images, or other data where similar meaning is placed near each other in a math space.

> *See also:* [Word embedding (Wikipedia)](https://en.wikipedia.org/wiki/Word_embedding)
