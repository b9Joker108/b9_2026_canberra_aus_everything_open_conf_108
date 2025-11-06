# GitHub Copilot Features, Behaviours, and Future-Proofing for This Repository

## Purpose

This document explicitly defines preferred, requested, and required behaviors for GitHub Copilot, Copilot Chat, Copilot Labs, and any related automation or AI-driven assistance in this repository. The instructions herein should be respected by all Copilot tools, bots, plugins, and future integrations for consistency, transparency, and productivity across all contributors and automation actors.

---

## Commit Message Generation

- **Default Behavior:**  
  — All commit messages **must** be automatically populated using AI-powered summarisation (Copilot or compatible).  
  — Summaries should be "detailed," i.e., they must describe the nature and scope of changes, affected sections, and rationale where possible.
  — After autogeneration, users should have the option to review and revise the suggested message pre-commit.
  — Feature should apply to all branches and all contributors.

- **Fallback:**  
  If Copilot (or other AI) is unavailable, fall back to detailed template-driven summaries. Indicate tool state in the commit message.

---

## Feature Guidance & Value-Add Scaffolding

### Current Feature Requirements

- **AI Summarisation:**  
  - Always on for commits and pull request descriptions.
  - Use natural language and, if valuable, include code block context for major additions or refactors.
- **Configurability:**  
  - Respect `.copilotrc` and `copilot.json` in repo root or `.github/`.
  - Prefer this COPILOT_FEATURES.md for clarifications or overrides.
- **Transparency:**  
  - Copilot and integrations should report any unhandled features, unsupported options, or version mismatches as comments or notifications.

### Value-Add Scaffolding

- **Multi-language Support:**  
  - Enable commit summarisation and code suggestion in all repository languages.
- **Accessibility:**  
  - All Copilot features must support accessibility standards (screen reader compatibility, keyboard shortcuts, descriptive help).
- **Security:**  
  - Detect and warn about committing secrets or sensitive information, summarise security-relevant changes.
- **Review Guidance:**  
  - Offer AI-powered suggestions for PR reviews, providing context links to referenced standards or previous related changes.

---

## Future Directions & Extensibility

- **Branch/Contextual Customization:**  
  - Allow toggling different Copilot behaviors per branch, per directory, or per file type via configuration.
- **Integration with Automated QA:**  
  - Summarize test coverage changes, point out QA-relevant diffs in commit and PR messages.
- **Commit Message Hooks:**  
  - Optionally enforce or validate presence and detail-level of AI-generated summaries before permitting push/merge.
- **Copilot Plugins:**  
  - Integrate with custom repo or org-level Copilot plugins (local or hosted) for enhanced commit message rules, security scanning, or change classification.

---

## Collaboration and Community Feedback

- Contributions to this file or the related config are welcome.  
- Issues and PRs proposing updates to Copilot interaction, configuration, or value-add features are strongly encouraged.

---

## References

- See [./copilot.json](./copilot.json) for machine-readable configuration.
- See [./.copilotrc](../.copilotrc) for additional repo-level configuration.
- For Copilot documentation: [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- For feedback: [GitHub Copilot Discussions](https://github.com/github/feedback/discussions/categories/copilot)

---

_Last updated: 2025-11-06 by b9Joker108. Please keep this document up to date as new Copilot features and workflows become standard._
