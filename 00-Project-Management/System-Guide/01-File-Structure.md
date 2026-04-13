# Vault File Structure

This document outlines the complete folder and file structure of the vault. Standard files are included to demonstrate recommended organization.

```
Spelunk-Vault/
├── 00-Project-Management/
│   ├── System-Guide/
│   │   ├── 00-Introduction-to-Spelunk-Vault.md
│   │   ├── 01-File-Structure.md
│   │   ├── 02-Tags.md
│   │   └── 03-Workflows.md
│   ├── Writing-Logs/
│   │   ├── 00-Writing-Logs-Guide.md
│   │   └── YYYY-MM-DD-Writer-Log.md
│   ├── Meetings/
│   │   ├── Meeting-Log.md
│   │   └── Action-Items.md
│   ├── Decisions/
│   │   ├── Decision-Log.md
│   │   └── Scope-Changes.md
│   ├── Schedules/
│   │   ├── Writing-Calendar.md
│   │   └── Milestones.md
│   └── Workflows/
│       ├── Writing-Process.md
│       └── Review-Process.md
│
├── 10-Book-Bible/
│   ├── Thesis/
│   │   ├── Thesis-Statement.md
│   │   └── Core-Argument.md
│   ├── Key-Arguments/
│   │   ├── Argument-List.md
│   │   └── Evidence-Summary.md
│   ├── Audience/
│   │   ├── Target-Reader.md
│   │   └── Comparable-Titles.md
│   ├── Timeline/
│   │   ├── Subject-Timeline.md
│   │   └── Historical-Context.md
│   └── Glossary/
│       ├── Terms.md
│       └── Abbreviations.md
│
├── 20-Research/
│   ├── Primary-Sources/
│   │   ├── Source-Index.md
│   │   └── [individual source notes]
│   ├── Secondary-Sources/
│   │   ├── Source-Index.md
│   │   └── [individual source notes]
│   ├── Interviews/
│   │   ├── Interview-Index.md
│   │   └── [individual interview transcripts/notes]
│   ├── Field-Notes/
│   │   └── [dated field notes]
│   ├── Data/
│   │   ├── Data-Index.md
│   │   └── [datasets, charts, analysis notes]
│   └── Bibliography/
│       ├── Master-Bibliography.md
│       ├── Annotated-Bibliography.md
│       └── Citation-Style-Guide.md
│
├── 30-Development/
│   ├── Proposal/
│   │   ├── Book-Proposal.md
│   │   ├── Chapter-Summaries.md
│   │   ├── Author-Bio.md
│   │   ├── Market-Analysis.md
│   │   └── Sample-Chapters.md
│   ├── Outlines/
│   │   ├── Book-Outline.md
│   │   ├── Chapter-Plans/
│   │   │   ├── Chapter-01-Plan.md
│   │   │   └── ...
│   │   └── Structural-Options.md
│   ├── Drafts/
│   │   ├── Working-Drafts/
│   │   └── Review-Drafts/
│   └── Archive/
│       ├── Deprecated-Outlines.md
│       └── Old-Versions/
│
├── 40-Manuscript/
│   ├── Front-Matter/
│   │   ├── Title-Page.md
│   │   ├── Dedication.md
│   │   ├── Epigraph.md
│   │   ├── Table-of-Contents.md
│   │   ├── Foreword.md
│   │   ├── Preface.md
│   │   ├── Acknowledgments.md
│   │   └── Introduction.md
│   ├── Chapters/
│   │   ├── Chapter-01.md
│   │   ├── Chapter-02.md
│   │   └── ...
│   ├── Back-Matter/
│   │   ├── Appendices.md
│   │   ├── Endnotes.md
│   │   ├── Bibliography.md
│   │   ├── Index-Notes.md
│   │   └── About-the-Author.md
│   ├── Style-Guide/
│   │   ├── Writing-Style.md
│   │   ├── Formatting-Guide.md
│   │   └── Voice-and-Tone.md
│   └── Editorial-Guidelines/
│       ├── Editorial-Standards.md
│       └── Review-Process.md
│
├── 50-Sources-and-Contacts/
│   ├── Experts/
│   │   ├── Expert-Directory.md
│   │   └── [individual expert profiles]
│   ├── Interviewees/
│   │   ├── Interviewee-Directory.md
│   │   └── [individual interviewee profiles]
│   ├── Correspondence/
│   │   ├── Correspondence-Log.md
│   │   └── [email/letter records]
│   └── Permissions/
│       ├── Permissions-Tracker.md
│       ├── Quote-Permissions/
│       ├── Image-Permissions/
│       └── Data-Permissions/
│
├── 60-Team/
│   ├── Editor/
│   │   ├── Editor-Notes.md
│   │   └── Editorial-Calendar.md
│   ├── Reviewers/
│   │   ├── Reviewer-List.md
│   │   ├── Review-Assignments.md
│   │   └── Feedback-Summary.md
│   ├── Agent/
│   │   ├── Agent-Notes.md
│   │   └── Submission-Tracker.md
│   ├── Publisher/
│   │   ├── Publisher-Notes.md
│   │   └── Contract-Notes.md
│   └── Fact-Checking/
│       ├── Fact-Check-Log.md
│       ├── Verification-Checklist.md
│       └── Corrections.md
│
├── 70-Maps/
│   ├── Argument-Maps/
│   │   ├── Main-Argument-Map.md
│   │   └── Chapter-Argument-Maps.md
│   ├── Concept-Maps/
│   │   ├── Key-Concepts.md
│   │   └── Concept-Relationships.md
│   ├── Structure-Maps/
│   │   ├── Book-Architecture.md
│   │   └── Chapter-Flow.md
│   └── Evidence-Maps/
│       ├── Evidence-to-Argument.md
│       └── Source-Coverage.md
│
└── 99-Templates/
    ├── Basic-Note.md
    ├── Writing-Log-Template.md
    ├── Chapter-Templates/
    │   ├── Chapter-Draft.md
    │   └── Chapter-Plan.md
    ├── Research-Templates/
    │   ├── Source-Note.md
    │   ├── Interview-Note.md
    │   ├── Field-Note.md
    │   └── Annotated-Source.md
    ├── Contact-Templates/
    │   ├── Expert-Profile.md
    │   ├── Interviewee-Profile.md
    │   └── Permission-Request.md
    └── Meeting-Templates/
        ├── Editorial-Meeting.md
        └── Research-Meeting.md
```

## Notes on Structure

### Johnny Decimal Numbering

The numeric prefix system follows a Johnny Decimal-inspired approach. Top-level folders are **areas**, numbered in tens (00, 10, 20, ..., 99). This maintains logical order, makes navigation intuitive, and leaves room for expansion. The gaps between numbers (00, 10, 20, etc.) are intentional — they allow new areas to be inserted without renumbering existing ones. For more on how this system works, see [[00-Introduction-to-Spelunk-Vault]].

### Folder Organization

Each major section serves a specific purpose in the nonfiction writing process. **Project Management (00-)** contains system documentation and operational files including guides, logs, and workflows. **Book Bible (10-)** holds the core reference materials that define the book's thesis, arguments, audience, and scope. **Research (20-)** is the backbone of the nonfiction process, housing primary and secondary sources, interviews, field notes, data, and the bibliography. **Development (30-)** contains work in progress materials including the book proposal, outlines, and drafts. **Manuscript (40-)** houses finalized manuscript materials organized into front matter, chapters, and back matter. **Sources and Contacts (50-)** manages relationships with experts, interviewees, and tracks permissions for quoted material. **Team (60-)** provides space for editor, reviewer, agent, and publisher coordination. **Maps (70-)** contains visual organization tools for tracking arguments, concepts, and evidence flow. **Templates (99-)** offers standard templates for consistency across documents.

### Research Organization

The `20-Research/` area is deliberately expansive because research is the foundation of nonfiction writing. Primary sources (original documents, data, firsthand accounts) are separated from secondary sources (books, articles, analyses by others) to maintain clarity about the evidentiary basis of your work. The bibliography in `20-Research/Bibliography/` is your working bibliography — the finalized version for publication goes in `40-Manuscript/Back-Matter/Bibliography.md`.

### Development vs Manuscript

Understanding the distinction between Development and Manuscript areas is crucial. **Development (30-)** is for work in progress, experimental structures, and materials still being refined. Content here may change significantly and is not yet considered final. **Manuscript (40-)** contains materials that are ready for editorial review or have been finalized. Content moves from Development to Manuscript when it reaches a stable, reviewed state.

### File Naming

File naming conventions ensure consistency and clarity. Use hyphens (-) for spaces in filenames to maintain compatibility across systems. Keep names clear and descriptive, avoiding abbreviations that might be unclear. Use consistent naming patterns within sections to make files easy to locate. For chapters, use zero-padded numbers like `Chapter-01.md` to ensure proper sorting.

### Depth

The structure maintains manageable complexity through depth limits. Keep folder hierarchies to a maximum of 3-4 levels deep to prevent navigation complexity. Achieve deeper organization through linking and tags rather than nested folders. Use the mapping system in `70-Maps/` to create conceptual organization beyond the file structure.
