# Development workflow

## 1. Plan
- Keep a prioritized backlog split into gameplay, narrative, art/animation, online systems, platform, analytics, QA, and publishing.
- Every task has an owner, acceptance criteria, risk, estimate, and dependency.
- Protect the ₹10 lakh prototype ceiling; obtain quotes and update the forecast weekly.

## 2. Implement
- Use Unity 6 LTS + URP only after a small device and pipeline spike confirms suitability.
- Keep source control for scripts, project settings, prefabs, scenes, and configuration. Use Git LFS for large binary assets if needed.
- Never commit API keys, signing keys, credentials, personal data, or private vendor materials.
- Prefer small changes and short-lived branches: `feature/<short-name>`, `fix/<short-name>`, `docs/<short-name>`.
- Require review for gameplay-affecting changes and any network/security changes.

## 3. Validate each change
- Run formatting/static checks available for the changed code.
- Run Unity EditMode tests; run PlayMode tests for gameplay behavior when available.
- Test on at least one low/mid-range Android device and one target reference device for relevant performance changes.
- Record reproduction steps, device/build details, expected vs actual behavior, and logs for defects.

## 4. Definition of done
- Acceptance criteria pass.
- No new critical/high-severity defect is known.
- Tests and device checks are recorded.
- Analytics and failure states are considered.
- Documentation and changelog are updated where behavior changes.
- Reviewer approval is recorded before merge.

## 5. Build/release
- Keep development, QA, and release builds separate.
- Use signed builds only in protected release infrastructure; signing credentials must be stored in a secret manager.
- Smoke-test install, startup, tutorial, mission completion, reward persistence, and 1v1 matchmaking before a test release.
- Tag releases and retain build artifacts plus test notes.

## 6. Current repository limitation
This repository was empty at initialization. These workflows are a starting process guide, not evidence of an existing Unity project, automated Unity build, or tested gameplay implementation. Add actual game source and configure Unity-specific CI after the project exists.
