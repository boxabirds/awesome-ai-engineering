# awesome-ai-engineering
List of resources helping you become a better AI engineer. 

# What's an AI Engineer? 

* [Microsoft's definition](https://learn.microsoft.com/en-us/training/career-paths/ai-engineer) "Artificial intelligence (AI) engineers are responsible for developing, programming and training the complex networks of algorithms that make up AI so that they can function like a human brain. This role requires combined expertise in software development, programming, data science and data engineering"
* [Coursera's definition](https://www.coursera.org/articles/ai-engineer) "Artificial intelligence engineers are individuals who use AI and machine learning techniques to develop applications and systems that can help organizations increase efficiency, cut costs, increase profits, and make better business decisions."
* [Tech Target](https://www.techtarget.com/whatis/feature/How-to-become-an-artificial-intelligence-engineer) "AI engineers develop, program and train the complex networks of algorithms that encompass AI so those algorithms can work like a human brain. AI engineers must be experts in software development, data science, data engineering and programming."
* [Swyx podcast](https://pca.st/episode/ada36079-7bfa-4f06-9020-cdf37e65e34f?t=498.0) (17 April 2024)
* [Scaler Blogs](https://www.scaler.com/blog/how-to-become-an-ai-engineer/) "AI engineers design, develop, and deploy intelligent systems using machine learning, deep learning, and NLP to solve complex problems and enable autonomous decision-making."

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

#### GPU Marketplaces
- [GPUList.ai](https://gpulist.ai/)
- [Vast.ai](https://vast.ai)
-[Prime Intellect](https://www.primeintellect.ai/)


#### free open weight playgrounds 
Try out open source models instantly. 
- [Perplexity Labs](https://labs.perplexity.ai) side by side comparison
- [Groq chat](https://chat.groq.com) demo a subset of models on Groq's proprietary inference hardware (LPUs)
- [Vercel AI Playground](https://sdk.vercel.ai/)

#### self-hosted Open weight inference 
- ollama (go/open source)
- [LocalAI](https://github.com/mudler/LocalAI) (go/open source)
- msty.app
- Nitro.jan.ai
- [Paddler](https://github.com/distantmagic/paddler) scaling / load balancing of llama.cpp inference

#### SaaS
- [fal.ai](https://fal.ai)
- [lepton.ai](https://www.lepton.ai/)
- modal.com: on demand Serverless container +GPU execution runtime
- Predibase: LLM fine-tuning and hosting
- [https://hpc-ai.com/](HPC AI): GPU rental
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
- Crusoe.ai GPU rental
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
-  [Jarvis Labs](https://jarvislabs.ai/) GPUs on demand
- [BentoML](https://bentoml.com/) open source open weight inference with cloud option
- [bitbop GPU dev the cloud](https://bitbop.io/)
- [Simplepid.ai](SimplePod)

### Structured output
- SGLang
- outlines
- Instructor
- Marginalia

### Prompt engineering
- [ATLAS](https://github.com/VILA-Lab/ATLAS)
- DSPy
- [Microsoft llmlingua prompt compression](https://github.com/microsoft/LLMLingua)


## LLM Development and Optimization
### LLM Testing and Evaluation
- promptfoo
- Ollama grid search
- Uptrain
- Google Cloud GCP AutoSxS
- Paloma
- LightEval
- Bayesian Evaluation
- Mozilla's experience
- Ruler (long context evaluation)
- OpenAI Simple Evals
- [Moonshot](https://github.com/aiverify-foundation/moonshot)



#### Leaderboards / Evaluations
- [SEAL](https://scale.com/leaderboard)
- Lmsys.org
- [HuggingFace Open LLM leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard)
- [Vectara Hallucination Leaderboard](https://huggingface.co/spaces/vectara/leaderboard) 
- [Text Embedding Leaderboard](https://huggingface.co/spaces/mteb/leaderboard)
- [Enterprise Use Case Leaderboard](https://huggingface.co/spaces/PatronusAI/enterprise_scenarios_leaderboard) Finance, Legal, Customer Support
- [MixEval](https://mixeval.github.io/)
- [Arena Hard Auto](https://github.com/lm-sys/arena-hard-auto)
- [Google Instruction Following Eval / IFEval](https://github.com/google-research/google-research/tree/master/instruction_following_eval) 

#### Observability
- [Phoenix](https://github.com/Arize-ai/phoenix) 
- [Helicone](https://www.helicone.ai/) 

### Pretraining
[llm.c: Andrey Karparthy's GPT-2 from thr ground up in raw C](https://x.com/yuchenj_uw/status/1798594515168903307?s=46)

### Human Input Methods
- RLHF
- DPO
- TKO
- LIPO
- DORA
- SPO

### Architecture Innovations
- Longformer
- Reformer
- BigBird
- Attention Beacons
- RWKV
- Denseformer
- [Microsoft SliceGPT](https://github.com/microsoft/TransformerCompression) remove up to 25% of layers
- [DCFormer](https://github.com/Caiyun-AI/DCFormer)

#### Tokenizers
- [ZeTT](https://github.com/bminixhofer/zett)

### Fine-Tuning and Optimization
- Lazy Axolotl
- Lit-GPT
- Predibase
- Fine Tune Llama 2 Colab (by HF)
- Openpipe.ai
- LISA
- Torchtune
- LASER layer reduction
- lmstudio.ai
- [AutoQuant](https://colab.research.google.com/drive/1b6nqC7UZVt8bx4MksX7s656GXPM-eWw4?usp=sharing)
- [Mistral fine tuning service](https://mistral.ai/news/customization/) [Github](https://github.com/mistralai/mistral-finetune)

### Task-Optimized LLMs and Context Extension
- Predibase LORALand
- RoPE
- Ailibi
- LongRoPE
- Unsloth+RoPE
- [InfiniAttention](https://github.com/kyegomez/Infini-attention): a pathway to ultra long context windows with manageable memory consumption

## Infrastructure and Tools
### Vector Stores / Information Retrieval
- pinecone
- weaviate
- chroma (open source)
- lancedb (open source)
- postgresql + pgvector (open source)
- sqlite + vss (open source)
- faiss by meta
- Vespa.ai + binary embeddings

#### Telemetry
- [IR measures](https://github.com/terrierteam/ir_measures)

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
- gomlx

### Prompt Debugging
- mitmproxy (via Show Me The Prompt)

### Agents and Swarms
- CrewAI
- Autogen
- OpenDevin
- [SWE-agent](https://github.com/princeton-nlp/SWE-agent)
- [Leda](https://github.com/elder-plinius/Leda)
- [Devon](https://github.com/entropy-research/Devon) open source pair programmer
- [HuggingFace Agents](https://huggingface.co/docs/transformers/main/en/agents)

### Analytics
- [Agent Ops](https://github.com/AgentOps-AI/agentops)
- [Weights and Biases](https://wandb.com)
- [Okareo](https://okareo.com/)

### Chat with Your Data/RAG
- Weaviate [Verba](https://github.com/weaviate/Verba): RAG solution using Weaviate
- Microsoft GitHub
- AWS Bedrock embeddings, streamlit, langchain, pinecone, claude, etc.
- AWS Serverless
- GCP 
- Gemini for document processing
- AWS knowledge bases for bedrock
- [FLARE](https://github.com/jzbjyb/FLARE) dynamically replace low-probability tokens with RAG lookups
- [Embedchain](https://github.com/embedchain/embedchain)

### Guardrails and Safety

#### Protection
- Llamaguard
- Llamaguard with streaming
- Guardrails for AWS Bedrock

#### Jailbreaks
- [Pliny the Prompter jailbreaks](https://github.com/elder-plinius/L1B3RT45)
- [Jailbreak LLMs](https://github.com/verazuo/jailbreak_llms)
- Haize

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
- Binary quantization (BitNet)

### Multi-Adapter Models
For hosting multiple fine-tunes at once
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
- WOPR (7 x 4090)

### Data Labeling
- Argilla Distilabel
- Spacy Prodigy
- Snorkel
- [Refuel-AI autolabel](https://github.com/refuel-ai/autolabel)

### Model Configuration Management
- DVCorg
- WandB Weave
