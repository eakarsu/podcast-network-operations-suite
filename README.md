# Podcast Network Operations Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AIPodcastNetworkOperationsAssistant`
- `AIPodcastNetworkOperationsOperations`
- `AIPodcastNetworkOperationsAnalytics`
- `AIPodcastNetworkOperationsWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/podcast-network-operations-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:5800`

Seeded users:
- `admin@podcast-network-operations.local / admin123`
- `manager@podcast-network-operations.local / manager123`
- `analyst@podcast-network-operations.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/podcast-network-operations-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:5800 npm run smoke
```
