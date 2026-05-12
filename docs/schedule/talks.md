---
Title: Accepted Talks
description: We have accepted 15 talks for this year's PyTexas. Topics include AI, Python features, security, data engineering, observability, and more!
---

These are the talks accepted to PyTexas 2026, listed in schedule order.

## Python as Your DSL

Python's flexibility makes it an excellent choice for creating Domain-Specific Languages (DSLs) that feel natural to domain experts while remaining powerful for developers. From Django's model definitions to Jupyter's configuration format, from SCons build scripts to Kubernetes manifest generation, Python DSLs are everywhere—but what makes a good one versus a confusing mess?

In this talk, we'll explore the art and science of designing Python DSLs that don't fight against the language's principles. You'll learn when to embrace Python's "magic" and when it becomes harmful, how to create APIs that feel pythonic even when they're domain-specific, and practical techniques for building DSLs through detailed analysis of successful real-world examples.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/K3JL5C8HFqo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
</div>

**Speaker: Moshe Zadka**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Moshe Zadka Headshot](https://pretalx.com/media/avatars/KYYQVJ_v0LCIik.webp){: width="150"}

</div>
<div markdown="1">

_Moshe has been a DevOps/SRE since before those terms existed, caring deeply about software reliability, build reproducibility, and other such things. They have worked in companies as small as three people and as big as tens of thousands—usually someplace around where software meets system administration._

</div>
</div>

## I Built an AI Running Coach (That Actually Remembers My Training)

Generic fitness apps don't know when you're sick, stressed, or injured. In this talk, I'll show how I built a personal AI running coach using Python. You'll learn how to reverse-engineer undocumented APIs (like Peloton), handle conflicting data, and use async serverless patterns to give LLMs "memory" and context.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/EfIbH20J97Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Adam's Resources**

- [Repo](https://github.com/adamgordonbell/ai-running-coach) (simplified version of what Adam's running)
- His [site](https://www.pulumi.com/community/community-engineering/adam-gordon-bell/)

</div>
</div>

**Speaker: Adam Gordon Bell**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Adam Gordon Bell Headshot](https://pretalx.com/media/avatars/GWK7YJ_1Hh3llG.webp){: width="150"}

</div>
<div markdown="1">

_Adam Gordon Bell is a software engineer and host of the CoRecursive podcast, where he interviews developers about the stories behind their code. He is known for his deep dives into system internals, including his popular work analyzing Python's Timsort merge logic. Currently, he is a Community Engineer at Pulumi, where he helps developers build infrastructure using the programming languages they already know. He works remotely from Canada and enjoys building overly complex Python automations for his daily life._

</div>
</div>

## Using MCP to Build Safe, Auditable AI Systems in Python

As Python developers start connecting LLMs to real systems—such as log files, automation scripts, or internal tools—questions around safety and control become increasingly important. Traditional function calling often exposes more capability than intended, and it can be difficult to monitor what the model is actually doing.

The Model Context Protocol (MCP) offers a structured way to expose Python tools with defined permissions, validated inputs, and clear auditability. Using the Python MCP SDK, this talk walks through how to design safe, predictable tool interfaces that reduce the risk of untrusted actions and make system behavior easier to understand.

We will show how to apply schema validation, introduce simple sandboxing rules, and log tool usage for transparency. The goal is to provide practical patterns that help developers build LLM-powered features in Python with more confidence and oversight.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/rYPl3Tp978Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Maria's Resources**

- [Repo](https://github.com/MS-Mielnic/pytexas-mcp-demo)

</div>
</div>

**Speaker: Maria Silvia Mielniczuk**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Maria Silvia Mielniczuk Headshot](../assets/images/speakers/Maria_Silvia_Mielniczuk.png){: width="150"}

</div>
<div markdown="1">

_Maria Silvia Mielniczuk is a data scientist with a Master of Applied Data Science from the University of Michigan (2025). She works at Splunk, a Cisco company, helping customers in Brazil tackle big-data challenges in cybersecurity and observability across financial services, ecommerce, and healthcare. Originally from Argentina, she spent 17 years living in Brazil and Mexico before becoming a proud Texan. She's also happily married and the mother of three teenage boys — her true inspiration to run marathons._

</div>
</div>

## Data Visualization in Python (Sponsored)

With over 150 open-source visualization tools in the Python ecosystem, picking the right one can feel like choosing a restaurant in a city you've never visited - overwhelming, and with real consequences if you get it wrong. This talk cuts through the noise. Dr. Bednar will walk through all the major categories of Python visualization libraries, lay out practical criteria for evaluating them, and show real examples of what each type of tool can actually do. Whether you're exploring a messy dataset, building an interactive dashboard, or publishing a polished figure, there's a right tool for that - and probably a wrong one you're currently using because someone on your team grabbed it first. Stop inheriting other people's defaults, and come find yours!

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/KpmEVWWN1Aw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Resources**

- [Presentation deck](https://tinyurl.com/pytexas26) (slides)

</div>
</div>

**Speaker: Dr. James A. Bednar**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Dr. James A. Bednar Headshot](../assets/images/speakers/james.jpg){: width="150"}

</div>
<div markdown="1">

_Senior Director of Professional Services at Anaconda, Inc., founder of the HoloViz project, and former Reader in Computational Neuroscience at U. Edinburgh._

</div>
</div>

## Why Installing Python Packages Is Still a Security Risk

While it is widely known that there are risks in installing untrusted Python packages, the nature of those risks are often unclear. Back when installation required directly calling `setup.py` with `python`, the risks were obvious. Now, using wheels, `pip install`, and `pyproject.toml`, it is at least possible to install a package without running arbitrary code. Yet even with the best modern tools, there remain many ways arbitrary code can be run or planted on installation. This talk will introduce installation-time threats and practical defenses, relevant for anyone who installs packages or maintains production Python environments.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/6nBqP0pGT3k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Resources**

- [libraries.io](https://libraries.io/)
- [snyk](https://snyk.io/)
- [pip-audit](https://github.com/pypa/pip-audit)
- [dependabot](https://docs.github.com/en/code-security/tutorials/secure-your-dependencies/dependabot-quickstart-guide) (There have been some exploits around dependabot recently - [here](https
://openssf.org/blog/2024/08/12/mitigating-attack-vectors-in-github-workflows/) is a great way to consider some more security posturing)
- [fetter.io](http://fetter.io)
- [flexatone](https://www.flexatone.net)

</div>
</div>

**Speaker: Christopher Ariza**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Christopher Ariza Headshot](https://pretalx.com/media/avatars/RGP8QS_KREo4xP.webp){: width="150"}

</div>
<div markdown="1">

_Christopher Ariza is Partner and Chief Technology Officer at Research Affiliates, a global leader in investment strategies and research. He is the creator of StaticFrame, an alternative Python DataFrame library that offers immutable and statically-typeable DataFrames. He is also the creator of Fetter, a Rust-implemented tool for system-wide Python package discovery, vulnerability auditing, and allow-list enforcement. Having worked in Python for over 25 years, he has developed tools in a variety of domains, writes on diverse technical topics, and has spoken at numerous conferences including PyCon USA, SciPy, PyBeach, and PyData._

</div>
</div>

## Behind the Magic: Unlocking Python's Descriptor Protocol

Ever wondered how @property really works? Or why setting an attribute sometimes feels … magical? That curiosity led me deep into one of Python's most powerful, yet hidden, features: the **descriptor protocol**.

In this talk, we'll reveal the magic of how Python decides what happens when you access object attributes. Through simple, live-coded examples, I'll demonstrate how descriptors enable read-only, cached, and validated attributes - and how they power familiar tools like properties, class methods, and slots.

You'll walk away with a clearer mental model of Python's object model, a few new "aha!" moments, and maybe the inspiration to build a descriptor or two yourself.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/NVKnYw4Z6B0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Resources**

- [Repo](https://github.com/sjirwin/behind-the-magic-slides)
- Python [descriptor guide](https://docs.python.org/3/howto/descriptor.html)

</div>
</div>

**Speaker: Scott Irwin**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Scott Irwin Headshot](https://pretalx.com/media/avatars/EWKHZ9_I9FQTKU.webp){: width="150"}

</div>
<div markdown="1">

_As a senior engineer at Bloomberg, Scott Irwin has spent more than a decade bridging engineering and education - building Python applications, leading development teams, and teaching hundreds of engineers through Bloomberg's internal training programs. He's passionate about helping developers write cleaner, more maintainable code. Beyond Bloomberg, Scott has taught Python to a broader audience through live online training events on the O'Reilly learning platform._

</div>
</div>

## Data Engineer's survival guide: writing pipelines that don't break at 3 AM

Let's say you are notified that a critical pipeline failed because a source file contained a string in a column that was supposed to be an integer.

Data Engineering doesn't have to be a constant cycle of firefighting. By borrowing battle tested practices from traditional software engineering like strict type hinting, robust unit testing, and defensive design, we can build pipelines that are resilient by default. This talk is a survival guide for the modern Data Engineer. We will move beyond scripting and explore how to use standard Python tools (like Pydantic, pytest, and logging) to catch dirty data and logic errors in CI/CD, long before they wake you up.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/vllVi_pKd9M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
</div>

**Speaker: [Indrasena Manga](https://www.linkedin.com/in/indra7979/)**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Indrasena Manga Headshot](../assets/images/speakers/Indrasena_Manga.png){: width="150"}

</div>
<div markdown="1">

_Indrasena Manga, a Senior Data Engineer at AXS.com (Texas, USA) with expertise in AI/ML systems, real-time data streaming, and large-scale data engineering. I've authored 10+ Scopus and IEEE indexed research papers, served as a Session Chair & Guest Speaker at IEEE ComputingCon-2025, served as a Session chair for GCAT-2025, and completed 30+ peer reviews for Elsevier, Springer, and IEEE. I'm a provisional patent holder (USPTO) for an AI-driven disaster relief system and an active member of IEEE, ACM (SIGAI, SIGKDD), and SCRS._

</div>
</div>

## Failed Experiments in Vibe Coding

"AI is going to replace all software engineers if we could just get it to stop deleting the database." This talk explores the possibility of non-developers using AI to "vibe code" software, along with some hilarious failures. Circular mazes, lava lamp screensavers, virtual abacuses, combination lock simulators, and an African geography map quiz: Al Sweigart presents AI-generated Python code that doesn't quite reach success.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/01NuRv-LsH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Resources**

- [Slides](https://docs.google.com/presentation/d/1kEWwytGKwSa12ZwMozxr_qsV75rM180E_omuxuR2SlM/edit?usp=sharing) (originally linked from [here](http://inventwithpython.com/pytexas2026))
- ButtonPad [repo](https://github.com/asweigart/buttonpad)
- Vibe Coding [experiment failures](https://inventwithpython.com/blog/vibe-coding-failures.html)

</div>
</div>

**Speaker: Al Sweigart**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Al Sweigart Headshot](https://pretalx.com/media/avatars/HVAES8_0rorN3p.webp){: width="150"}

</div>
<div markdown="1">

_Al Sweigart (rhymes with "why dirt") is a software developer, tech book author, artist, and Fellow of the Python Software Foundation. His books include Automate the Boring Stuff with Python, The Recursive Book of Recursion, and The Big Book of Small Python Projects. He is the maintainer of several open source projects, including PyAutoGUI and pyperclip. He enjoys writing software, creating digital art, fostering cats, donating platelets, folding origami, and picking up litter._

</div>
</div>

## The Bakery: How PEP810 sped up my bread operations business

Discover how PEP 810's explicit lazy imports can dramatically improve Python application startup times. Using a real CLI tool as a case study, that we totally use in our real business, this talk demonstrates practical techniques to optimize import performance while maintaining code clarity and safety.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/JplCNLBD5Dw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Resources**

- [Repo](https://github.com/jacobcoffee/breadctl)

</div>
</div>

**Speaker: Jacob Coffee**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Jacob Coffee Headshot](https://pretalx.com/media/avatars/S9XY8N_8FyIg6i.webp){: width="150"}

</div>
<div markdown="1">

_Jacob Coffee is an Infrastructure Engineer at the Python Software Foundation and a newly invited CPython triager. He supports key Python services such as PyPI.org and Python.org while also contributing to the maintenance of the Litestar ecosystem which boasts libraries such as Litestar, Advanced Alchemy, Polyfactory, and more. He is passionate about open-source development, the mission of the PSF, and enhancing the tools that empower developers worldwide._

</div>
</div>

## Python in the Browser: Building Interactive Documentation with MkDocs & JupyterLite

Installation shouldn't be a barrier to learning Python. In this talk, you'll discover how to turn traditional documentation into fully interactive, zero-setup Python environments straight in your browser - no servers, containers, or local installation necessary. You'll learn how to use MkDocs + JupyterLite (via WebAssembly) to embed live code, auto-sync code examples from your repo without duplication, and make presentation of your training documentation easier to utilize.

If you maintain docs, teach Python, build internal tools, or just want smoother developer experiences, you'll walk away knowing exactly how to choose and implement the right approach for your team or project while gaining a fresh appreciation for how accessible Python learning can be when we remove barriers.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/XNS3IwQZD80" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Resources**

- mkdocs [Site](https://resume.prosperousheart.com/mkdocs-jupyterlite-template-repo/) (including embedded deck) for the template [repo](https://github.com/ProsperousHeart/mkdocs-jupyterlite-template-repo)

</div>
</div>

**Speaker: [Kassandra Keeton](https://www.linkedin.com/in/kkeeton/), the Prosperous Heart**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Kassandra Keeton Headshot](https://pretalx.com/media/avatars/TAGTJC_OCnUUcW.webp){: width="150"}

</div>
<div markdown="1">

_Kassandra is currently a Customer Delivery Software Architect at Cisco Systems who is passionate about empowering others to create greater success in their lives. She does so by being a developer advocate, breaking down what she knows into easy-to-understand byte-sized pieces, and sharing her experiences in the hopes that others can achieve their desired outcomes faster. A budding gardener, she also enjoys finding ways to more efficiently utilize technology to support people and our planet._

</div>
</div>

## Mastered development but still stuck? The hidden power of soft skills in your codebase.

Your code might be brilliant, passing every test and adhering to best practices, yet some projects still feel stuck, or teams struggle to truly gel. What if the most persistent "bugs" in your development process aren't found in your Traceback but in the human interactions that shape your codebase?

This talk will delve into this often-overlooked reality, exploring why mastering people skills is the ultimate next level for any developer aiming for greater impact and career satisfaction. We will examine the hidden costs of poor communication and a lack of empathy, and uncover how these "soft" skills are, in fact, foundational for robust technical outcomes and a thriving development culture.

**Speaker: Sumaiya Nalukwago**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Sumaiya Nalukwago Headshot](https://pretalx.com/media/avatars/YZWKNQ_xbBJ8Hj.webp){: width="150"}

</div>
<div markdown="1">

_Sumaiya Nalukwago is an experienced IT Professional currently working with Mbarara University of Science and Technology and Tech Community Lead with over six years of proven success in leveraging technology to drive economic development and nurture innovation across Uganda and beyond. As a Community Manager for Google Developer Groups Cloud Mbarara and an Ambassador for Google Women Techmakers (with Technovation), Sumaiya actively skills and mentors thousands of youth and women entrepreneurs in digital literacy, business development, and tech-solution design._

</div>
</div>

## Events are the Wrong Abstraction (Sponsored)

Modern software applications are distributed systems. They need to connect and communicate with other applications across a network. Event-Driven Architecture is a common pattern for facilitating this connectivity, using Events as the communication abstraction. However, this pattern introduces complexities as well, such as fragmented logic, increased latency, decreased observability, and more. But what if there were a way to get the benefits of Event-Driven Architecture without the complexities?

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/r1YI5o5P8h8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Resources**

- Play with the Durable Execution playground [here](https://t.mp/pytx2026) (it has instructions)

</div>
</div>

**Speaker: Mason Egger**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Mason Egger Headshot](https://github.com/masonegger.png){: width="150"}

</div>
<div markdown="1">

_Mason is currently a Senior Solutions Architect at Temporal Technologies, where he works with customers to architect and implement durable execution solutions. He specializes in Python, distributed systems, building community, and creating developer-focused educational content. He's an avid programmer, speaker, educator, and writer/blogger. He is President of the PyTexas Foundation, Conference Chair of the PyTexas Conference, and a founding organizer of the PyTexas Meetup. He was made a PSF Fellow in October 2025._

</div>
</div>

## Are API Tests Overrated? Let's Mitigate Risks in Smarter Ways

API tests are often seen as essential, but are they always worth the effort? In this talk, we will challenge conventional testing strategies and explore whether API tests are truly the best way to catch meaningful bugs. We will consider smarter alternatives like unit testing handlers, contract testing, and well-placed UI tests — all through the lens of Domain-Driven Design. Rather than advocating for zero API tests, this is a call to be more deliberate about where and why we test. You'll leave with practical insights for building faster, more focused, and more maintainable test suites.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/3juU3JOIG3E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
</div>

**Speaker: Pandy Knight**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Pandy Knight Headshot](https://pretalx.com/media/avatars/8WV93W_PThO96W.webp){: width="150"}

</div>
<div markdown="1">

_Andrew Knight, also known as "Pandy," is the Automation Panda. He's a software quality champion who loves to help people build better quality software. Currently, he works as the Senior Director of Product Management at Cycle Labs, focusing on building an excellent test automation platform for enterprise systems. Previously, Pandy spent a decade as a SDET building solutions to testing problems at various tech companies. He also previously led Developer Relations and Test Automation University at Applitools. Apart from software, Pandy spends time with his family, his French Bulldog, and his vintage Volkswagens._

</div>
</div>

## Introducing Meow'py: Observability for the Internet of Living Things

Observability is the cornerstone of our modern distributed systems - if your app has services, having an observable system is crucial. But what if we applied the same logic to living things? This talk introduces my python-coded virtual cat, Meow'py, and basic functions of OpenTelemetry with Elastic Observability. I will show the basic data flow of my app, give a quick code deep dive, and present a demo of Meow'py enjoying his habitat (AKA eating, pooping, attempting escapes..) as his observability stats fluctuate in our Kibana dashboard. Attendees will leave with a greater understanding of OpenTelemetry, and learn the benefits of implementing observability to the internet of things, living or not.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/r2X48XuvRT4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
</div>

**Speaker: Sophia Solomon**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Sophia Solomon Headshot](https://pretalx.com/media/avatars/XGSEGN_CSCncDP.webp){: width="150"}

</div>
<div markdown="1">

_Hello, my name is Sophia! With a background in Biochemistry from UT Austin, I discovered a passion for coding in the DIY Diagnostics lab, where wet lab research and software development went hand in hand. After graduating in 2021, I began my career at GM as a Deployment Engineer/Analyst, later transitioning into a Software Engineering role observing real-time LLM based robotic systems on the plant floor. Now, as a Developer Advocate at Elastic, I draw on my experience optimizing and troubleshooting logs, traces, and metrics in high-stakes, in-plant production environments._

</div>
</div>

## Tying Up Loose Threads: Making your Project No-GIL Ready

If you, a project maintainer, want to support the free-threaded interpreter, but are unsure how, then this is for you! I'll show why ditching the GIL will yield extra performance, tips on making your compiled extensions compatible with the new ABI, and catching bugs as part of your automated workflows.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/Z43-0VII3QA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
</div>

**Speaker: Charlie Lin**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Charlie Lin Headshot](https://pretalx.com/media/avatars/CF8GNQ_bi6rPLz.webp){: width="150"}

</div>
<div markdown="1">

_Fervent open-source enthusiast, and (self-inflicted) daily driver of bleeding edge pre-release software on both Linux and Windows._

</div>
</div>

## Upgrading Python CLIs: From Scripts to Interactive Tools

Most Python command-line tools start simple: print statements, argument parsing, some "--help" outputs and some error handling. They work fine, but as they grow, they become harder to use and debug.

In this talk, we will show that we can do better than that, using libraries like Textual, Rich and Typer. We will cover the process to move from basic scripts into professional Terminal User Interfaces (TUIs) with interactive components, real-time updates and visual feedback. We will go over practical patterns for building tools that you can use for data processing, monitoring or config management.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/ZbAtJ4E9AGQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Resources**

- [Slides](https://github.com/ab93/building-cli-talk/blob/main/slides/slides.pdf)
- [Repo](https://github.com/ab93/shap-monitor)


</div>
</div>

**Speaker: [Avik Basu](https://www.linkedin.com/in/avik-basu/)**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Avik Basu Headshot](https://pretalx.com/media/avatars/Z7XLKH_Rey05Sy.webp){: width="150"}

</div>
<div markdown="1">

_Avik is a seasoned data scientist and software engineer passionate about writing elegant code and building intelligent systems that benefit humanity._

</div>
</div>

## Lint Fast, Type Hard: Elevate your code quality in Python with modern, ultra-fast tooling

Modern Python tooling has turned code quality into a speed advantage. This talk shows how ultra-fast linters, formatters, and type checkers—like Ruff and Pyrefly—remove the usual friction and make best practices feel effortless. You'll learn how to introduce these tools across engineering teams without disruption, why performance drives adoption, and how to build a workflow where quality checks become the fastest part of your day.

<div class="speaker-video-section" markdown="1">
<div class="video-wrapper">
<iframe src="https://www.youtube-nocookie.com/embed/chfwQqqofdI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
<div class="talk-links" markdown="1">

**Resources**

- [Slides](https://github.com/lmiguelvargasf/lint_fast_type_hard)
- [pre-commit](https://pre-commit.com/)
- [prek](https://prek.j178.dev)

</div>
</div>

**Speaker: Miguel Vargas**

<div class="speaker-middle" markdown="1">
<div markdown="1">

![Miguel Vargas Headshot](https://pretalx.com/media/avatars/KBMPUQ_Kzd91NX.webp){: width="150"}

</div>
<div markdown="1">

_Software engineer from Ecuador with over a decade of experience across healthcare, fintech, and real estate startups. I build with Python and TypeScript, focusing on Django, FastAPI, React, and Next.js. I'm driven by a deep interest in math, science, AI, and robotics._

</div>
</div>
