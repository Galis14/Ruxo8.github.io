---
title = "stop"
description = "The stop command description and usage"
keywords = ["stop, SIGKILL, SIGTERM"]
parent = "smn_cli"
---

# stop

    Usage: docker stop [OPTIONS] CONTAINER [CONTAINER...]

    Stop a container by sending SIGTERM and then SIGKILL after a
    grace period

      --help             Print usage
      -t, --time=10      Seconds to wait for stop before killing it

The main process inside the container will receive `SIGTERM`, and after a grace
period, `SIGKILL`.
