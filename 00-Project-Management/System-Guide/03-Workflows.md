# System Workflows

## Adding New Content

When adding new content to the vault, follow a consistent process to maintain organization. First, choose the appropriate folder location based on the content type and development stage. Use the relevant template from `99-Templates/` as your starting point to ensure consistency. Apply appropriate tags from the tagging system to enable cross-referencing. Link to related content using wikilinks to build connections across the vault. Finally, update relevant indices or maps to reflect the new content.

## Research Workflow

Research is the backbone of nonfiction writing and follows a structured process. Begin by identifying the type of source — primary, secondary, or tertiary — and file it in the appropriate subfolder of `20-Research/`. Create a source note using the [[Source-Note]] template, capturing full bibliographic information immediately. Tag with appropriate `#source/` and `#research/` tags. Add the source to [[Master-Bibliography]] right away — don't wait until the end. As you read, create annotations using the [[Annotated-Source]] template. Link source notes to relevant arguments in `10-Book-Bible/Key-Arguments/` and to any chapters where the material will be used.

## Interview Workflow

Interviews require careful documentation for both accuracy and ethics. Before the interview, create an interviewee profile in `50-Sources-and-Contacts/Interviewees/` using the [[Interviewee-Profile]] template. Confirm permissions and attribution preferences — will they be named, anonymous, or on background? During or immediately after the interview, create interview notes in `20-Research/Interviews/` using the [[Interview-Note]] template. Tag with `#doc/interview #source/primary #research/interview`. Log the correspondence in `50-Sources-and-Contacts/Correspondence/`. Link the interview notes to the interviewee profile and to any chapters where the material will be used.

## Bibliography Management

Maintain the bibliography as a living document throughout the project. Add every source to [[Master-Bibliography]] as soon as you encounter it. Use the citation format specified in [[Citation-Style-Guide]] for consistency. The [[Annotated-Bibliography]] provides space for notes about each source's relevance and reliability. When the manuscript is finalized, compile the publication-ready bibliography in `40-Manuscript/Back-Matter/Bibliography.md` from the master bibliography, including only sources actually cited in the final text.

## Book Proposal Workflow

The book proposal is typically the first major deliverable. Develop proposal materials in `30-Development/Proposal/`. Start with the [[Book-Proposal]] template, which includes sections for overview, chapter summaries, market analysis, comparable titles, and author bio. Draft sample chapters in `30-Development/Proposal/Sample-Chapters.md`. Use the comparable titles analysis from `10-Book-Bible/Audience/Comparable-Titles.md` to strengthen the market positioning. Track submissions to agents or publishers in `60-Team/Agent/Submission-Tracker.md`.

## Development to Manuscript

Moving content from development to manuscript status follows a structured process. Move the content from `30-Development/Drafts/` to the appropriate location in `40-Manuscript/Chapters/`. Update tags from `#stage/draft` to the appropriate manuscript stage. Archive draft versions in `30-Development/Archive/`. Ensure all citations in the chapter are reflected in the bibliography. Update the argument and structure maps in `70-Maps/` to reflect the finalized content. Record the transition in project logs.

## Fact-Checking Workflow

Fact-checking ensures the accuracy and credibility of the manuscript. For each chapter entering the editing phase, create entries in `60-Team/Fact-Checking/Fact-Check-Log.md`. Use the [[Verification-Checklist]] to systematically verify claims, statistics, dates, quotes, and attributions. Cross-reference claims against source notes in `20-Research/`. Flag any `#source/unverified` or `#source/disputed` material for additional review. Document corrections in `60-Team/Fact-Checking/Corrections.md`. Update the manuscript and source notes when corrections are made.

## Editorial Review Workflow

The editorial review process ensures quality and coherence. Submit chapters for review by tagging with `#stage/review` and noting the submission in `60-Team/Editor/Editorial-Calendar.md`. Reviewers add feedback using the `#pm/feedback` tag in separate feedback documents or inline comments. Track reviewer assignments in `60-Team/Reviewers/Review-Assignments.md`. Compile feedback in `60-Team/Reviewers/Feedback-Summary.md`. The author addresses feedback and updates the content, documenting changes. Once approved, update the stage tag to `#stage/editing` or `#stage/final`.

## Permissions Workflow

Permissions for quoted material, images, or data must be tracked systematically. Identify all materials requiring permission and log them in `50-Sources-and-Contacts/Permissions/Permissions-Tracker.md`. Tag items with `#perm/needed`. Draft permission request letters using the [[Permission-Request]] template. Send requests and update tags to `#perm/requested`. Log all correspondence in `50-Sources-and-Contacts/Correspondence/`. When permission is received or denied, update the tracker and tags accordingly. For materials where permission is denied, identify alternatives or make fair use determinations.

## Writing Logs

Writing logs provide a record of progress and decisions. Create a dated log file in `00-Project-Management/Writing-Logs/` using the format `YYYY-MM-DD-[Writer/Team]-Log.md`. Tag with appropriate tags: `#pm/workflow`, `#team/author`, `#doc/note`. Include session goals, progress updates, challenges encountered, and next steps. Link to any related content or documents referenced during the session. For AI assistant sessions, include prompt details and generation approach used.

## Scope and Decision Management

Nonfiction books frequently evolve in scope during research and writing. Document scope changes in `00-Project-Management/Decisions/Scope-Changes.md` with rationale and date. Update the thesis and key arguments in `10-Book-Bible/` when scope changes affect the book's core premise. Review the book outline in `30-Development/Outlines/` to ensure structural coherence after scope changes. Communicate changes to the editorial team and update any affected timelines.

## Archiving Content

When content is no longer current but should be preserved, follow the archiving workflow. Move content to `30-Development/Archive/`. Update tags to reflect archived status using `#stage/archived`. Maintain links to replacement content so the evolution can be traced. Update related documentation to point to current versions. Record the archiving action in change logs with date and reason.
