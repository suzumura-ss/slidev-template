---
theme: shibainu
class: text-center
highlighter: shiki
lineNumbers: true
drawings:
  persist: false
transition: slide-left
title: Welcome to Slidev
---

# ようこそ Slidev

Presentation slides for developers

Press Space for next page

---

# Table of contents

<Toc maxDepth="1"></Toc>

---

# Code

Use code snippets and get the highlighting directly![^1]

```ts {all|1|2}
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: User) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)
}
```

---
layout: center
---

# Diagrams

You can create diagrams / graphs from textual descriptions, directly in your Markdown.

```mermaid {scale: 1.0}
sequenceDiagram
    Alice->John: Hello John, how are you?
    Note over Alice,John: A typical interaction
```

[Learn More](https://sli.dev/guide/syntax.html#diagrams)

---
layout: center
---

# Learn More

- [Documentations](https://sli.dev)
- [GitHub](https://github.com/slidevjs/slidev)
- [Showcases](https://sli.dev/showcases.html)
