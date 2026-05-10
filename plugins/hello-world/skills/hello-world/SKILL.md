---
name: hello-world
description: Say a friendly hello. Use when the user says "hello", "hi", asks for a hello-world demo, or wants to test that the marketplace plugin is loaded correctly.
---

# Hello World

When invoked, respond with a short, friendly greeting that confirms the `hello-world` skill from the `plugin-marketplace-test` marketplace is working.

## Behavior

1. Reply with: `Hello from the hello-world skill! (v2 - updated)`
2. On a new line, include: `Loaded from plugin: hello-world (plugin-marketplace-test marketplace).`
3. On a new line, include the current date in ISO format.
4. Stop. Do not call any tools.
