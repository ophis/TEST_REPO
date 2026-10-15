# AGENTS.md

This repository is public: anyone can read every commit, branch, pull request, issue, Actions log and artifact. Deleting one later does not unpublish it: forks, caches and clones keep it.

- Never commit or print secrets: tokens, API keys, passwords, private keys, `.env` files, cookies, anything read from a keychain. A workflow that needs one reads it from GitHub Actions secrets and never echoes it.
- Never commit private code or data: nothing copied from a private repository, no personal data, no internal docs, notes or transcripts.
- Use it only for throwaway tests and demos: synthetic files and empty commits.
