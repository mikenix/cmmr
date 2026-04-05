---
title: "How We Write Technical Strategy Memos"
description: "A lightweight structure for decisions that engineering, product, and founders can all align around."
pubDate: "Apr 02 2026"
heroImage: "/blog-placeholder-1.jpg"
---

At CMMR we use short strategy memos to make hard product and technical decisions explicit.

Each memo should answer four questions:

## 1) What decision are we making?

Be precise. One memo, one decision.

## 2) What are the options?

List the realistic options and include tradeoffs.

## 3) Why this option now?

Tie rationale to current constraints: timeline, team capacity, and risk.

## 4) What does success look like?

Include measurable outcomes and a review date.

### Memo Skeleton

```markdown
# Decision

## Context
- What is changing?
- Why now?

## Options
1. Option A
2. Option B

## Decision
- Selected option
- Why

## Risks and Mitigations
- Risk 1 -> Mitigation

## Success Criteria
- Metric
- Review date
```

Good memos reduce rework and increase team trust. They are a small habit with large leverage.

![blog placeholder](/blog-placeholder-about.jpg)

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

### Blockquote without attribution

#### Syntax

```markdown
> Tiam, ad mint andaepu dandae nostion secatur sequo quae.  
> **Note** that you can use _Markdown syntax_ within a blockquote.
```

#### Output

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.  
> **Note** that you can use _Markdown syntax_ within a blockquote.

### Blockquote with attribution

#### Syntax

```markdown
> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>
```

#### Output

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

### Syntax

```markdown
| Italics   | Bold     | Code   |
| --------- | -------- | ------ |
| _italics_ | **bold** | `code` |
```

### Output

| Italics   | Bold     | Code   |
| --------- | -------- | ------ |
| _italics_ | **bold** | `code` |

## Code Blocks

### Syntax

we can use 3 backticks ``` in new line and write snippet and close with 3 backticks on new line and to highlight language specific syntax, write one word of language name after first 3 backticks, for eg. html, javascript, css, markdown, typescript, txt, bash

````markdown
```html
<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8" />
		<title>Example HTML5 Document</title>
	</head>
	<body>
		<p>Test</p>
	</body>
</html>
```
````

### Output

```html
<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8" />
		<title>Example HTML5 Document</title>
	</head>
	<body>
		<p>Test</p>
	</body>
</html>
```

## List Types

### Ordered List

#### Syntax

```markdown
1. First item
2. Second item
3. Third item
```

#### Output

1. First item
2. Second item
3. Third item

### Unordered List

#### Syntax

```markdown
- List item
- Another item
- And another item
```

#### Output

- List item
- Another item
- And another item

### Nested list

#### Syntax

```markdown
- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese
```

#### Output

- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese

## Other Elements — abbr, sub, sup, kbd, mark

### Syntax

```markdown
<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
```

### Output

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
