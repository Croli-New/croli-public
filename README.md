# Croli

**A multi-agent coding workspace.** Run every AI coding agent in one place — and let them work together.

Croli aggregates your sessions from every supported agent CLI into one searchable
workspace, and lets a main agent delegate to sub-agents of other types within a
single task. Work you'd rather not sit through goes on a to-do board instead —
each task in its own branch, running unattended, waiting for your review before
it lands.

It runs as a desktop app, a standalone server, or a Docker container, with
native iOS and Android clients for when you're away from your desk. Multiple
agents come built in, and you can register any other ACP-compatible agent
yourself.

## Download

Get the latest build for macOS, Windows, or Linux from
**[croli.net/download](https://www.croli.net/download/)**.

| Platform | Notes |
| --- | --- |
| macOS | Apple silicon and Intel, signed `.dmg` |
| Windows | x64 installer |
| Linux | x64 |

## Feedback

**This repository is the public home for product feedback.** The application's
source code is not published here — this repo exists so that bug reports and
feature requests have a public, searchable place to live.

- **[Open a bug report](https://github.com/Croli-New/croli-public/issues/new?template=bug_report.yml)**
  — something is broken or behaves unexpectedly.
- **[Request a feature](https://github.com/Croli-New/croli-public/issues/new?template=feature_request.yml)**
  — an idea for how Croli could work better.
- **[Browse existing issues](https://github.com/Croli-New/croli-public/issues)**
  — please check first; adding to an existing report is more useful than a
  duplicate.

You can also reach these from inside the app: **Help ▸ Send Feedback** on macOS,
or **Settings ▸ System ▸ Send Feedback** on every platform. Both open a
pre-filled issue with your version and platform already filled in.

### What makes a report actionable

Croli is a workspace that sits in front of many different agent CLIs, so the
single most useful thing you can include is **which agent** was involved and
**what the session was doing**. Reports that name the agent, the version, and
the steps that led there get reproduced and fixed; reports that only say "it
didn't work" are hard to act on.

Logs can help too — the app keeps them under **Help ▸ Open Logs** (macOS) or the
runtime-logs location shown in **Settings**. Please skim them before attaching:
they may contain file paths and prompt text you would rather not publish.

## Learn more

Everything official lives on **[croli.net](https://www.croli.net)**:

- **[Product overview](https://www.croli.net)** — what Croli is and what it
  does.
- **[Download](https://www.croli.net/download/)** — the latest build for each
  platform.
- **[Pricing](https://www.croli.net/pricing/)** — plans and availability.
- **[Resources](https://www.croli.net/resources/)** — background reading on
  agents, MCP, skills, and workflows, linking out to the official sources for
  each.

## License

The Croli application is proprietary software. This repository contains product
documentation and issue templates only.

## Acknowledgments

Croli is built on **[Codeg](https://github.com/spacering-net/codeg)**, the
open-source collaborative multi-agent coding workspace. Croli would not exist
without it, and we are glad to say so.

Codeg is released under the
[Apache-2.0 license](https://github.com/spacering-net/codeg/blob/main/LICENSE).
Sincere thanks to its authors, maintainers, and everyone who has contributed
to it.

Croli also relies on the wider ecosystem of agent CLIs and open protocols it
brings together — thanks as well to the teams behind
[Agent Client Protocol](https://agentclientprotocol.com) and every agent
Croli supports.
