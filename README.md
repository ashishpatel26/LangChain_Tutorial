# 🦜️🔗 LangChain Tutorial

⚡ Building applications with LLMs through composability ⚡

[![lint](https://github.com/hwchase17/langchain/actions/workflows/lint.yml/badge.svg)](https://github.com/hwchase17/langchain/actions/workflows/lint.yml) [![test](https://github.com/hwchase17/langchain/actions/workflows/test.yml/badge.svg)](https://github.com/hwchase17/langchain/actions/workflows/test.yml) [![linkcheck](https://github.com/hwchase17/langchain/actions/workflows/linkcheck.yml/badge.svg)](https://github.com/hwchase17/langchain/actions/workflows/linkcheck.yml) [![Downloads](https://camo.githubusercontent.com/e4796338c72e102e954541dad216e1d203e015306ceaac50abe8f1b0d4f804fe/68747470733a2f2f7374617469632e706570792e746563682f62616467652f6c616e67636861696e2f6d6f6e7468)](https://pepy.tech/project/langchain) [![License: MIT](https://camo.githubusercontent.com/78f47a09877ba9d28da1887a93e5c3bc2efb309c1e910eb21135becd2998238a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d79656c6c6f772e737667)](https://opensource.org/licenses/MIT) [![Twitter](https://camo.githubusercontent.com/1c2e325d2339ff83058312c86964f80ebc5f28c8d2769f67c2667e21a535f16a/68747470733a2f2f696d672e736869656c64732e696f2f747769747465722f75726c2f68747470732f747769747465722e636f6d2f6c616e67636861696e61692e7376673f7374796c653d736f6369616c266c6162656c3d466f6c6c6f772532302534304c616e67436861696e4149)](https://twitter.com/langchainai) [![img](https://camo.githubusercontent.com/dafad31410896f1d826306b256c8a0cc3cd9e4f2bbe1362ca17ec197cba65539/68747470733a2f2f646362616467652e76657263656c2e6170702f6170692f7365727665722f3661644d517853704a533f636f6d706163743d74727565267374796c653d666c6174)](https://discord.gg/6adMQxSpJS)

**Production Support:** As you move your LangChains into production, we'd love to offer more comprehensive support. Please fill out [this form](https://forms.gle/57d8AmXBYp8PP8tZA) and we'll set up a dedicated support Slack channel.

## Quick Install

```
pip install langchain` or `conda install langchain -c conda-forge
```

## 🤔 What is this?

Large language models (LLMs) are emerging as a transformative technology, enabling developers to build applications that they previously could not. But using these LLMs in isolation is often not enough to create a truly powerful app - the real power comes when you can combine them with other sources of computation or knowledge.

This library is aimed at assisting in the development of those types of applications. Common examples of these types of applications include:

**❓ Question Answering over specific documents**

- [Documentation](https://langchain.readthedocs.io/en/latest/use_cases/question_answering.html)
- End-to-end Example: [Question Answering over Notion Database](https://github.com/hwchase17/notion-qa)

**💬 Chatbots**

- [Documentation](https://langchain.readthedocs.io/en/latest/use_cases/chatbots.html)
- End-to-end Example: [Chat-LangChain](https://github.com/hwchase17/chat-langchain)

**🤖 Agents**

- [Documentation](https://langchain.readthedocs.io/en/latest/modules/agents.html)
- End-to-end Example: [GPT+WolframAlpha](https://huggingface.co/spaces/JavaFXpert/Chat-GPT-LangChain)

## 📖 Documentation

Please see [here](https://langchain.readthedocs.io/en/latest/?) for full documentation on:

- Getting started (installation, setting up the environment, simple examples)
- How-To examples (demos, integrations, helper functions)
- Reference (full API docs)
- Resources (high-level explanation of core concepts)

## 🚀 What can this help with?

There are six main areas that LangChain is designed to help with. These are, in increasing order of complexity:

**📃 LLMs and Prompts:**

This includes prompt management, prompt optimization, generic interface for all LLMs, and common utilities for working with LLMs.

**🔗 Chains:**

Chains go beyond just a single LLM call, and are sequences of calls (whether to an LLM or a different utility). LangChain provides a standard interface for chains, lots of integrations with other tools, and end-to-end chains for common applications.

**📚 Data Augmented Generation:**

Data Augmented Generation involves specific types of chains that first interact with an external datasource to fetch data to use in the generation step. Examples of this include summarization of long pieces of text and question/answering over specific data sources.

**🤖 Agents:**

Agents involve an LLM making decisions about which Actions to take, taking that Action, seeing an Observation, and repeating that until done. LangChain provides a standard interface for agents, a selection of agents to choose from, and examples of end-to-end agents.

**🧠 Memory:**

Memory is the concept of persisting state between calls of a chain/agent. LangChain provides a standard interface for memory, a collection of memory implementations, and examples of chains/agents that use memory.

**🧐 Evaluation:**

[BETA] Generative models are notoriously hard to evaluate with traditional metrics. One new way of evaluating them is using language models themselves to do the evaluation. LangChain provides some prompts/chains for assisting in this.

For more information on these concepts, please see our [full documentation](https://langchain.readthedocs.io/en/latest/).

---

**This is for Educational Purpose Only.🙏🙏🙏**

---

