# plugin-marketplace-test

A test Claude Code plugin marketplace with placeholder hello-world skills.

## Structure

```
.claude-plugin/marketplace.json    # marketplace manifest
plugins/
  hello-world/
    .claude-plugin/plugin.json
    skills/hello-world/SKILL.md
  greet-pack/
    .claude-plugin/plugin.json
    skills/
      good-morning/SKILL.md
      good-night/SKILL.md
```

## Local install / test

From any Claude Code session:

```
/plugin marketplace add /Users/kirillkuts/learn/plugin-marketplace-test
/plugin install hello-world@plugin-marketplace-test
/plugin install greet-pack@plugin-marketplace-test
```

Then trigger the skills by saying "hello", "good morning", or "good night".

## Install from GitHub (after pushing)

```
/plugin marketplace add <github-user>/plugin-marketplace-test
/plugin install hello-world@plugin-marketplace-test
```
