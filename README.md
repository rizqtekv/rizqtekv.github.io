# rizqtekv.github.io

Root of the GitHub Pages host for [Bonedle](https://github.com/rizqtekv/bonedle). It forwards
visitors to https://rizqtekv.github.io/bonedle/ and serves `.well-known/assetlinks.json`, which
Android reads from the host's root to verify Bonedle's App Links. Generate that file in the
Bonedle repository with `./gradlew :app:writeAssetLinks -Pbonedle.certSha256=<SHA-256>` and copy
it here.
