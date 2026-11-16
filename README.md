# ENSLD 300-420 Practice Exam

Practice app for Cisco CCNP ENSLD (300-420 v1.1). 713 original questions, weighted to the blueprint (25/25/20/20/10).

- **Full exam**: 60 questions, 90 minutes, all drawn from the hard scenario set. Cisco-style rules by default: one question at a time, no going back, no flags. Switch to "Allow review" on the home screen if you want.
- **Hard scenarios**: 213 requirement-driven design questions, choose-two items, exhibits (configs, tables, BGP paths), and drag-and-drop style matching.
- **5-question test**: timed (8 min), scored at the end, hard scenarios only.
- **Quick practice, domain drills, missed questions**: 5, 10, 20, 50, or all at a time, unseen first.
- Offline-capable PWA with backup/restore of progress.

## Files

- `index.html`: the app and the core question bank
- `hard1.js` (domains 1-2) and `hard2.js` (domains 3-5 plus exhibits): the hard set. `hard3.js` and `hard4.js` add a tougher second set (multi-constraint designs, exhibits to work out). Fields: `id, d, h:1, q, o, a, e`. Match items use `t:"m"`, `items`, `cats`, and `a` as the category index for each item.
- `sw.js`, `manifest.webmanifest`, `icon-*.png`: offline support and install

Questions are original study material, not exam dumps.
