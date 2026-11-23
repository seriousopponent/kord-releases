# Kord

A desktop workspace for coding with your own Codex or Claude Code account.

**[Download Kord](https://joinkord.com/#downloadSection)** · **[Release notes](https://github.com/seriousopponent/kord-releases/releases)** · **[Report a bug](https://github.com/seriousopponent/kord-releases/issues)**

This public repository contains official installers, release notes and usage documentation. Kord's application source and development history are maintained in a separate private repository.

## Linux beta 0.4.3

Linux x86_64 packages are available in [the 0.4.3 release](https://github.com/seriousopponent/kord-releases/releases/tag/harness-v0.4.3-linux):

- **AppImage:** download it, make it executable with `chmod +x Kord-Harness-0.4.3-x86_64.AppImage`, then open it.
- **Debian / Ubuntu:** install with `sudo apt install ./Kord-Harness-0.4.3-amd64.deb`.
- **Verify:** download both packages and `SHA256SUMS` into the same folder, then run `sha256sum -c SHA256SUMS`.

These are unsigned Linux beta packages. Updates are installed manually. Public Windows and macOS installers are not available yet.

## First task

1. Install the official Codex or Claude Code CLI. Use a local Git project for isolated Codex edits.
2. Open Kord and choose the project folder. Select your provider, check the CLI sign-in in Kord, and enter a task.
3. In Codex isolated worker mode, open **Sonuç** (Results) to inspect the worker’s patch and any recorded checks. Select **Projeye uygula** (Apply to project) when you’re ready.
4. Claude Code sessions and Codex sessions with read-only workers can edit the selected folder directly.

Codex defaults to GPT-6.2 Astra for orchestration and GPT-6.2 Sol for delegated work. Check records show observed command outcomes. One command can finish before later edits, so review the final patch as well.

No Kord account or subscription is required. Your AI provider's terms, usage limits and charges still apply. Kord is independent of OpenAI and Anthropic.

## Feedback

Use [Issues](https://github.com/seriousopponent/kord-releases/issues) for reproducible bugs and feature requests. Include your Kord version, operating system and steps to reproduce. Remove credentials, private prompts and project files from logs before sharing.

Contact: [hello@joinkord.com](mailto:hello@joinkord.com).

## Terms

Kord is proprietary software. Use is subject to [Kord’s terms](https://joinkord.com/terms) and [privacy policy](https://joinkord.com/privacy). Third-party components retain their own licences and notices.

GitHub's automatically generated “Source code” archives contain this distribution repository’s documentation.
