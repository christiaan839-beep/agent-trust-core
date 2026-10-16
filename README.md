# agent-trust-core

The trust core for AI agents that work for a business. An agent built on it can read and propose, but it cannot act: every
change waits for the owner's yes, and every action it takes leaves a receipt signed with the business's own Ed25519 key,
which anyone can check with [verifiable-receipts](https://github.com/christiaan839-beep/verifiable-receipts).

Built in the open by Sovereign Matrix, a studio in Cape Town. Nothing is released yet: the first version is being built now,
with its tests and an attack suite, and this README will say how to use it when there is something to use.

Licensed under the Apache License, Version 2.0 (see [LICENSE](LICENSE)).
