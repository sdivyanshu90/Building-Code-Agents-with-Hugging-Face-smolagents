# Building Code Agents with Hugging Face *smolagents*

A short course offered by **[DeepLearning.AI](https://www.deeplearning.ai/)** in collaboration with **[Hugging Face](https://huggingface.co/)**, designed to teach developers how to build and evaluate code agents using the lightweight **smolagents** framework.

This course introduces the concept of code agents, explains how they differ from function-calling agents, and provides hands-on practice in building secure, reliable, and production-ready agentic systems.

---

## Introduction

Traditional tool-calling agents rely on large language models (LLMs) to write multiple function calls sequentially—generate a call, execute it, observe, reason, and repeat. While flexible, this approach can be inefficient and error-prone.

**Code agents** take a different approach:

* Instead of multiple steps, the LLM outputs an entire **block of code** representing its plan of action.
* This code block is then executed in one go, resulting in **faster and more reliable outcomes**.

In this course, you’ll learn to:

* Build your own code agents with **smolagents**.
* Run LLM-generated code safely using sandboxing and constrained execution.
* Evaluate, monitor, and improve agent performance.
* Develop a multi-agent research system capable of finding, organizing, and presenting information interactively.

---

## Course Topics

### 1. A Brief History of Agents

In this section, you’ll gain historical context on **AI agents**—systems that use LLMs to interact with tools, APIs, and data sources.

* Learn how agents evolved from **basic prompt-following models** to **function-calling systems**, and finally to **code agents**.
* Understand the limitations of function-calling agents, such as sequential inefficiency and error accumulation.
* Discover why code agents, with their ability to **generate complete executable code plans**, represent a **significant step forward in agentic design**.

---

### 2. Introduction to Code Agents

This module provides a deep dive into what makes **code agents unique**.

* **Concept**: Instead of generating step-by-step function calls, a code agent writes a **full snippet of code** representing its reasoning and execution plan.
* **Comparison**: Explore the differences between code agents and tool-calling agents in terms of **efficiency, flexibility, and reliability**.
* **Benefits**:

  * More robust execution of complex tasks.
  * Reduced errors from step-by-step reasoning.
  * Ability to handle multi-step workflows within a single block of code.

---

### 3. Secure Code Execution

One of the biggest challenges in running code agents is **safety**—since the code they produce comes from an LLM, it can be unpredictable. This section covers:

* Running LLM-generated code in a **constrained Python interpreter**.
* Using **sandboxing with E2B (Execution Environment)** to isolate execution and prevent harmful operations.
* Techniques for **minimizing risk** when allowing LLMs to write and execute code.
  By the end, you’ll understand how to keep your system **secure and reliable** when deploying code agents in production.

---

### 4. Monitoring and Evaluating Your Agent

Building a code agent is only the first step—ensuring that it behaves correctly and reliably is just as important. In this module, you’ll learn to:

* **Trace and debug** the agent’s reasoning and execution flow.
* Use logging and monitoring tools to gain visibility into its decisions.
* **Evaluate performance** by creating benchmarks and test cases.
* Optimize your agent’s behavior so that it **consistently produces high-quality results** in real-world scenarios.

---

### 5. Build a Deep-Research Agent

In the final project, you’ll apply your knowledge to build a **multi-agent research system**. This agent will:

* Search for information on the web.
* Organize collected data into structured knowledge.
* Present the findings in an **interactive report format**.
  This hands-on project demonstrates the **practical power of code agents**, showing how they can handle complex, multi-step workflows that involve reasoning, data collection, and structured reporting.

---

## Acknowledgment

This course is proudly brought to you by:

* **[DeepLearning.AI](https://www.deeplearning.ai/)** – Leading provider of AI education, founded by Andrew Ng.
* **[Hugging Face](https://huggingface.co/)** – Creator of cutting-edge open-source AI tools, including the **smolagents** framework.

Special thanks to the instructors and contributors for making this course accessible to developers worldwide.
