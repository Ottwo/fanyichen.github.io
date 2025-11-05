---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a third year undergraduate student from [College of CIS](https://cis.swu.edu.cn/), [Southwest University](https://www.swu.edu.cn/). My research interest includes computer vision, computer graphics, machine learning, and computational photography.Besides, as a fan of leading edge technology,I has already taken aim at agent field and get ready for struggling for state-of-the-art!



Hello everyone!I'm Fan Yichen.Nice to meet you all!
======
Fan Yichen is a dedicated third-year undergraduate student deeply fascinated by the frontier of artificial intelligence. His academic focus lies at the intersection of ​​deep learning​​, ​​continual learning​​, and the development of autonomous AI agents. He is particularly interested in how intelligent systems can progressively acquire, refine, and utilize knowledge over time without succumbing to ​​catastrophic forgetting​​, a primary challenge in continual learning where learning new information interferes with previously retained knowledge
.
A significant part of his interest involves the architecture and capabilities of ​​AI Agents​​—systems that can perceive their environment, make decisions, and take actions to achieve specific goals
. He is exploring how these agents can be designed to learn continuously from their interactions with dynamic environments, moving beyond static, task-specific models towards more general and adaptable intelligence. This exploration naturally extends to the ​​Model Context Protocol (MCP)​​, which he understands as a pivotal framework for enabling large language models (LLMs) to connect seamlessly with external data sources, tools, and services
. He is keen on understanding how MCP functions as a standardized "USB-C interface for AI," facilitating the flexible tool-use and context-aware capabilities that are essential for building more powerful and practical AI agents
.
His current conceptual work involves investigating various methodologies to achieve effective continual learning. This includes studying ​​regularization-based approaches​​ that constrain parameter updates to protect old knowledge, ​​replay-based methods​​ that rehearse past experiences, and ​​architectural strategies​​ that dynamically allocate or modularize network components to accommodate new skills
. He is also intrigued by the potential of leveraging large-scale pre-trained ​​foundation models​​ as a base to reduce forgetting and improve knowledge transfer in continual learning scenarios
.
Looking forward, he aims to deepen his practical understanding by applying these concepts to tangible problems. Potential areas of application include optimizing workflows or developing adaptive systems that can operate in complex, evolving environments. Through his ongoing coursework and self-directed study, he is building a solid foundation in the core principles of deep neural networks, reinforcement learning, and the system design thinking required to contribute to the advancement of lifelong learning machines.

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
