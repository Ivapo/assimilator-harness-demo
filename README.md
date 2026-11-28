# Assimilator: recorded example studies

https://ivapo.github.io/assimilator-harness-demo/

Two example studies made with the Assimilator harness, replayed in your browser exactly as they were run: a question asked in
plain words, the test design the harness proposed and the user approved, the simulation runs, and the answer with its
uncertainty. Nothing on this site runs an AI model or a simulation, and you can't ask a question of your own here. Reports
and slides aren't available to download yet.

- Barcelona, Poblenou: "If Poblenou's nine blocks became a superblock, how much more traffic would the streets around them carry, and which streets?"
- Norrköping: "How much does the morning's car traffic make Norrköping's buses late, and on which lines?"

The simulator itself runs in your browser at https://ivapo.github.io/assimilator-demo/.

## Data

- Street networks, their geometry and street names: © OpenStreetMap contributors, available under the Open Database License (ODbL), https://www.openstreetmap.org/copyright. The recorded studies hold extracts of them.
- Norrköping's bus timetable: Östgötatrafiken's GTFS feed (CC0).
- The car trips are not observed traffic and not a forecast: Poblenou's are illustrative, written by rule; Norrköping's are synthetic, generated from open map data. Each study's sources and credits are in `examples/<id>/README.md`.

## Code

This repository holds the site as built: the page's code, minified. The harness's source is not published, and no licence
is granted for this code. The open-source packages the page includes, and their licences, are listed in
`THIRD_PARTY_NOTICES.md`. The page's mono face is JetBrains Mono 2.304 (Regular and Bold, unmodified), © 2020 The JetBrains
Mono Project Authors, under the SIL Open Font License 1.1; its licence is `fonts/jetbrains-mono/OFL.txt`. `build-info.json`
lists the last commits of the harness's repository at the build, for the page's Recent updates.

This repository is written by a deploy from the harness's own repository; a change made here is overwritten.
