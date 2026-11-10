# Mytube updates

Personal Android YouTube client based on [NewPipe](https://github.com/TeamNewPipe/NewPipe) v0.29.2.

Download **Mytube.apk** from [the latest release](https://github.com/sevketsakalli/mytube-updates/releases/latest). Future updates are detected and downloaded inside Mytube. Android asks for installation approval. Keep the existing app installed to preserve local data.

Every release includes **Mytube-source.zip**, containing the corresponding modified application source and build instructions. GPL-3.0-or-later; see LICENSE and MYTUBE.md inside the source archive. Not affiliated with YouTube or NewPipe.

The strict Shorts filter also hides ordinary videos of 3 minutes or less and videos with unknown duration. Embedded sponsor segments are not removed.

Update metadata: `releases/latest/download/update.json`. APK identity, version, SHA-256 and signing certificate are checked before opening Android's installer.
