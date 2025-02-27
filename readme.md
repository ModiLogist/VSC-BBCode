# BBCode Extension for Visual Studio Code

## Overview

The BBCode extension for Visual Studio Code provides syntax highlighting, auto-closing brackets, and a variety of snippets to make writing BBCode easier and more efficient.

## Features

### Snippets

The extension includes a comprehensive set of snippets for common BBCode tags. Below is a list of available snippets:

- **BB URL**

  - **Prefix**: `url=`
  - **Body**: `[url=${1:link}]${2:title}[/url]$0`
  - **Description**: BB-Code URL

- **BB List**

  - **Prefix**: `list`
  - **Body**:
    ```plaintext
    [list]
    [*]${1:first input}
    [*]${2:second input}
    [*]${3:third input}
    [/list]$0
    ```
  - **Description**: BB-Code List

- **BB Spoiler**

  - **Prefix**: `spoiler`
  - **Body**: `[spoiler]${1:text}[/spoiler]$0`
  - **Description**: BB-Code Spoiler

- **BB Quote**

  - **Prefix**: `quote`
  - **Body**: `[quote]${1:text}[/quote]$0`
  - **Description**: BB-Code Quote

- **BB Code**

  - **Prefix**: `code`
  - **Body**: `[code]${1:text}[/code]$0`
  - **Description**: BB-Code Code

- **BB Image**

  - **Prefix**: `img`
  - **Body**: `[img]${1:link}[/img]$0`
  - **Description**: BB-Code Image

- **BB Bold**

  - **Prefix**: `b`
  - **Body**: `[b]${1:title}[/b]$0`
  - **Description**: BB-Code Bold

- **BB Italic**

  - **Prefix**: `i`
  - **Body**: `[i]${1:text}[/i]$0`
  - **Description**: BB-Code Italic

- **BB Underline**

  - **Prefix**: `u`
  - **Body**: `[u]${1:text}[/u]$0`
  - **Description**: BB-Code Underline

- **BB Strike**

  - **Prefix**: `s`
  - **Body**: `[s]${1:text}[/s]$0`
  - **Description**: BB-Code Strike

- **BB Size**

  - **Prefix**: `size`
  - **Body**: `[size=${1:1}]${2:text}[/size]$0`
  - **Description**: BB-Code Size

- **BB Bold Size 4**

  - **Prefix**: `b4`
  - **Body**: `[size=4][b]${1:title}[/b][/size]$0`
  - **Description**: BB-Code Bold Size 4

- **BB Bold Size 3**

  - **Prefix**: `b3`
  - **Body**: `[size=3][b]${1:title}[/b][/size]$0`
  - **Description**: BB-Code Bold Size 3

- **BB Bold Size 2**

  - **Prefix**: `b2`
  - **Body**: `[size=2][b]${1:title}[/b][/size]$0`
  - **Description**: BB-Code Bold Size 2

- **BB Bold Size 1**

  - **Prefix**: `b1`
  - **Body**: `[size=1][b]${1:title}[/b][/size]$0`
  - **Description**: BB-Code Bold Size 1

- **BB Bold Italic**
  - **Prefix**: `bi`
  - **Body**: `[b][i]${1:title}[/i][/b]$0`
  - **Description**: BB-Code Bold Italic

### Auto-Closing Brackets

The extension provides auto-closing brackets for BBCode tags. When you type an opening tag, the corresponding closing tag is automatically inserted. This feature helps to ensure that your BBCode is properly formatted and reduces the chance of errors.

### Syntax Highlighting

The extension includes syntax highlighting for BBCode. The following tags are highlighted:

- **Bold**: `[b]...[/b]`
- **Italic**: `[i]...[/i]`
- **Underline**: `[u]...[/u]`
- **Strikethrough**: `[s]...[/s]`
- **URL**: `[url=...]...[/url]`
- **Spoiler**: `[spoiler]...[/spoiler]`
- **List**: `[list]...[*]...[/list]`
- **Quote**: `[quote]...[/quote]`
- **Code**: `[code]...[/code]`
- **Image**: `[img]...[/img]`
- **Size**: `[size=...]...[/size]`

The syntax highlighting makes it easier to read and edit BBCode by visually distinguishing different tags and their content.

## Installation

To install the BBCode extension:

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
3. Search for "BBCode".
4. Click "Install" on the BBCode extension.

## Usage

To use the BBCode snippets:

1. Open a file with the `.bbcode` extension.
2. Start typing the prefix for the desired snippet (e.g., `b` for bold).
3. Select the snippet from the suggestions list and press `Enter`.

The snippet will be inserted into your document, and you can fill in the placeholder text.

## Contributing

If you would like to contribute to the BBCode extension, please visit the [GitHub repository](https://github.com/ModiLogist/VSC-BBCode) and submit a pull request.

## License

This extension is licensed under the MIT License.
