# Operations Manual: 8-Node Sovereign Cluster

## Cluster Status
- Status: Initialized
- Nodes: 8
- Orchestration Engine: MAXIMUS

## Node Maintenance Protocols
1. **Security:** Never expose node SSH ports to the public internet.
2. **Updates:** All OS and model updates must be applied via local offline mirrors.
3. **Audit:** Every major configuration change must be logged in `docs/audit/CHANGELOG.md` before execution.

## Disaster Recovery
- In the event of node failure, refer to the local hardware registry (stored off-repo) for manual restoration steps.
- 
