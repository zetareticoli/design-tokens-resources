# design-tokens-resources

A small collection of checklists and templates to help teams design, audit, manage, and propose changes to design tokens.

This repository contains opinionated resources you can copy or adapt to establish governance and processes around design tokens across platforms.

Contents

- `design-tokens-audit-checklist.md` — A detailed audit checklist to validate tokens before release (naming, scales, units, accessibility, usage, documentation, and implementation checks).
- `design-tokens-management-checklist.md` — Ongoing management and release checklist that covers versioning, deprecation, distribution, automation, and repository responsibilities.
- `design-tokens-proposal-pr-template.md` — A pull request template to propose token additions or changes; includes motivation, migration strategy, examples, and testing guidance.
- `LICENSE` — Repository license.

How to use these files

1. Copy and adapt: Use these files as starting points. Copy them into your design system repository or create references to them in your team handbook.
2. Propose changes: When proposing a token change, create a branch in your tokens repo, update the token source files (JSON/TS/SCSS, etc.), then open a PR using the `design-tokens-proposal-pr-template.md`.
3. Run the audit: Before merging, run through `design-tokens-audit-checklist.md` as part of your PR review. Confirm accessibility (contrast, ranges), naming consistency, units, token usage, and test coverage across platforms.
4. Follow management checklist: For releases or deprecations, use `design-tokens-management-checklist.md` to ensure versions, changelogs, migration guides, and consumers are notified.

Recommended workflow

- Fork or branch your design tokens repo.
- Make changes to the token source files.
- Fill out the proposal PR template in the PR description.
- Attach screenshots, token usage examples, and migration instructions.
- Assign reviewers from both design and engineering.
- Verify platform builds and automated tests that consume tokens.
- Run the audit checklist and address findings before merging.

Customizing for your team

These resources are intentionally generic. Tailor the checklists and template to match your tooling, token formats, and release cadence. Consider adding automation steps that fail CI if tokens break contracts (naming, missing tokens, type mismatches).

Contributing

- Improvements welcome: open an issue to discuss changes or submit a PR with edits to these documents.
- If you add new resources, follow the same template style and add an entry to this README.

License

This repository is licensed under the terms in the `LICENSE` file.

Contact

If you have questions or need help adapting these resources, open an issue or contact the repository owner.
