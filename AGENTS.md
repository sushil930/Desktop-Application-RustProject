## Project Continuity Rules (Always follow these)

At the START of every conversation:
1. Check if `CODEBASE_KNOWLEDGE.md` exists in the project — if yes, read it silently
2. Check if `CHANGE_LOG.md` exists — if yes, read the top session + CURRENT STATE section
3. Brief me: what was last worked on, what's broken, what's next
4. Ask if I want to continue from there or start something new

While working:
- Log every file change, install, config edit, bug fix, or decision to `CHANGE_LOG.md` immediately — never batch at the end
- Be specific: file path, what changed, why, what it affects

At the END of every conversation (or when I say "done", "bye", "switching"):
1. Write session summary to `CHANGE_LOG.md`
2. Update the CURRENT STATE + OPEN TASKS sections
3. Output a ready-to-paste handoff message for the next agent

Never ask me to re-explain the project if these files exist. They are your memory.