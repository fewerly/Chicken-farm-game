# Chicken Farm Game — Test checklist

## Manual checks (not yet executed on real devices)
1. Open the site on Android Chrome, iOS Safari and desktop Chrome.
2. New player sees 1,000 coins, 1 plot, 0 eggs and 0 chickens.
3. Buy egg: coins fall to 900 and timer begins near 24:00:00.
4. Refresh: egg and coins persist in the same browser.
5. Attempt 11 eggs on one plot: the 11th is rejected.
6. Wait 24 hours or use a controlled test clock: egg becomes a chicken.
7. Immediately after hatch, collecting gives no coins.
8. After another 24 hours, collecting grants 25 coins per chicken, only once.
9. Buy land: cost 500 coins, capacity increases by 10.
10. Test offline shell only after first successful online load over HTTPS.
11. Install from a compatible browser and verify standalone display.

## Known limitations
- Game is local-only and can be modified via browser tools.
- Browser localStorage can be cleared; no account recovery.
- Real-time economy needs a server authoritative clock and database.
- No blockchain, payments, Solana tokens or NFTs implemented.
- Deployment and device testing are pending.
