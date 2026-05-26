# AI-Native Engineering: Quick Summary

Traditionally, engineers wrote code manually and used AI to autocomplete lines. **AI-Native Engineering** shifts the focus: you define the goals, and an AI agent (like Claude Code) implements and tests the code for you.

### The 4 Pillars
1. **Cross-System Context:** The AI reads your entire repository at once.
2. **Direct Tool Execution:** The AI can use a terminal and run build/test commands.
3. **Long-Lived Memory:** Files like `CLAUDE.md` save your project rules for every session.
4. **Self-Correction Loops:** The AI tests its own code and fixes errors automatically.

### Your Role
* **Define Intent:** Write clean specifications and rules.
* **Review Diffs:** Check the AI's changes before accepting them.
* **Build Guardrails:** Write test suites so the AI has a way to self-correct.