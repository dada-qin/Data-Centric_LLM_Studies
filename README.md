# Data-Centric LLM Studies
A list of papers focusing on data-centric studies in Large Language Models (LLMs).

## Contents

- [Pretraining](#pretraining)

  - [Scaling Laws](#scaling-laws)
  - [Data Quality Evaluation](#data-quality-evaluation)
  - [Data Quality Improvement](#data-quality-improvement)
  - [Data Management System](#data-management-system)

- [Supervised Fine-Tuning](#supervised-fine-tuning)

  - [Scaling Laws](#scaling-laws-1)
  - [Data Quality Evaluation](#data-quality-evaluation-1)
  - [Data Quality Improvement](#data-quality-improvement-1)
  - [Data Management System](#data-management-system-1)

- [Survey](#survey)
- [Useful Resources](#useful-resources)

## Pretraining

### Scaling Laws

- Scaling Laws for Neural Language Models (Arxiv, Jan. 2020) [[Paper]](https://arxiv.org/abs/2001.08361)

- An empirical analysis of compute-optimal large language model training (NeurIPS 2022) [[Paper]](https://papers.nips.cc/paper_files/paper/2022/hash/c1e2faff6f588870935f114ebe04a3e5-Abstract-Conference.html)

- Will we run out of data? An analysis of the limits of scaling datasets in Machine Learning (Arxiv, Oct. 2022) [[Paper]](https://arxiv.org/abs/2211.04325)

- Scaling Data-Constrained Language Models (Arxiv, May 2023) [[Paper]](https://arxiv.org/abs/2305.16264) [[Code]](https://github.com/huggingface/datablations)

### Data Quality Evaluation
- A Survey on Evaluation of Large Language Models (Arxiv, Oct. 2023) [[Paper]](https://arxiv.org/abs/2307.03109)

### Data Quality Improvement

- #### Data Deduplication

  - Deduplicating training data makes language models better (ACL 2022) [[Paper]](https://arxiv.org/abs/2107.06499) [[Code]](https://github.com/google-research/deduplicate-text-datasets)
  - Deduplicating training data mitigates privacy risks in language models (ICML 2022) [[Paper]](https://proceedings.mlr.press/v162/kandpal22a.html) 
  - Noise-Robust De-Duplication at Scale (ICLR 2022) [[Paper]](https://scholar.harvard.edu/dell/publications/noise-robust-de-duplication-scale) 
  - SemDeDup: Data-efficient learning at web-scale through semantic deduplication (Arxiv, Mar. 2023) [[Paper]](https://arxiv.org/pdf/2303.09540.pdf) [[Code]](https://github.com/facebookresearch/SemDeDup)
  - The MiniPile Challenge for Data-Efficient Language Models (Arxiv, April 2023) [[Paper]](https://arxiv.org/abs/2304.08442) [[Dataset]](https://huggingface.co/datasets/JeanKaddour/minipile)

- #### Data Filter
  - An Empirical Exploration in Quality Filtering of Text Data (Arxiv, Sep. 2021) [[Paper]](https://arxiv.org/abs/2109.00698) 
  - Quality at a glance: An audit of web-crawled multilingual datasets (ACL 2022) [[Paper]](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00447/109285/Quality-at-a-Glance-An-Audit-of-Web-Crawled) 
  - A Pretrainer's Guide to Training Data: Measuring the Effects of Data Age, Domain Coverage, Quality, & Toxicity (Arxiv, May 2023) [[Paper]](https://arxiv.org/abs/2305.13169)
  - Textbooks Are All You Need (Arxiv, Jun. 2023) [[Paper]](https://arxiv.org/abs/2306.11644) [[Code]](https://github.com/kyegomez/phi-1)
  - The RefinedWeb Dataset for Falcon LLM: Outperforming Curated Corpora with Web Data, and Web Data Only (NeurIPS Dataset and Benchmark track 2023) [[Paper]](https://www.semanticscholar.org/paper/7a1e71cb1310c4a873e7a4e54d1a6dab0553adce) [[Dataset]](https://huggingface.co/datasets/tiiuae/falcon-refinedweb)
  - Textbooks Are All You Need II: phi-1.5 technical report (Arxiv, Sep. 2023) [[Paper]](https://arxiv.org/abs/2309.05463) [[Model]](https://huggingface.co/microsoft/phi-1_5)
  - When less is more: Investigating Data Pruning for Pretraining LLMs at Scale (Arxiv, Sep. 2023) [[Paper]](https://arxiv.org/abs/2309.04564) 

- #### Data Composition
  - Data Selection for Language Models via Importance Resampling (Arxiv, Feb. 2023) [[Paper]](https://arxiv.org/pdf/2302.03169.pdf) [[Code]](https://github.com/p-lambda/dsir)
  - CodeGen2: Lessons for Training LLMs on Programming and Natural Languages (ICLR 2023) [[Paper]](https://arxiv.org/abs/2305.02309) [[Model]](https://github.com/salesforce/CodeGen2)
  - DoReMi: Optimizing Data Mixtures Speeds Up Language Model Pretraining (Arxiv, May 2023) [[Paper]](https://arxiv.org/abs/2305.10429) [[Code]](https://github.com/sangmichaelxie/doremi)
  - A Pretrainer's Guide to Training Data: Measuring the Effects of Data Age, Domain Coverage, Quality, & Toxicity (Arxiv, May 2023) [[Paper]](https://arxiv.org/abs/2305.13169)
  - SlimPajama-DC: Understanding Data Combinations for LLM Training (Arxiv, Sep. 2023) [[Paper]](https://arxiv.org/abs/2309.10818) [[Model]](https://huggingface.co/MBZUAI-LLM) [[Dataset]](https://huggingface.co/datasets/cerebras/SlimPajama-627B)
  - DoGE: Domain Reweighting with Generalization Estimation (Arxiv, Oct. 2023) [[Paper]](https://arxiv.org/abs/2310.15393)
  - Self-Influence Guided Data Reweighting for Language Model Pre-training (Arxiv, Nov. 2023) [[Paper]](https://arxiv.org/pdf/2311.00913.pdf)

- #### Curriculum Learning

  - The Efficiency Spectrum of Large Language Models: An Algorithmic Survey (Arxiv, Dec. 2023) [[Paper]](https://arxiv.org/pdf/2312.00678.pdf)

### Data Management System

- Data-Juicer: A One-Stop Data Processing System for Large Language Models (Arxiv, Sep. 2023) [[Paper]](https://arxiv.org/abs/2309.02033) [[Code]](https://github.com/alibaba/data-juicer)
- Oasis: Data Curation and Assessment System for Pretraining of Large Language Models (Arxiv, Nov. 2023) [[Paper]](https://arxiv.org/abs/2311.12537) [[Code]](https://github.com/tongzhou21/oasis)

## Supervised Fine-Tuning

### Scaling Laws

- Exploring the Impact of Instruction Data Scaling on Large Language Models: An Empirical Study on Real-World Use Cases (Arxiv, Mar. 2023) [[Paper]](https://arxiv.org/abs/2303.14742) 
- Lima: Less is more for alignment (Arxiv, May 2023) [[Paper]](https://arxiv.org/abs/2305.11206) 
- Maybe Only 0.5% Data is Needed: A Preliminary Exploration of Low Training Data Instruction Tuning (Arxiv, May 2023) [[Paper]](https://arxiv.org/abs/2305.09246) 
- Scaling Relationship on Learning Mathematical Reasoning with Large Language Models (Arxiv, Aug. 2023) [[Paper]](https://arxiv.org/abs/2308.01825) [[Code]](https://github.com/OFA-Sys/gsm8k-ScRel)
- How Abilities In Large Language Models Are Affected By Supervised Fine-Tuning Data Composition (Arxiv, Oct. 2023) [[Paper]](https://arxiv.org/pdf/2310.05492.pdf) 
- Dynamics of Instruction Tuning: Each Ability of Large Language Models Has Its Own Growth Pace (Arxiv, Oct. 2023) [[Paper]](https://arxiv.org/pdf/2310.19651.pdf) 

### Data Quality Evaluation
- INSTRUCTEVAL: Towards Holistic Evaluation of Instruction-Tuned Large Language Models (Arxiv, Jun. 2023) [[Paper]](https://arxiv.org/abs/2306.04757) [[Code]](https://github.com/declare-lab/instruct-eval)
  
### Data Quality Improvement

- #### Data Generation
  - Self-Instruct: Aligning Language Models with Self-Generated Instructions (ACL, May 2023) [[Paper]](https://arxiv.org/abs/2212.10560) 
  - Lima: Less is more for alignment (Arxiv, May 2023) [[Paper]](https://arxiv.org/abs/2305.11206) 
  - Self-Alignment with Instruction Backtranslation (Arxiv. Aug. 2023) [[Paper]](https://arxiv.org/abs/2308.06259) 

- #### Data Selection
  - Instruction mining: High-quality instruction data selection for large language models (Arxiv, Jul. 2023) [[Paper]](https://arxiv.org/pdf/2307.06290.pdf) 

- #### Data Composition
  - How Abilities in Large Language Models are Affected by Supervised Fine-tuning Data Composition (Arxiv, Oct. 2023) [[Paper]](https://arxiv.org/pdf/2310.05492.pdf) 
  
- #### Curriculum Learning
  - The Efficiency Spectrum of Large Language Models: An Algorithmic Survey (Arxiv, Dec. 2023) [[Paper]](https://arxiv.org/pdf/2312.00678.pdf)
  
- #### Prompt Engineering
  - Reframing instructional prompts to gptk’s language (ACL Findings, 2022) [[Paper]](https://arxiv.org/abs/2109.07830v3) [[Code]](https://github.com/allenai/reframing)
  - Prompt Waywardness: The Curious Case of Discretized Interpretation of Continuous Prompts (NAACL, 2022) [[Paper]](https://arxiv.org/abs/2112.08348) [[Code]](https://github.com/alrope123/prompt-waywardness)
  - Demystifying Prompts in Language Models via Perplexity Estimation (Arxiv, Dec. 2022) [[Paper]](https://arxiv.org/abs/2212.04037) 
  - Did You Read the Instructions? Rethinking the Effectiveness of Task Definitions in Instruction Learning (ACL, 2023) [[Paper]](https://arxiv.org/abs/2306.01150) [[Code]](https://github.com/fanyin3639/rethinking-instruction-effectiveness)
  - Do Models Really Learn to Follow Instructions? An Empirical Study of Instruction Tuning (ACL, 2023) [[Paper]](https://arxiv.org/abs/2305.11383) 
  - The False Promise of Imitating Proprietary LLMs (Arxiv, May 2023) [[Paper]](https://arxiv.org/abs/2305.15717) 
  - Exploring Format Consistency for Instruction Tuning (Arxiv, Jul. 2023) [[Paper]](https://arxiv.org/pdf/2307.15504.pdf) 
  - Mind the instructions: a holistic evaluation of consistency and interactions in prompt-based learning (Arxiv, Oct. 2023) [[Paper]](https://arxiv.org/pdf/2310.13486.pdf) 
  - Dynamics of Instruction Tuning: Each Ability of Large Language Models Has Its Own Growth Pace (Arxiv, Oct. 2023) [[Paper]](https://arxiv.org/pdf/2310.19651.pdf) 


### Data Management System

  - Data-Juicer: A One-Stop Data Processing System for Large Language Models (Arxiv, Sep. 2023) [[Paper]](https://arxiv.org/abs/2309.02033) [[Code]](https://github.com/alibaba/data-juicer)

  - LoBaSS: Gauging Learnability in Supervised Fine-tuning Data (Arxiv, Oct. 2023) [[Paper]](https://arxiv.org/pdf/2310.13008.pdf) 

## Survey
- Data Management For Large Language Models: A Survey (Arxiv, Dec. 2023) [[Paper]](https://arxiv.org/abs/2312.01700)
- A Survey of Large Language Models (Arxiv, Dec. 2023) [[Paper]](https://arxiv.org/abs/2312.01700)
- Efficient Large Language Models: A Survey (Arxiv, Nov. 2023) [[Paper]](https://arxiv.org/abs/2303.18223)
- The Efficiency Spectrum of Large Language Models: An Algorithmic Survey (Arxiv, Dec. 2023) [[Paper]](https://arxiv.org/pdf/2312.00678.pdf)
- A Survey on Evaluation of Large Language Models (Arxiv, Oct. 2023) [[Paper]](https://arxiv.org/abs/2307.03109)

## Useful Resources
- Data Management for LLM [[Repo]](https://github.com/ZigeW/data_management_LLM)
- Practical guides for LLM [[Repo]](https://github.com/Mooler0410/LLMsPracticalGuide#practical-guide-for-data)
- Introduction to LLM [[Repo]](https://github.com/datainsightat/introduction_llm?search=1)
- Survey of LLM [[Repo]](https://github.com/RUCAIBox/LLMSurvey)
- Data-centric AI [[Repo]](https://github.com/daochenzha/data-centric-AI#prompt-engineering)
- Scaling laws for LLM [[Repo]](https://github.com/RZFan525/Awesome-ScalingLaws)
- Instruction datasets [[Repo]](https://github.com/yaodongC/awesome-instruction-dataset#the-multi-modal-instruction-datasets)
- Instruction tuning [[Repo1]](https://github.com/zhilizju/Awesome-instruction-tuning) [[Repo2]](https://github.com/SinclairCoder/Instruction-Tuning-Papers)
