# Awesome-Limited-Partner-Portal

INTERNET
                            │
                            ▼
                       CDN / WAF
                            │
                            ▼
                       API Gateway
                            │
                            ▼
                     Authentication
                       Keycloak
                            │
                            ▼
                       LP Portal
                     Next.js / React
                            │
          ┌─────────────────┼─────────────────┐
          │                 │                 │
          ▼                 ▼                 ▼
       Investor          Reporting         Documents
       Services           Engine             Service
          │                 │                 │
          ▼                 ▼                 ▼
       PostgreSQL         Superset           MinIO
          │                 │                 │
          └─────────────────┼─────────────────┘
                            ▼
                     Fund Data Layer
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
          Fineract       Formance        Hemrock
             │              │              │
             └──────────────┼──────────────┘
                            ▼
                      Data Warehouse
                            │
                            ▼
                      AI / Analytics
