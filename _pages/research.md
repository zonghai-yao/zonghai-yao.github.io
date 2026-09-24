---
page_class: academic-page research-page
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
description: Learning and decision-making for trustworthy generative AI.
---

I develop learning and decision-making methods for generative AI, with a focus on multimodal models and agents that gather evidence and use tools. My work has progressed from Transformer language modeling to learning with human edits and synthetic feedback, multimodal reasoning, and decisions over longer tasks.

I pursue capability, trustworthiness, and interpretability together. This means improving what a system can do, testing whether its decisions follow the available evidence, and making the basis of those decisions accessible for human review and correction. Healthcare provides concrete problems in which an early observation or action can affect many later steps.

## Clinical decision support

I study how agents interpret evidence across medical images, distinguish missing patient information from gaps in medical knowledge, and choose whether to ask a question, retrieve evidence, or withhold a recommendation. My evaluations examine where errors begin and whether the final answer depends on the intended evidence.

Related work includes [Medical Thinking with Multiple Images]({{ '/publications/' | relative_url }}#medthinkvqa), [MedQA-MM]({{ '/publications/' | relative_url }}#medqa-mm), [MultiViewDx]({{ '/publications/' | relative_url }}#multiviewdx), [MedQA-CS]({{ '/publications/' | relative_url }}#medqa-cs), and [MedAbstain]({{ '/publications/' | relative_url }}#medabstain). My research on clinical documentation also uses human edits and synthetic corrections to improve factual generation, including [Improving Summarization with Human Edits]({{ '/publications/' | relative_url }}#human-edits), [SYNFAC-EDIT]({{ '/publications/' | relative_url }}#synfac-edit), and [NoteChat]({{ '/publications/' | relative_url }}#notechat).

## Patient support

I develop systems that explain medical information, check understanding through focused questions, and revise their guidance using the person's responses. This includes visual explanations linked to clinical findings and support that adapts across conversations.

[PaniniQA]({{ '/publications/' | relative_url }}#paniniqa), [README]({{ '/publications/' | relative_url }}#readme), and [DischargeSim]({{ '/publications/' | relative_url }}#dischargesim) study explanations and evidence of understanding. Work on [MedImageEdu]({{ '/publications/' | relative_url }}#medimageedu) and [MediSketch]({{ '/publications/' | relative_url }}#medisketch) examines the relationship among a medical finding, an image, and its explanation. [ChatCLIDS]({{ '/publications/' | relative_url }}#chatclids) and [ChatThero]({{ '/publications/' | relative_url }}#chatthero) study how support should respond to a person's concerns and feedback across conversations.

## Scientific research

My recent deep research work studies how agents coordinate evidence gathering and analysis when conclusions are difficult to verify directly. Healthcare prediction provides an initial setting. I study whether evidence matches the population, outcome, and time window of a question, and whether conflicting or outdated evidence changes an agent's next action.

Ongoing work is adding executable analyses of reference patient cohorts to medical evidence search. I am investigating how checks on source support and tool operations can provide feedback for planning and coordination, including when to search again, revise an analysis, or stop. Future extensions will examine images and longitudinal records, with attention to the time and expertise needed to review and correct the work.

## Dissertation

**Long-Horizon Health AI Agents That Think and Act**  
Ph.D. dissertation, University of Massachusetts Amherst, 2026. Advisor: Hong Yu.

My dissertation studies how early interpretations, information-gathering choices, and patient responses shape later decisions in clinical decision support and patient education. It develops evaluations that follow evidence and corrections across intermediate steps and repeated interactions.

[Browse all publications]({{ '/publications/' | relative_url }})
