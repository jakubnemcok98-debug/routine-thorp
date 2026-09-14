# routine-thorp

Dedicated repo for THORP's Claude Code cloud routines (`THORP Pre-Market Check`,
`THORP End-of-Day Report`). These routines don't actually need repo content —
they only make network calls (Alpaca REST API + Telegram Bot API) — this repo
just exists to give the routines their own git checkout, separate from the
shared `claude-routines-demo` repo.
