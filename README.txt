FAMILY FEUD ANYTIME — 2v2 GAME NIGHT
====================================
This is a SEPARATE game from Thanksgiving Family Feud.

Features:
- 100 original everyday game-night questions, 6 answers each
- Random questions and fewer repeats between games on the same host device
- Two teams of two; 3/5/7/10 questions per game; tiebreakers
- Automatic three-stage answer matching, scores, strikes, play/pass/steal
- 5-question practice mode and animated how-to-play instructions
- iPhone host and live iPad / AirPlay audience board
- Save/resume game and sound, with no sign-in or paid hosting
- Reuses your existing free Firebase Realtime Database project

HOW TO PUBLISH ON GITHUB PAGES
1. Leave your existing thanksgiving-family-feud repository ALONE.
2. On GitHub, create a NEW public repository: family-feud-anytime.
3. Upload the included index.html and live.js to the root of that new repository.
4. Commit the changes to the main branch.
5. Go to Settings > Pages > Build and deployment > Deploy from a branch.
6. Set Branch = main and folder = / (root), then Save.
7. Your new site should be at:
   https://3d4ubusiness.github.io/family-feud-anytime/
   (This URL is a suggestion until you actually create the repo.)
8. Open the site on your iPhone. Tap Start iPad / TV connection.
9. Use Copy iPad link and open it on the iPad, then AirPlay iPad to TV.

FYI: The Firebase configuration is public client-side information (normal for web apps).
The database access rules control who can edit sessions. Keep your existing
Firebase Authentication Anonymous sign-in and Realtime Database rules enabled.

Survey-style scores are made up for a fun home game; they are not official survey data.
