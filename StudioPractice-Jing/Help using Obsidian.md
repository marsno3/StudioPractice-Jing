
## A quick guide to Obsidian

Obsidian is a note-taking app that stores everything as plain Markdown (`.md`) files on your own computer. Your notes stay readable in any text editor, and Obsidian adds linking, search and visual tools on top.

### 1. Vaults

A **vault** is just a folder on your computer that Obsidian treats as your notes library. When you first open the app, create a new vault or point it at an existing folder. You can have several vaults (for example work and personal), but most people do well with one. 

### 2. Creating and organising notes

- **New note:** `Ctrl/Cmd + N`
- **Quick switcher** (jump to or create a note by name): `Ctrl/Cmd + O`
- **Command palette** (every action in the app): `Ctrl/Cmd + P`
- Folders work as you'd expect, but many people keep folders light and rely on links and tags instead.

### 3. Linking notes

Type `[[` and start typing a note name to link to it. If the note doesn't exist yet, clicking the link creates it. Every note shows its **backlinks**, meaning the other notes that point to it, so connections build up over time. The **Graph view** (left sidebar) shows these connections as a web.

### 4. Editing modes

Obsidian has **Live Preview** (formatting renders as you type) and **Reading view**. Toggle between them with `Ctrl/Cmd + E`. Source mode, which shows the raw Markdown, is available in settings.

### 5. Markdown examples

**Basic formatting**

```markdown
# Heading 1
## Heading 2
### Heading 3

**bold**, *italic*, ~~strikethrough~~, ==highlight==, `inline code`
```

**Lists and tasks**

```markdown
- Bullet point
  - Indented bullet (press Tab)
1. Numbered item
2. Another item

- [ ] A task to do
- [x] A completed task
```

**Links and embeds (Obsidian-specific)**

```markdown
[[Meeting Notes]]                  Link to another note
[[Meeting Notes|see the notes]]    Link with custom display text
[[Meeting Notes#Actions]]          Link to a heading inside a note
![[Meeting Notes]]                 Embed a whole note inline
![[diagram.png]]                   Embed an image from your vault
[Obsidian site](https://obsidian.md)   Standard external link
```

**Tags**

```markdown
#project #ideas/writing
```

Nested tags like `#ideas/writing` help group related topics. Click any tag to search for it.

**Quotes, callouts and code blocks**

````markdown
> A regular blockquote.

> [!note] This is a callout
> Callouts are Obsidian's styled boxes.
> Try [!tip], [!warning] or [!question] too.

```python
print("Code blocks get syntax highlighting")
```
````

**Tables**

```markdown
| Task      | Status  |
|-----------|---------|
| Draft     | Done    |
| Review    | Pending |
```

**Properties (metadata at the top of a note)**

```markdown
---
tags: [meeting, work]
date: 2026-09-28
status: draft
---
```

### 6. Useful core plugins to switch on

In **Settings → Core plugins**, try these:

- **Daily notes** creates one note per day, which is great for journals or work logs.
- **Templates** lets you insert reusable note layouts.
- **Canvas** is an infinite whiteboard where you can arrange notes and cards.
- **Bookmarks** pins notes you use often.
- There are also lots of themes and colour options other people have created.

Once you're comfortable, **Community plugins** add many more features. Dataview, Calendar and Excalidraw are popular starting points.
