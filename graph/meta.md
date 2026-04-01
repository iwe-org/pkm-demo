# 📖 Knowledge Base Structure

This knowledge base is a demo showcasing different PKM (Personal Knowledge Management) methodologies working together in a unified system.

## Top-Level Containers

- 📂 **Demo** (`index.md`) - Root entry point linking all methodologies
- 📅 **Timeline** - Date-based navigation organized hierarchically
- 📓 **Journal** - Daily reflections and personal entries
- 📋 **PARA** - Tiago Forte's personal organization system
- 🧠 **Zettelkasten** - Luhmann-inspired atomic note-taking
- ✅ **GTD** - David Allen's Getting Things Done task management

## GTD Structure

The GTD system captures and organizes actionable items:

- 📥 **Inbox** (`inbox.md`) - Capture bucket for new items
- ⚡ **Next Actions** (`next-actions.md`) - Context-based action lists
  - `@work` - Office/professional tasks
  - `@computer` - Digital tasks
  - `@home` - Household tasks
  - `@errands` - Out-and-about tasks
  - `@calls` - Phone calls to make
- ⏳ **Waiting For** (`waiting-for.md`) - Delegated items awaiting response
- 💭 **Someday Maybe** (`someday-maybe.md`) - Future possibilities
- 🎯 **Projects** (`projects.md`) - Multi-step outcomes
- 📚 **Reference** (`reference.md`) - Static reference information

## PARA Structure

PARA organizes information by actionability:

- 🎯 **Projects** (`para/projects/`) - Active work with deadlines
- 🏠 **Areas** (`para/areas/`) - Ongoing responsibilities
- 📚 **Resources** (`para/resources/`) - Topic-based reference material
- 🗄️ **Archive** (`para/archive/`) - Inactive or completed items

## Zettelkasten Conventions

Zettelkasten notes follow these patterns:

- **ID Format**: Timestamp-based IDs using `YYYYMMDDHHmm` format
  - Example: `202601011200` = January 1, 2026 at 12:00
- **Atomic Notes**: Each note captures exactly one idea
- **Linking**: Notes end with a "Related:" section containing links to connected ideas

## Timeline Conventions

Hierarchical date-based navigation:

- **Months**: `YYYY-MM` format (e.g., `2026-01`)
- **Weeks**: `YYYY-Wnn` format (e.g., `2026-W01`)
- **Days**: `YYYY-MM-DD` format (e.g., `2026-01-01`)

Months link to weeks, weeks link to days.

## Journal Conventions

Journal entries use short alphanumeric IDs (e.g., `j7x2k`, `a3m9p`) with descriptive titles. Each entry is a standalone reflection or note from a specific day.

## Writing Structure

The Writing section provides a creative writing workflow with progressive stages:

- 💡 **Ideas** (`writing-ideas.md`) - Sparks, prompts, and concepts waiting to be developed
- 📝 **Drafts** (`writing-drafts.md`) - First attempts at pieces, rough and exploratory
- 🔄 **Revisions** (`writing-revisions.md`) - Pieces being actively refined and polished
- 📖 **Published** (`writing-published.md`) - Finished, polished pieces

### Writing Conventions

- **ID Format**: Short IDs with `w-` prefix (e.g., `w-threshold`, `w-morning-ritual`)
- **Workflow**: Ideas → Drafts → Revisions → Published
- **Piece Types**: Flash fiction, poetry, short stories, essays
- **Notes**: Drafts and revisions may include inline notes marked with `*[...]*`

## Books Structure

The Books section collects books that have influenced thinking and practice.

- 📚 **Books** (`books.md`) - Hub linking to individual book notes
- **ID Format**: `bk-` prefix with short slug (e.g., `bk-smart-notes`, `bk-atomic-habits`)
- **Structure**: Title, Author (linked if person exists), summary, key ideas, and links to related Zettel notes

## People Structure

The People section tracks thinkers, authors, and creators whose ideas appear across the knowledge base.

- 👤 **People** (`people.md`) - Hub linking to individual person notes
- **ID Format**: `p-` prefix with name slug (e.g., `p-niklas-luhmann`, `p-tiago-forte`)
- **Structure**: Name, biographical note, links to Ideas (Zettel notes) and Books

## Quotes Structure

The Quotes section captures memorable passages and their sources.

- 💬 **Quotes** (`quotes.md`) - Hub linking to individual quotes
- **ID Format**: `q-` prefix with short slug (e.g., `q-writing-thinking`, `q-slip-box`)
- **Structure**: Quote text, attribution (linked to person and/or book), and related notes
