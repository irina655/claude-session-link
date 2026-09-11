# Claude session link

A single static page that turns a normal https link into the right way of opening a Claude Code session on the device you are holding.

Usage: `https://irina655.github.io/claude-session-link/?s=<desktop id>&c=<claude.ai id>`

- `s=local_...` is the Claude desktop session id. On a computer the page opens `claude://code/continue?session=...`.
- `c=session_...` is the same session's claude.ai (Remote Control) id. On a phone the page offers the Claude app and claude.ai.
- `s=last` opens the most recently active desktop session.

The page holds no data. The session ids live only in the link you share.
