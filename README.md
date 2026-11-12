# Phish Out of Water

**A security awareness session kit: slides, exercises, and a one-page takeaway.** Everything you need to run an hour on scams and safer accounts for a team, a family, a senior center, or a classroom, in plain language and without scare tactics.

From [neon1](https://neon1.tech). *1 is glad to be of service.*

---

## What a session does

People leave an hour of Phish Out of Water able to:

1. **Spot the pressure.** Every scam leans on the same few levers: hurry, fear, secrecy, and an unusual way to pay.
2. **Use the pause.** Hang up, look up the real number, and call back. Never act from inside the message that asked.
3. **Lock the front door.** Two-step sign-in turned on for their email, during the session, before they leave.
4. **Know who to tell.** A family code word, a way to report at work, and who to call if money is gone.

## What's inside

| Folder | What it holds |
|---|---|
| [`session/`](session/index.md) | The run sheet, a [slide deck](session/slides.md) in Markdown, and a [facilitator script](session/facilitator-script.md) with what to say at each slide. |
| [`exercises/`](exercises/index.md) | Spot the scam, role-plays, the two-step sign-in lab, and a family code word activity. |
| [`handouts/`](handouts/index.md) | The [one-page takeaway](handouts/one-page-takeaway.md), a who-to-call card, a before-and-after quiz, and a feedback form. |
| [`guide/`](guide/index.md) | A field guide to eleven common scams: what each looks like, the tell, and what to do. |
| [`audiences/`](audiences/index.md) | How to adapt the hour for families and seniors, workplace teams, and students. |

## Running one

1. Read the [run sheet](session/index.md) and pick your [audience](audiences/index.md).
2. Swap two or three examples in [spot the scam](exercises/spot-the-scam.md) for ones your group has really received, with names removed.
3. Turn the slides into a presentation (below) and print the takeaway, one per person.
4. Follow the [facilitator script](session/facilitator-script.md). Leave the last fifteen minutes for the two-step sign-in lab. It's the part that changes the most.

## The slides

[`session/slides.md`](session/slides.md) is written for [Marp](https://marp.app), an open-source Markdown slide tool. Open it in VS Code with the Marp extension, or from the command line:

```
npx @marp-team/marp-cli session/slides.md --pdf     # or --pptx, or --html
```

It reads fine as a plain document on GitHub, too.

## How it fits with neon1's other guides

- [Ready, Secure, Go](https://github.com/neon1llc/ready-secure-go) is the reference: practice cards, playbooks for when something already went wrong, and teach kits for specific groups. Phish Out of Water links to its cards for anyone who wants to go deeper.
- [Home Is Where the Smart Is](https://github.com/neon1llc/home-is-where-the-smart-is) is the household handbook for the person who looks after a family's devices and accounts.
- [SOC It 2 Me](https://github.com/neon1llc/soc-it-2-me) is SOC 2 readiness training for companies. A Phish Out of Water session can serve as part of a company's yearly awareness training.

Want neon1 to run a session for your group? See [neon1.tech](https://neon1.tech).

## Checking a change

```
node tools/check.mjs    # front matter on every page, and no broken links
```

## Licenses

| What | License | What it means |
|---|---|---|
| Written material (everything except `tools/` and `.github/`) | [CC BY-SA 4.0](LICENSE) | Share it, teach from it, adapt it, even commercially. Credit it as *"Based on Phish Out of Water by neon1 (neon1.tech), CC BY-SA 4.0"* and share your changes under the same license. |
| Code (`tools/`, `.github/`) | [MIT](LICENSE-CODE) | Use it for anything, keeping the copyright notice. |
| The Phish Out of Water and neon1 names and the neon1 logo | Reserved | Not covered by either license. See [TRADEMARK.md](TRADEMARK.md). |

Phish Out of Water is © 2026 neon1 LLC. Keep the [NOTICE](NOTICE) file in copies and adaptations.

Found something wrong or outdated? See [SECURITY.md](SECURITY.md). Want to help? See [CONTRIBUTING.md](CONTRIBUTING.md).
