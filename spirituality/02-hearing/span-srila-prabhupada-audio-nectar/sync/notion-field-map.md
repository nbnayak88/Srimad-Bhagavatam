# GitHub → Notion sync contract

Canonical metadata: recording ID, collection, verified title, recording URL, date, duration, scriptural references, GitHub permalink and source verification status.

Notion-owned learner fields: status, listening date, personal notes, reflection and practice. Never overwrite these fields from GitHub.

Targets: https://app.notion.com/p/e1085636f50c4cfa8933b8bd3dbfd362 and https://app.notion.com/p/c34157784917404681681825911a7573

Sync implementation: pending. Configure GitHub Actions with Notion integration token and database ID; upsert by stable SPAN ID, use idempotency and conflict reporting. No always-on sync is active merely because this document exists.
