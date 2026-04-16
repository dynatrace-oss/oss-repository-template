# AGENTS.md

## Purpose

This repository is a template for creating new repositories in the `dynatrace-oss` organization.

Agents working in this repository should optimize for:
- clear ownership
- durable repository standards
- minimal but useful baseline automation
- documentation that is easy for maintainers to update after repository creation

## Repository expectations

- Keep changes simple, explicit, and easy for maintainers to understand.
- Prefer small, reviewable pull requests.
- Do not remove required governance files without a clear reason.
- Preserve placeholder content only where the maintainer is expected to replace it after generating a repository from this template.

## Required baseline files

Unless the task explicitly says otherwise, preserve or improve the following files:
- `README.md`
- `LICENSE`
- `CODEOWNERS`
- `SUPPORT.md`
- `.github/PULL_REQUEST_TEMPLATE.md`
- `.github/dependabot.yml`
- `.github/workflows/`
- `.github/ISSUE_TEMPLATE/`

## Documentation guidance

- Treat the root `README.md` as a maintainer setup guide for the template.
- Keep instructions concrete and action-oriented.
- Prefer policy-style wording over informal guidance where expectations are mandatory.
- Make support and ownership expectations explicit.

## Workflow guidance

Before proposing changes:
- check whether ownership, support, or publication expectations are affected
- preserve branch protection and review-friendly workflows
- avoid adding unnecessary complexity or language-specific tooling unless requested

## Pull request guidance

When preparing a pull request:
- summarize what changed
- explain why the change improves the template
- call out any new required maintainer actions
- keep examples short and easy to copy

## Review guidelines

When reviewing this repository or generated repositories:
- verify `CODEOWNERS` is present
- verify support expectations are documented
- verify placeholder text is clearly marked
- verify no secrets or environment-specific values are included
- verify baseline automation is present and understandable

## What to avoid

- Do not assume repositories created from this template are commercially supported.
- Do not add heavy automation unless it is broadly useful across most repositories.
- Do not leave unclear placeholders that could accidentally ship to a public repository.
