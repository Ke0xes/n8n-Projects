mermaid
```
flowchart TD
    A[Cron Trigger] --> B[Init Sources Function]
    B --> C1[Execute Command - Nmap Scan]
    B --> C2[HTTP Request - Ubiquiti API]
    C1 --> D[Normalize Data Function]
    C2 --> D
    D --> E[AI Node - Enrichment & Classification]
    E --> F[Spreadsheet File - Save to Excel]
    F --> G[Optional Notification - Email/Slack]
```
