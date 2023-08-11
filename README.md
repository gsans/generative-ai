# Generative AI for Angular Developers

<img src="https://i.imgur.com/ak41dgy.png" alt="Angular + PalM2 + VertexAI" width="50%">

This is a curated list of resources on leveraging generative AI tools like **Google Vertex AI** and **PaLM APIs** in Angular applications. 

## Contents

- [Introduction](#introduction)
- [Google Vertex AI](#google-vertex-ai)
- [Courses](#courses)
- [Talks & Articles](#talks--articles)
- [How-Tos](#how-tos)

## Introduction

Generative AI is a type of artificial intelligence that can create new data, such as text, images, or music. It is a powerful tool that can be used for a variety of applications.

Google Cloud Platform offers services like **Vertex AI** and access **PaLM 2 APIs** that can enable developers to build AI-powered features.

## Google Vertex AI

- [generative-ai repository](https://github.com/GoogleCloudPlatform/generative-ai/) by Google Cloud - examples and tools for using Vertex AI generative models
- [generative-ai web demos](https://github.com/google/generative-ai-docs/tree/main/demos/palm/web) by Google - sample web projects implementing whole generative ai features using PaLM 2

## Courses 

- [Generative AI with AutoML & Vertex AI Specialization](https://www.cloudskillsboost.google/quests/299) on Cloud Skills Boost ($3)

- [Generate synthetic data with Vertex AI](https://www.cloudskillsboost.google/journeys/118) free course on Cloud Skills Boost

## Talks & Articles

- [Keynote. Will chatGPT take your job? The rise of conversational AIs (25min)](https://www.youtube.com/watch?v=qG9l6QPjbN4) - Introduction to ChatGPT and GPT models

- [Article. The Start of a New Era in AI](https://gerard-sans.medium.com/openai-the-start-of-a-new-era-in-ai-1eef98d0e2a3) - Podcast on generative AI and its future impact

- [Talk. OpenAI and the AI that may overtake humans (50min)](https://www.youtube.com/watch?v=Z6KqBb451fE) - Talk on GPT-3 at JFokus 2022

- [How to generate text](https://huggingface.co/blog/how-to-generate) - Explains Temperature, TopK, TopP parameters.
- [Top-k & Top-p](https://docs.cohere.com/docs/controlling-generation-with-top-k-top-p) - Visual explanation for TopK and TopP

## How-Tos

- [Integrating Vertex AI into Angular Apps](https://docs.google.com/document/d/1wi7rvFp1yfYVDmnpEK8Q1njhIp8amcJKdGO4YrAAkMc/edit?usp=sharing) - Angular guide using Google Cloud SDK + HttpClient

## Transformer Architecture

- [Attention is all you need](https://arxiv.org/pdf/1706.03762.pdf) - Original paper from Google introducing the Transformer
- [An In-Depth Look at the Transformer Based Models](https://medium.com/@yulemoon/an-in-depth-look-at-the-transformer-based-models-22e5f5d17b6b) - Overview of the diferent types of Transformers

## Playground

### Most popular
- [Google Bard](https://bard.google.com) - based on PaLM 2 by Google (uses external tools including Google Search)
- [Claude](https://claude.ai/) - based on claude 2 by Anthropic (isolated, data cutout 2023, 100K context)
- [ChatGPT](https://chat.openai.com) - based on GPT by OpenAI (free version isolated, data cutout 2021)

### All-in-one (multiple models in one interface)
- [Poe](https://poe.com/) - Access to ChatGPT/GPT, Claude, Llama and PaLM 2 models.
- [Nat.dev](https://nat.dev/) - Most number of models. Access to all previous models and many more including open source.
