
# AI Therapy Reddit

This repository contains the data, code, and annotation framework for our ACL 2026 paper:

**“Like a Therapist, But Not: Reddit Narratives of AI in Mental Health Contexts”**

## Overview
Large language models are increasingly used for emotional support outside clinical settings. This project studies how people evaluate, trust, and engage with AI tools for mental health using real world Reddit discussions.

We analyze over 5,000 posts from 47 mental health communities, focusing on:
- User perceptions of AI for emotional support
- Adoption factors such as trust, usefulness, and outcomes
- Therapeutic alignment including task, goal, and emotional bond
- Risks such as dependence, misinformation, and symptom escalation

## Dataset
The dataset used in this study is publicly available on Zenodo:

👉 https://zenodo.org/records/18751157

Due to the sensitive nature of mental health data, we do not release raw text. Instead, the dataset includes:
- Post identifiers
- Annotation labels
- Derived features

Please follow ethical guidelines when using this data.


## Methods
We use a theory grounded framework combining:
- Technology Acceptance Model (TAM)
- Therapeutic alliance theory

A hybrid pipeline of large language models and human validation is used to annotate and analyze discourse at scale.


## Citation
If you use this work, please cite:

@article{aghakhani2026like,
  title={Like a Therapist, But Not: Reddit Narratives of AI in Mental Health Contexts},
  author={Aghakhani, Elham and Rezapour, Rezvaneh},
  journal={arXiv preprint arXiv:2601.20747},
  year={2026}
}


## Ethics
This work uses publicly available Reddit data. We avoid sharing identifiable content and focus on aggregate analysis. This repository is for research purposes only and does not provide medical advice.


