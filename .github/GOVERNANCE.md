# Governance

> **Status: draft.** This document describes a generic, minimal governance
> structure and is a starting point for the ICT Directorate to review, amend,
> and formally adopt. It is not yet an approved Ministry policy. Replace the
> placeholders below once the Director of ICT confirms the actual roles,
> names, and escalation path.

## Purpose

This document describes how decisions are made across repositories in the
`mohcc-zw` GitHub organization: who can approve changes, how new projects
and maintainers are added, and how disagreements are resolved.

## Roles

| Role | Responsibility |
|---|---|
| **Director of ICT** (sponsor) | tchawurura@mohcc.org.zw — final decision authority for the organization; approves new repositories, org-wide policy changes, and resolves escalations. |
| **Organization owner / maintainer** | ichihwai@mohcc.org.zw — holds GitHub admin rights on `mohcc-zw` (GitHub account: chihwayi); manages membership, org settings, and org-wide `.github` defaults (this repository); reviews and merges pull requests. |
| **Contributors** | Anyone submitting issues or pull requests per [CONTRIBUTING.md](CONTRIBUTING.md). |

*As more projects and staff join the organization, add named maintainers per
repository here.*

## Decision-making

- **Day-to-day changes** (bug fixes, minor features) are approved by a
  project's maintainer(s) via normal pull request review.
- **Significant changes** (new dependencies, architecture changes, anything
  touching health-data handling) require sign-off from at least one
  organization owner in addition to the maintainer.
- **Org-wide changes** (this `.github` repository, new repositories, adding
  or removing members) require approval from an organization owner, with
  the Director of ICT notified.

## Escalation path

1. Raise the disagreement in the relevant issue or pull request.
2. If unresolved, a project maintainer escalates to an organization owner.
3. If still unresolved, the organization owner escalates to the Director of
   ICT, whose decision is final.

## Adding or removing members and repositories

- New repositories are created by an organization owner, following the
  naming and structure conventions used across this organization.
- New members are added by an organization owner after confirmation from
  the Director of ICT (or delegated authority).
- Members who violate the [Code of Conduct](CODE_OF_CONDUCT.md) may have
  their access revoked by an organization owner.

## Amending this document

Changes to this document require approval from an organization owner and
notice to the Director of ICT. Once formally adopted, this notice and the
"draft" status above should be removed.
