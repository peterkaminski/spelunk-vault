# Content Tagging System

This document outlines the standardized tagging system used throughout the vault. Tags help categorize, cross-reference, and track content across different areas of development and manuscript production.

Each item should have at least one tag from each relevant category. Tags can be combined to create precise classifications of content.

## Canon Status

Canon status tags indicate the authoritative level of content within the series universe.

- `#canon/core` - Main series, definitely canon
- `#canon/soft` - Supplementary but official
- `#canon/beta` - Development/testing material
- `#canon/deprecated` - Formerly canon, now superseded
- `#canon/proto` - Early worldbuilding that shaped canon
- `#canon/alt` - Alternate versions/timelines

## Document Purpose

Document purpose tags identify the primary function of a file.

- `#doc/bible` - Series bible components
- `#doc/guide` - Guidelines & standards
- `#doc/map` - Relationship or story maps
- `#doc/timeline` - Chronological organization
- `#doc/sheet` - Character/location sheets
- `#doc/manuscript` - Volume/chapter manuscripts
- `#doc/outline` - Story outlines
- `#doc/note` - General notes
- `#doc/research` - Background research

## Project Management

Project management tags track operational aspects of the writing project.

- `#pm/todo` - Tasks to be done
- `#pm/meeting` - Meeting notes
- `#pm/decision` - Decision records
- `#pm/milestone` - Major project points
- `#pm/deadline` - Time-sensitive items
- `#pm/feedback` - Notes from reviews
- `#pm/workflow` - Process documentation

## Development Stage

Development stage tags indicate where content is in the writing process.

- `#stage/concept` - Initial ideas
- `#stage/outline` - Story structure
- `#stage/draft` - Work in progress
- `#stage/revision` - Under revision
- `#stage/editing` - Editorial review
- `#stage/final` - Approved/published
- `#stage/archived` - Stored for reference

## Content Type

Content type tags categorize the subject matter of documents.

- `#type/worldbuild` - Setting/universe rules
- `#type/character` - Character details
- `#type/plot` - Story events
- `#type/arc` - Multi-volume story arcs
- `#type/mechanics` - System rules (magic, tech, etc.)
- `#type/lore` - Background history
- `#type/timeline` - Chronological events
- `#type/style` - Writing style guides
- `#type/glossary` - Terminology definitions
- `#type/continuity` - Cross-volume continuity

## Manuscript Status

Manuscript status tags track the publication readiness of content.

- `#ms/drafting` - Currently being written
- `#ms/revision` - Under revision
- `#ms/editing` - With editor
- `#ms/final` - Finalized manuscript
- `#ms/published` - Published volume
- `#ms/reference` - Kept for reference
- `#ms/on-hold` - Temporarily paused

## Team Area

Team area tags identify which team is responsible for or should reference the content.

- `#team/writing` - Writing team materials
- `#team/story` - Story team materials
- `#team/editorial` - Editorial team notes
- `#team/continuity` - Continuity checking
- `#team/all` - Full team materials

## Access Level

Access level tags control information sharing and privacy.

- `#access/public` - Shareable externally
- `#access/team` - Internal team only
- `#access/restricted` - Limited access
- `#access/private` - Personal notes

## Version Control

Version control tags track the significance of changes.

- `#ver/major` - Significant canon changes
- `#ver/minor` - Small updates/tweaks
- `#ver/patch` - Corrections/clarifications

## Volume References

For multi-volume tracking, use volume reference tags to indicate which volumes are relevant to the content.

- `#vol/00` - Prototype/prequel material
- `#vol/01` - Volume 1 content
- `#vol/02` - Volume 2 content
- `#vol/03` - Volume 3 content
- `#vol/series` - Spans entire series

## Tag Usage Examples

A character sheet for a main character might use: `#doc/sheet #type/character #canon/core #vol/series #access/team`

A draft chapter from Volume 2 might use: `#doc/manuscript #stage/draft #ms/drafting #vol/02 #access/team`

A plot thread tracking document spanning multiple volumes might use: `#doc/map #type/plot #type/arc #vol/series #team/story #access/team`

A continuity note for Volume 3 referencing earlier volumes might use: `#doc/note #type/continuity #vol/03 #vol/01 #vol/02 #team/continuity #access/team`
