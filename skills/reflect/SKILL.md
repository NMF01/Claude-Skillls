---
name: reflect
description: Review the current conversation to extract lasting preferences, communication style, recurring instructions, and reusable workflows that could become a Skill. Use when the user types /reflect or asks to "review this conversation", "what should you remember", "save my preferences", or "turn this workflow into a skill". Always shows the proposed additions for approval before saving anything.
---

# Reflect

Review everything covered in this conversation.

## 1. Identify
- **Lasting preferences, communication style, or recurring instructions** that would help give better responses in future chats.
- **Reusable workflows** created in this conversation that are reusable enough to become a Skill.

Only include things that will matter again. Skip one-off details.

## 2. Show the plan FIRST
Before saving or creating anything, show exactly what you plan to add, so the user can approve or edit it first:
- **Preferences/memory:** the exact text to be saved, and where (memory / CLAUDE.md).
- **Skills:** proposed name, one-line description, and the full SKILL.md content.

Keep it short and scannable (bullets or a table). If nothing qualifies, say so.

## 3. Wait for approval
Do NOT write, save, or create anything until the user approves. Apply edits they request, then save only what was approved.
