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

## Google PaLM API

- [GraphQL wrapper of PaLM API (v1beta2) using Apollo Server (v4.9)](https://codesandbox.io/p/sandbox/eager-monad-fj2l8l?file=%2Fsrc%2Findex.ts%3A13%2C12)
- [Angular client (v16) for GraphQL PaLM API (v1beta2)](https://stackblitz.com/edit/stackblitz-starters-xkwxnp?file=src%2Fmain.ts)

## Courses 

- [Generative AI Explorer - Vertex AI](https://www.cloudskillsboost.google/quests/299) introduction to prompt design, Generative AI Studio and Vertex AI on Cloud Skills Boost (cost: $3 or 3 credits)

- [Generative AI learning path by Google Cloud](https://www.cloudskillsboost.google/journeys/118) 10x individual courses on Cloud Skills Boost (free)

## Talks & Articles

- [Talk. Everything you need to know about Google's new Generative AI platform](https://www.youtube.com/watch?v=JtULDpWH-I0) - In this talk, you are going to learn about Google's new Generative AI platform Vertex AI, the latest tools and APIs to foundational models

- [Keynote. How OpenAI Codex learned to write and refactor JavaScript](https://www.youtube.com/watch?v=FwRtzlYINrA&t=1s) - Introduction to Codex a LLM specialised around code

- [Keynote. Will chatGPT take your job? The rise of conversational AIs (25min)](https://www.youtube.com/watch?v=qG9l6QPjbN4) - Introduction to ChatGPT and GPT models

- [Article. The Start of a New Era in AI](https://gerard-sans.medium.com/openai-the-start-of-a-new-era-in-ai-1eef98d0e2a3) - Podcast on generative AI and its future impact

- [Talk. OpenAI and the AI that may overtake humans (50min)](https://www.youtube.com/watch?v=Z6KqBb451fE) - Talk on GPT-3 at JFokus 2022

- [How to generate text](https://huggingface.co/blog/how-to-generate) - Explains Temperature, TopK, TopP parameters.
- [Top-k & Top-p](https://docs.cohere.com/docs/controlling-generation-with-top-k-top-p) - Visual explanation for TopK and TopP

## How-Tos

- [Blogpost. Getting Started with Generative AI in Angular](https://gerard-sans.medium.com/getting-started-with-generative-ai-in-angular-b72737a59982) - General guide around how to get started with Vertex AI and PaLM 2 APIs using Angular
- [Notes. Integrating Vertex AI into Angular Apps](https://docs.google.com/document/d/1wi7rvFp1yfYVDmnpEK8Q1njhIp8amcJKdGO4YrAAkMc/edit?usp=sharing) - Angular guide using Google Cloud SDK + HttpClient

## Transformer Architecture

- [Attention is all you need](https://arxiv.org/pdf/1706.03762.pdf) - Original paper from Google introducing the Transformer
- [An In-Depth Look at the Transformer Based Models](https://medium.com/@yulemoon/an-in-depth-look-at-the-transformer-based-models-22e5f5d17b6b) - Overview of the diferent types of Transformers

## Playground (play with LLMs available for free)

### Most popular
- [Google Bard](https://bard.google.com) - based on PaLM 2 by Google (uses external tools including Google Search)
- [Claude](https://claude.ai/) - based on claude 2 by Anthropic (isolated, data cutout 2023, 100K context)
- [ChatGPT](https://chat.openai.com) - based on GPT by OpenAI (free version isolated, data cutout 2021)

### All-in-one (multiple models in one interface)
- [Poe](https://poe.com/) - Access to ChatGPT/GPT, Claude, Llama and PaLM 2 models.
- [Nat.dev](https://nat.dev/) - Most number of models. Access to all previous models and many more including open source.
