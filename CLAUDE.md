# Working agreement with Claude

## Default workflow: preview → approve → edit
- For ANY task that involves modifying files in this repo, do not edit
  immediately. First respond with a short plan:
    1. Which files you'll change
    2. What the change is (1–3 sentences per file, or a small code sketch)
    3. Anything risky or worth flagging
- Wait for explicit approval ("ok", "go ahead", "do it") before writing
  to disk. Treat anything else as a request for revision.
- For trivial fixes (typos, single-character changes) you can ask
  "shall I just fix this?" instead of a full plan.

## Commits
- Never run `git commit`, `git push`, or any git-mutating command on
  my behalf. Commits are always done by the human in PyCharm.

## Code style for this site
- Plain HTML/CSS/JS only. No frameworks, no build step, no bundlers.
- Match existing indentation in the file you're editing.
- Don't reformat unrelated code.
