Introduction
============

For larger networks, RTRTR is an ideal companion to Routinator. For example, it
is possible to centralise validation performed by Routinator and have RTRTR
running in various locations around the world to which routers can connect.

RTRTR can read RPKI data from multiple RPKI Relying Party instances via RTR and
JSON and, in turn, provide an RTR service for routers to connect to. The HTTP
server provides the validated data set in JSON format, as well as a monitoring
endpoint in plain text and Prometheus format. RTRTR also supports SLURM, so you
can add your local exceptions to any instances you're pulling data from.
