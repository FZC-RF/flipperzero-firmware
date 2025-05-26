# Contributing to FZC-RF

Welcome to the Flipper Zero Cyber Resilience Firmware (FZC-RF) project! We’re building a defense-first firmware for ethical red/blue teaming, featuring AI anomaly detection and robust protocol support. Your contributions are vital to our success.

## How to Contribute
- **Code Style**: Follow Flipper SDK conventions (see `CODING_STYLE.md`). Use 4-space indents, camelCase for variables/functions.
- **Formatting**: Run `clang-format` on C files before submitting.
  `ash
  clang-format -i file.c
  ``n- **Pull Requests (PRs)**:
  - Fork the repo: `https://github.com/FZC-RF/flipperzero-firmware`.
  - Create a branch: `git checkout -b feature/your-feature`.
  - Commit changes: `git commit -m \"Add feature X\"".
  - Push: `git push origin feature/your-feature`.
  - Open PR with clear title, description, and linked GitHub Issue.
  - PRs require at least one approval.
- **Issues**: Report bugs/features via GitHub Issues. Use labels: `bug`, `feature`, `docs`, `enhancement`.
- **Ethics**: Adhere to `docs/ethics.md`. Ensure contributions align with ethical use (authorized testing, legal compliance).

## Development Process
- **Phase 1 (May 26-30, 2025)**: Set up repo, dev environment, and docs.
- **Phase 2 (May 31-June 4)**: PoC with Sub-GHz replay, BLE spoofing, ethical UI.
- **Phase 3 (June 5-15)**: Beta with Sub-GHz, NFC, BLE, AI, Lua scripting.
- **Phase 4 (June 16+)**: Refine AI, release tools, engage community.

## Community
- Join our Discord (`FZC-RF-Dev`, link in `README.md`) for collaboration.
- Engage on X: #FZC-RF, #FlipperZero.
- Test builds via r/flipperzero (sign up on Discord `#community`).

Thank you for contributing to FZC-RF’s mission of cybersecurity resilience!
