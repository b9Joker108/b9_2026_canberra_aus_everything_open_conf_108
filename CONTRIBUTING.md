File: xxx

# Contributing to This Repository

Welcome! We’re excited to have you collaborate. This repository is designed for high transparency, knowledge-centric development, and seamless onboarding of both human contributors and AI agents.

---

## 1. Commit Message Policy (AI-Driven, Detailed, and Reviewable)

**Required:**  
- Every commit message **must** be detailed and descriptive.
- If available, use GitHub Copilot or compatible AI to auto-generate the commit summary.  
  - Commit message should summarize:  
    - What changed  
    - Why it changed (rationale, context)  
    - Any special risks or follow-ups
- Always review (and edit, if needed) the generated message before finalizing your commit.

**Why?**  
- Detailed commit messages are critical for:  
  - Knowledge base creation and later reference  
  - AI underwriter and Oracle assistant training  
  - High-quality PR reviews and onboarding  
  - Effective compliance and auditing

Refer to [`.github/COPILOT_FEATURES.md`](.github/COPILOT_FEATURES.md) and [`./.copilotrc`](./.copilotrc) for policy and AI configuration.

---

## 2. Repo-Level Configuration

- All Copilot and repo automation preferences are in:
  - `.github/COPILOT_FEATURES.md` — feature policy and future-proofing
  - `.github/copilot.json` — machine-readable settings
  - `.copilotrc` — additional configuration for tools/bots
- If you build integrations or tools, **read and respect these files**.

---

## 3. Branching & PR Guidelines

- Use descriptive branch names for features and fixes (`feature/org-structure-improvements`, `bugfix/stakeholder-role-labeling`, etc.).
- All changes must go through pull requests.
- PR descriptions should clarify context, rationale, and relevant links or decisions.
- Use AI suggestions (where available) for both commit and PR descriptions, then review.

---

## 4. Knowledge Capture & Documentation

- When adding new features or patterns, update documentation as you go.
- Ensure that changes to conventions, scaffolding, or AI policies are reflected in all relevant config/documentation files.

---

## 5. Collaborator & AI Onboarding

- New human and AI collaborators:  
  - Read this `CONTRIBUTING.md` in full.  
  - Understand expected workflows, commit/PR protocols, and configuration defaults.

- AI/Oracle agents:  
  - Parse `.github/copilot.json` and `.copilotrc` for workflow and summarisation config.
  - Use commit/PR metadata for ongoing training and semantic context.

---

## 6. Inclusion, Accessibility & Security

- Follow [GitHub’s Community Guidelines](https://docs.github.com/en/site-policy/github-terms/github-community-guidelines).
- All code, docs, and commit messages must be accessible and free of secrets/personal data.

---

## 7. Feedback and Iteration

- Propose updates to this file if workflows or expectations evolve.
- Raise issues for any ambiguity or improvement in documentation, automation, or Copilot tuning.

---

Thank you for helping advance knowledge-driven, AI-augmented collaboration!
