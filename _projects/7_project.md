---
layout: page
title: Evaluating Medical Agent Pipelines for Diabetes Prediction
description: AI Safety in Healthcare
img: assets/img/diabetes-agent.png
importance: 0
category: AI
giscus_comments: true
---

CS 6604 Course Project(<a href="https://github.com/IreneTanggh/MedAgentPPL">Github</a>)

<h3> Background and Challenge: </h3>
The "black box" nature of many LLM agents obscures their decision-making process, raising concerns for critical healthcare applications where transparency is essential. Additionally, existing agent systems struggle to effectively interpret individual patient data within the broader context of population-level trends, and there is limited research on how different types of agents (traditional ML and LLM-based) can collaborate effectively for comprehensive medical tasks.

<h3> Our Method: </h3>
- This project addresses these challenges by designing and implementing three distinct LLM agent architectures for diabetes classification and personalized advice generation. 
- This research aims to identify the most effective pipeline for integrating LLMs into medical advisory systems while advancing the field of autonomous healthcare agents.
- Three pipelines:

<img src="{{ '/assets/img/MedAgentPPL/A1.png' | relative_url }}" alt="Pipeline A1" width='600px' />
<img src="{{ '/assets/img/MedAgentPPL/A2.png' | relative_url }}" alt="Pipeline A2" width='600px'/>
<img src="{{ '/assets/img/MedAgentPPL/A3.png' | relative_url }}" alt="Pipeline A3" width='600px'/>

<h3> Conclusion: </h3>
- A3's ML method demonstrated consistent predictions across multiple runs.
- Benefits of Combining multi-agent framework with traditional ML methods: transparent reasoning, structured and detailed analysis, evidence-based personalization.