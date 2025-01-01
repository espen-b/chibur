# Chibur
Chibur is an open-source, modular platform that unites modern data science with centuries of Jewish textual wisdom. Designed to seamlessly plug into a variety of text sources and analytical workflows, Chibur helps you explore, analyze, and uncover new insights in Hebrew texts—from Torah and Talmud to Midrashic literature and beyond.

# What is Chibur?

Chibur (Hebrew for “connection”) aims to bridge the gap between cutting-edge computational approaches—like NLP, machine learning, and data visualization—and the rich tapestry of Jewish texts. By fostering a plug-and-play ecosystem of “plugins,” developers can add new functionality without rewriting the core engine or refactoring existing code.

Whether you're interested in Gematria (numerological analysis), linguistic research, graph-based exploration, or simply want to experiment with Hebrew LLMs, Chibur gives you a robust foundation to build upon.

# Key Features

Plugin-Based Design
Easily create or add new data-ingestion, analysis, or reporting modules.
No need to alter the core—just drop your plugin into the correct directory.
Flexible Text Workflow
Supports both “raw” and “processed” text outputs for maximum clarity and debugging.
Chain multiple plugins for a complete pipeline: ingestion → analysis → reporting.
Topological or Linear Execution
Topological: let Chibur automatically detect dependencies and order your plugins.
Linear: manually define an exact sequence of steps for more controlled pipelines.
Rich Ecosystem
Out-of-the-box input plugins for local files, Sefaria references, and custom sources.
Analysis examples include Gematria, NLP tasks, and more.
Reporting plugins that generate Markdown, PDF, or visual analytics.
Open for Collaboration
Built by a community of technologists, rabbis, data scientists, and passionate learners.
We welcome new contributors, whether to fix bugs, add features, or propose entirely new directions.

Quick Start

- Clone this repository

- git clone https://github.com/username/chibur.git

- cd chibur

- Install dependencies:

- pip install -r requirements.txt

- Explore the example plugins in plugins/.

- Run the app in your environment—this might be: python main.py or a Docker-based environment if you prefer containers.

- Dive In: Check out the Plugin Development Guide to learn how to add your own plugins.

# Plugin-Driven Architecture

Chibur’s architecture makes it easy to drop new files into plugins/input/active, plugins/analysis/active, or plugins/report/active, and they’ll automatically be discovered and run. No system-wide modifications required.

We encourage you to:

Create a new plugin for specialized text ingestion (like an API or local database).
Experiment with advanced analysis (machine learning, AI-based commentary, named-entity recognition).
Generate beautiful or interactive reports (Markdown, PDF, dashboards).
Contributing

We’d love for you to join our mission of merging data science with timeless texts. Here’s how you can get involved:

-Fork this repository and submit a pull request with your new plugin, bug fix, or enhancement.

-Open Issues if you have questions or suggestions.

-Discuss bigger features or architectural changes in Discussions or Slack.
If you’re unsure where to start, ask us how you can help—chances are there’s a piece of Chibur that needs your creativity!

# License

This project is licensed under GPL—see the LICENSE file for details.

# Thank You
Thank you for your interest in Chibur! We hope this platform inspires new ways to engage with and learn from our collective textual heritage. If you have ideas or want to contribute, please don’t hesitate to get involved—together, let’s build a better future for Jewish text exploration and discovery.
