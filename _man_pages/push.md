---
title: "push"
description: "The push command description and usage"
keywords: ["share, push, image"]
parent: "smn_cli"
layout: man_pages
---

# push

    Usage: docker push [OPTIONS] NAME[:TAG]

    Push an image or a repository to the registry

      --disable-content-trust=true   Skip image signing
      --help                         Print usage

Use `docker push` to share your images to the [Docker Hub](https://hub.docker.com)
registry or to a self-hosted one.

Killing the `docker push` process, for example by pressing `CTRL-c` while it is
running in a terminal, will terminate the push operation.

Registry credentials are managed by [docker login](login.md).
