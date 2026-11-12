# Glossary

The terms Pocket Timer uses, in plain words.

## Session

A session is a block of focused work. You start one with `pocket start`. It lasts 25 minutes by default and rings when it ends. Change the length with `session_minutes`, as described in [Configuration](configuration.md#session-length).

## Break

A break is a short rest between sessions. You start one with `pocket break`. It lasts 5 minutes and never counts toward your daily goal.

## Daily goal

The daily goal is how many sessions make a full day. `daily_goal = 8` is the default. Run `pocket today` to see your progress. See [Configuration](configuration.md#daily-goal) to change it.

## History

The history is the record of your sessions and breaks. It lives in `~/.pocket/history.jsonl`, one line per session or break. `pocket today` lists today's entries. See the [FAQ](faq.md#where-is-my-history-stored) for details.

Back to [the index](index.md).
