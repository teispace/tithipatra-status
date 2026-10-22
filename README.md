# Tithipatra status

Live checks of Tithipatra's public services, published at
**[status.tithipatra.com](https://status.tithipatra.com)**.

## [Live status](https://status.tithipatra.com): <!--live status--> **Checking**

<!--start: status pages-->
<!--end: status pages-->

## How it works

- [Upptime](https://github.com/upptime/upptime)'s checker runs from GitHub Actions every
  five minutes, from outside our servers. A site that goes down gets an issue in this
  repository (closed when it is back) and an email to the maintainer.
- The workflows are our own, not Upptime's generated ones: every action is pinned by
  commit, each job has only the permissions it needs, the built-in token is the only
  token, and nothing updates itself. Upgrades are reviewed changes.
- The page is built with a read-only token and published through GitHub Pages.
- Planned maintenance: open an issue from the **Planned maintenance** template.

The design and the reasons are in the Tithipatra hub's research note
`docs/02-research/notes/status-page.md`.
