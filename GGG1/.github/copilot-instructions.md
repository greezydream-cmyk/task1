# Copilot Instructions for GGG1 Project

## Project Overview
This is a Git tutorial documentation project written in Russian. It consists of Markdown files providing instructions on Git commands and workflows.

## Architecture
- **Main entry point**: `readme.md` serves as the index with table of contents and links to other sections.
- **Content structure**: Each Git command or topic has its own `.md` file (e.g., `add.md` for `git add`).
- **Assets**: `assets/` folder contains images like the Git logo.
- **License**: MIT license in `license.md`.

## Key Patterns
- **Language**: All content is in Russian. Maintain this convention for new additions.
- **Markdown usage**: Use standard Markdown with headers (`#`, `##`), links (`[text](./file.md)`), and code blocks for Git commands (````bash=`).
- **File naming**: Use lowercase, descriptive names for `.md` files (e.g., `add.md`).
- **Linking**: Reference other files using relative paths, e.g., `[git add](./add.md)` in `readme.md`.

## Workflows
- **Editing**: Modify `.md` files directly in VS Code. Use Markdown preview to check formatting.
- **Adding content**: Create new `.md` files in the root directory, update `readme.md` table of contents accordingly.
- **Images**: Place images in `assets/` and reference with `./assets/filename.png`.

## Examples
- Adding a new section: Create `commit.md` with content like `add.md`, then add link in `readme.md` under "Содержание".
- Code blocks: Always use ````bash=` for Git commands, as in `add.md`.

## Conventions
- Keep content concise and instructional.
- Include copyright notices for images, as in `readme.md`.
- No build process; static Markdown files.