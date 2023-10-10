
# LLMs Intro
The following resources will give you a thourough introduction to large language models (LLMs) and how to use them. You can either pick one of the resources listed in [All-in-one resources](#0-all-in-one-resources) or follow the chapters 1 to 6 in order. Chapter 7 offers more context on generative AI in general. 

The essential content for each chapter is marked with a **bold** font, the additional resources offer a more in depth view on the topic.  

I'd encourage you to come back to Chip Huyen's blog post [Building LLM applications for production](https://huyenchip.com/2023/04/11/llm-engineering.html) from time to time. It is listed in chapter 1, but as you learn more about LLMs, you will be able to explore the article more in depth.

## Table of Contents
0. [All-in-one resources](#0-all-in-one-resources)
1. [High-level overview](#1-high-level-overview)
2. [Deep-dive into language and transformers](#2-deep-dive-into-language-and-transformers)
3. [Training LLMs](#3-training-llms)
4. [Fine-tuning LLMs](#4-fine-tuning-llms)
5. [Using LLMs](#5-using-llms)
6. [Building applications with LLMs](#6-building-applications-with-llms)
7. [More on generative AI in general](#7-more-on-generative-ai-in-general)

## 0. All-in-one resources
Gain a comprehensive insight into LLMs and their applications. These resources offer both theoretical knowledge and practical applications, enabling you to explore and utilize large language models effectively.
- The ultimate [LLM Learning Mind Map](https://lucid.app/lucidspark/98705f5a-a385-4820-a648-be35c9d1cda6/edit?page=0_0#)
- Intro to LLMs and building applications with LangChain and VectorDBs: [LangChain & Vector Databases in Production](https://learn.activeloop.ai/courses/langchain) - 40 hours course

## 1. High-level overview
Embark on your journey into the world of large language models, understanding their basic functioning, potential and use cases.
- **A mellow introduction to language models and generative AI: [How GPT models work](https://towardsdatascience.com/how-gpt-models-work-b5f4517d5b5)**
- LLMs from a practical perspective: [Building LLM applications for production](https://huyenchip.com/2023/04/11/llm-engineering.html)

## 2. Deep-dive into language and transformers (the underlying architecture of LLMs)
Explore the intricacies of the transformer architecture, understanding key concepts like attention mechanisms, position embeddings, and the foundational principles that enable LLMs to understand and generate human-like text.
- TODO: Concise post on transformers
- TODO: Post on embeddings
- **Video series giving a nice starting point to understand language and transformers: Visual Guide to Transformers**
  - Part 0: [The Neuroscience of “Attention”](https://www.youtube.com/watch?v=48gBPL7aHJY)
  - Part 1: [Position Embeddings](https://www.youtube.com/watch?v=dichIcUZfOw)
  - Part 2: [Multi-Head & Self-Attention](https://www.youtube.com/watch?v=mMa2PmYJlCo)
  - Part 3: [Decoder’s Masked Attention](https://www.youtube.com/watch?v=gJ9kaJsE78k&t=172s)
- Illustrated guides to [Attention](https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/) and [Transformers](https://jalammar.github.io/illustrated-transformer/) (also available as [video](https://www.youtube.com/watch?v=-QH8fRhqFHM))
- Technical deep-dive into the underlying transformer architecture: [Transformers from Scratch](https://e2eml.school/transformers.html)
- The OG paper: [Attention is all you need](https://proceedings.neurips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf)

## 3. Training LLMs
Learn how language models trained and how you can train your own model.
- **Step-by-step guides to train a language model from scratch with the Hugging Face transformers library:**
  - [How to train a new language model from scratch using Transformers and Tokenizers](https://huggingface.co/blog/how-to-train)
  - [Training a language model with 🤗 Transformers using TensorFlow and TPUs](https://huggingface.co/blog/tf_tpu)
- Putting the golden layer on a language model and make for a human like chat experience: [RLHF: Reinforcement Learning from Human Feedback](https://huyenchip.com/2023/05/02/rlhf.html)
- More practical explanation of RLHF: [Illustrating Reinforcement Learning from Human Feedback (RLHF)](https://huggingface.co/blog/rlhf)

## 4. Fine-tuning LLMs
Unlock the true potential of pre-trained LLMs by learning about fine-tuning processes, exploring various strategies to adapt existing models to your specific use-cases and understanding how to incorporate domain-specific knowledge.
- **Introduction to fine-tuning: [LLMs Unleashed: The Power of Fine-Tuning](https://lucaspauker.com/articles/llms-unleashed-the-power-of-fine-tuning)**
- **Incorportate domain knowledge without fine-tuning: [Retrieval Augmented Generation](https://www.promptingguide.ai/techniques/rag)**
- When to apply fine-tuning, how to prepare the data and how to execute it: [Fine-tuning LLMs, Deeplerning.AI](https://www.deeplearning.ai/short-courses/finetuning-large-language-models/) - 1 hour course
- Fine-tune without retraining and little data: [SetFit: Efficient Few-Shot Learning Without Prompts](https://huggingface.co/blog/setfit)
- Examples of fine-tuning models:
  - [LLaMa 2 model, including code, data, and hardware requirements](https://huggingface.co/blog/ram-efficient-pytorch-fsdp)
  - [LLaMa model with reinforcement Learning with humand feedback (RLHF)](https://huggingface.co/blog/stackllama)

## 5. Using LLMs
Understand how to effectively communicate with LLMs, learning about prompt engineering and discovering strategies to extract desired outputs and answers from models.
- **Interact with a model and to get the answer you need: [Prompt Engineering Guide](https://www.promptingguide.ai)**
- **Learn how to chain prompts effectively: [Building Systems with the ChatGPT API, Deeplerning.AI](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/)** - 1 hour course
- Introduction to [Prompt Engineering, Deeplerning.AI](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) - 1 hour course

## 6. Building applications with LLMs
Learn to develop applications utilizing LLMs to transition from theoretical understanding to actual implementation of language models in real-world applications.
- **Learn the basics of LangChain and how to use them: [LangChain for LLM Application Development, Deeplerning.AI](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)** - 1 hour course
- TODO: Post on VectorDBs

## 7. More on generative AI in general
Explore the broader sphere of generative AI, learning about its historical development, underlying technologies like Generative Adversarial Networks (GANs), and gaining insights into the broader implications and applications of generative models in the AI field.
- OpenAI giving an intro to GenAI back in 2016: [Generative Models](https://openai.com/research/generative-models)
- The technique powering good generative output: [Generative Adversarial Nets (GANs)](https://arxiv.org/pdf/1406.2661.pdf)
- That same technique explained in an understandable way: [A Gentle Introduction to Generative Adversarial Networks (GANs)](https://machinelearningmastery.com/what-are-generative-adversarial-networks-gans/)