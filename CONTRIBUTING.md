# Contributing

This repository collects cases where an AI agent's authority changes because people, keys, approvals or roles change around it. Contributions are new cases, corrections, sources, and runnable vectors.

## What a contribution needs

- A proposed invariant names the failure mode it prevents.
- A case marked verified carries a sourced quote. A case without one stays hypothetical or candidate.
- A case that tests proposed text is labeled candidate, not conformance.
- Keep the status of every statement you touch. Do not claim more than the evidence shows.

## Checks

Edit `cases.json`, then run:

```
python3 scripts/validate_cases.py
python3 scripts/build_cases_md.py --check
python3 scripts/check_links.py
```

All three must pass before a PR.

## Good places to start

Look for issues labeled `good first issue` or `help wanted`, or read OPEN-QUESTIONS.md.

## License

By contributing you agree your work is released under Apache-2.0.
