# Existing Codebase Documentation Prompts

These prompts are useful for entering an existing codebase that doesn't have a ton of documentation in it.

Each prompt is designed to output one or many .md documents. These serve as documentation, but can also help future LLM prompting, by helping the LLM mimic existing patterns, and reducing the amount of searching it has to do.

Files generated:
- overview.md - A high-level description of what this project is, and any important details to understand its context
- technologies.md - Lists the basic technologies used in this project, including programming languages and any important frameworks and libraries
- repo-structure.md - Defines the basic layout of the repository itself, including location of source code, tests, docs
- XXX-style-guide.md - A style guide for the given language or framework, defining things like formatting, naming conventions, and high-level coding patterns
    - NOTE: the prompt for generates a style-guide based on your existing codebase. If your codebase is inconsistent, the style guide may be off. It's recommended to review and edit the outupt. 
    - If you want opionated style guides, check out the 'style-guides' folder in this repo


