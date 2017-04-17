# Pgbouncer Docker Image

Create a folder containing ```pgbouncer.ini``` and ```userlist.txt``` and mount configuration as volume::

    docker run -v <pgbouncer_config_dir>:/etc/pgbouncer:ro pgbouncer

The default configuration file writes logs to STDOUT
And listens on ``localhost:6432``.
