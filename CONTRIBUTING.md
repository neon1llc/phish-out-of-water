# Contributing

Scams change every month, so fresh examples and corrections help most.

## What helps most

- New scam examples you or your group received, with every name, number, and link removed or replaced.
- Corrections to reporting numbers and websites, with a link to the official source.
- Adaptations for an audience the kit doesn't serve yet, and translations.
- Accessibility fixes: large-print versions, plain-language rewrites, and screen reader checks.

## How to write here

- **Respect the room.** Scams are run by organized groups working from scripts, and they catch careful people.
- **No fear selling.** Say what the risk is and how likely it is.
- **Every lesson ends in an action** someone can do that day.
- **Never include a working scam link or phone number** in an example. Use `example.com` addresses and 555 numbers.
- Use the serial comma.

## Checking your change

```
node tools/check.mjs
```

## Branches and commits

Name branches `feat/`, `fix/`, `docs/`, or `chore/` plus a short hyphenated description. Use [Conventional Commits](https://www.conventionalcommits.org/), for example `feat(guide): add rental listing scams` or `fix(handouts): correct the elder fraud hotline number`. Merge with `git merge --no-ff`, and never rewrite history on `main`.
