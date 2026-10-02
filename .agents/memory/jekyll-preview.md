---
name: Root-level Jekyll Preview
description: Non-obvious cleanup and routing behavior after replacing the generated application scaffold with Jekyll.
---

Removing the generated application directories does not necessarily stop their running servers. Preview must be verified through the public development address, not just a local screenshot.

**Why:** Old Vite and API processes continued running from deleted directories. Configuring a new workflow also restored a legacy public-port mapping to a server that no longer existed, even though Jekyll itself was healthy.

**How to apply:** When removing or replacing scaffold workflows, stop any orphaned project server processes. After configuring workflows, inspect the effective port mappings and verify that the public development address serves Jekyll. Do not add a framework or an extra server implementation to solve Preview routing.