---
title: Tutorials
description: Tutorials were held April 17, 2026.
---

## Schedule

!!! info "Microsoft Sponsored Tutorials — Open to All Weekend Attendees"
    Both Microsoft-sponsored tutorials are open to **all weekend ticket holders**. If you hold a Saturday/Sunday conference ticket but do not have a Friday tutorials ticket, you are still welcome to attend these sessions.

### Friday, April 17

|       Time        | Tutorial | Instructor |
| :---------------: | :------: | :--------: |
| 09:00am - 12:00pm | [Import is Important: The Secret Life of Python Modules and Packages](#import-is-important-the-secret-life-of-python-modules-and-packages)  | Heather Crawford |
| 01:30pm - 04:30pm | [Becoming a Better Python Developer with AI](#becoming-a-better-python-developer-with-ai) | Bernát Gábor |
| 04:30pm - 06:00pm | [Build Agentic AI with Semantic Kernel and Graph RAG on PostgreSQL (Sponsored)](#build-agentic-ai-with-semantic-kernel-and-graph-rag-on-postgresql-sponsored) | Microsoft |

### Saturday, April 18

|       Time        | Tutorial | Instructor |
| :---------------: | :------: | :--------: |
| 04:30pm - 06:00pm | [Building a Full-Stack FastAPI App with Open Source DocumentDB via Docker (Sponsored)](#building-a-full-stack-fastapi-app-with-open-source-documentdb-via-docker-sponsored) | Microsoft |

## Tutorials

### Import is Important: The Secret Life of Python Modules and Packages

Python is a richer and much more performant language because of the range of available libraries. Unfortunately, all of this power is sadly unavailable if you struggle with how to make it available to your codebase.

Python imports are an arcane set of spells that can stump even the most experienced programmer. With a little time, experience, and guidance, you too can harness the power of existing code and understand how modules can be used and reused, all while keeping your codebase lean and performant.

In this tutorial, participants will learn how Python manages modules, how to import from them, and how to debug common issues with imports and modules. Specifically, we'll cover the following topics:

* Namespaces and Python
* Using  __init__.py
* Understanding modules and packages
* Choosing between namespace and regular packages
* Leveraging relative vs. absolute imports
* Understanding module lookup
* Unveiling import and module tips and tricks
* Coming in Python 3.15 - explicit lazy imports

#### Prerequisites

Participants should have the following for the hands-on portion of the tutorial:

* a laptop with a Web browser (Chrome, Safari, etc.)
* a GitHub account (the free personal account is perfect!)
* some knowledge of Python basics, including functions, variables, objects, and scoping
* some knowledge of git basics, including cloning repos, branching, and the add-commit-push cycle.

#### Presenter: Heather Crawford

![Heather Crawford Headshot](https://pycon-assets.s3.amazonaws.com/2024/media/speaker_photos/187.jpg.256x256_q85.jpg){: style="height:150px;width:150px" align=left}

_Heather Crawford is an Engineering Technical Trainer at Bloomberg and a former university professor. In her roles as a professional educator, she has taught learners at many levels from university students at all levels to both entry-level and experienced software engineers. She has presented at many academic and industry conferences. A Python lover, Heather has used it since 2007._

<br clear="all">

### Becoming a Better Python Developer with AI

According to Sonar's 2026 State of Code Developer Survey report, 72% of developers who have tried AI coding tools now use them every day, while 42% of committed code is AI-generated or assisted. However, 96% of developers don't fully trust that AI-generated code is functionally correct, and 61% agree that AI often produces code that "looks correct, but isn't reliable." The result? A verification bottleneck.

While AI promises productivity gains, developers are spending significant time reviewing and correcting AI output—and only 48% always check AI-generated code before committing it. The survey also found that the #1 skill developers need in the AI era isn't prompting — instead, it's "reviewing and validating AI-generated code for quality and security."

This hands-on workshop bridges the gap between AI's promise and productive reality. You'll learn some mental models and workflows that will help use AI assistants effectively while maintaining code quality. Using real open source issues for our exercises, you'll practice the brainstorm → plan → execute methodology, understand when to use different AI modes (ask, edit, plan, agent), and develop and put guardrails into practice to keep AI-generated code safe and reviewable.

What we'll cover:

* **Mental models**: How to think about AI as a code archaeologist, junior engineer with full-context access, and/or senior reviewer—and when each mental model applies.
* **AI interaction modes**: When to use ask, edit, plan, and agent modes for different tasks.
* **The brainstorm → plan → execute workflow**: A structured methodology for tackling complex changes safely.
* **Context management**: How context windows work, why they matter, and how to keep them focused for better results.
* **Prompting AI coding assistants**: Explicit instructions, positive framing, and techniques specific to current models (Note: while we'll primarily use Claude Code, this workshop is IDE-agnostic; the skills transfer to any AI coding assistant).
* **Hallucination reduction**: Grounding AI in actual code, requiring citations, and verification strategies.
* **Test-driven development with AI**: Writing failing tests first, then letting AI iterate toward passing code.
* **Contribution workflows**: Using AI to understand contribution guidelines, draft PRs, and create clean commits.

You'll walk away with:

* A framework for deciding when and how to use AI coding assistants—and when to be extra careful.
* Practical experience applying agentic AI workflows to real open source issues.
* Techniques for managing context windows and reducing hallucinations.
* Prompting patterns you can apply immediately to get better results.
* Guardrails for reviewing AI-generated code before it reaches production.
* Confidence to explore unfamiliar codebases with assistance from AI.

#### Presenter: Bernát Gábor

![Bernát Gábor Avatar](https://avatars.githubusercontent.com/u/690238?v=4){: style="height:150px;width:150px" align=left}

_Bernát works at Bloomberg US - Los Angeles on the data ingestion pipelines quality control segment. He is a PSF Fellow and has authored numorous highly used Python packages. You can find a full list [here](https://bernat.tech/about/)_

<br clear="all">

### Build Agentic AI with Semantic Kernel and Graph RAG on PostgreSQL (Sponsored)

In this hands-on lab, you will build an agent-driven Retrieval-Augmented Generation (RAG) application using a U.S. Case Law dataset. You will work with Azure Database for PostgreSQL, Visual Studio Code, and the Semantic Kernel Agent Framework to explore AI-powered text and vector search. The lab also introduces GraphRAG with Apache AGE, enabling enriched querying across structured and graph-based data. By the end, you'll gain practical skills in semantic search, vector indexing, and intelligent data retrieval.

**Topics Covered:**

* Setup your Azure PostgreSQL Database
* Launch PSQL Command Line Shell in VS Code
* Using AI-driven features in Postgres
* Using Semantic Vector Search and DiskANN Index
* Perform a Semantic Search Query
* Semantic Agent Configuration and Plugin Assembly

#### Presenter: Microsoft

### Building a Full-Stack FastAPI App with Open Source DocumentDB via Docker (Sponsored)

This hands-on lab guides you through the process of building a modern, full-stack web application using FastAPI for the backend and open source DocumentDB as the database, all orchestrated with Docker containers. Attendees will learn how to rapidly prototype and deploy scalable Python APIs, leverage containerization for consistent development and testing, and integrate with DocumentDB for flexible, cloud-ready data storage.

**Topics Covered:**

* Setting up a FastAPI backend and connecting it to DocumentDB using Docker Compose.
* Best practices for local development, testing, and CI/CD integration with Docker.
* How open source DocumentDB enables rapid iteration and seamless migration to cloud environments.
* Real-world patterns for building, running, and debugging full-stack apps in isolated, reproducible environments.

By the end of the lab, you'll have a working application, a deeper understanding of containerized development workflows, and practical experience with the latest open source tools for Python and NoSQL development.

#### Presenter: Microsoft
