# Content Tagging System

This document outlines the standardized tagging system used throughout the vault. Tags help categorize, cross-reference, and track content across different areas of research, development, and manuscript production.

Each item should have at least one tag from each relevant category. Tags can be combined to create precise classifications of content.

## Source Status

Source status tags indicate the reliability and verification level of research materials.

- `#source/primary` - Original documents, firsthand accounts, raw data
- `#source/secondary` - Published analyses, books, articles by others
- `#source/tertiary` - Encyclopedias, textbooks, general references
- `#source/unverified` - Not yet fact-checked
- `#source/verified` - Fact-checked and confirmed
- `#source/disputed` - Conflicting accounts or contested claims

## Document Purpose

Document purpose tags identify the primary function of a file.

- `#doc/bible` - Book bible components
- `#doc/guide` - Guidelines and standards
- `#doc/map` - Argument or concept maps
- `#doc/timeline` - Chronological organization
- `#doc/profile` - Expert or interviewee profiles
- `#doc/manuscript` - Chapter manuscripts
- `#doc/outline` - Book or chapter outlines
- `#doc/note` - General notes
- `#doc/research` - Background research
- `#doc/proposal` - Book proposal materials
- `#doc/bibliography` - Citation and bibliography entries
- `#doc/interview` - Interview transcripts or notes
- `#doc/fieldnote` - Field observation notes

## Project Management

Project management tags track operational aspects of the book project.

- `#pm/todo` - Tasks to be done
- `#pm/meeting` - Meeting notes
- `#pm/decision` - Decision records
- `#pm/milestone` - Major project points
- `#pm/deadline` - Time-sensitive items
- `#pm/feedback` - Notes from reviews
- `#pm/workflow` - Process documentation
- `#pm/submission` - Agent/publisher submissions

## Development Stage

Development stage tags indicate where content is in the writing process.

- `#stage/concept` - Initial ideas and exploration
- `#stage/research` - Active research phase
- `#stage/outline` - Structural planning
- `#stage/draft` - Work in progress
- `#stage/revision` - Under revision
- `#stage/review` - Out for review
- `#stage/editing` - Editorial review
- `#stage/copyedit` - Copy editing pass
- `#stage/proofread` - Proofreading pass
- `#stage/final` - Approved for publication
- `#stage/archived` - Stored for reference

## Content Type

Content type tags categorize the subject matter of documents.

- `#type/argument` - Core arguments and claims
- `#type/evidence` - Supporting evidence
- `#type/narrative` - Storytelling and anecdotal material
- `#type/analysis` - Analytical content
- `#type/context` - Background and historical context
- `#type/data` - Quantitative information
- `#type/quote` - Notable quotations
- `#type/anecdote` - Stories and examples
- `#type/definition` - Key term definitions
- `#type/biography` - Biographical information about subjects
- `#type/methodology` - Methods and approaches

## Manuscript Status

Manuscript status tags track the publication readiness of content.

- `#ms/drafting` - Currently being written
- `#ms/revision` - Under revision
- `#ms/review` - Out for peer/expert review
- `#ms/editing` - With editor
- `#ms/copyedit` - In copy editing
- `#ms/final` - Finalized manuscript
- `#ms/published` - Published
- `#ms/on-hold` - Temporarily paused

## Team Area

Team area tags identify who is responsible for or should reference the content.

- `#team/author` - Author materials
- `#team/editor` - Editor notes and feedback
- `#team/reviewer` - Reviewer materials
- `#team/factcheck` - Fact-checking materials
- `#team/agent` - Agent-related materials
- `#team/publisher` - Publisher-related materials
- `#team/all` - Full team materials

## Research Type

Research type tags categorize the kind of research activity.

- `#research/literature` - Literature review materials
- `#research/interview` - Interview-based research
- `#research/field` - Field research and observation
- `#research/archival` - Archival research
- `#research/data` - Data collection and analysis
- `#research/expert` - Expert consultation

## Access Level

Access level tags control information sharing and privacy.

- `#access/public` - Shareable externally
- `#access/team` - Internal team only
- `#access/confidential` - Source-protected or sensitive material
- `#access/private` - Personal notes
- `#access/embargoed` - Not to be shared until a specific date

## Permissions Status

Permissions tags track the status of rights clearances.

- `#perm/needed` - Permission required but not yet requested
- `#perm/requested` - Permission request sent
- `#perm/granted` - Permission obtained
- `#perm/denied` - Permission refused
- `#perm/fairuse` - Fair use determination made
- `#perm/publicdomain` - Public domain material

## Chapter References

For tracking which chapters content relates to, use chapter reference tags.

- `#ch/01` - Chapter 1 content
- `#ch/02` - Chapter 2 content
- `#ch/03` - Chapter 3 content
- (extend as needed)
- `#ch/front` - Front matter
- `#ch/back` - Back matter
- `#ch/all` - Spans entire book

## Tag Usage Examples

A primary source document might use: `#source/primary #source/verified #doc/research #type/evidence #ch/03 #access/team`

A draft chapter might use: `#doc/manuscript #stage/draft #ms/drafting #ch/05 #access/team`

An interview transcript might use: `#doc/interview #source/primary #research/interview #type/quote #type/anecdote #access/confidential`

An argument map showing how evidence supports claims might use: `#doc/map #type/argument #type/evidence #ch/all #team/author`

A permission request for a quoted passage might use: `#doc/note #perm/requested #type/quote #ch/07 #team/author`
