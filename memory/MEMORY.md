<!-- 2026-09-12 16:39:34 [01a0959a] -->
## pi tooling preference — no hard guards

#decision Pi must NOT be hard-blocked from using `bash` + python/sed/awk for text edits. A `tool_call` blocking extension (no-script-edit.ts) was written on 2026-09-12 then removed at user request ("back lại như lúc đầu đi - đừng có ép nó dùng nữa").
#preference Nudge only: `~/.pi/agent/AGENTS.md` has a "## File Editing" section preferring `target_edit`/`quick_edit` (pi-snap-edit) over scripted edits. Do not re-propose enforcement/extensions that block tools without being asked.
