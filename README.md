# homebrew-tap

Homebrew tap for [Murmur](https://github.com/yash-coded/voiceprompt).

```bash
brew install --cask yash-coded/tap/murmur
```

Murmur is ad-hoc-signed, so macOS quarantines it on install (current Homebrew
no longer honours `--no-quarantine`). On first launch, approve it via
**System Settings → Privacy & Security → Open Anyway**, or clear the flag:

```bash
xattr -dr com.apple.quarantine /Applications/Murmur.app
```
