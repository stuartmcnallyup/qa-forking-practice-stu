# Markdown Crash Course

DevOps Culture and Methodologies

## What is Markdown?

Markdown is a lightweight way to format plain text. You write simple symbols (like `#` for a heading or `**` for bold) and they get rendered into nicely formatted text. You've already been using it without realising: every README file on GitHub, every pull request description, and every issue comment is written in Markdown.

Beyond GitHub, you'll find Markdown in documentation tools, wikis, Slack, Notion, Jira, Azure DevOps, and many other tools you'll encounter at work. Learning Markdown once means you can format text almost everywhere.

## The Six Things That Cover 90% of Your Needs

### 1. Headings

Use `#` symbols at the start of a line. More `#` symbols mean smaller headings.

```markdown
# Main Heading
## Sub-heading
### Smaller Sub-heading
```

### 2. Bold and Italic

Wrap text in asterisks to emphasise it.

```markdown
**This text is bold**
*This text is italic*
***This text is both***
```

### 3. Lists

Use `-` for bullet points or numbers for numbered lists. Leave a blank line before the list starts.

```markdown
- First item
- Second item
- Third item

1. Step one
2. Step two
3. Step three
```

### 4. Links

Put the link text in square brackets, followed by the URL in round brackets.

```markdown
[GitHub](https://github.com)
[Markdown Guide](https://www.markdownguide.org)
```

### 5. Code

Use backticks for inline code and triple backticks for code blocks. For code blocks, you can add the language name after the opening backticks to get syntax highlighting.

Inline code:

```markdown
Run `git status` to check your repo.
```

Code block:

````markdown
```bash
git add .
git commit -m "my first commit"
git push origin main
```
````

### 6. Images

Same as links, but with an exclamation mark in front.

```markdown
![Screenshot of the pipeline](screenshot.png)
```

## Bonus: A Few More Useful Tricks

**Blockquotes** use `>` at the start of a line:

```markdown
> This is a quote or a callout.
```

**Horizontal rules** use three hyphens on their own line:

```markdown
---
```

**Tables** use pipes and hyphens:

```markdown
| Tool   | Purpose         |
|--------|-----------------|
| Git    | Version control |
| Docker | Containers      |
```

**Task lists** (GitHub-specific) use `- [ ]` and `- [x]`:

```markdown
- [x] Clone the repo
- [ ] Create a branch
- [ ] Open a pull request
```

## Where You'll Use This

- **GitHub READMEs:** Every repo should have a `README.md` explaining what the project is and how to use it. You've been creating these today.
- **Pull request descriptions:** When you open a PR, a well-formatted description helps reviewers understand your changes.
- **Issue tracking:** GitHub Issues, Jira, Azure DevOps; most issue trackers support Markdown.
- **Documentation:** Many teams write their docs in Markdown and convert to HTML or PDF.
- **Config and notes:** Tools like Notion, Obsidian, and Slack all use Markdown or Markdown-like formatting.

## Try It Yourself

The best way to learn Markdown is to type it. Here are three excellent free resources:

- **[Markdown Tutorial](https://www.markdowntutorial.com/)** — interactive exercises you can complete in about 10 minutes. Start here.
- **[Markdown Guide: Basic Syntax](https://www.markdownguide.org/basic-syntax/)** — a clean reference page to bookmark for day-to-day use.
- **[CommonMark Tutorial](https://commonmark.org/help/tutorial/)** — another interactive option with a lesson-by-lesson structure.

## Quick Reference

| What you want       | What you type                    | What you get              |
|----------------------|----------------------------------|---------------------------|
| Heading              | `# Heading`                      | A large heading           |
| Bold                 | `**bold**`                       | **bold**                  |
| Italic               | `*italic*`                       | *italic*                  |
| Link                 | `[text](url)`                    | Clickable link            |
| Inline code          | `` `code` ``                     | `code`                    |
| Code block           | ` ``` ` on its own line          | Formatted code block      |
| Bullet list          | `- item`                         | Bullet point              |
| Numbered list        | `1. item`                        | Numbered item             |
| Image                | `![alt](url)`                    | Embedded image            |
| Blockquote           | `> text`                         | Indented quote            |
| Horizontal rule      | `---`                            | Divider line              |
