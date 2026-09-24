---
page_class: academic-page about-page
layout: about
title: About
permalink: /
subtitle: Research Assistant Professor · Computer Science · UMass Lowell
nav: false
profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
    <p>University of Massachusetts Lowell</p>
    <p><a href="mailto:zonghai_yao@uml.edu">zonghai_yao@uml.edu</a></p>
selected_papers: false
social: true
announcements:
  enabled: false
  scrollable: false
  limit: 8
---

I am a Research Assistant Professor in Computer Science at the University of Massachusetts Lowell and a member of the [UMass BioNLP Lab](https://bio-nlp.github.io/). I received my Ph.D. in Computer Science from UMass Amherst in 2026, advised by [Hong Yu](https://scholar.google.com/citations?user=TyXe64wAAAAJ&hl=en).

My research develops learning and decision-making methods for generative AI systems that people can rely on for complex work. I study LLMs, vision-language models (VLMs), and agents that gather evidence, use tools, and adapt as new information or human corrections become available. Healthcare is a central setting, with applications in clinical decision support and patient support. My recent work also studies agents that coordinate evidence gathering and analysis for scientific questions.

I pursue **capability, trustworthiness, and interpretability** together, with the goal of supporting informed human judgment and sustained inquiry. I focus on long-horizon tasks, where an early interpretation or action changes the evidence available at later steps. Alongside the quality of a system's decisions, I consider the time and expertise people need to verify and correct its work.

[Research]({{ '/research/' | relative_url }}) · [Publications]({{ '/publications/' | relative_url }}) · [Teaching]({{ '/teaching/' | relative_url }}) · [CV (PDF)]({{ '/assets/pdf/Zonghai_Yao_CV.pdf' | relative_url }})

## News

{% include news.liquid limit=true %}

[All news]({{ '/news/' | relative_url }})

## Research directions

### Learning for generative models and agents

I study how model design and training signals shape what a system learns, and how feedback can improve the decisions it makes during a task. This work connects language modeling, factual generation, reasoning, and the training of agents that use tools.

- **Modeling context and learning from examples.** My earlier work examines [long-range context for entity linking]({{ '/publications/' | relative_url }}#entity-linking) and [architectures for next-word prediction and factual summarization]({{ '/publications/' | relative_url }}#pointer-networks). [BioInstruct]({{ '/publications/' | relative_url }}#bioinstruct), [NoteChat]({{ '/publications/' | relative_url }}#notechat), and [LLMs as in-context teachers]({{ '/publications/' | relative_url }}#in-context-teachers) study how instruction data, synthetic conversations, and explanations support learning.
- **Turning corrections into useful feedback.** [Improving Summarization with Human Edits]({{ '/publications/' | relative_url }}#human-edits) and [SYNFAC-EDIT]({{ '/publications/' | relative_url }}#synfac-edit) connect edits to errors in generated text. [MCQG-SRefine]({{ '/publications/' | relative_url }}#mcqg-srefine) studies iterative critique, correction, and comparison. Across these settings, I examine feedback that identifies what needs to change while preserving supported content.
- **Learning across longer tasks.** My work on [tree-structured credit assignment]({{ '/publications/' | relative_url }}#tree-credit) examines how learning signals are assigned within reasoning. Ongoing projects investigate [rollout budget allocation]({{ '/publications/' | relative_url }}#measure-first) and [improvement of tool-using agent teams]({{ '/publications/' | relative_url }}#residualforge), extending these questions to training and coordination across a workflow.

### Multimodal evidence and clinical reasoning

A diagnosis can depend on findings distributed across images and patient context. I study how models represent that evidence, how interpretation errors affect later reasoning, and what supervision helps preserve relationships across a case.

- **Establishing what an answer depends on.** Our [GPT-4V evaluation]({{ '/publications/' | relative_url }}#gpt4v-audit) examines errors behind medical question-answering scores. [Medical Thinking with Multiple Images]({{ '/publications/' | relative_url }}#medthinkvqa) separates image interpretation from later diagnostic reasoning, and [MedQA-MM]({{ '/publications/' | relative_url }}#medqa-mm) tests shortcut routes that can produce correct answers without the intended visual evidence.
- **Learning with the complete case.** [MultiViewDx]({{ '/publications/' | relative_url }}#multiviewdx) studies case-level supervision that links related views and clinical context to diagnostic evidence. This connects evaluation of evidence use with training that preserves the information a diagnosis requires.
- **Choosing further help.** Ongoing work on [specialist consultation for medical visual reasoning]({{ '/publications/' | relative_url }}#specialist-consultation) studies how an agent can seek additional expertise during visual reasoning. The broader aim is to make intermediate findings useful for both subsequent decisions and human correction.

### Information gathering, retrieval, and uncertainty

Missing patient observations and missing medical knowledge require different actions. I study how agents recognize those gaps, acquire useful evidence, and decide whether the available information supports a conclusion.

- **Asking and abstaining.** [MedQA-CS]({{ '/publications/' | relative_url }}#medqa-cs) evaluates clinical information gathering and other clinical skills through case-specific tasks. [MedAbstain]({{ '/publications/' | relative_url }}#medabstain) tests what happens when decisive evidence is removed. Together, these settings examine whether an agent's next action responds to what is missing.
- **Searching and using experience.** [JMLR]({{ '/publications/' | relative_url }}#jmlr) studies joint medical LLM and retrieval training; [RARE]({{ '/publications/' | relative_url }}#rare) and [PRIME]({{ '/publications/' | relative_url }}#prime) connect retrieval with reasoning, planning, and memory. [TARSE]({{ '/publications/' | relative_url }}#tarse) extends this line to adaptation through retrieved skills and experience.
- **Checking intermediate work.** [From Scores to Steps]({{ '/publications/' | relative_url }}#scores-to-steps) evaluates the steps behind medical calculations. This work supports a broader goal: locating which observation, retrieved source, or operation needs correction before an error affects later decisions.

### Patient understanding and support over time

Patient support requires a system to find out what a person understands and use that feedback to choose the next explanation. My work connects accessible language, interactive education, visual evidence, and continuity across conversations.

- **Making medical information accessible.** [MedJEx]({{ '/publications/' | relative_url }}#medjex), [README]({{ '/publications/' | relative_url }}#readme), and [medical jargon prioritization]({{ '/publications/' | relative_url }}#jargon-prioritization) study medical language in context. [MedReadCtrl]({{ '/publications/' | relative_url }}#medreadctrl) studies how generation can adapt to different readability needs.
- **Checking and repairing understanding.** [PaniniQA]({{ '/publications/' | relative_url }}#paniniqa), [Chatbot To Help Patients Understand Their Health]({{ '/publications/' | relative_url }}#noteaid-chatbot), and [DischargeSim]({{ '/publications/' | relative_url }}#dischargesim) examine questions, explanations, and feedback during patient education. They connect the information provided with checks of understanding, including evaluations with simulated patients.
- **Connecting explanations to visual findings.** [MedImageEdu]({{ '/publications/' | relative_url }}#medimageedu) and [MediSketch]({{ '/publications/' | relative_url }}#medisketch) study how an image, a visual mark, and a verbal explanation refer to the same medical finding, and how further computation can help repair an identified error.
- **Adapting across conversations.** [ChatCLIDS]({{ '/publications/' | relative_url }}#chatclids) and [ChatThero]({{ '/publications/' | relative_url }}#chatthero) study support as concerns, goals, and circumstances change. Our perspective on [patient journey evaluation]({{ '/publications/' | relative_url }}#patient-journey) develops the broader question of how to evaluate health assistance over a person's experience with a system.

### Reviewable scientific research and population evidence

Scientific questions often require evidence from multiple sources and analyses whose assumptions can change. I study how agents can carry out more of this work while keeping scientists able to inspect, revise, and direct it.

- **Working with clinical records and populations.** My collaborations include [eviction identification]({{ '/publications/' | relative_url }}#eviction-identification), [synthetic health records for eviction detection]({{ '/publications/' | relative_url }}#synthehr-eviction), and [eviction surveillance]({{ '/publications/' | relative_url }}#eviction-surveillance), as well as studies of [social needs and cognitive outcomes]({{ '/publications/' | relative_url }}#ptsd-cognition) and [food-pantry access]({{ '/publications/' | relative_url }}#food-pantries). These studies examine how clinical records and other data can support questions about social conditions, access to care, and health outcomes.
- **Coordinating evidence gathering and analysis.** Current manuscripts study [multi-agent deep research for healthcare prediction]({{ '/publications/' | relative_url }}#healthcare-predictions), [temporal grounding as evidence changes]({{ '/publications/' | relative_url }}#temporal-grounding), and [evidence use in diagnostic decision support]({{ '/publications/' | relative_url }}#evidence-use). Ongoing work is adding executable analyses of reference patient cohorts and examining whether sources match a question's population, outcome, and time window.
- **Supporting review and intervention.** Our [AI Hospital survey]({{ '/publications/' | relative_url }}#aihospital-survey) examines multi-agent clinical workflows. Our perspective on [reviewable medical evidence synthesis]({{ '/publications/' | relative_url }}#reviewable-evidence) addresses how evidence can be made available for review. I am extending these questions to feedback for planning and coordination, including when an agent should search again, revise an analysis, or request human judgment.

## Teaching and mentoring

I co-teach **Methods in Data Science (COMP.4770/5770)** at UMass Lowell in Fall 2026. The course connects problem definition, data curation, and evaluation with current AI methods. [Teaching details]({{ '/teaching/' | relative_url }})

During my Ph.D., I worked with more than twenty undergraduate and master's students on research projects, helping them define questions, implement baselines, and interpret results. Students interested in related research are welcome to email me with a brief introduction and their interests.

## Service

I serve as an area chair for ACL Rolling Review (ARR) and review for AI, NLP, and health informatics venues. I also helped organize the UMass BioNLP Workshop in 2023, 2024, and 2025. Further details are available in my [CV]({{ '/cv/' | relative_url }}).
