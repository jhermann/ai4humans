# AI Glossary of Terms<!-- omit from toc -->

> *Building a glossary for something as fast-moving as AI is a bit like trying to organize a library while the building is still being constructed.*
>
> ![A word cloud centered on the term LLM, featuring AI and machine learning terminology in varying text sizes. Prominent terms include: Large Language Model, Deep Learning, Machine Learning, Generative AI, Transformer, Tokens, Neural Network, Parameters, Fine-tuning, Prompt Engineering, Reinforcement Learning, Retrieval-Augmented Generation, Alignment, Chain-of-Thought, Foundation Models, and Explainable AI. The image is displayed on a crumpled white paper background on a wooden surface, creating an informal, approachable aesthetic that emphasizes the constantly evolving nature of AI concepts.](assets/images/glossary-word-cloud_720x393.png)
>
> *It’s easy for things to get messy, so maintaining this glossary is guarded and assisted by [Copilot instructions](.github/instructions/glossary-instructions.md).*

**External Sources**

- [mattpocock/dictionary-of-ai-coding](https://github.com/mattpocock/dictionary-of-ai-coding): AI coding jargon, explained in plain English.

**Index**
- [A](#a)
  - [AI Washing](#ai-washing)
  - [Agent Loop](#agent-loop)
  - [Agentic AI](#agentic-ai)
  - [Alignment](#alignment)
  - [Attention Mechanism](#attention-mechanism)
  - [Artificial General Intelligence (AGI)](#artificial-general-intelligence-agi)
  - [Artificial Superintelligence (ASI)](#artificial-superintelligence-asi)
  - [Autonomous Agent](#autonomous-agent)
- [B](#b)
  - [Bias](#bias)
- [C](#c)
  - [Chain-of-Thought (CoT) Prompting](#chain-of-thought-cot-prompting)
  - [Constitutional AI](#constitutional-ai)
  - [Context Window](#context-window)
- [D](#d)
  - [Dark Factory](#dark-factory)
  - [Deep Learning](#deep-learning)
  - [Diffusion Model](#diffusion-model)
- [E](#e)
  - [Embeddings](#embeddings)
  - [Energy Based Model (EBM)](#energy-based-model-ebm)
  - [Explainable AI (XAI)](#explainable-ai-xai)
- [F](#f)
  - [Few-shot Learning](#few-shot-learning)
  - [Fine-tuning](#fine-tuning)
  - [Foundation Models](#foundation-models)
- [G](#g)
  - [Generative AI (GenAI)](#generative-ai-genai)
  - [Goal Decomposition](#goal-decomposition)
  - [Grounding](#grounding)
- [H](#h)
  - [Hallucination](#hallucination)
- [J](#j)
  - [Jailbreaking](#jailbreaking)
- [L](#l)
  - [Large Language Model (LLM)](#large-language-model-llm)
  - [Large Reasoning Models](#large-reasoning-models)
  - [Latent Space](#latent-space)
  - [Low-Rank Adaptation (LoRA)](#low-rank-adaptation-lora)
- [M](#m)
  - [Machine Learning (ML)](#machine-learning-ml)
  - [Mixture of Experts (MoE)](#mixture-of-experts-moe)
  - [Model Context Protocol (MCP)](#model-context-protocol-mcp)
  - [Multimodality](#multimodality)
- [N](#n)
  - [Neural Network](#neural-network)
- [P](#p)
  - [Parameters](#parameters)
  - [Pre-training](#pre-training)
  - [Prompt Chaining](#prompt-chaining)
  - [Prompt Engineering](#prompt-engineering)
  - [Prompt Injection](#prompt-injection)
- [Q](#q)
  - [Quantization](#quantization)
- [R](#r)
  - [Red Teaming](#red-teaming)
  - [Reinforcement Learning (RL)](#reinforcement-learning-rl)
  - [Retrieval-Augmented Generation (RAG)](#retrieval-augmented-generation-rag)
- [S](#s)
  - [Small Language Model (SLM)](#small-language-model-slm)
  - [Source Citations](#source-citations)
  - [Stochastic Parrot](#stochastic-parrot)
  - [Synthetic Data](#synthetic-data)
- [T](#t)
  - [Tokens](#tokens)
  - [Tool Use](#tool-use)
  - [Transformer](#transformer)
- [V](#v)
  - [Vector Database](#vector-database)
  - [Vector Embedding](#vector-embedding)
- [W](#w)
  - [Weights](#weights)
  - [World Model](#world-model)
- [Z](#z)
  - [Zero-shot Learning](#zero-shot-learning)


## A

### AI Washing
*AI Washing* is when a company markets a product as "AI" even though AI is not a meaningful part of it.

> *See also:* [AI washing (Wikipedia)](https://en.wikipedia.org/wiki/AI_washing)

### Agent Loop
*Agent Loop* is the repeating cycle an [*Autonomous Agent*](#autonomous-agent) uses to finish a task: notice what is happening, decide what to do, act, and check the result.

> *See also:* [OODA loop (Wikipedia)](https://en.wikipedia.org/wiki/OODA_loop)

### Agentic AI
*Agentic AI* describes AI systems built around [*Autonomous Agents*](#autonomous-agent) that can pursue goals across many steps with limited human guidance. They make decisions along the way and use [*Tool Use*](#tool-use) to do real actions.

> *See also:* [Agentic AI (Wikipedia)](https://en.wikipedia.org/wiki/Agentic_AI)

### Alignment
*Alignment* is the scientific work of making sure an AI system's goals and behavior match what humans actually want.

> *See also:* [AI alignment (Wikipedia)](https://en.wikipedia.org/wiki/AI_alignment)

### Attention Mechanism
*Attention Mechanism* is a method that helps a model focus on the most important parts of the input.

> *See also:* [Attention (machine learning) (Wikipedia)](https://en.wikipedia.org/wiki/Attention_(machine_learning))

### Artificial General Intelligence (AGI)
*Artificial General Intelligence (AGI)* is a theoretical type of AI that could handle most thinking tasks at about human level across many fields.

> *See also:* [Artificial general intelligence (Wikipedia)](https://en.wikipedia.org/wiki/Artificial_general_intelligence)

### Artificial Superintelligence (ASI)
*Artificial Superintelligence (ASI)* is a hypothetical form of AI that would perform better than humans at almost every thinking task.

> *See also:* [Superintelligence (Wikipedia)](https://en.wikipedia.org/wiki/Superintelligence)

### Autonomous Agent
*Autonomous Agent* is an AI system that can plan and carry out actions toward a goal with little step-by-step human instruction. It often uses [*Goal Decomposition*](#goal-decomposition) to break big goals into smaller tasks.

> *See also:* [Intelligent agent (Wikipedia)](https://en.wikipedia.org/wiki/Intelligent_agent)

## B

### Bias
*Bias* is a systematic error where an AI makes unfair or lopsided decisions because of issues in training data or model behavior.

> *See also:* [Bias in artificial intelligence (Wikipedia)](https://en.wikipedia.org/wiki/Bias_in_artificial_intelligence)

## C

### Chain-of-Thought (CoT) Prompting
*Chain-of-Thought (CoT) Prompting* is a technique that asks a model to reason through steps before giving a final answer.

> *See also:* [Prompt engineering (Wikipedia)](https://en.wikipedia.org/wiki/Prompt_engineering#Chain-of-thought)

### Constitutional AI
*Constitutional AI* trains a model to follow a written set of rules meant to keep behavior safer and more helpful.

> *See also:* [Constitutional AI (Anthropic)](https://www.anthropic.com/news/constitutional-ai-harmlessness-from-ai-feedback)

### Context Window
*Context Window* is the amount of information a model can consider at one time while producing a response.

> *See also:* [Large language model (Wikipedia)](https://en.wikipedia.org/wiki/Large_language_model#Context_window)

## D

### Dark Factory
*Dark Factory* is a fully automated manufacturing facility that operates without human workers on-site. All production processes are handled by machines, robots, and AI systems, often running continuously without lights or climate controls needed for people.

> *See also:* [Lights-out manufacturing (Wikipedia)](https://en.wikipedia.org/wiki/Lights-out_manufacturing)

### Deep Learning
*Deep Learning* is a way to train AI with many layers of neural networks so it can learn hard patterns from data.

> *See also:* [Deep learning (Wikipedia)](https://en.wikipedia.org/wiki/Deep_learning)

### Diffusion Model
*Diffusion Model* is a model that learns to create images or other data by removing noise step by step.

> *See also:* [Diffusion model (Wikipedia)](https://en.wikipedia.org/wiki/Diffusion_model)

## E

### Embeddings
*Embeddings* are lists of numbers that represent meaning, so similar ideas end up close together.

> *See also:* [Word embedding (Wikipedia)](https://en.wikipedia.org/wiki/Word_embedding)

### Energy Based Model (EBM)
An *Energy Based Model (EBM)* is a type of machine learning model that assigns a scalar energy value to each possible configuration of inputs and outputs — low energy means a likely or compatible pairing, high energy means unlikely.

Rather than learning explicit probability distributions, EBMs learn an energy landscape, making them flexible enough to model complex dependencies. They underpin approaches like denoising score matching and have influenced diffusion models and contrastive learning.

> *See also:* [Energy-based model (Wikipedia)](https://en.wikipedia.org/wiki/Energy-based_model)

### Explainable AI (XAI)
*Explainable AI (XAI)* means building AI in a way people can review and understand why it made a decision.

> *See also:* [Explainable artificial intelligence (Wikipedia)](https://en.wikipedia.org/wiki/Explainable_artificial_intelligence)

## F

### Few-shot Learning
*Few-shot Learning* is when a model learns a task from only a few examples.

> *See also:* [Few-shot learning (Wikipedia)](https://en.wikipedia.org/wiki/Few-shot_learning)

### Fine-tuning
*Fine-tuning* is extra training on an already trained model so it performs better for one specific task or topic.

> *See also:* [Fine-tuning (deep learning) (Wikipedia)](https://en.wikipedia.org/wiki/Fine-tuning_(deep_learning))

### Foundation Models
*Foundation Models* are large, general-purpose models trained on broad data that can be adapted to many tasks.

> *See also:* [Foundation models (Wikipedia)](https://en.wikipedia.org/wiki/Foundation_models)

## G

### Generative AI (GenAI)
*Generative AI (GenAI)* describes models designed to generate new content such as text, images, audio, or code.

> *See also:* [Generative artificial intelligence (Wikipedia)](https://en.wikipedia.org/wiki/Generative_artificial_intelligence)

### Goal Decomposition
*Goal Decomposition* is the process of breaking a big goal into smaller, ordered tasks that can be done step by step.

> *See also:* [Task analysis (Wikipedia)](https://en.wikipedia.org/wiki/Task_analysis)

### Grounding
*Grounding* means linking answers to trusted sources so responses stay accurate and easy to check.

> *See also:* [Grounding (Wikipedia)](https://en.wikipedia.org/wiki/Grounding)

## H

### Hallucination
*Hallucination* is when a model gives an answer that sounds right but is made up or wrong.

> *See also:* [Hallucination (artificial intelligence) (Wikipedia)](https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence))

## J

### Jailbreaking
*Jailbreaking* is trying to get an AI system to ignore its safety rules.

> *See also:* [Prompt injection (Wikipedia)](https://en.wikipedia.org/wiki/Prompt_injection)

## L

### Large Language Model (LLM)
*Large Language Model (LLM)* is an AI model trained on a lot of text so it can understand and produce human-like language.

> *See also:* [Large language model (Wikipedia)](https://en.wikipedia.org/wiki/Large_language_model)

### Large Reasoning Models
*Large Reasoning Models* are [*Large Language Models (LLMs)*](#large-language-model-llm) tuned to solve harder problems by doing extra thinking before giving a final answer.

> *See also:* [Chain-of-thought prompting (Wikipedia)](https://en.wikipedia.org/wiki/Chain-of-thought_prompting)

### Latent Space
*Latent Space* is the model's internal math space where similar things are placed closer together.

> *See also:* [Latent space (Wikipedia)](https://en.wikipedia.org/wiki/Latent_space)

### Low-Rank Adaptation (LoRA)
*Low-Rank Adaptation (LoRA)* is a fine-tuning method that changes a small set of values instead of updating all model [*Weights*](#weights).

> *See also:* [LoRA (arXiv)](https://arxiv.org/abs/2106.09685)

## M

### Machine Learning (ML)
*Machine Learning (ML)* is part of AI where models learn from data instead of only following fixed rules written by people.

> *See also:* [Machine learning (Wikipedia)](https://en.wikipedia.org/wiki/Machine_learning)

### Mixture of Experts (MoE)
*Mixture of Experts (MoE)* is a model design where only a few specialized parts are used for each request, which can make the model faster and cheaper to run.

> *See also:* [Mixture of experts (Wikipedia)](https://en.wikipedia.org/wiki/Mixture_of_experts)

### Model Context Protocol (MCP)
*Model Context Protocol (MCP)* is a standard way for AI systems to connect to outside tools and data sources. It enables consistent [*Tool Use*](#tool-use) so one assistant can work with many integrations in the same way.

> *See also:* [Communication protocol (Wikipedia)](https://en.wikipedia.org/wiki/Communication_protocol)

### Multimodality
*Multimodality* means a model can work with more than one data type, like text, images, video, and audio.

> *See also:* [Multimodal learning (Wikipedia)](https://en.wikipedia.org/wiki/Multimodal_learning)

## N

### Neural Network
*Neural Network* is a layered math model inspired by the brain, and it is used widely in modern machine learning.

> *See also:* [Neural network (Wikipedia)](https://en.wikipedia.org/wiki/Neural_network)

## P

### Parameters
*Parameters* are the learned numbers inside a model that shape how it responds.

> *See also:* [Statistical parameter (Wikipedia)](https://en.wikipedia.org/wiki/Statistical_parameter)

### Pre-training
*Pre-training* is the first training stage where a model learns general patterns before later steps like [*Fine-tuning*](#fine-tuning).

> *See also:* [Pre-training (machine learning) (Wikipedia)](https://en.wikipedia.org/wiki/Pre-training)

### Prompt Chaining
*Prompt Chaining* is doing a task in steps, where each prompt uses the previous step's output.

> *See also:* [Prompt engineering (Wikipedia)](https://en.wikipedia.org/wiki/Prompt_engineering)

### Prompt Engineering
*Prompt Engineering* is the practice of writing better inputs and instructions so models give better answers.

> *See also:* [Prompt engineering (Wikipedia)](https://en.wikipedia.org/wiki/Prompt_engineering)

### Prompt Injection
*Prompt Injection* is a security attack where hidden instructions in input try to make an AI system ignore its intended rules.

> *See also:* [Prompt injection (Wikipedia)](https://en.wikipedia.org/wiki/Prompt_injection)

## Q

### Quantization
*Quantization* lowers number precision in a model so it uses less memory and can run faster.

> *See also:* [Quantization (signal processing) (Wikipedia)](https://en.wikipedia.org/wiki/Quantization_(signal_processing))

## R

### Red Teaming
*Red Teaming* is stress-testing an AI system to find safety, security, or reliability problems.

> *See also:* [Red team (Wikipedia)](https://en.wikipedia.org/wiki/Red_team)

### Reinforcement Learning (RL)
*Reinforcement Learning (RL)* trains agents with rewards and penalties so they learn actions that work better over time.

> *See also:* [Reinforcement learning (Wikipedia)](https://en.wikipedia.org/wiki/Reinforcement_learning)

### Retrieval-Augmented Generation (RAG)
*Retrieval-Augmented Generation (RAG)* is a method where a model first looks up relevant documents, often through a [*Vector Database*](#vector-database), and then uses that information to produce a more grounded answer.

> *See also:* [Retrieval-augmented generation (Wikipedia)](https://en.wikipedia.org/wiki/Retrieval-augmented_generation)

## S

### Small Language Model (SLM)
*Small Language Model (SLM)* is a language model with fewer [*Parameters*](#parameters), often built to be cheaper and faster.

> *See also:* [Language model (Wikipedia)](https://en.wikipedia.org/wiki/Language_model)

### Source Citations
*Source Citations* are references that show which source passages an AI answer is based on, so people can check whether a claim is supported.

> *See also:* [Citation (Wikipedia)](https://en.wikipedia.org/wiki/Citation)

### Stochastic Parrot
*Stochastic Parrot* is a term that says language models mainly predict likely text patterns, not true understanding.

> *See also:* [On the Dangers of Stochastic Parrots (ACM FAccT)](https://dl.acm.org/doi/10.1145/3442188.3445922)

### Synthetic Data
*Synthetic Data* is data made by software instead of collected from the real world.

> *See also:* [Synthetic data (Wikipedia)](https://en.wikipedia.org/wiki/Synthetic_data)

## T

### Tokens
*Tokens* are the basic text units a language model processes, which can be whole words, parts of words, or punctuation.

> *See also:* [Lexical analysis (Wikipedia)](https://en.wikipedia.org/wiki/Lexical_analysis#Tokenization)

### Tool Use
*Tool Use* is the ability of an AI system to call external tools, such as APIs, databases, or scripts, to take actions beyond text generation.

> *See also:* [Application programming interface (Wikipedia)](https://en.wikipedia.org/wiki/API)

### Transformer
*Transformer* is the model design behind most modern language models, built around [*Attention Mechanism*](#attention-mechanism).

> *See also:* [Transformer (deep learning architecture) (Wikipedia)](https://en.wikipedia.org/wiki/Transformer_(deep_learning_architecture))

## V

### Vector Database
*Vector Database* is a database built for storing and searching [*Vector Embeddings*](#vector-embedding), so systems can find content by meaning instead of exact keyword matches.

> *See also:* [Vector database (Wikipedia)](https://en.wikipedia.org/wiki/Vector_database)

### Vector Embedding
*Vector Embedding* is a numeric representation of text, images, or other data where similar meaning is placed near each other in a math space.

> *See also:* [Word embedding (Wikipedia)](https://en.wikipedia.org/wiki/Word_embedding)

## W

### Weights
*Weights* are the adjustable numbers in a model that store what it learned.

> *See also:* [Artificial neural network (Wikipedia)](https://en.wikipedia.org/wiki/Artificial_neural_network)

### World Model
*World Model* is an internal map an agent uses to predict what will happen after an action.

> *See also:* [World model (Wikipedia)](https://en.wikipedia.org/wiki/World_model)

## Z

### Zero-shot Learning
*Zero-shot Learning* is when a model can do a new task without seeing direct examples first.

> *See also:* [Zero-shot learning (Wikipedia)](https://en.wikipedia.org/wiki/Zero-shot_learning)
