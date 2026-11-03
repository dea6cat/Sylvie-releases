# Sylvie

Sylvie is a workspace for building software with coding agents. A thread is a
project: it has the tools you build with (an editor and file Explorer, Git, run
and debug, terminals, language servers, Flutter tools) and a harness that does
the work, such as Claude Code, Clyde, Pi or Codex. Follow a thread live, steer it
at any point, or hand it to another harness.

You can use Sylvie from the desktop app, a browser, a phone on your Wi-Fi, a
command line, or an HTTP API. It runs on your own machines and sends no usage
data.

This repository holds the downloads and the issue tracker. The source code is
not published here.

## Download

Get the latest build from [Releases](https://github.com/dea6cat/Sylvie-releases/releases/latest). Needs an Apple Silicon Mac (M1 or later).

1. Download the `.dmg` and open it.
2. Drag **Sylvie** to Applications.
3. The app is not code-signed yet. The first time, right-click Sylvie and choose **Open**. If macOS still blocks it, run `xattr -dr com.apple.quarantine /Applications/Sylvie.app` in Terminal.

Sylvie checks for new versions itself from 1.28.3 on. If you have 1.28.1 or
1.28.2, download the latest build once by hand.

The two "Source code" links GitHub adds to every release hold only this
repository's README and issue forms, not the Sylvie source.

## Report a problem or ask for a feature

Open an [issue](https://github.com/dea6cat/Sylvie-releases/issues/new/choose). [FILING_ISSUES.md](FILING_ISSUES.md) explains what a useful report contains.
