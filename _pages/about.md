---
layout: about
title: about
permalink: /


profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  address: >

news: true
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: # leave blank to include all the news in the `_news` folder

---

<div style="padding:10px 14px; border-left:4px solid #f97316; background: rgba(249,115,22,0.12); border-radius:10px; margin: 10px 0;">
  <span style="color:#f97316; font-weight:700;">
    I will be on the job market starting in Fall 2025.
  </span>
  <span>
    If you believe I might be a good fit for your institution or organization, I’d love to connect—please feel free to reach out at
    <span style="font-weight:700;">zonghaiyao [at] umass [dot] edu</span>.
  </span>
</div>


I am a Ph.D. candidate in Computer Science at the University of Massachusetts Amherst (expected May 2026), working with [Prof. Hong Yu](https://scholar.google.com/citations?user=TyXe64wAAAAJ&hl=en) in the [UMass BioNLP Lab](https://bio-nlp.github.io/). I work at the intersection of AI, NLP, and health. My long-term goal is an **“AI Hospital”**: a set of reliable AI agents that can **think** and also **communicate** across real clinical workflows. In this vision, agents are not standalone chatbots; they are tool-using teammates that can reason over evolving patient context, coordinate across roles, and stay verifiably grounded in clinical evidence. I am especially excited about promising directions like long-horizon agent learning in realistic simulations, multimodal clinical world models, and evaluation that ties model behavior to safety- and outcome-relevant signals. Previously, I received my B.S. in Computer Science from Nankai University.


My work focuses on three connected problems:

1. A central focus is **agents that think in high-stakes settings**. I build LLM agents for **evidence-based clinical reasoning**, where models plan, retrieve guidelines or knowledge graphs, and justify decisions with verifiable support rather than fluent guesses. I am also deeply interested in **multimodal medical agents in “multiple images” settings**—where “multiple” can mean **time** (longitudinal imaging across a patient’s care journey, or video such as surgical procedures), **space** (3D volumes), and **modality** (e.g., X-ray, CT, MRI, polysomnography). My goal is to develop agents that can reason over these heterogeneous streams in a unified, step-by-step way.


2. I also study **agents that communicate with patients and clinicians over long horizons**. I build multi-agent simulations for discharge education, chronic disease management, and recovery support, with a focus on **multi-session interactions** where goals unfold over days, weeks or months. I evaluate whether agents can maintain state, adapt explanations to health literacy and emotion, and remain safe and helpful under realistic conversational drift and social pressure.

3. I develop **methods to optimize, train, and stress-test these agents**. On the system side, I design **test-time orchestration** loops (planning, retrieval, tool use, self-check) that make reasoning more structured and auditable. On the learning side, I use **data-centric pipelines** (expert annotation, human edits, synthetic data, hard-case mining) and **learning from feedback** (preference signals, outcome-verifiable objectives, and RL-style training in simulation) to improve faithfulness, robustness, and long-horizon behavior. Across projects, I pair these with **fine-grained evaluation** that diagnoses failures at the step level and under distribution shift, so we can iterate on both models and agent policies.



Concretely, some areas I have been publishing on recently include:

<details open markdown="1">
  <summary>
    <strong>1) Multi-agent interaction and long-horizon dialogue</strong><br/>
    <span style="display:block; margin-top:.2rem; font-size:.92em; opacity:.78;">
      I use multi-agent simulation to study long-horizon behavior, social pressure, and strategy.
    </span>
  </summary>

  <div markdown="1">
  - ChatCLIDS: Simulating Persuasive AI Dialogues to Promote Closed-Loop Insulin Adoption in Type 1 Diabetes Care ([AAAI 2026, AI for Social Impact](https://arxiv.org/abs/2509.00891))
  - ChatThero: A Language Agent for Recovery Support ([Preprint, 2025](https://arxiv.org/abs/2508.20996))
  - A Survey on LLM-based Multi-Agent AI Hospital ([Preprint, 2025](https://osf.io/preprints/osf/bv5sg_v1))
  </div>
</details>

<details open markdown="1">
  <summary>
    <strong>2) Agentic reasoning with retrieval, tools, and structured inference (including multimodal “multiple” settings)</strong><br/>
    <span style="display:block; margin-top:.2rem; font-size:.92em; opacity:.78;">
      I build structured reasoning loops that combine planning, retrieval, memory, and “multiple” multimodal evidence.
    </span>
  </summary>

  <div markdown="1">
  - Medical Thinking with Multiple Images ([Under review, 2026](https://openreview.net/forum?id=h2p5eOFpcF&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICLR.cc%2F2026%2FConference%2FAuthors%23your-submissions)))
  - MCQG-SRefine: Multiple Choice Question Generation and Evaluation with Iterative Self-Critique, Correction, and Comparison Feedback ([NAACL 2025, Oral](https://aclanthology.org/2025.naacl-long.538/))
  - PRIME: Planning and Retrieval-Integrated Memory for Enhanced Reasoning ([AAAI 2026](https://arxiv.org/abs/2509.22315))
  - RARE: Retrieval-Augmented Reasoning Enhancement for Large Language Models ([ACL 2025](https://aclanthology.org/2025.acl-long.896/))
  - JMLR: Joint Medical LLM and Retrieval Training for Enhancing Reasoning and Professional QA ([Preprint, 2024](https://arxiv.org/abs/2402.17887))
  </div>
</details>

<details markdown="1">
  <summary>
    <strong>3) Patient-facing NLP and personalization for understanding</strong><br/>
    <span style="display:block; margin-top:.2rem; font-size:.92em; opacity:.78;">
      I build patient-facing systems, and I test if they improve understanding, not only text quality.
    </span>
  </summary>

  <div markdown="1">
  - DischargeSim: A Simulation Benchmark for Educational Doctor–Patient Communication at Discharge ([EMNLP 2025](https://arxiv.org/abs/2509.07188))
  - PaniniQA: Enhancing Patient Education Through Interactive Question Answering ([TACL 2023](https://aclanthology.org/2023.tacl-1.86/))
  - Chatbot To Help Patients Understand Their Health ([EMNLP Findings 2025](https://arxiv.org/abs/2509.05818))
  - README: Bridging Medical Jargon and Lay Understanding for Patient Education through Data-Centric NLP ([EMNLP Findings 2024](https://aclanthology.org/2024.findings-emnlp.737/))
  - MedReadCtrl: Personalizing Medical Text Generation with Readability-Controlled Instruction Learning ([Preprint, 2025](https://arxiv.org/abs/2507.07419))
  </div>
</details>

<details markdown="1">
  <summary>
    <strong>4) Optimization, feedback, and fine-grained evaluation for trustworthy LLMs</strong><br/>
    <span style="display:block; margin-top:.2rem; font-size:.92em; opacity:.78;">
      I design training and evaluation that show where models fail, so fixes are specific and measurable.
    </span>
  </summary>

  <div markdown="1">
  - Improving Summarization with Human Edits ([EMNLP 2023](https://aclanthology.org/2023.emnlp-main.158/))
  - SYNFAC-EDIT: Synthetic Imitation Edit Feedback for Factual Alignment in Clinical Summarization ([EMNLP 2024](https://aclanthology.org/2024.emnlp-main.1120/))
  - Unveiling GPT-4V’s Hidden Challenges Behind High Accuracy on USMLE Questions: Observational Study ([JMIR 2025](https://www.jmir.org/2025/1/e65146/))
  - From Scores to Steps: Diagnosing and Improving LLM Performance in Evidence-Based Medical Calculations ([EMNLP 2025, Oral](https://arxiv.org/abs/2509.16584))
  - Exploiting Tree Structure for Credit Assignment in RL Training of LLMs ([Preprint, 2025](https://arxiv.org/abs/2509.18314))
  </div>
</details>

<details markdown="1">
  <summary>
    <strong>5) Data, benchmarks, and deployment-oriented clinical NLP</strong><br/>
    <span style="display:block; margin-top:.2rem; font-size:.92em; opacity:.78;">
      I build datasets and pipelines that support scaling, testing, and real-world use in clinical NLP.
    </span>
  </summary>

  <div markdown="1">
  - MedQA-CS: Benchmarking Large Language Models Clinical Skills Using an AI-SCE Framework ([Preprint, 2024](https://arxiv.org/abs/2410.01553))
  - NoteChat: A Dataset of Synthetic Doctor-Patient Conversations Conditioned on Clinical Notes ([ACL Findings 2024](https://aclanthology.org/2024.findings-acl.901/))
  - BioInstruct: Instruction Tuning of Large Language Models for Biomedical Natural Language Processing ([JAMIA 2024](https://academic.oup.com/jamia/article/31/9/1821/7687618))
  - Automated Identification of Eviction Status from Electronic Health Record Notes ([JAMIA 2023](https://academic.oup.com/jamia/article/30/8/1429/7172838))
  - SynthEHR-Eviction: Enhancing Eviction SDoH Detection with LLM-Augmented Synthetic EHR Data ([Preprint, 2025](https://arxiv.org/abs/2507.07421))
  - Development of a Surveillance System to Identify Incidence of Evictions Among Patients in Veterans Affairs Medical Centers Across the United States ([Journal of Community Health 2025](https://link.springer.com/article/10.1007/s10900-025-01491-5))
  </div>
</details>


<div style="padding:12px 14px; border-left:4px solid rgba(100,116,139,0.7); background: rgba(100,116,139,0.10); border-radius:10px; margin: 14px 0;">
  <div style="font-weight:700; margin-bottom:6px;">
    To junior Ph.D./master/undergraduate students
  </div>
  <div>
    If you would like to chat about your career plan or research ideas related to my research interests, please email me to schedule a meeting. I will dedicate 30 minutes to each meeting weekly. I encourage students from underrepresented groups to reach out and will prioritize these meetings.
  </div>
</div>



### Service

* **Area Chair (ACL Rolling Review):** NAACL ARR (2025), ACL ARR (2025), EMNLP ARR (2025), AACL ARR (2025), EACL ARR (2025)
* **Conference Reviewer (2023–present):** ICLR, NeurIPS, ICML, AAAI, ACL / EMNLP / NAACL / COLING / EACL (and related workshops)
* **Journal Reviewer (2022–present):**

  * *npj Digital Medicine*, *npj Health Systems*, *Scientific Reports*
  * *Journal of Medical Internet Research (JMIR)*, *Journal of the American Medical Informatics Association (JAMIA)*
  * *Bioinformatics*, *Expert Systems with Applications*
  * *BMC Medical Informatics and Decision Making*, *BMC Medical Research Methodology*
  * *European Heart Journal – Digital Health*

