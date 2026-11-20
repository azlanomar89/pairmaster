# PairMaster

Pairings, results and standings for Scrabble tournaments, in a single file that runs offline in
your web browser. PairMaster reads and writes AuPair 6.16 `.TOU` files exactly as AuPair does,
so it fits into the existing ratings workflow.

## Download and run

1. Download the latest `PairMaster-x.y.zip` from the [Releases](../../releases/latest) page and unzip it,
   or download `PairMaster.html` on its own.
2. Double-click `PairMaster.html`. It opens in your browser; nothing is installed and no internet is needed.
3. Use **Google Chrome** or **Microsoft Edge** for the best experience (they let PairMaster save
   into a folder you choose). Safari and Firefox work too, but saved files go to Downloads.

Read the [user guide](guide.html) (also linked from **Help** inside the app).

## Features

- **Draws:** Australian (Swiss, no rematches, with fresh start), Lagged Australian, King of the Hill,
  Round robin, Halves, Quarters, Chance; first-round quarters/halves/chance options.
- **Byes and designated results** handled as AuPair does; missing players and late entrants.
- **Balanced starts** (who goes first), fixed tables (`@12`, `@R`), manual re-pairing.
- **Gibsonization** for clinched prize places.
- **Several divisions**, with table numbers running on from one division to the next.
- **Standings** by wins then spread (or total score), at any earlier round.
- **Printouts:** pairings, round results, standings, player scorecards, wall chart, round-robin schedule.
- **AuPair `.TOU` files:** open and save, byte-for-byte compatible with AuPair 6.16.
- **Safe by design:** autosaves in your browser, reminds you to save a `.TOU` backup after each
  round, checks damaged files before opening them, and makes no internet connections at all.

## Testing

PairMaster's standings were compared with AuPair's own `touprint` program on thousands of random
tournaments and with TSH 3.340 on hundreds more, with the same results. Its draws were stress-tested
up to 500 players and 60-player, 59-round events.

## Versions

- **1.0.1**: `.TOU` files now match AuPair 6.16 exactly in every case found by round trips through AuPair itself:
  a player left without an opponent in a division of 10+ players, opponents numbered 100+, and byes.
- **1.0**: first public release.

## Licence

MIT. See [LICENSE](LICENSE). Free to use, copy and share.

Written by Mohamad Azlan Omar.

PairMaster is an independent program. It is not affiliated with or endorsed by the authors of
AuPair or TSH; those names belong to their respective owners.
