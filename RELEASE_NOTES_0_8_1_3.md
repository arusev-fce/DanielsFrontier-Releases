# Daniel's Frontier 0.8.1.3 Hotfix

- Corrects Stormrider's in-world size to fit between Arclight and Horizon. Its authored weapon and engine markers scale with the model.
- Reduces first-hit hull-contact setup and prepares acceleration data ahead of combat. Tested impact positions are unchanged.
- Reuses BIO droplet geometry while preserving the barrage's size, motion, timing and appearance.
- Expands connection reports with snapshot-stage, combat-effect, hull-query/cache, movement/turn/reset, allocation/GC and rendering counters.
- Separates HTTP transport timing from the delay resuming on the game thread. This helps distinguish connection spikes from client stalls.
- Send report to support continues to deliver the report directly to the private inbox. Matching server accepts the new metrics.

Gameplay balance and movement speeds are unchanged. These changes address measured client hitches; they do not claim to eliminate every connection spike. Updater binary unchanged.
