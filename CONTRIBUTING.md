# Contributing to Awesome-IDEs

Thank you for your interest in contributing to **Awesome-IDEs**! We welcome additions of new IDEs, editors, and tools to make this the most comprehensive list available.

## How to Add an IDE

1.  **Check for Duplicates**: Ensure the IDE isn't already listed.
2.  **Determine the Category**: Place your entry in the most appropriate section (e.g., General Purpose, Web, Mobile, AI-Powered, Game Development).
3.  **Format the Entry**: Use the standardized table format below.
4.  **Add an Icon**:
    *   Find a high-quality (transparent PNG preferred) icon for the IDE.
    *   Name it `ide_name.png` (lowercase, underscores).
    *   Place it in `Resources/Icons/` (or use the placeholder format if you cannot add the file).
    *   This repository uses `<name>.png` as the standard convention.

### Table Format

Each entry must follow this strict format:

```markdown
| Name | Description | Links | System Support | Fees | Tags |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <img src="Resources/Icons/icon_name.png" alt="icon" width=15 height=15> **IDE Name** | Brief description. | [Website](url) | `Mac` `Windows` `Linux` | Free/Paid | `Tag1` `Tag2` |
```

### Columns Guide

*   **Name**: The official name of the IDE/Editor.
*   **Description**: A concise summary (1-2 sentences).
*   **Links**: A link to the official **Website** is required. Adding **Github** or **PlayStore** links is encouraged where applicable.
*   **System Support**: List officially supported platforms as code tags.
    *   Use: `Mac`, `Windows`, `Linux`, `Web`, `Android`, `iOS`, `BSD`.
    *   **Avoid "All Platforms"**: Please list the specific major platforms.
*   **Fees**: listing the pricing model.
    *   Examples: `Free`, `Paid`, `Freemium`, `Free, Open-Source`.
*   **Tags**: Add relevant tags to help filter and categorize.
    *   Examples: `Lightweight`, `Rust`, `AI-Native`, `Education`, `Vim`, `Cloud`.

## Pull Request Process

1.  Fork the repository.
2.  Create a new branch for your feature (`git checkout -b add-new-ide`).
3.  Commit your changes.
4.  Push to the branch (`git push origin add-new-ide`).
5.  Open a Pull Request.

Happy Coding!
