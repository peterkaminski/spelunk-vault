# Spelunk Vault System Guide

This guide explains how to effectively use the Spelunk Vault system for nonfiction book development, from initial research through final manuscript.

Spelunk Vault is an opinionated framework with specific recommendations and guidelines. Feel free to customize the framework to make it fit your project and its needs.

## Core Principles

The Spelunk Vault system is built on five foundational principles that guide its organization and use. **Clear Organization** ensures that every file has its place in the hierarchy, making it easy to locate materials regardless of project complexity. **Research Integrity** keeps sources, evidence, and citations traceable and well-documented throughout the writing process. **Iterative Development** supports the natural evolution of a nonfiction book from initial research through proposal, outline, drafts, and final manuscript. **Accessibility** provides easy navigation and cross-referencing through wikilinks and tags, allowing writers to quickly find related content. Finally, **Collaboration** enables smooth workflows between authors, editors, reviewers, fact-checkers, and other contributors.

## Key Components

The system consists of four key components working together. The **Folder Structure** organizes content by purpose and stage in the writing process, using a Johnny Decimal-inspired numbering system. The **Tagging System** enables cross-referencing and categorization of content across different areas of the vault. **Templates** maintain consistency across documents and provide starting points for common content types. **Workflows** establish standard processes for common tasks like moving content from research to manuscript or managing editorial review.

## Johnny Decimal Organization

Spelunk Vault uses a numbering system inspired by [Johnny Decimal](https://johnnydecimal.com/), a method for organizing projects using structured numeric prefixes.

### How Johnny Decimal Works in Spelunk Vault

In the Johnny Decimal system, every piece of information has a unique, predictable address. The system uses two levels of hierarchy:

- **Areas** are the broadest groupings, numbered in tens: `00`, `10`, `20`, `30`, etc. Each area represents a major phase or function of the book project.
- **Categories** are subfolders within each area. They group related content together without going too deep.

The key rules are:

1. **No more than ten areas** (00 through 99). This forces you to think broadly about what the major parts of your project really are.
2. **Keep folder depth shallow** — ideally 2-3 levels. Use tags and wikilinks for deeper connections instead of deeper nesting.
3. **Gaps are intentional** — the numbering jumps by tens (00, 10, 20, 30...) to leave room for future areas if needed.
4. **Every file has a home** — if you can't figure out where something goes, it's a signal that you may need a new category within an existing area.

### Spelunk Vault Areas at a Glance

| Area | Name | Purpose |
| :--- | :--- | :--- |
| **00** | Project Management | System docs, logs, meetings, schedules |
| **10** | Book Bible | Core reference: thesis, arguments, scope, audience |
| **20** | Research | Sources, interviews, field notes, bibliography |
| **30** | Development | Proposal, outlines, drafts, archive |
| **40** | Manuscript | Final chapters, front/back matter, style guide |
| **50** | Sources and Contacts | Expert profiles, correspondence, permissions |
| **60** | Team | Editor, reviewers, agent, publisher, fact-checking |
| **70** | Maps | Argument maps, concept maps, structure visualizations |
| **99** | Templates | Standard templates for consistency |

This numbering means you always know roughly where to look. Research materials? Start with `20-Research/`. Need to check who you've interviewed? Go to `50-Sources-and-Contacts/`. Looking for the latest chapter draft? Check `30-Development/` for works in progress or `40-Manuscript/` for finalized text.

## Getting Started

To begin using Spelunk Vault effectively, start by reviewing the tagging system in [[02-Tags]] to understand how content is categorized and cross-referenced. Familiarize yourself with the folder structure detailed in [[01-File-Structure]] to know where different types of content belong. When creating new content, use templates from `99-Templates/` to maintain consistency. Follow established workflows documented in [[03-Workflows]] for your specific role on the project.

## Navigation Tips

Effective navigation relies on several practices. Use tags for cross-referencing content across different areas of the vault. Link related documents using the double-square-bracket `[[Page Name]]` wikilink convention, which works seamlessly in Obsidian. Maintain the Book Bible in `10-Book-Bible/` as your canonical reference for the book's thesis, scope, and arguments. Keep your bibliography current in `20-Research/Bibliography/` as your single source of truth for citations. Track relationships between arguments, evidence, and chapters in `70-Maps/`.

## Nonfiction-Specific Considerations

Writing nonfiction requires special attention to research management and factual accuracy. Every claim in your manuscript should be traceable back to a source in `20-Research/`. Interview notes and correspondence with sources should be carefully documented in `50-Sources-and-Contacts/` for fact-checking purposes. Permissions for quoted material, images, or data must be tracked and secured before publication. The bibliography should be maintained continuously rather than assembled at the end.
