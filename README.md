# AnimeStream (iOS)

SwiftUI app: AniList discovery, AVPlayer playback, user-added source repos.
Ships with NO sources. Users add their own repo URLs in the Sources tab.

## Build (no Mac needed)
1. Push this folder to a GitHub repo (branch `main`).
2. Repo > Actions > "Build IPA" > wait for green check.
3. Open the run > Artifacts > download `AnimeStream-ipa`, unzip.
4. Sideload `AnimeStream.ipa` with SideStore.
If the build fails, download the `build-log` artifact and send me the errors.

Keep API keys out of the repo (Secrets.xcconfig / .env are git-ignored).
