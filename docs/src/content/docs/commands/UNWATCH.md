---
title: UNWATCH
description: UNWATCH removes the previously created query subscription
---

<!-- This file is automatically generated. Any modifications made directly to this file
  may be overwritten. For more details on how this file is generated and how to use
  the related commands, refer to the documentation available in the `internal/cmd/cmd_*.go` files.
-->

#### Syntax

```
UNWATCH <fingerprint>
```


WATCH command creates a subscription to the key and returns a fingerprint. Use this fingerprint to UNWATCH the subscription.
After running the UNWATCH command, the subscription will be removed and the data changes will no longer be sent to the client.

Note: If you are using the DiceDB CLI, then you need not run this command given the REPL will implicitly run this command when
you exit the watch mode.
	

#### Examples

```

localhost:7379> UNWATCH 2356444921
OK
	
```
