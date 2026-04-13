# CLAUDE.md - Arc Vault Guidelines

_This file provides Claude Code with context and instructions about this repo. It may be helpful for human writers and other AI systems as well._

## About This Project

This is a text-based project management system for multi-volume novel series development. The system is used for organizing series bible, manuscript materials, and development content. It is built for use with Obsidian.md and Massive Wiki, with all content organized hierarchically using numbered prefixes.

Arc Vault is adapted from [Prisma Vault](https://github.com/peterkaminski/prisma-vault) for novel writing rather than serialized fiction.

## File Structure

The vault is organized into numbered sections that reflect the novel development lifecycle:

- `00-Project-Management/`: System documentation and operational files
- `10-Series-Bible/`: Core canonical content for the entire series
- `20-Development/`: Work in progress materials (concepts, outlines, drafts)
- `30-Manuscript/`: Active manuscript materials organized by volume
- `40-Research/`: Background and reference materials
- `50-Team/`: Team-specific resources
- `60-Maps/`: Visual organization tools for tracking arcs, characters, and plots
- `99-Templates/`: Standard templates for consistency

## Tagging System

Use the standard tags from `00-Project-Management/System-Guide/02-Tags.md`:

- Canon status tags: `#canon/core`, `#canon/soft`, etc.
- Document purpose tags: `#doc/bible`, `#doc/manuscript`, `#doc/outline`, etc.
- Project management tags: `#pm/todo`, `#pm/meeting`, etc.
- Development stage tags: `#stage/concept`, `#stage/draft`, `#stage/revision`, `#stage/editing`, etc.
- Content type tags: `#type/worldbuild`, `#type/character`, `#type/arc`, etc.
- Manuscript status tags: `#ms/drafting`, `#ms/revision`, `#ms/editing`, `#ms/final`, etc.

## Writing Logs

All writing logs are stored in `00-Project-Management/Writing-Logs/` with the filename format `YYYY-MM-DD-[Writer/Team]-Log.md`. Use the template from `99-Templates/Writing-Log-Template.md` and include appropriate tags and links to related content.

## File Naming Conventions

File names should use hyphens (-) for spaces and be clear and descriptive. Use consistent naming patterns within sections and maintain a maximum depth of 3-4 levels to prevent complexity. Link related documents using the double-square-bracket `[[Page Name]]` wikilink convention without specifying directory paths. Use names that are unique across the repo.

## Content Creation Guidelines

When creating new content, follow these practices:

1. Use existing templates from `99-Templates/` when creating new content
2. Create new templates in 99-Templates/ as necessary
3. Follow the established tagging system to maintain organization
4. Create links between related documents
5. Keep files organized according to their purpose and stage
6. Update relevant indices or maps when adding new content
7. For writing logs, follow the workflow in `00-Project-Management/System-Guide/03-Workflows.md`

## Volume and Chapter Organization

Each volume in `30-Manuscript/Volumes/` should contain:

- A `Chapters/` subdirectory for chapter files
- `Volume-Outline.md` for overall structure
- `Arc-Summary.md` for narrative arcs in this volume
- `Continuity-Notes.md` for tracking consistency

## Continuity Tracking

Arc Vault emphasizes continuity across volumes. When working with multi-volume content:

- Track character arcs in `60-Maps/Character-Maps/`
- Track plot threads in `60-Maps/Story-Maps/Plot-Threads.md`
- Maintain series timeline in `10-Series-Bible/Timeline/`
- Use continuity notes in each volume's folder
- Tag content with volume references for easy cross-referencing

## Workflow Commands

This is a text-based project with no build, test, or lint commands. Use Obsidian or text editors to create and edit content. For version control with Git:

- `git status`: Check changes
- `git add [files]`: Stage changes
- `git commit -m "message"`: Commit changes
- `git push`: Push to remote repository (if using Git for team collaboration)

## Style Preferences

Content should use Markdown formatting with a blank line between different types of content blocks such as headers and bullet lists. Create clear hierarchical structure with headings, use bullet points for lists, link related documents liberally, and tag documents according to the established system. Use the numeric prefixing system for new folders and follow established workflows for updating content.
