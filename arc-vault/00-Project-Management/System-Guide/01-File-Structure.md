# Vault File Structure

This document outlines the complete folder and file structure of the vault. Standard files are included to demonstrate recommended organization.

```
Arc-Vault/
├── 00-Project-Management/
│   ├── System-Guide/
│   │   ├── 00-Introduction-to-Arc-Vault.md
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
│   │   └── Canon-Changes.md
│   ├── Schedules/
│   │   ├── Writing-Calendar.md
│   │   └── Milestones.md
│   └── Workflows/
│       ├── Writing-Process.md
│       └── Review-Process.md
│
├── 10-Series-Bible/
│   ├── Characters/
│   │   ├── Character-List.md
│   │   ├── Relationships.md
│   │   └── Character-Arcs.md
│   ├── World/
│   │   ├── World-Rules.md
│   │   ├── Locations.md
│   │   ├── Cultures.md
│   │   └── Technology.md
│   ├── Timeline/
│   │   ├── Series-Timeline.md
│   │   └── Historical-Events.md
│   ├── Magic-Systems/
│   │   ├── Magic-Rules.md
│   │   └── Power-Systems.md
│   └── Glossary/
│       ├── Terms.md
│       └── Naming-Conventions.md
│
├── 20-Development/
│   ├── Volumes/
│   │   └── Volume-00/
│   │       ├── Volume-Outline.md
│   │       └── Prototype-Canon.md
│   ├── Concepts/
│   │   ├── Story-Seeds.md
│   │   └── Worldbuilding-Ideas.md
│   ├── Outlines/
│   │   ├── Series-Arc.md
│   │   ├── Volume-Arcs.md
│   │   └── Chapter-Structures.md
│   ├── Drafts/
│   │   ├── Working-Drafts/
│   │   └── Review-Drafts/
│   └── Archive/
│       ├── Deprecated-Canon.md
│       └── Old-Versions/
│
├── 30-Manuscript/
│   ├── Volumes/
│   │   ├── Volume-01/
│   │   │   ├── Chapters/
│   │   │   │   ├── Chapter-01.md
│   │   │   │   ├── Chapter-02.md
│   │   │   │   └── ...
│   │   │   ├── Volume-Outline.md
│   │   │   ├── Arc-Summary.md
│   │   │   └── Continuity-Notes.md
│   │   ├── Volume-02/
│   │   │   ├── Chapters/
│   │   │   ├── Volume-Outline.md
│   │   │   ├── Arc-Summary.md
│   │   │   └── Continuity-Notes.md
│   │   └── Volume-03/
│   │       ├── Chapters/
│   │       ├── Volume-Outline.md
│   │       ├── Arc-Summary.md
│   │       └── Continuity-Notes.md
│   ├── Style-Guide/
│   │   ├── Writing-Style.md
│   │   └── Formatting-Guide.md
│   └── Editorial-Guidelines/
│       ├── Editorial-Standards.md
│       └── Review-Process.md
│
├── 40-Research/
│   ├── References/
│   │   ├── Genre-Analysis.md
│   │   └── Similar-Works.md
│   └── Resources/
│       ├── Technical-Details.md
│       └── Background-Info.md
│
├── 50-Team/
│   ├── Writing/
│   │   ├── Writer-Guides.md
│   │   └── Style-Notes.md
│   ├── Story/
│   │   ├── Arc-Planning.md
│   │   └── Plot-Threads.md
│   ├── Editorial/
│   │   ├── Editorial-Notes.md
│   │   └── Review-Guidelines.md
│   └── Continuity/
│       ├── Continuity-Checklist.md
│       └── Cross-Volume-Tracking.md
│
├── 60-Maps/
│   ├── Character-Maps/
│   │   ├── Relationship-Web.md
│   │   ├── Character-Arcs.md
│   │   └── Character-Growth.md
│   ├── Story-Maps/
│   │   ├── Plot-Threads.md
│   │   ├── Arc-Map.md
│   │   └── Volume-Connections.md
│   └── World-Maps/
│       ├── Location-Links.md
│       └── World-Connections.md
│
└── 99-Templates/
    ├── Basic-Note.md
    ├── Writing-Log-Template.md
    ├── Character-Templates/
    │   ├── Main-Character.md
    │   └── Supporting-Character.md
    ├── Volume-Templates/
    │   ├── Volume-Outline.md
    │   ├── Chapter-Template.md
    │   └── Arc-Summary.md
    └── Meeting-Templates/
        ├── Story-Meeting.md
        └── Editorial-Meeting.md
```

## Notes on Structure

### Numeric Prefixes

The numeric prefix system serves multiple purposes. It maintains logical order of folders, making navigation intuitive and predictable. The system allows for insertion of new sections if needed without disrupting the existing structure. The gaps in numbering (00, 10, 20, etc.) provide room for future expansion.

### Folder Organization

Each major section serves a specific purpose in the writing process. **Project Management (00-)** contains system documentation and operational files including guides, logs, and workflows. **Series Bible (10-)** holds core canonical content that defines the series world, characters, and rules. **Development (20-)** contains work in progress materials including concepts, outlines, and drafts. **Manuscript (30-)** houses active manuscript materials organized by volume with chapters and continuity notes. **Research (40-)** stores background materials and references that inform the writing. **Team (50-)** provides team-specific content organized by role. **Maps (60-)** contains visual organization tools for tracking relationships and arcs. **Templates (99-)** offers standard templates for consistency across documents.

### Volume Organization

Each volume folder in `30-Manuscript/Volumes/` follows a consistent structure. The `Chapters/` subdirectory contains individual chapter files. `Volume-Outline.md` provides the overall structure and pacing for the volume. `Arc-Summary.md` describes the narrative arcs that develop within this volume. `Continuity-Notes.md` tracks consistency with previous volumes and series bible.

### File Naming

File naming conventions ensure consistency and clarity. Use hyphens (-) for spaces in filenames to maintain compatibility across systems. Keep names clear and descriptive, avoiding abbreviations that might be unclear. Use consistent naming patterns within sections to make files easy to locate. For chapters, use zero-padded numbers like `Chapter-01.md` to ensure proper sorting.

### Depth

The structure maintains manageable complexity through depth limits. Keep folder hierarchies to a maximum of 3-4 levels deep to prevent navigation complexity. Achieve deeper organization through linking and tags rather than nested folders. Use the mapping system in `60-Maps/` to create conceptual organization beyond the file structure.

## Development vs Manuscript

Understanding the distinction between Development and Manuscript areas is crucial. **Development (20-)** is for work in progress, experimental content, and materials still being refined. Content here may change significantly and is not yet considered final. **Manuscript (30-)** contains materials that are ready for editorial review or have been finalized. Content here follows established canon and is organized for publication workflow.

Content typically moves from Development to Manuscript when it reaches a stable state and aligns with series canon. This transition is documented in writing logs and decision records.
