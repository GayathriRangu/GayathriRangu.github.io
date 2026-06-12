---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
page_theme: cv
background_image: bg-ai-robotics-subtle.jpg
redirect_from:
  - /resume
---

{% include base_path %}

<p><a class="btn btn--primary" href="/files/Resume.pdf">Download full resume PDF</a></p>

## Education

**Ph.D., Computer Science and Engineering**, Indian Institute of Technology Guwahati<br>
2021-2026 | CGPA: 7.83

**B.Tech**, Jawaharlal Nehru Technological University Hyderabad<br>
2017-2021 | CGPA: 8.58

**Intermediate**, Telangana State Board of Intermediate Education<br>
2017 | 96.4%

**Secondary**, Saint Mary's High School<br>
2015 | CGPA: 9.3

## Research

My Ph.D. is on **Federated Reinforcement Learning for Multi-Robot Systems: Enhancing Selective Aggregation, Experience Replay & Skill Discovery**.

I specialize in **Federated Reinforcement Learning (FRL)**, **multi-robot systems**, and **embodied AI**. My work develops scalable learning frameworks for distributed robotic systems, including selective aggregation, prioritized experience replay, decentralized swarm learning, unsupervised skill discovery, and sim-to-real transfer.

I also work on deep reinforcement learning pipelines across simulation and real robotic platforms, with broader interests in LLM-assisted robotics, autonomous AI systems, and web-based AI tools.

## Industry Experience

**Research Intern, Qualcomm**, Bangalore<br>
Feb. 2024 - Aug. 2024

* Developed AI/ML pipelines on Qualcomm QRB5-powered robotic platforms for edge-based robotic applications.
* Built an LLM-assisted ticket retrieval system for identifying semantically similar entries from internal Lessons Learnt JIRA repositories.
* Contributed AI models and deployment workflows to the Qualcomm AI Hub platform.

**Network Engineering Intern, CtrlS Datacenters Ltd.**, Hyderabad<br>
Dec. 2020 - Jun. 2021

* Worked on network monitoring, ticket resolution, and network simulation workflows using Cisco Packet Tracer.

## Teaching Assistantship

* **Head TA**, CS321 Smart Systems Lab - Spring 2026, Spring 2023
* **Head TA**, CS1102 Programming in C - Fall 2025
* **Head TA**, CS561 Artificial Intelligence - Spring 2025
* **Head TA**, CS666 Mobile Robotics Lab - Fall 2024, Fall 2023
* **TA**, CS321 System Software Lab - Fall 2022
* **Head TA**, CS101 Introduction to Computing - Spring 2022
* **TA**, CS565 Intelligent Systems and Interfaces - Fall 2021

## Selected Projects

**Aerial Guardian: Drone-based Multi-Object Person Tracking**<br>
May 2026 - Jun. 2026

* Developed an aerial person detection and multi-object tracking pipeline using the VisDrone MOT dataset.
* Fine-tuned YOLO26n for small-object aerial detection and integrated ByteTrack and BoT-SORT with Global Motion Compensation.
* Achieved 40+ FPS on a Tesla P100 GPU and improved tracking performance from 24.2% to 28.3% MOTA and 38.8% IDF1.

**Real-time Information Synthesis Agent (RIS Agent)**<br>
Jan. 2025 - Apr. 2026

* Developed an autonomous LLM-based information synthesis pipeline for real-time ingestion, summarization, and aggregation of technical content.
* Built adaptive summarization workflows using Llama 3, Qwen, and GPT-OSS with chunking, embeddings, and semantic clustering.
* Led collaboration with a 6-member research team and evaluated performance using ROUGE and semantic similarity metrics.

**KERNEL: Knowledge-Embedded Robot Navigation using LLMs**<br>
Dec. 2024 - Jul. 2025

* Developed an LLM-assisted robotic navigation framework with persistent knowledge bases for object localization, exploration, and multi-robot coordination.
* Implemented knowledge reuse and embedding-based retrieval to reduce redundant LLM queries.
* Evaluated single-robot and multi-robot scenarios, reducing LLM calls by up to 45%.

## Technical Skills

* **Programming:** Python, C++, C, Java
* **AI/ML:** PyTorch, TensorFlow, Reinforcement Learning, Federated Learning, LLM Systems
* **Robotics:** Webots, MuJoCo, Gymnasium, ROS, SLAM, Multi-Agent Systems, Robot Learning
* **Systems and Tools:** Linux, Git, Socket Programming, MQTT
* **Hardware:** Qualcomm RB5, mBot Mega, FireBird V, LEGO Mindstorms, Raspberry Pi, Arduino

## Mentoring and Collaborations

* Mentored bachelor's and master's thesis students at IIT Guwahati on reinforcement learning, drone-based applications, sensor fusion, and LLMs for robots.
* Collaborated with Ph.D. researchers on multi-agent systems and IoT-based applications.
* Led an external research collaboration with MadScientist Research on LLM-based real-time information synthesis.

## Leadership and Academic Service

* Chairperson, IEEE Student Branch, Guwahati Subsection, 2024-2025.
* General Secretary, IEEE Student Branch, Guwahati Subsection, 2023-2024.
* External Reviewer, ACM/IEEE HRI 2026.
* Organizing Team, VLSID 2025.
* Volunteer and outreach contributor for IEEE events, NERC 2022, VEGA Processor Ecosystem workshop, and Voice4Girls.

## Achievements

* Invited as Guest of Honor for IEEE QT3 16.0.
* Received USD 450 travel grant to attend GECCO 2024.
* Selected for the INDOML 2025 Graduate Forum.
* Secured 96.9 percentile in GATE CSE 2021.
* Gold Medalist and department topper at GNI Hyderabad.
* Won 1st Prize and Best Paper Presentation Award at SPOORTHI 2019.

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
