# CLAUDE.md - Spelunk Vault Guidelines

_This file provides Claude Code with context and instructions about this repo. It may be helpful for human writers and other AI systems as well._

## About This Project

This is a text-based project management system for nonfiction book development. The system is used for organizing research, source materials, manuscript drafts, and publication workflow. It is built for use with Obsidian.md and Massive Wiki, with all content organized hierarchically using a Johnny Decimal-inspired numbered prefix system.

Spelunk Vault is a sibling framework to [Arc Vault](https://github.com/peterkaminski/arc-vault) (multi-volume novels) and [Prisma Vault](https://github.com/peterkaminski/prisma-vault) (serialized fiction), adapted for nonfiction book writing.

## File Structure

The vault is organized into numbered areas that reflect the nonfiction writing lifecycle:

- `00-Project-Management/`: System documentation, writing logs, meetings, decisions, schedules, workflows
- `10-Book-Bible/`: Core reference: thesis, key arguments, audience, timeline, glossary
- `20-Research/`: Primary sources, secondary sources, interviews, field notes, data, bibliography
- `30-Development/`: Book proposal, outlines, drafts, archive
- `40-Manuscript/`: Final chapters, front matter, back matter, style guide, editorial guidelines
- `50-Sources-and-Contacts/`: Expert profiles, interviewee records, correspondence, permissions
- `60-Team/`: Editor, reviewers, agent, publisher, fact-checking
- `70-Maps/`: Argument maps, concept maps, structure maps, evidence maps
- `99-Templates/`: Standard templates for consistency

## Tagging System

Use the standard tags from `00-Project-Management/System-Guide/02-Tags.md`:

- Source status tags: `#source/primary`, `#source/secondary`, `#source/verified`, etc.
- Document purpose tags: `#doc/bible`, `#doc/manuscript`, `#doc/interview`, `#doc/proposal`, etc.
- Project management tags: `#pm/todo`, `#pm/meeting`, `#pm/decision`, etc.
- Development stage tags: `#stage/concept`, `#stage/research`, `#stage/draft`, `#stage/editing`, etc.
- Content type tags: `#type/argument`, `#type/evidence`, `#type/narrative`, `#type/data`, etc.
- Manuscript status tags: `#ms/drafting`, `#ms/revision`, `#ms/editing`, `#ms/final`, etc.
- Research type tags: `#research/literature`, `#research/interview`, `#research/field`, etc.
- Permissions tags: `#perm/needed`, `#perm/requested`, `#perm/granted`, etc.
- Chapter reference tags: `#ch/01`, `#ch/02`, `#ch/front`, `#ch/back`, etc.

## Writing Logs

All writing logs are stored in `00-Project-Management/Writing-Logs/` with the filename format `YYYY-MM-DD-[Writer/Team]-Log.md`. Use the template from `99-Templates/Writing-Log-Template.md` and include appropriate tags and links to related content.

## File Naming Conventions

File names should use hyphens (-) for spaces and be clear and descriptive. Use consistent naming patterns within sections and maintain a maximum depth of 3-4 levels to prevent complexity. Link related documents using the double-square-bracket `[[Page Name]]` wikilink convention without specifying directory paths. Use names that are unique across the repo.

## Content Creation Guidelines

When creating new content, follow these practices:

1. Use existing templates from `99-Templates/` when creating new content
2. Create new templates in `99-Templates/` as necessary
3. Follow the established tagging system to maintain organization
4. Create links between related documents
5. Keep files organized according to their purpose and stage
6. Update relevant indices or maps when adding new content
7. For writing logs, follow the workflow in `00-Project-Management/System-Guide/03-Workflows.md`
8. Add every source to `20-Research/Bibliography/Master-Bibliography.md` immediately upon discovery

## Research Management

Spelunk Vault emphasizes rigorous research tracking for nonfiction:

- Every factual claim in the manuscript should be traceable to a source in `20-Research/`
- Primary and secondary sources are separated for clarity about evidentiary basis
- Interviews are documented with attribution preferences and consent records
- The bibliography is maintained continuously, not assembled at the end
- Permissions for quoted material are tracked in `50-Sources-and-Contacts/Permissions/`

## Manuscript Organization

The manuscript in `40-Manuscript/` is organized into:

- `Front-Matter/`: Title page, dedication, epigraph, table of contents, foreword, preface, acknowledgments, introduction
- `Chapters/`: Individual chapter files, numbered sequentially
- `Back-Matter/`: Appendices, endnotes, bibliography, index notes, about the author
- `Style-Guide/`: Writing style, formatting, and voice/tone conventions
- `Editorial-Guidelines/`: Standards and review process

## Workflow Commands

This is a text-based project with no build, test, or lint commands. Use Obsidian or text editors to create and edit content. For version control with Git:

- `git status`: Check changes
- `git add [files]`: Stage changes
- `git commit -m "message"`: Commit changes
- `git push`: Push to remote repository (if using Git for team collaboration)

## Style Preferences

Content should use Markdown formatting with a blank line between different types of content blocks such as headers and bullet lists. Create clear hierarchical structure with headings, use bullet points for lists, link related documents liberally, and tag documents according to the established system. Use the numeric prefixing system for new folders and follow established workflows for updating content.
