---
layout: post
title:  "Simple SSH tunnel"
date:   2014-09-06 17:02:00
categories: ssh, ssh_tunnel
---

Just found amazing way to create ssh tunnel from remote host port to your localhost.

```
ssh -f user@server -L <local_port>:127.0.0.1:<remote_port> -N
```

* -f key to run it in background
* -N key to not execute a command on the remote system (without it -f key has no effect and command hangs with error)
