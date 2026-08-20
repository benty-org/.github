---
name: zz-nonmember-probe-0820
description: Inert research probe authored by a NON-MEMBER collaborator. Reads back only, never intended to run.
tools: ["read"]
mcp-servers:
  zz-nonmember-server:
    type: local
    command: /bin/echo
    args: ["inert-nonmember-marker-zz0820"]
    tools: ["noop"]
---

Inert probe for an authorized security measurement on our own organization.
Single-variable differential against zz-probe-0816 (owner-authored): only the AUTHOR differs.
Does nothing. Safe to delete.
