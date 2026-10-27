---
title: "SoMem — Self-Organized Document Memory"
excerpt: "Persistent agent memory built from editable Markdown documents with references to immutable conversation records. Separate Writer and Reader roles organize and retrieve evidence.<br/><a href='https://github.com/Qi202/SoMem'>GitHub</a>"
collection: portfolio
---

**[GitHub](https://github.com/Qi202/SoMem)**

SoMem provides persistent, document-based memory for agents. It separates immutable conversation records, editable semantic documents, and bounded context supplied before search.

A Writer organizes and revises Markdown documents with stable references to source evidence. Deterministic validation checks document structure and references before accepting edits and rebuilding access views. A Reader chooses which documents to search and read, and can return to the original records when needed.

The framework supports lexical and semantic retrieval, workspace validation, agent adapters, and MCP integration. Writer and Reader roles can use the same model or separate models sharing a workspace.

The public repository contains the framework and selected offline integrity tests; benchmark data, experimental configurations, and evaluation results are not included.
