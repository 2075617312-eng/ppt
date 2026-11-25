---
name: ppt-master
description: Create, edit, reconstruct, beautify, and enhance editable PowerPoint PPTX presentations using the full PPT Master workflow.
---

# PPT Master launcher

The complete upstream PPT Master skill is stored as a Git submodule at `vendor/ppt-master`.

When this skill is invoked:
1. Read `vendor/ppt-master/skills/ppt-master/SKILL.md` in full.
2. Treat `vendor/ppt-master/skills/ppt-master` as the upstream skill directory (`SKILL_DIR`).
3. Follow that upstream skill's mandatory load order and all of its workflow, integrity, and safety requirements exactly.
4. Do not skip its scripts, references, templates, workflows, or integrity checks.
5. If the submodule is not initialized or the upstream files are unavailable, stop and tell the user to initialize Git submodules; do not pretend the skill is installed.

Upstream: https://github.com/hugohe3/ppt-master
