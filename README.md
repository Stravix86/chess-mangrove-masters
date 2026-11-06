# Chess Mangrove — Masters database

Static files used by the Chess Mangrove site's "Learn from masters" to find master games that followed a player's exact move order.

- Over-the-board master games: [PGN Mentor](https://www.pgnmentor.com/files.html) player collections.
- Online games between 2500+ players: [Lichess Elite Database](https://database.nikonoel.fr/), derived from the [Lichess database](https://database.lichess.org/) (CC0).

Built with `scripts/build-masters.mjs`. Each game keeps its first 30 moves; Lichess games link to the full game.
