# Elimination players

Download the current list here:

[`players.json`](https://raw.githubusercontent.com/WinterValor/elim_players_2026/main/players.json)

The file starts from the completed 730-day active-player scan. It contains
players whose FFScouter `bs_estimate` was above 1 billion and who still returned
`Unknown` for the Elimination team at the most recent scan. It is refreshed by an
automated scanner in the private [`elim_scanner`](https://github.com/WinterValor/elim_scanner)
repository. A player disappears from this file as soon as Torn reports a team.

Fields are `name`, `id`, `team`, `bs estimate`, and `bs estimate human`.

