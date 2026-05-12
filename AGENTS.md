# Obsidian Vaults Repository

This repository is a collection of multiple independent Obsidian vaults.

## Vault Structure & Paths
- **Multiple Vaults**: Any top-level directory containing an `.obsidian` folder is a separate Obsidian vault (e.g., `Zettelkasten`, `pkm-beta`, `2026년 4월 게임 역기획`).
- **Templates**: Each vault typically maintains its own template directory (e.g., `Template`, `System/Templates`, or `Data/Template`). Always check for and utilize existing templates when creating new notes.
- **Path Quoting**: File and directory names extensively use Korean characters and spaces. **ALWAYS quote paths** in bash commands (e.g., `cd "2026년 4월 게임 역기획"`).
- **Read-Only Configs**: Do NOT manually edit JSON configuration or cache files inside `.obsidian/` directories unless explicitly requested, as this may conflict with the Obsidian app's internal state.

## Obsidian Markdown Conventions
When creating or editing notes, follow Obsidian-flavored Markdown conventions observed in the repository:
- **Properties/Frontmatter**: Use YAML blocks (`---`) at the very top of files for metadata (e.g., `date_created`, `주제`).
- **Callouts**: Use Obsidian callout syntax (e.g., `> [!important] 내용`).
- **Wikilinks**: Prefer `[[Page Name]]` syntax for linking to other notes within the same vault.
- **Footnotes**: Use inline footnotes (`^[footnote text]`).
- **Comments**: Use Obsidian's comment syntax (`%% comment %%`) for non-rendered notes.
- **Styling**: HTML tags like `<font color="808080">text</font>` and `<div style="page-break-after: always;"></div>` are actively used for formatting and should be maintained.

## Core Directives
- **Korean Language**: As per the global `AGENTS.md`, all interactions and responses must be in **Korean**.
- **User Consent**: You must use the `question` (Options) tool to ask for user consent before executing any file edits. Read operations are unrestricted, but edits require explicit confirmation.