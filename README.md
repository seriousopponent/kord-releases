# Kord

A desktop workspace for coding agent teams. Bring your own Codex or Claude account.

**[Download Kord](https://joinkord.com/#downloadSection)** · **[Release notes](https://github.com/seriousopponent/kord-releases/releases)** · **[Report a bug](https://github.com/seriousopponent/kord-releases/issues)**

This public repository contains official installers, release notes and usage documentation. Kord's application source and development history are maintained in a separate private repository.

## Linux beta 0.4.2

Linux x86_64 packages are available in [the 0.4.2 release](https://github.com/seriousopponent/kord-releases/releases/tag/harness-v0.4.2-linux):

- **AppImage:** download it, make it executable with `chmod +x Kord-Harness-0.4.2-x86_64.AppImage`, then open it.
- **Debian / Ubuntu:** install with `sudo apt install ./Kord-Harness-0.4.2-amd64.deb`.
- **Verify:** download both packages and `SHA256SUMS` into the same folder, then run `sha256sum -c SHA256SUMS`.

These are unsigned Linux beta packages. Updates are installed manually. Public Windows and macOS installers are not available yet.

## First task

1. Install Git and sign in with the official Codex or Claude Code CLI.
2. Open Kord, select a local Git project and enter a small task in Team mode.
3. For isolated edits, choose Codex and the Git worktree worker mode. Inspect the worker transcript, patch and any recorded test results before applying.
4. Claude Code sessions may edit the project directly; they do not use the Codex worker review flow.

No Kord account or subscription is required. Your AI provider's terms, usage limits and charges still apply. Kord is independent of OpenAI and Anthropic.

## Feedback

Use [Issues](https://github.com/seriousopponent/kord-releases/issues) for reproducible bugs and feature requests. Include your Kord version, operating system and steps to reproduce. Remove credentials, private prompts and project files from logs before sharing.

Contact: [hello@joinkord.com](mailto:hello@joinkord.com).

## Terms

Kord is proprietary software. Public downloads do not grant access to the application source or an open-source licence. Use is subject to [Kord's terms](https://joinkord.com/terms); see also the [privacy policy](https://joinkord.com/privacy). Third-party components retain their own licences and notices.

GitHub's automatically generated “Source code” archives contain this distribution repository's documentation, not Kord's application source.
