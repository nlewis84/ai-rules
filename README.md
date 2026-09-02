# AI Rules

These rules guide AI behavior in Cursor.

Rules apply automatically based on their `alwaysApply` setting. You can also reference specific rules during conversations to activate them.

Available rules:
- **Brainstorming** — Structured questioning to refine ideas into designs
- **Systematic Debugging** — Four-phase debugging that finds root causes before fixes
- **Test-Driven Development** — Write tests first, implement second
- **Defense in Depth** — Multiple layers of validation
- **Root Cause Tracing** — Track data flow backwards to find bugs
- **Spec Generation** — Create detailed specifications before building
- **PR Descriptions** — Write clear, useful pull request descriptions
- **Condition-Based Waiting** — Replace timeouts with condition checks
- **Verification Before Completion** — Verify work before marking done
- **Testing Anti-patterns** — Avoid common testing mistakes
- **Preserving Productive Tensions** — Balance conflicting design goals
- **Clear Writing (AI Tropes)** — Concrete prose; avoid prefab AI phrasing
- **Linear Issue Planning Flow** — RED, GREEN, REVERT, REWRITE, REFACTOR
- **Remix Performance Principles** — Actions for mutations; loaders for GET

Each rule includes when to use it, the process to follow, and what success looks like.

## Writing rule on one machine

`ai-writing-tropes-to-avoid.mdc` in this repo is the file to edit. To have Cursor apply it in every project, copy it to `~/.cursor/rules/ai-writing-tropes-to-avoid.mdc`. When the git file changes, copy it again. Do not edit only the home copy.
