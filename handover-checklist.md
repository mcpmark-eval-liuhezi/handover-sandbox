# Handover Checklist — While Hezi is away

A short routine for covering Hezi Liu's GitHub work (notifications + pull
requests) until they are back from leave.

## Triaging notifications

- Check https://github.com/notifications at least once a day; work through **review requests first**, then mentions, then CI failures, then issue/PR assignments.
- Use the "Participating" filter for threads already in flight; **mute** noisy threads instead of leaving them unread forever.
- Route security alerts (Dependabot, code scanning, secret scanning) to the owning team immediately — do not batch them.
- If a thread genuinely needs Hezi, reply that they are on leave and tag whoever is covering.

## Handling pull requests

- Never commit straight to `main` — **branch first**, then open a PR with a clear title and a short description of what changed and why.
- Read the **whole diff** before approving; leave line-level review comments rather than blanket approvals.
- Wait for CI to pass before merging — if jobs fail, re-run them or investigate; don't ignore red checks.
- Merge with squash, then delete the branch, per the team's routine.

> This branch + pull request is a **live walkthrough**: review it, then merge it
> yourself to complete the exercise.
