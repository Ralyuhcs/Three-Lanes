# Three Lanes — Online PvP Playtest (v2.9)

Free static hosting with GitHub Pages. No paid hosting required.

## Publish

1. Sign in to https://github.com and create a new **Public** repository named `three-lanes`.
2. Open the repository, choose **Add file → Upload files**.
3. Extract this ZIP on your computer and upload **index.html** and **README.md** to the root of the repository. Do not upload the ZIP itself.
4. Click **Commit changes**.
5. Go to **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select branch **main**, folder **/(root)**, then **Save**.
8. Wait for deployment and visit `https://YOUR-USERNAME.github.io/three-lanes/`.

## Test multiplayer

- Both players visit the same hosted website on separate devices.
- Select **Online**, then choose a deck.
- Player 1 selects **HOST A GAME** and shares the six-digit code.
- Player 2 enters the code and selects **JOIN GAME**.
- The host selects **START MATCH**.
- Both devices need an active internet connection.

## Notes

- Online play is experimental, using PeerJS from a CDN and its public signaling infrastructure. Free availability and connection success are not guaranteed.
- Peer-to-peer networking may fail on some restricted networks; there is no guaranteed reconnection.
- This is not a cheat-resistant or production-grade multiplayer server.
- To publish updates, replace `index.html` in the repository and commit.

Game build: v2.9
