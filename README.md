# STREET OPS — Real Streets. Real Ops.

Mobile GPS territory game prototype v0.2.

## Map troubleshooting
- The game tries CARTO Streets first, then automatically switches to OpenStreetMap if map images fail to load.
- Use the ▧ layers control at the right to switch maps manually.
- Tap SHOW MORE MAP on the bottom sheet for a wider map view.
- If the map is blank, open the game directly in Chrome, check the data connection and reload. GPS needs permission and HTTPS.

## Included
- Live GPS trail tracking (while app is in foreground)
- Automatic territory capture when the trail crosses an earlier segment
- Claimed areas and route history shown on the map
- 20 original, meme-inspired emoji avatars
- Tap-to-draw demo mode and a one-tap demo loop
- Local saved territories and installable web app

## How to play
Open the site over HTTPS on your phone. Allow location access, tap START GPS, ride a loop, and cross your earlier trail. The loop automatically claims territory.

To test while staying still, tap TRY DEMO LOOP on the OPS screen, or activate DEMO MODE and tap points on the map.

## Known limitations
This is a prototype, not live multiplayer. Maps need internet. Claimed territory is saved in your device browser. Other players cannot see your real-time position. The visibility option stores a future preference only. Keep the app open/unlocked for GPS; most mobile browsers suspend tracking while in the background. Always ride safely without looking at the screen.

## Hosting
The repository currently is private. GitHub Pages hosting options depend on your account plan; for a free Pages deployment, a public repo may be necessary. A public static host is another option. No server, child accounts, or multiplayer databases are set up yet.
