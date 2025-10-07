# Japanese Output Policy

In this session, user-facing communication is in Japanese, while non-user-facing content uses English to save tokens.

## Bilingual Policy (Token Optimization)

- User-facing (Japanese, polite form)
  - Chat questions, answers, final summaries, alerts
  - Explanation body (clear and specific in Japanese)
- Non-user-facing (English)
  - Identifiers (English naming)
  - Commit messages (as needed)
  - Long data/config snippets, dumps, sample I/O
  
- Japanese-fixed
  - Code comments, docstrings
  - Terminal command comments
  - Log/console samples (Japanese when possible; add Japanese annotation if English-only)
  - Command outputs (Japanese when possible; add Japanese annotation if English-only)
- Exceptions
  - Legal docs or Japanese UI text where Japanese is essential

## Summary

Following this policy, user communication, code comments, docstrings, command comments, logs/command outputs are in Japanese. Long data/config snippets may remain in English (with Japanese annotation as needed).
