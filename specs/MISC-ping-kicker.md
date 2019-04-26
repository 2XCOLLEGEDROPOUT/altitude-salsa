# Ping-Kicker
Replace Altitude's built-in ping-kicker with a custom one:
1. Only work on players who are **not** spectating. No reason to kick spectators.
1. Poll each player's ping and kick on exceeding streaks.
1. Also consider spiking connections that might not be kicked by merely checking for exceeding streaks. Maybe give it a stability score and define a limit on that metric.
1. If using a stability score, define a limit on game start to only take into account stable-ping players when assigning teams.
