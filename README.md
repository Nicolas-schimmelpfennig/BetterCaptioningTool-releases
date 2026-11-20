# Better Captioning Tool — downloads

Animated captions for video, timed to every spoken word. Transcribed and refined by
[Claude Code](https://claude.com/claude-code), fine-tuned in this Mac app.

## Install

1. Download the newest **BetterCaptioningTool-&lt;version&gt;.zip** from the
   [releases page](https://github.com/Nicolas-schimmelpfennig/BetterCaptioningTool-releases/releases/tag/updates).
2. Unzip it and move **BetterCaptioningTool.app** to your Applications folder.
3. Open it. If macOS says it can't verify the app, open **System Settings → Privacy & Security**,
   scroll down and click **Open Anyway** (once).

After that the app updates itself: **Better Captioning Tool → Check for Updates…**

## Requirements

- macOS 26 on Apple silicon
- [Claude Code](https://claude.com/claude-code), signed in — then choose
  **Better Captioning Tool → Connect to Claude Code…** once
- ffmpeg and Python 3.10+: `brew install ffmpeg python`

The first transcription sets up a Python environment and downloads the speech models (about 2 GB).

This repository only hosts the app downloads and its update feed.
