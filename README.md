<!-- <h1 align="center">
  <strong>A Comprehensive Survey of Self-Evolving AI Agents<br>A New Paradigm Bridging Foundation Models and Lifelong Agentic Systems</strong>
</h1> -->

<h1 align="center">
  <strong>Awesome-Self-Evolving-Agents</strong>
</h1>
<div align="center">


[![Awesome](https://awesome.re/badge.svg?logo=stylelint)](https://awesome.re)
[![arXiv](https://img.shields.io/badge/Arxiv-Self_Evoloving_AI_Agents-b31b1b.svg?logo=arXiv)](https://arxiv.org/abs/2508.07407)
[![Contribution Welcome](https://img.shields.io/badge/Contributions-welcome-Green?logo=mercadopago&logoColor=white)](https://github.com/EvoAgentX/Awesome-Self-Evolving-Agents/pulls)
[![GitHub star chart](https://img.shields.io/github/stars/EvoAgentX/Awesome-Self-Evolving-Agents?style=social)](https://star-history.com/#EvoAgentX/Awesome-Self-Evolving-Agents)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?)](LICENSE)

<h3 align="center">
  <strong>🤖 We're still cooking — Stay tuned! 🤖<br>⭐ Give us a star if you like it! ⭐</strong>
</h3>

<img src="./assets/evolve-tree.jpg" alt="Evolve Tree">
<br>
<em>Figure: A visual taxonomy of AI agent evolution and optimisation techniques, categorised into three major directions: single-agent optimisation, multi-agent optimisation, and domain-specific optimisation. The tree structure illustrates the development of these approaches from 2023 to 2025, including representative methods within each branch.</em>

</div>

## AI Agents Development Path

<p align="center">
  <img src="./assets/evolve-path.png" alt="Development Path", width="500">
</p>

## Conceptual Framework of the Self-Evolving AI Agents
<p align="center">
  <img src="./assets/evolve-framework.png" alt="Conceptual Framework", width="500">
</p>

## Open-Source Framework
- **EvoAgentX**: [[https://github.com/EvoAgentX/EvoAgentX](https://github.com/EvoAgentX/EvoAgentX)] [[paper](https://arxiv.org/abs/2507.03616)]


## 1. Single-Agent Optimisation 

### 1.1 🤖 LLM Behaviour Optimisation 

#### 1.1.1 📌 Training-Based Behaviour Optimisation 

##### (1) 🔧 Supervised Fine-Tuning Approaches 
- (*ICLR'24*) ToRA: A tool-integrated reasoning agent for mathematical problem solving [[📝 Paper](https://arxiv.org/abs/2309.17452)] [[💻 Code](https://github.com/microsoft/ToRA)]
- (*NeurIPS'22*) STaR : Bootstrapping reasoning with reasoning [[📝 Paper](https://arxiv.org/abs/2203.14465)] [[💻 Code](https://github.com/ezelikman/STaR)]
- (*Arxiv'24*) NExT: Teaching large language models to reason about code execution [[📝 Paper](https://arxiv.org/abs/2404.14662)]
- (*EMNLP'24*) MuMath-Code: Combining Tool-Use Large Language Models with Multi-perspective Data Augmentation for Mathematical Reasoning [[📝 Paper](https://arxiv.org/abs/2405.07551)] 

##### (2) 🔧 Reinforcement Learning Approaches 
- (*ICML'24*) Self-Rewarding Language Models [[📝 Paper](https://arxiv.org/abs/2401.10020)] [[💻 Code](https://github.com/lucidrains/self-rewarding-lm-pytorch)]
- (*Arxiv'24*) Tulu 3: Pushing Frontiers in Open Language Model Post-Training [[📝 Paper](https://arxiv.org/abs/2411.15124)] [[💻 Code](https://github.com/allenai/open-instruct)]
- (*EMNLP'24*) Learning Planning-based Reasoning by Trajectories Collection and Process Reward Synthesizing [[📝 Paper](https://arxiv.org/abs/2402.00658)] [[💻 Code](https://github.com/SparkJiao/dpo-trajectory-reasoning)]
- (*Arxiv'24*) Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents [[📝 Paper](https://arxiv.org/abs/2408.07199)]
- (*Arxiv'24*) DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data [[📝 Paper](https://arxiv.org/abs/2405.14333)]
- (*Arxiv'25*) Absolute Zero: Reinforced Self-play Reasoning with Zero Data [[📝 Paper](https://arxiv.org/abs/2505.03335)]
- (*Arxiv'25*) R-Zero: Self-Evolving Reasoning LLM from Zero Data [[📝 Paper](https://arxiv.org/abs/2508.05004)] [[💻 Code](https://github.com/Chengsong-Huang/R-Zero)]


#### 1.1.2 📌 Test-Time Behaviour Optimisation 

##### (1) 🔧 Feedback-Based Approaches 
- (*ICLR'23*) CodeT: Code Generation with Generated Tests [[📝 Paper](https://arxiv.org/abs/2207.10397)] [[💻 Code](https://github.com/microsoft/CodeT)]
- (*ICML'23*) LEVER: Learning to Verify Language-to-Code Generation with Execution [[📝 Paper](https://arxiv.org/abs/2302.08468)] [[💻 Code](https://github.com/niansong1996/lever)]
- (*ESEC/FSE'23*) Baldur: Whole-Proof Generation and Repair with Large Language Models [[📝 Paper](https://arxiv.org/abs/2303.04910)]
- (*ACL'24*) Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations [[📝 Paper](https://arxiv.org/abs/2312.08935)]
- (*EMNLP'24*) Learning Planning-based Reasoning by Trajectories Collection and Process Reward Synthesizing [[📝 Paper](https://arxiv.org/abs/2402.00658)] [[💻 Code](https://github.com/SparkJiao/dpo-trajectory-reasoning)]
- (*Arxiv'24*) Skywork-Reward: Bag of Tricks for Reward Modeling in LLMs [[📝 Paper](https://arxiv.org/abs/2410.18451)]
- (*ICLR'25*) Rewarding Progress: Scaling Automated Process Verifiers for LLM Reasoning [[📝 Paper](https://arxiv.org/abs/2410.08146)] 
- (*Arxiv'25*) Skywork-Reward-V2: Scaling Preference Data Curation via Human-AI Synergy [[📝 Paper](https://arxiv.org/abs/2507.01352)] [[💻 Code](https://github.com/SkyworkAI/Skywork-Reward-V2)]


##### (2) 🔧 Search-Based Approaches 
- (*ICLR'23*) Self-consistency improves chain of thought reasoning in language models [[📝 Paper](https://arxiv.org/abs/2203.11171)]
- (*ACL'23*) Solving Math Word Problems via Cooperative Reasoning induced Language Models [[📝 Paper](https://arxiv.org/abs/2210.16257)] [[💻 Code](https://github.com/TianHongZXY/CoRe)]
- (*NeurIPS'23*) Tree of thoughts: Deliberate problem solving with large language models [[📝 Paper](https://arxiv.org/abs/2305.10601)] [[💻 Code](https://github.com/princeton-nlp/tree-of-thought-llm)]
- (*NeurIPS'24*) Buffer of Thoughts: Thought-Augmented Reasoning with Large Language Models [[📝 Paper](https://arxiv.org/abs/2406.04271)] [[💻 Code](https://github.com/YangLing0818/buffer-of-thought-llm)]
- (*COLM'24*) Deductive Beam Search: Decoding Deducible Rationale for Chain-of-Thought Reasoning [[📝 Paper](https://arxiv.org/abs/2401.17686)] [[💻 Code](https://github.com/OSU-NLP-Group/Deductive-Beam-Search)]
- (*AAAI'24*) Graph of thoughts: Solving elaborate problems with large language models [[📝 Paper](https://arxiv.org/abs/2308.09687)] [[💻 Code](https://github.com/spcl/graph-of-thoughts)]
- (*ICML'25*) Forest-of-Thought: Scaling Test-Time Compute for Enhancing LLM Reasoning [[📝 Paper](https://arxiv.org/abs/2412.09078)] [[💻 Code](https://github.com/iamhankai/Forest-of-Thought)]

### 1.2 💬 Prompt Optimisation

#### 1.2.1 📌 Edit-Based Prompt Optimisation 
- (*EMNLP'22*) GPS: Genetic Prompt Search for Efficient Few-shot Learning [[📝 Paper](https://arxiv.org/abs/2210.17041)] [[💻 Code](https://github.com/hwxu20/GPS)]
- (*EACL'23*) GrIPS: Gradient-free, Edit-based Instruction Search for Prompting Large Language Models [[📝 Paper](https://arxiv.org/abs/2203.07281)] [[💻 Code](https://github.com/archiki/GrIPS)]
- (*ICLR'23*) TEMPERA: Test-Time Prompting via Reinforcement Learning [[📝 Paper](https://arxiv.org/abs/2211.11890)] [[💻 Code](https://github.com/tianjunz/TEMPERA)]
- (*ACL'24*) Plum: Prompt Learning using Metaheuristic [[📝 Paper](https://arxiv.org/abs/2311.08364)] [[💻 Code](https://github.com/research4pan/Plum)]

#### 1.2.2 📌 Evolutionary Prompt Optimisation 
- (*ICLR'24*) EvoPrompt: Connecting LLMs with Evolutionary Algorithms Yields Powerful Prompt Optimizers [[📝 Paper](https://arxiv.org/abs/2309.08532)] [[💻 Code](https://github.com/beeevita/EvoPrompt)]
- (*ICML'24*) Promptbreeder: Self-Referential Self-Improvement Via Prompt Evolution [[📝 Paper](https://arxiv.org/abs/2309.16797)]

#### 1.2.3 📌 Generative Prompt Optimisation 
- (*ICLR'23*) Large Language Models Are Human-Level Prompt Engineers [[📝 Paper](https://arxiv.org/abs/2211.01910)] [[💻 Code](https://github.com/keirp/automatic_prompt_engineer)]
- (*ICLR'24*) PromptAgent: Strategic Planning with Language Models Enables Expert-level Prompt Optimization [[📝 Paper](https://arxiv.org/abs/2310.16427)] [[💻 Code](https://github.com/XinyuanWangCS/PromptAgent)]
- (*ICLR'24*) Large Language Models as Optimizers [[📝 Paper](https://arxiv.org/abs/2309.03409)] [[💻 Code](https://github.com/google-deepmind/opro)]
- (*ICLR'24*) Retroformer: Retrospective Large Language Agents with Policy Gradient Optimization [[📝 Paper](https://arxiv.org/abs/2308.02151)] [[💻 Code](https://github.com/weirayao/Retroformer)]
- (*EMNLP'24*) Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs [[📝 Paper](https://arxiv.org/abs/2406.11695)] [[💻 Code](https://github.com/stanfordnlp/dspy)]
- (*Arxiv'24*) Prompt Optimization with Human Feedback [[📝 Paper](https://arxiv.org/abs/2405.17346)] [[💻 Code](https://github.com/xqlin98/APOHF)]
- (*Arxiv'24*) StraGo: Harnessing Strategic Guidance for Prompt Optimization [[📝 Paper](https://arxiv.org/abs/2410.08601)]
- (*Arxiv'25*) Self-Supervised Prompt Optimization [[📝 Paper](https://arxiv.org/abs/2502.06855)] 

#### 1.2.4 📌 Text Gradient-Based Prompt Optimisation 
- (*EMNLP'23*) Automatic Prompt Optimization with "Gradient Descent" and Beam Search [[📝 Paper](https://arxiv.org/abs/2305.03495)] [[💻 Code](https://github.com/microsoft/LMOps/tree/main/prompt_optimization)]
- (*Arxiv'24*) TextGrad: Automatic "Differentiation" via Text [[📝 Paper](https://arxiv.org/abs/2406.07496)] [[💻 Code](https://github.com/zou-group/textgrad)]
- (*Arxiv'24*) How to Correctly do Semantic Backpropagation on Language-based Agentic Systems [[📝 Paper](https://arxiv.org/abs/2412.03624)] [[💻 Code](https://github.com/HishamAlyahya/semantic_backprop)]
- (*Arxiv'24*) GRAD-SUM: Leveraging Gradient Summarization for Optimal Prompt Engineering [[📝 Paper](https://arxiv.org/abs/2407.12865)]
- (*AAAI'25*) Unleashing the Potential of Large Language Models as Prompt Optimizers: Analogical Analysis with Gradient-based Model Optimizers [[📝 Paper](https://arxiv.org/abs/2402.17564)] [[💻 Code](https://github.com/RUCAIBox/GPO)]
- (*ICML'25*) REVOLVE: Optimizing AI Systems by Tracking Response Evolution in Textual Optimization [[📝 Paper](https://arxiv.org/abs/2412.03092)] [[💻 Code](https://github.com/Peiyance/REVOLVE)]
 
### 1.3 🧠 Memory Optimization
- (*ICML'24*) A Human-Inspired Reading Agent with Gist Memory of Very Long Contexts [[📝 Paper](https://arxiv.org/abs/2402.09727)]
- (*ICML'24*) Agent Workflow Memory [[📝 Paper](https://arxiv.org/abs/2409.07429)] 
- (*AAAI'24*) MemoryBank: Enhancing Large Language Models with Long-Term Memory [[📝 Paper](https://arxiv.org/abs/2305.10250)]
- (*EMNLP'24*) GraphReader: Building graph-based agent to enhance long-context [[📝 Paper](https://arxiv.org/abs/2406.14550)]
- (*Arxiv'24*) "My agent understands me better": Integrating Dynamic Human-like Memory Recall and Consolidation in LLM-Based Agents [[📝 Paper](https://arxiv.org/abs/2404.00573)] 
- (*ICLR'25*) Compress to Impress: Unleashing the Potential of Compressive Memory in Real-World Long-Term Conversations [[📝 Paper](https://arxiv.org/abs/2402.11975)]
- (*ICLR'25*) Boosting knowledge intensive reasoning of llms via inference-time hybrid information [[📝 Paper](https://arxiv.org/abs/2410.08815)] [[💻 Code](https://github.com/icip-cas/StructRAG)]
- (*ACL'25*) Improving factuality with explicit working memory [[📝 Paper](https://arxiv.org/abs/2412.18069)]
- (*Arxiv'25*) A-MEM: Agentic Memory for LLM Agents [[📝 Paper](https://arxiv.org/abs/2502.12110)]
- (*Arxiv'25*) Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory [[📝 Paper](https://arxiv.org/abs/2504.19413)] 

### 1.4 🧰 Tool Optimization
- (*EMNLP'23*) CREATOR : Tool creation for disentangling abstract and concrete reasoning of large language model [[📝 Paper](https://arxiv.org/abs/2305.14318)] [[💻 Code](https://github.com/qiancheng0/CREATOR)]
- (*ICLR'24*) ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs [[📝 Paper](https://arxiv.org/abs/2307.16789)] [[💻 Code](https://github.com/beijixiong1/ToolLLM)]
- (*ICML'24*) Offline Training of Language Model Agents with Functions as Learnable Weights [[📝 Paper](https://arxiv.org/abs/2402.11359)] 
- (*AAAI'24*) Iterative tool learning from introspection feedback by easy-to-difficult curriculum [[📝 Paper](https://arxiv.org/abs/2308.14034)] [[💻 Code](https://github.com/shizhl/Confucius)] 
- (*Arxiv'25*) Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents [[📝 Paper](https://arxiv.org/pdf/2505.22954)] [[💻 Code](https://github.com/jennyzzt/dgm)] 
- (*Arxiv'25*) ReTool: Reinforcement Learning for Strategic Tool Use in LLMs [[📝 Paper](https://arxiv.org/abs/2504.11536)] [[💻 Code](https://github.com/ReTool-RL/ReTool)] 
- (*Arxiv'25*) ToolRL: Reward is All Tool Learning Needs [[📝 Paper](https://arxiv.org/abs/2504.13958)] [[💻 Code](https://github.com/qiancheng0/ToolRL)] 
- (*Arxiv'25*) Alita: Generalist Agent Enabling Scalable Agentic Reasoning with Minimal Predefinition and Maximal Self-Evolution [[📝 Paper](https://arxiv.org/abs/2505.20286)] [[💻 Code](https://github.com/CharlesQ9/Alita)]

### 1.5 🧰 Unified Optimization
- (*Arxiv'25*) Building Self-Evolving Agents via Experience-Driven Lifelong Learning: A Framework and Benchmark [[📝 Paper](https://arxiv.org/abs/2508.19005)] [[💻 Code](https://github.com/ECNU-ICALK/ELL-StuLife)]

## 2. Multi-Agent Optimisation 
- (*ICML'25*) Multi-Agent Architecture Search via Agentic Supernet [[📝 Paper](https://doi.org/10.48550/arXiv.2502.04180)][[💻 Code](https://github.com/bingreeky/MaAS)]
- (*ICML'25*) MA-LoT: Multi-Agent Lean-based Long Chain-of-Thought Reasoning enhances Formal Theorem Proving [[📝 Paper](https://arxiv.org/abs/2503.03205)]
- (*ICLR'25*) AFlow: Automating Agentic Workflow Generation [[📝 Paper](https://arxiv.org/abs/2410.10762)] [[💻 Code](https://github.com/geekan/MetaGPT/tree/main/examples/aflow)]
- (*ICLR'25*) WorkflowLLM: Enhancing Workflow Orchestration Capability of Large Language Models [[📝 Paper](https://openreview.net/forum?id=3Hy00Wvabi)]
- (*ICLR'25*) Flow: Modularized Agentic Workflow Automation [[📝 Paper](https://openreview.net/forum?id=sLKDbuyq99)]
- (*ICLR'25*) Automated Design of Agentic Systems [[📝 Paper](https://arxiv.org/abs/2408.08435)] [[💻 Code](https://github.com/ShengranHu/ADAS)]
- (*Arxiv'25*) FlowReasoner: Reinforcing Query-Level Meta-Agents [[📝 Paper](https://doi.org/10.48550/arXiv.2504.15257)]
- (*Arxiv'25*) AgentNet: Decentralized Evolutionary Coordination for LLM-Based Multi-Agent Systems [[📝 Paper](https://arxiv.org/abs/2504.00587)]
- (*Arxiv'25*) MAS-GPT: Training LLMs to Build LLM-Based Multi-Agent Systems [[📝 Paper](https://arxiv.org/abs/2503.03686)]
- (*Arxiv'25*) FlowAgent: Achieving Compliance and Flexibility for Workflow Agents [[📝 Paper](https://doi.org/10.48550/arXiv.2502.14345)]
- (*Arxiv'25*) ScoreFlow: Mastering LLM Agent Workflows via Score-Based Preference Optimization [[📝 Paper](https://arxiv.org/abs/2502.04306)] [[💻 Code](https://github.com/Gen-Verse/ScoreFlow)]
- (*Arxiv'25*) Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies [[📝 Paper](https://arxiv.org/abs/2502.02533)]
- (*Arxiv'25*) MAS-ZERO: Designing Multi-Agent Systems with Zero Supervision [[📝 Paper](https://arxiv.org/abs/2505.14996)]
- (*Arxiv'25*) MermaidFlow: Redefining Agentic Workflow Generation via Safety-Constrained Evolutionary Programming [[📝 Paper](https://arxiv.org/abs/2505.22967)]
- (*ICML'24*) GPTSwarm: Language Agents as Optimizable Graphs [[📝 Paper](https://arxiv.org/abs/2402.16823)] [[Code](https://github.com/metauto-ai/gptswarm)]
- (*ICLR'24*) DSPy: Compiling Declarative Language Model Calls into State-of-the-Art Pipelines [[📝 Paper](https://openreview.net/forum?id=sY5N0zY5Od)] [[💻 Code](https://github.com/stanfordnlp/dspy)]
- (*ICLR'24*) AgentVerse: Facilitating Multi-Agent Collaboration and Exploring Emergent Behaviors [[📝 Paper](https://openreview.net/forum?id=EHg5GDnyq1)] [[💻 Code](https://github.com/OpenBMB/AgentVerse)]
- (*ICLR'24*) MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework [[📝 Paper](https://openreview.net/forum?id=VtmBAGCN7o)] [[💻 Code](https://github.com/geekan/MetaGPT)]
- (*COLM'24*) A Dynamic LLM-Powered Agent Network for Task-Oriented Agent Collaboration [[📝 Paper](https://openreview.net/forum?id=XII0Wp1XA9)]
- (*COLM'24*) AutoGen: Enabling next-Gen LLM Applications via Multi-Agent Conversations [[📝 Paper](https://openreview.net/forum?id=BAakY1hNKS)] [[💻 Code](https://github.com/microsoft/autogen)]
- (*Arxiv'24*) G-Designer: Architecting Multi-Agent Communication Topologies via Graph Neural Networks [[📝 Paper](https://doi.org/10.48550/arXiv.2410.11782)]
- (*Arxiv'24*) AutoFlow: Automated Workflow Generation for Large Language Model Agents [[📝 Paper](https://arxiv.org/abs/2407.12821)] [[💻 Code](https://github.com/agiresearch/AutoFlow)]
- (*Arxiv'24*) Symbolic Learning Enables Self-Evolving Agents [[📝 Paper](https://arxiv.org/abs/2406.18532)] [[💻 Code](https://github.com/aiwaves-cn/agents)]
- (*Arxiv'24*) Adaptive In-Conversation Team Building for Language Model Agents [[📝 Paper](https://arxiv.org/abs/2405.19425)]

## 3. Evaluation 

### 3.1 📈 Benchmark-Based Evaluation 

#### 3.1.1 📌 Tool and API-Driven Agents 
- (*Arxiv'23*) On the Tool Manipulation Capability of Open-source Large Language Models [[📝 Paper](https://arxiv.org/abs/2305.16504)] [[💻 Code](https://github.com/sambanova/toolbench)]
- (*EMNLP'23*) API-Bank: A Comprehensive Benchmark for Tool-Augmented LLMs [[📝 Paper](https://arxiv.org/abs/2304.08244)] [[💻 Code](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank)]
- (*NeurIPS'23*) ToolQA: A Dataset for LLM Question Answering with External Tools [[📝 Paper](https://arxiv.org/abs/2306.13304)] [[💻 Code](https://github.com/night-chen/ToolQA)]
- (*ICLR'24*) MetaTool Benchmark for Large Language Models: Deciding Whether to Use Tools and Which to Use
 [[📝 Paper](https://arxiv.org/abs/2310.03128)] [[💻 Code](https://github.com/HowieHwong/MetaTool)] 

#### 3.1.2 📌 Web Navigation and Browsing Agents 
- (*ICLR'24*) WebArena: A Realistic Web Environment for Building Autonomous Agents [[📝 Paper](https://arxiv.org/abs/2307.13854)] [[💻 Code](https://github.com/web-arena-x/webarena)]
- (*Arxiv'25*) BrowseComp: A Simple Yet Challenging Benchmark for Browsing Agents [[📝 Paper](https://arxiv.org/abs/2504.12516)] [[💻 Code](https://github.com/openai/simple-evals)]
- (*ACL'25*) WebWalker: Benchmarking LLMs in Web Traversal [[📝 Paper](https://arxiv.org/abs/2501.07572)] [[💻 Code](https://github.com/Alibaba-NLP/WebAgent)]

#### 3.1.3 📌 Multi-Agent Collaboration and Generalists 
- (*ICLR'23*) GAIA: a benchmark for General AI Assistants [[📝 Paper](https://arxiv.org/abs/2311.12983)] [[💻 Code](https://huggingface.co/gaia-benchmark)]
- (*ICLR'24*) AgentBench: Evaluating LLMs as Agents [[📝 Paper](https://arxiv.org/abs/2308.03688)] [[💻 Code](https://github.com/THUDM/AgentBench)]
- (*Arxiv'25*) MultiAgentBench: Evaluating the Collaboration and Competition of LLM agents [[📝 Paper](https://arxiv.org/abs/2503.01935)] [[💻 Code](https://github.com/MultiagentBench/MARBLE)]
- (*Arxiv'25*) Benchmarking LLMs' Swarm intelligence [[📝 Paper](https://arxiv.org/abs/2505.04364)] [[💻 Code](https://github.com/RUC-GSAI/YuLan-SwarmIntell)]

#### 3.1.4 📌 GUI and Multimodal Environment Agents
- (*ACL'24*) Mobile-Bench: An Evaluation Benchmark for LLM-based Mobile Agents [[📝 Paper](https://arxiv.org/abs/2407.00993)] [[💻 Code](https://github.com/XiaoMi/MobileBench)]
- (*NeurIPS'24*) OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments [[📝 Paper](https://arxiv.org/abs/2404.07972)] [[💻 Code](https://github.com/xlang-ai/OSWorld)]
- (*ICLR'25*) AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents [[📝 Paper](https://arxiv.org/abs/2405.14573)] [[💻 Code](https://github.com/google-research/android_world)]

#### 3.1.4 📌 Domain-Specific Tasks 
- (*NeurIPS'23*) OpenAGI: When LLM Meets Domain Experts [[📝 Paper](https://arxiv.org/abs/2304.04370)] [[💻 Code](https://github.com/agiresearch/OpenAGI)]
- (*ICLR'24*) SWE-bench: Can Language Models Resolve Real-World GitHub Issues? [[📝 Paper](https://arxiv.org/abs/2310.06770)] [[💻 Code](https://github.com/SWE-bench/SWE-bench)]
- (*Arxiv'25*) DataSciBench: An LLM Agent Benchmark for Data Science [[📝 Paper](https://arxiv.org/abs/2502.13897)] [[💻 Code](https://github.com/THUDM/DataSciBench)]
- (*Arxiv'25*) MLGym: A New Framework and Benchmark for Advancing AI Research Agents [[📝 Paper](https://arxiv.org/abs/2502.14499)] [[💻 Code](https://github.com/facebookresearch/MLGym)]

### 3.2 ⚖️ LLM-Based Evaluation 

#### 3.2.1 📌 LLM-as-a-Judge

- (*Arxiv'24*) Towards Better Human-Agent Alignment: Assessing Task Utility in LLM-Powered Applications [[📝 Paper](https://arxiv.org/abs/2402.09015)] 
- (*Arxiv'24*) LLMs-as-Judges: A Comprehensive Survey on LLM-based Evaluation Methods [[📝 Paper](https://arxiv.org/abs/2412.05579)]
- (*Arxiv'25*) LiveIdeaBench: Evaluating LLMs’ Divergent Thinking for Scientific Idea Generation with Minimal Context [[📝 Paper](https://arxiv.org/abs/2412.17596)] [[💻 Code](https://github.com/x66ccff/liveideabench)]
- (*ACL'25*) Auto-Arena: Automating LLM Evaluations with Agent Peer Debate and Committee Voting [[📝 Paper](https://arxiv.org/abs/2405.20267)] [[💻 Code](https://github.com/DAMO-NLP-SG/Auto-Arena-LLMs)]
- (*Arxiv'25*) MCTS-Judge: Test-Time Scaling in LLM-as-a-Judge for Code Correctness Evaluation [[📝 Paper](https://arxiv.org/abs/2502.12468)]

#### 3.2.2 📌 Agent-as-a-Judge

- (*Arxiv'24*) Agent-as-a-Judge: Evaluate Agents with Agents [[📝 Paper](https://arxiv.org/abs/2410.10934)] [[💻 Code](https://github.com/metauto-ai/agent-as-a-judge)]

### 3.3 🛡 Safety, Alignment, and Robustness for Lifelong / Self-Evolving Agents

- (*Arxiv'24*) AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents [[📝 Paper](https://arxiv.org/abs/2410.09024) ]
- (*NeurIPS'24 – Datasets & Benchmarks*) RedCode: Risky Code Execution and Generation [[📝 Paper](https://arxiv.org/abs/2411.07781) ]
- (*Arxiv'24*) MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control [[📝 Paper](https://arxiv.org/abs/2410.17520)] [[mobilesafetybench.github.io](https://mobilesafetybench.github.io/)]
- (*Arxiv'23*) Do the Rewards Justify the Means? Measuring Trade-Offs Between Rewards and Ethical Behavior in the MACHIAVELLI Benchmark [[📝 Paper](https://arxiv.org/abs/2304.03279) ]
- (*Arxiv'24*) R-Judge: Benchmarking Safety Risk Awareness for LLM Judges [[📝 Paper](https://arxiv.org/abs/2401.10019)] [[💻 Code](https://rjudgebench.github.io/)]
- (*ACL'25*) SafeLawBench: Towards Safe Alignment of Large Language Models [[📝 Paper](https://arxiv.org/abs/2506.06636) ]

[![Star History Chart](https://api.star-history.com/svg?repos=EvoAgentX/Awesome-Self-Evolving-Agents&Date&type=Date)](https://www.star-history.com/#EvoAgentX/Awesome-Self-Evolving-Agents&Date&Date)


## 📚 Citation

If you find this survey useful in your research and applications, please cite using this BibTeX:

```
@article{fang2025comprehensive,
  title={A Comprehensive Survey of Self-Evolving AI Agents: A New Paradigm Bridging Foundation Models and Lifelong Agentic Systems},
  author={Fang, Jinyuan and Peng, Yanwen and Zhang, Xi and Wang, Yingxu and Yi, Xinhao and Zhang, Guibin and Xu, Yi and Wu, Bin and Liu, Siwei and Li, Zihao and others},
  journal={arXiv preprint arXiv:2508.07407},
  year={2025}
}
```


## ☕ Acknowledgement

We would like to thank Shuyu Guo for his valuable contributions to the early-stage exploration and literature
review on agent optimisation.

## ✉️ Contact Us

If you have any questions or suggestions, please feel free to contact us via:

Email: j.fang.2@research.gla.ac.uk and Zaiqiao.Meng@glasgow.ac.uk
