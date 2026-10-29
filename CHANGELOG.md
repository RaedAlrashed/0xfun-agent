# Changelog

## Unreleased

- Require a separate folder for each challenge, including its inputs, scripts, logs, and checkpoint.
- Record challenge identity and the absolute working directory for session handoffs, with collision and resume rules.
- Replace the README's visual introduction with the technical CTF workflow and document session-directory behavior.
- Remove solver instructions for an installer that is not shipped; document runtime skill commands and make writeups opt-in.

## 1.1.0

- Standalone `0xfun` command on macOS, Linux, and Windows; no shell alias or separately installed agent required.
- Animated skull, large wordmark, active model, current directory, and compact CTF greeting.
- 4.5-second non-blocking startup animation and `/banner` replay.
- Bundled CTF operating instructions, portable skill references, pink theme, web research, audit workflows, prompts, and subagent support.
- Pinned dependencies and shrinkwrap for reproducible installs.
- Separate `~/.0xfun/agent/` configuration, credentials, and session storage.
- Quiet startup; required third-party licenses and distribution exclusions are documented separately.
