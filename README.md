---
title: "Test MDX Page"
description: "Simple MDX example for testing Mintlify or local MDX renderers"
---

import Callout from './components/Callout.mdx'

# Hello from MDX

This is a simple MDX test page. The content below uses a component when rendered by an MDX-aware site, and falls back to plain Markdown on GitHub.

<Callout type="info">
This is a **Callout** component. If your renderer does not support JSX, you will still see the raw tag in the file but the Markdown content above and below remains readable.
</Callout>

## Features to check

- Frontmatter is present and can be read by static site generators.
- Plain Markdown headings, lists, and code blocks render on GitHub.
- MDX components render when served by Mintlify, Nextra, Docusaurus, or a local MDX dev server.

### Example code block

```js
// sample code block
export function greet(name) {
  return `Hello, ${name}!`
}
