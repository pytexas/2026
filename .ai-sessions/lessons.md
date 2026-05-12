# Lessons Learned

## Recent
<!-- 10 most recent lessons, newest first -->
- A `[text](url1 url2)` typo in markdown survives local preview but lychee URL-encodes the space to `%20` and reports a single 404. Run `just link-check` before pushing schedule/talks edits (2026-05-12)
- When one instance of a service fails link-check but other instances of the same service pass on the same branch, it's targeted rate-limiting. Prefer a single-URL `.lycheeignore` entry over a wildcard (2026-05-12)
- For failing GH Actions logs, `gh api repos/{owner}/{repo}/actions/jobs/{id}/logs` is more reliable than `gh run view --log`, which can return empty (2026-05-12)
- Before removing a URL from a markdown link target, verify the URL is linked elsewhere on the page so no info is lost (2026-05-12)
- Never use em-dashes in user-facing prose for Mason. Rewrite with commas, periods, colons, or restructured clauses (2026-05-12)
- When marking a conference site as post-event, keep the SEO-rich descriptive paragraph from the original. Rewrite it to past tense rather than deleting it (the 2025 archive does this) (2026-05-12)
- When editing a file, grep the same file for related issues (e.g. other em-dashes) in the same pass instead of leaving them as a separate follow-up (2026-05-12)
- Before proposing a rewrite, list the load-bearing elements of the original (bold emphasis, anchor keywords, anniversary/branding callouts) and confirm each survives the rewrite (2026-05-12)
- Run `gh pr view` and `gh api .../comments` in parallel to pull PR metadata and inline review comments in one round trip (2026-05-12)

## Workflow
- Before proposing a rewrite, list the load-bearing elements of the original (bold emphasis, anchor keywords, anniversary/branding callouts) and confirm each survives the rewrite (2026-05-12)
- When editing a file, grep the same file for related issues (e.g. other em-dashes) in the same pass instead of leaving them as a separate follow-up (2026-05-12)
- Before removing a URL from a markdown link target, verify the URL is linked elsewhere on the page so no info is lost (2026-05-12)

## Documentation
- When marking a conference site as post-event, keep the SEO-rich descriptive paragraph from the original. Rewrite it to past tense rather than deleting it (the 2025 archive does this) (2026-05-12)
- Never use em-dashes in user-facing prose for Mason. Rewrite with commas, periods, colons, or restructured clauses (2026-05-12)

## Tooling
- Run `gh pr view` and `gh api .../comments` in parallel to pull PR metadata and inline review comments in one round trip (2026-05-12)
- For failing GH Actions logs, `gh api repos/{owner}/{repo}/actions/jobs/{id}/logs` is more reliable than `gh run view --log`, which can return empty (2026-05-12)

## Debugging
- A `[text](url1 url2)` typo in markdown survives local preview but lychee URL-encodes the space to `%20` and reports a single 404. Run `just link-check` before pushing schedule/talks edits (2026-05-12)
- When one instance of a service fails link-check but other instances of the same service pass on the same branch, it's targeted rate-limiting. Prefer a single-URL `.lycheeignore` entry over a wildcard (2026-05-12)
