---
title: Dummy
tags: dummy, test, placeholder
description: Dummy presentation
slideOptions:
  theme: night
  slideNumber: true
  transition: slide
---

# Instructions

- You should send POST-request with filepath to your own Markdown-file

- With the default port
  - Address
    ```plain
    http://localhost:1948/localFile/
    ```

  - Body
  ```json
  {
      "filepath": "/path/to/your/file/the-file.md"
  }
  ```

---

# The end
