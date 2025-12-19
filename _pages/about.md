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
  limit: 5 # leave blank to include all the news in the `_news` folder

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


<!-- =========================
     Research focus (3 pillars)
========================= -->

My work focuses on three connected problems:

1. A central focus is **agents that think in high-stakes settings**. I build LLM agents for **evidence-based clinical reasoning**, where models plan, retrieve guidelines or knowledge graphs, and justify decisions with verifiable support rather than fluent guesses. I am also deeply interested in **multimodal medical agents in “multiple images” settings**—where “multiple” can mean **time** (longitudinal imaging across a patient’s care journey, or video such as surgical procedures), **space** (3D volumes), and **modality** (e.g., X-ray, CT, MRI, polysomnography). My goal is to develop agents that can reason over these heterogeneous streams in a unified, step-by-step way.


2. I also study **agents that communicate with patients and clinicians over long horizons**. I build multi-agent simulations for discharge education, chronic disease management, and recovery support, with a focus on **multi-session interactions** where goals unfold over days, weeks or months. I evaluate whether agents can maintain state, adapt explanations to health literacy and emotion, and remain safe and helpful under realistic conversational drift and social pressure.

3. I develop **methods to optimize, train, and stress-test these agents**. On the system side, I design **test-time orchestration** loops (planning, retrieval, tool use, self-check) that make reasoning more structured and auditable. On the learning side, I use **data-centric pipelines** (expert annotation, human edits, synthetic data, hard-case mining) and **learning from feedback** (preference signals, outcome-verifiable objectives, and RL-style training in simulation) to improve faithfulness, robustness, and long-horizon behavior. Across projects, I pair these with **fine-grained evaluation** that diagnoses failures at the step level and under distribution shift, so we can iterate on both models and agent policies.


<!-- ===============================
     Selected areas & recent papers
=============================== -->

<div style="padding:12px 14px; border:1px solid rgba(59,130,246,.22); border-radius:14px; background:rgba(59,130,246,.06); margin: 12px 0 12px 0;">
  <div style="font-weight:800; margin-bottom:4px;">Selected areas & recent publications</div>
  <div style="opacity:.78;">Concretely, some areas I have been publishing on recently include:</div>
</div>

<!-- Area 1 -->
<div style="padding:10px 12px; border:1px solid rgba(148,163,184,.22); border-radius:14px; background:rgba(148,163,184,.04); margin: 10px 0;">
  <details open>
    <summary style="cursor:pointer;">
      <strong>1) Multi-agent interaction and long-horizon dialogue</strong><br/>
      <span style="display:block; margin-top:.25rem; font-size:.92em; opacity:.78;">
        I use multi-agent simulation to study long-horizon behavior, social pressure, and strategy.
      </span>
    </summary>
    <div style="margin-top:10px;">
      <ul style="margin:0; padding-left:1.1rem;">
        <li>ChatCLIDS: Simulating Persuasive AI Dialogues to Promote Closed-Loop Insulin Adoption in Type 1 Diabetes Care (<a href="https://arxiv.org/abs/2509.00891" target="_blank" rel="noopener">AAAI 2026, AI for Social Impact</a>)</li>
        <li>ChatThero: A Language Agent for Recovery Support (<a href="https://arxiv.org/abs/2508.20996" target="_blank" rel="noopener">Preprint, 2025</a>)</li>
        <li>A Survey on LLM-based Multi-Agent AI Hospital (<a href="https://osf.io/preprints/osf/bv5sg_v1" target="_blank" rel="noopener">Preprint, 2025</a>)</li>
      </ul>
    </div>
  </details>
</div>

<!-- Area 2 -->
<div style="padding:10px 12px; border:1px solid rgba(148,163,184,.22); border-radius:14px; background:rgba(148,163,184,.04); margin: 10px 0;">
  <details open>
    <summary style="cursor:pointer;">
      <strong>2) Agentic reasoning with retrieval, tools, and structured inference (including multimodal “multiple” settings)</strong><br/>
      <span style="display:block; margin-top:.25rem; font-size:.92em; opacity:.78;">
        I build structured reasoning loops that combine planning, retrieval, memory, and “multiple” multimodal evidence.
      </span>
    </summary>
    <div style="margin-top:10px;">
      <ul style="margin:0; padding-left:1.1rem;">
        <li>Medical Thinking with Multiple Images (<a href="https://openreview.net/forum?id=h2p5eOFpcF&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICLR.cc%2F2026%2FConference%2FAuthors%23your-submissions)" target="_blank" rel="noopener">Under review, 2026</a>)</li>
        <li>MCQG-SRefine: Multiple Choice Question Generation and Evaluation with Iterative Self-Critique, Correction, and Comparison Feedback (<a href="https://aclanthology.org/2025.naacl-long.538/" target="_blank" rel="noopener">NAACL 2025, Oral</a>)</li>
        <li>PRIME: Planning and Retrieval-Integrated Memory for Enhanced Reasoning (<a href="https://arxiv.org/abs/2509.22315" target="_blank" rel="noopener">AAAI 2026</a>)</li>
        <li>RARE: Retrieval-Augmented Reasoning Enhancement for Large Language Models (<a href="https://aclanthology.org/2025.acl-long.896/" target="_blank" rel="noopener">ACL 2025</a>)</li>
        <li>JMLR: Joint Medical LLM and Retrieval Training for Enhancing Reasoning and Professional QA (<a href="https://arxiv.org/abs/2402.17887" target="_blank" rel="noopener">Preprint, 2024</a>)</li>
      </ul>
    </div>
  </details>
</div>

<!-- Area 3 -->
<div style="padding:10px 12px; border:1px solid rgba(148,163,184,.22); border-radius:14px; background:rgba(148,163,184,.04); margin: 10px 0;">
  <details>
    <summary style="cursor:pointer;">
      <strong>3) Patient-facing NLP and personalization for understanding</strong><br/>
      <span style="display:block; margin-top:.25rem; font-size:.92em; opacity:.78;">
        I build patient-facing systems, and I test if they improve understanding, not only text quality.
      </span>
    </summary>
    <div style="margin-top:10px;">
      <ul style="margin:0; padding-left:1.1rem;">
        <li>DischargeSim: A Simulation Benchmark for Educational Doctor–Patient Communication at Discharge (<a href="https://aclanthology.org/2025.emnlp-main.546/" target="_blank" rel="noopener">EMNLP 2025</a>)</li>
        <li>PaniniQA: Enhancing Patient Education Through Interactive Question Answering (<a href="https://aclanthology.org/2023.tacl-1.86/" target="_blank" rel="noopener">TACL 2023</a>)</li>
        <li>Chatbot To Help Patients Understand Their Health (<a href="https://aclanthology.org/2025.findings-emnlp.351/" target="_blank" rel="noopener">EMNLP Findings 2025</a>)</li>
        <li>README: Bridging Medical Jargon and Lay Understanding for Patient Education through Data-Centric NLP (<a href="https://aclanthology.org/2024.findings-emnlp.737/" target="_blank" rel="noopener">EMNLP Findings 2024</a>)</li>
        <li>MedReadCtrl: Personalizing Medical Text Generation with Readability-Controlled Instruction Learning (<a href="https://arxiv.org/abs/2507.07419" target="_blank" rel="noopener">Preprint, 2025</a>)</li>
      </ul>
    </div>
  </details>
</div>

<!-- Area 4 -->
<div style="padding:10px 12px; border:1px solid rgba(148,163,184,.22); border-radius:14px; background:rgba(148,163,184,.04); margin: 10px 0;">
  <details>
    <summary style="cursor:pointer;">
      <strong>4) Optimization, feedback, and fine-grained evaluation for trustworthy LLMs</strong><br/>
      <span style="display:block; margin-top:.25rem; font-size:.92em; opacity:.78;">
        I design training and evaluation that show where models fail, so fixes are specific and measurable.
      </span>
    </summary>
    <div style="margin-top:10px;">
      <ul style="margin:0; padding-left:1.1rem;">
        <li>Improving Summarization with Human Edits (<a href="https://aclanthology.org/2023.emnlp-main.158/" target="_blank" rel="noopener">EMNLP 2023</a>)</li>
        <li>SYNFAC-EDIT: Synthetic Imitation Edit Feedback for Factual Alignment in Clinical Summarization (<a href="https://aclanthology.org/2024.emnlp-main.1120/" target="_blank" rel="noopener">EMNLP 2024</a>)</li>
        <li>Unveiling GPT-4V’s Hidden Challenges Behind High Accuracy on USMLE Questions: Observational Study (<a href="https://www.jmir.org/2025/1/e65146/" target="_blank" rel="noopener">JMIR 2025</a>)</li>
        <li>From Scores to Steps: Diagnosing and Improving LLM Performance in Evidence-Based Medical Calculations (<a href="https://aclanthology.org/2025.emnlp-main.548/" target="_blank" rel="noopener">EMNLP 2025, Oral</a>)</li>
        <li>Exploiting Tree Structure for Credit Assignment in RL Training of LLMs (<a href="https://arxiv.org/abs/2509.18314" target="_blank" rel="noopener">Preprint, 2025</a>)</li>
      </ul>
    </div>
  </details>
</div>

<!-- Area 5 -->
<div style="padding:10px 12px; border:1px solid rgba(148,163,184,.22); border-radius:14px; background:rgba(148,163,184,.04); margin: 10px 0 6px 0;">
  <details>
    <summary style="cursor:pointer;">
      <strong>5) Data, benchmarks, and deployment-oriented clinical NLP</strong><br/>
      <span style="display:block; margin-top:.25rem; font-size:.92em; opacity:.78;">
        I build datasets and pipelines that support scaling, testing, and real-world use in clinical NLP.
      </span>
    </summary>
    <div style="margin-top:10px;">
      <ul style="margin:0; padding-left:1.1rem;">
        <li>MedQA-CS: Benchmarking Large Language Models Clinical Skills Using an AI-SCE Framework (<a href="https://arxiv.org/abs/2410.01553" target="_blank" rel="noopener">Preprint, 2024</a>)</li>
        <li>NoteChat: A Dataset of Synthetic Doctor-Patient Conversations Conditioned on Clinical Notes (<a href="https://aclanthology.org/2024.findings-acl.901/" target="_blank" rel="noopener">ACL Findings 2024</a>)</li>
        <li>BioInstruct: Instruction Tuning of Large Language Models for Biomedical Natural Language Processing (<a href="https://academic.oup.com/jamia/article/31/9/1821/7687618" target="_blank" rel="noopener">JAMIA 2024</a>)</li>
        <li>Automated Identification of Eviction Status from Electronic Health Record Notes (<a href="https://academic.oup.com/jamia/article/30/8/1429/7172838" target="_blank" rel="noopener">JAMIA 2023</a>)</li>
        <li>SynthEHR-Eviction: Enhancing Eviction SDoH Detection with LLM-Augmented Synthetic EHR Data (<a href="https://arxiv.org/abs/2507.07421" target="_blank" rel="noopener">Preprint, 2025</a>)</li>
        <li>Development of a Surveillance System to Identify Incidence of Evictions Among Patients in Veterans Affairs Medical Centers Across the United States (<a href="https://link.springer.com/article/10.1007/s10900-025-01491-5" target="_blank" rel="noopener">Journal of Community Health 2025</a>)</li>
      </ul>
    </div>
  </details>
</div>


<!-- ===============================
     To students
=============================== -->


<div style="padding:12px 14px; border-left:4px solid rgba(34,197,94,.45); background: rgba(34,197,94,.08); border-radius:10px; margin: 14px 0;">
  <div style="font-weight:700; margin-bottom:6px;">
    To junior Ph.D./master/undergraduate students
  </div>
  <div>
    If you would like to chat about your career plan or research ideas related to my research interests, please email me to schedule a meeting. I will dedicate 30 minutes to each meeting weekly. I encourage students from underrepresented groups to reach out and will prioritize these meetings.
  </div>
</div>





<!-- ===============================
     Academic Service
=============================== -->


### Service

<details markdown="1">
  <summary><strong>AI Conference Area Chair (2025–present)</strong></summary>
  <div markdown="1">
  NAACL ARR (2025), ACL ARR (2025), EMNLP ARR (2025), AACL ARR (2025), EACL ARR (2025)
  </div>
</details>

<details markdown="1">
  <summary><strong>AI Conference Reviewer (2023–present)</strong></summary>
  <div markdown="1">
  ICLR, NeurIPS, ICML, AAAI, ACL / EMNLP / NAACL / COLING / EACL (and related workshops)
  </div>
</details>

<details markdown="1">
  <summary><strong>Medical Journal Reviewer (2022–present)</strong></summary>
  <div markdown="1">

  * *npj Digital Medicine*, *npj Health Systems*, *Scientific Reports*
  * *Journal of Medical Internet Research (JMIR)*, *Journal of the American Medical Informatics Association (JAMIA)*
  * *Bioinformatics*, *Expert Systems with Applications*
  * *BMC Medical Informatics and Decision Making*, *BMC Medical Research Methodology*
  * *European Heart Journal – Digital Health*

  </div>
</details>



