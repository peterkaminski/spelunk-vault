# System Workflows

## Adding New Content

When adding new content to the vault, follow a consistent process to maintain organization. First, choose the appropriate folder location based on the content type and development stage. Use the relevant template from `99-Templates/` as your starting point to ensure consistency. Apply appropriate tags from the tagging system to enable cross-referencing. Link to related content using wikilinks to build connections across the vault. Finally, update relevant indices or maps to reflect the new content.

## Updating Canon

Canon changes require careful documentation to maintain series consistency. Begin by tagging existing content as `#canon/deprecated` to indicate it has been superseded. Create the new canonical version with appropriate `#canon/core` or `#canon/soft` tags. Update all Series Bible references that relate to the changed content. Record the change in the Decision Log with rationale and date. Update relevant maps, timelines, and continuity notes to reflect the new canon. Check all volumes for content that might conflict with the canon change.

## Development to Manuscript

Moving content from development to manuscript status follows a structured process. Move the content from `20-Development/` to the appropriate location in `30-Manuscript/`. Update tags from `#canon/beta` to `#canon/core` and from `#stage/draft` to `#stage/final` or appropriate manuscript stage. Archive prototype or draft versions in `20-Development/Archive/`. Update all related documentation including outlines, arc summaries, and continuity notes. Record the transition in project logs with date and any relevant notes.

## Volume Development Workflow

Developing a new volume follows a multi-stage process. Begin with concept development in `20-Development/Concepts/` where initial ideas are explored. Create a volume outline in `20-Development/Outlines/` that structures the narrative. Draft chapters in `20-Development/Volumes/Volume-XX/` during the writing phase. Move completed drafts to `30-Manuscript/Volumes/Volume-XX/` when ready for editorial review. Conduct editorial review and revision within the manuscript folder. Finalize the manuscript and update all continuity notes and series bible entries as needed.

## Character Arc Tracking

Character arcs spanning multiple volumes require systematic tracking. Document the overall character arc in `60-Maps/Character-Maps/Character-Arcs.md` showing development across the series. Create or update character sheets in `10-Series-Bible/Characters/` with canonical information. Note volume-specific character development in each volume's `Arc-Summary.md` file. Link character moments across volumes using wikilinks and tags. Update relationship maps in `60-Maps/Character-Maps/Relationship-Web.md` as relationships evolve.

## Plot Thread Management

Plot threads often span multiple volumes and need careful management. Create plot thread entries in `60-Maps/Story-Maps/Plot-Threads.md` with setup, development, and resolution notes. Tag plot thread documents with relevant volume tags to show which volumes the thread appears in. Link plot threads to specific chapters where key developments occur. Update the series arc document in `20-Development/Outlines/Series-Arc.md` to show how threads contribute to the overall story. Mark threads as resolved when completed and note the resolution location.

## Continuity Checking

Maintaining continuity across volumes requires regular checking and documentation. Before finalizing each volume, review the Series Bible for canonical information. Check character details, world rules, and timeline consistency. Document any potential conflicts in the volume's `Continuity-Notes.md` file. Cross-reference with previous volumes using the continuity checklist in `50-Team/Continuity/`. Update the series timeline in `10-Series-Bible/Timeline/` with new events. Create continuity notes for future volumes if needed.

## Archiving Content

When content is no longer current but should be preserved, follow the archiving workflow. Move content to the appropriate Archive folder in `20-Development/Archive/`. Update tags to reflect archived status using `#stage/archived` and `#canon/deprecated` if applicable. Maintain links to replacement content so the evolution can be traced. Update related documentation to point to current versions. Record the archiving action in change logs with date and reason.

## Writing Logs

Writing logs provide a record of progress and decisions. Create a dated log file in `00-Project-Management/Writing-Logs/` using the format `YYYY-MM-DD-[Writer/Team]-Log.md`. Tag with appropriate tags: `#pm/workflow`, `#team/writing`, `#doc/note`. Include session goals, progress updates, challenges encountered, and next steps. Link to any related content or documents referenced during the session. For AI assistant logs, include prompt details and generation settings used.

## Review and Feedback Process

The review process ensures quality and consistency across the series. Submit content for review by moving it to the appropriate manuscript location and tagging with `#stage/review`. Reviewers add feedback using the `#pm/feedback` tag in comments or separate feedback documents. The writer addresses feedback and updates the content, documenting changes in the file's change log. Once approved, update the stage tag to `#stage/final` and record the approval in the Decision Log. Update any affected continuity notes or series bible entries based on review outcomes.
