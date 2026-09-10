# .github

Organization-wide defaults for **Certum-Legal-Solutions**.

GitHub serves the files here to any repository in the organization that does not
carry its own copy — so a pull request template lives in one place instead of
being copy-pasted into every repository as the repository count grows.

## This repository is public, and it has to be

GitHub does not support a private `.github` repository for default community
health files, and pull request templates in particular are only served
organization-wide from a **public** one. Everything committed here is
world-readable. Nothing about the organization's private repositories is exposed
by that on its own — but the contents of *these files* are, so write them for a
public audience and keep internal specifics out.

The defaults still apply to private repositories; only this repository is public.

## What is here

| File | Serves |
|---|---|
| `profile/README.md` | The organization's public profile page |
| `SECURITY.md` | Vulnerability reporting policy, to every repository without its own |
| `PULL_REQUEST_TEMPLATE.md` | The default pull request template |

## Overriding a default

A repository that needs something different commits its own copy at the same
path. The local copy wins; nothing here needs changing.
