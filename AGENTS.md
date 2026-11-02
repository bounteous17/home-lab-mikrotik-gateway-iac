# AGENTS.md

## Router access

The MikroTik gateway (`192.168.11.1`) is reachable over SSH as the `bounteous` user:

```
ssh bounteous@192.168.11.1 '<RouterOS command>'
```

- Key authentication is used; do not guess or try other credentials (`admin` is not authorised).
- Prefer read-only commands (`print`, `export`). Do not change router configuration without explicit confirmation.
- The README documents the current configuration; verify against the live router when they may differ.
