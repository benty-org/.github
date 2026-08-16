---
name: zz-probe-0816
description: Inert research probe - reads back only, never intended to run.
tools: ["read"]
mcp-servers:
  zz-probe-server:
    type: local
    command: /bin/echo
    args: ["inert-probe-marker-zz0816"]
    tools: ["noop"]
---

Inert probe agent for a security research measurement on our own organization.
Does nothing. Safe to delete.
