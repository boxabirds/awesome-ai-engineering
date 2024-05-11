# awesome-ai-engineering
List of resources helping you become a better AI engineer. 

# What's an AI Engineer? 

* [Microsoft's definition](https://learn.microsoft.com/en-us/training/career-paths/ai-engineer) "Artificial intelligence (AI) engineers are responsible for developing, programming and training the complex networks of algorithms that make up AI so that they can function like a human brain. This role requires combined expertise in software development, programming, data science and data engineering"
* [Coursera's definition](https://www.coursera.org/articles/ai-engineer) "Artificial intelligence engineers are individuals who use AI and machine learning techniques to develop applications and systems that can help organizations increase efficiency, cut costs, increase profits, and make better business decisions."
* [Tech Target](https://www.techtarget.com/whatis/feature/How-to-become-an-artificial-intelligence-engineer) "AI engineers develop, program and train the complex networks of algorithms that encompass AI so those algorithms can work like a human brain. AI engineers must be experts in software development, data science, data engineering and programming."
* [Swyx podcast](https://pca.st/episode/ada36079-7bfa-4f06-9020-cdf37e65e34f?t=498.0) (17 April 2024)
# What's the difference between an AI Engineer and a Machine Learning Engineer?

* [UpWork](https://www.upwork.com/resources/ai-engineer-vs-ml-engineer#:~:text=AI%20engineers%20work%20on%20a,predictions%20from%20large%20data%20sets.) "AI engineers work on a broader set of tasks that encompass various forms of machine intelligence, like neural networks, to develop AI models for specific applications. In contrast, ML engineers focus more on ML algorithms and models that can self-tune to better learn and make predictions from large data sets."

# What's the difference between an AI Engineer and a Software Engineer? 
* [IEEE](https://www.computer.org/csdl/magazine/so/2022/06/09928183/1HJux2cbygM) ChatGPT's summary of that page "**AI engineers blend traditional software engineering skills with a deep understanding of machine learning and artificial intelligence** to develop systems that enhance decision-making and automation within organizations. They are proficient in AI technologies and statistical analysis, focusing on building and integrating AI models into applications. On the other hand, software engineers focus broadly on designing, implementing, and maintaining software systems, with a comprehensive grasp of the software development lifecycle, from requirement analysis to deployment and maintenance. The distinction is further marked by the AI engineer's need to navigate emerging AI technologies, whereas software engineers adhere to established engineering principles and practices across various platforms and technologies"

# Practical Tools & Techniques

This section covers useful stuff you can use to become a better AI engineer. 

## LLM Platforms and APIs
### LLM Platforms
- ChatGPT
- Claude.ai
- Phind (dev focus, GPT4+own)
- Microsoft Copilot (GPT4+own)
- Perplexity.ai
- You.com
- groq.com

### LLM APIs and Inference Services
- ollama: OS LLM inference service
- lmstudio.ai: local fine tuning UI
- msty.app: local OS LLM inference
- Nitro.jan.ai: OS LLM inference
- modal.com: on demand Serverless container +GPU execution runtime
- Predibase: LLM fine-tuning and hosting
- brev.dev: 
- Replicate.com: models-as-a service
- Together.ai: Serverless LLM / multimodal inference
- Lambda Labs: Manual rental of GPUs / clusters
- Beam.cloud: Serverless generative AI fast standup
- Runpod
- [Cloudflare Workers AI](https://blog.cloudflare.com/workers-ai)
- Coreweave: autoscale GPU + Serverless (knative)
- Mosaicml: (acquired by Databricks)
- mixedbread.ai: retrieval as a service (search, reranking, embedding)
- lamini.ai: LLM inference
- Anyscale + rai.ai scaling
- HF inference API
- massedcompute.com
- Salad.com
- Openpipe.ai
- Unsloth.ai
- Vast.ai: GPU rental market
- Akash
- Groq: ultra fast LLM for selected models
- BoltAI
- [Saturn Cloud](https://saturncloud.io/)
- Fireworks.ai
- Inferless.com
- Banana.dev (defunct)
- pipeline.ai 
- [hyperstack.cloud](https://www.hyperstack.cloud/)
- [Alibaba Elastic GPU service](https://www.alibabacloud.com/en/product/heterogeneous_computing?_p_lc=1)
- [Cloudalize GPU Kubenetes Service](https://www.cloudalize.com/solutions/kubernetes-gpu-cloud/)
- [Tensordock.com](https://tensordock.com/benchmarks) 
- [Fly GPU](https://fly.io/gpu) GPUs on demand

### Structured prompts 
- DSPy
- [Microsoft llmlingua prompt compression](https://github.com/microsoft/LLMLingua)
- SGLang
- outlines
- Instructor
- Marginalia
- natural-functions
- Qwen 0.5B
- Phidata

## LLM Development and Optimization
### LLM Testing and Evaluation
- promptfoo
- Ollama grid search
- Uptrain
- Google Cloud GCP AutoSxS
- Lmsys.org
- Paloma
- LightEval
- Bayesian Evaluation
- Mozilla's experience
- Ruler (long context evaluation)
- OpenAI Simple Evals

### Human Input Methods
- RLHF
- DPO
- TKO
- LIPO

### Architecture Innovations
- Longformer
- Reformer
- BigBird
- Attention Beacons
- RWKV
- Denseformer
- [Microsoft SliceGPT](https://github.com/microsoft/TransformerCompression) remove up to 25% of layers

### Fine-Tuning and Optimization
- Lazy Axolotl
- Lit-GPT
- Predibase
- Fine Tune Llama 2 Colab (by HF)
- Novelcrafter fine tune
- Openpipe.ai
- LISA
- Torchtune
- LASER layer reduction

### Task-Optimized LLMs and Context Extension
- Predibase LORALand
- RoPE
- Ailibi
- LongRoPE
- Unsloth+RoPE
- [InfiniAttention](https://github.com/kyegomez/Infini-attention): a pathway to ultra long context windows with manageable memory consumption

## Infrastructure and Tools
### Vector Stores
- pinecone
- weaviate
- chroma (open source)
- lancedb (open source)
- postgresql + pgvector (open source)
- sqlite + vss (open source)
- faiss by meta
- Vespa.ai + binary embeddings

### Cloud Hosting
- Blueocean / paperspace for GPU
- AWS
- GCP
- Azure
- Hetzner GPU
- Cloudflare

### Notebooks and Code Interpreters
- Lightning Studio
- Google Colab
- ChatGPT
- Julius.ai

### Attention Mechanisms
- FlashAttentionv2
- HippoAttention
- RingAttention
- PagedAttention

### Model Merging
- Efficient Linear Model Merging for LLMs
- Automerge
- Sakana Evolutionary Model Merge

### Optimizers and Autodifferentiation
#### Optimizers
- Adam
- AdamW
- Prodigy
- Schedule-free optimizers (April 2024)

#### Autodifferentiation Libraries
- SymPy
- torch.autograd
- Autograd
- tf.GradientTape

### Prompt Debugging
- mitmproxy (via Show Me The Prompt)

### Agents and Swarms
- CrewAI
- Autogen
- OpenDevin
- SWE-agent
- [Leda](https://github.com/elder-plinius/Leda)

### Chat with Your Data/RAG
- Weaviate [Verba](https://github.com/weaviate/Verba): RAG solution using Weaviate
- Microsoft GitHub
- AWS Bedrock embeddings, streamlit, langchain, pinecone, claude, etc.
- AWS Serverless
- GCP 
- Gemini for document processing
- AWS knowledge bases for bedrock

### Guardrails and Safety
- Llamaguard
- Llamaguard with streaming
- Guardrails for AWS Bedrock

### Embeddings and Document Processing
#### Embeddings Services
- Amazon Titan Embeddings
- Huggingface
- Nomic + ollama
- Cohere multi-aspect embeddings
- LLM2Vec

#### Document Extraction Services
- Amazon Kendra

#### Embeddings Algorithms
- Colbert
- Binary quantization

### Multi-Adapter Models
- Punica

### GPU Usage Optimization
- Run.ai -- service for bare metal GPU cluster management now owned by Nvidia

### Important Datasets
- sst2 sentiment movie sentiment (HF)
- 650,000 English books
- Openwebtext
- Fineweb

### Synthetic Data Generation
- generator9000

### GPUs and Accelerators
- Groq
- Truffle-1

### Data Curation
- NeMo-Curator

### ML Local Mini Clusters
- Tinybox / tinygrad

### Custom Rigs
- WOPR (7 x 4090)

### Data Labeling
- Argilla Distilabel
- Spacy Prodigy
- Snorkel

### Model Configuration Management
- DVCorg
- WandB Weave