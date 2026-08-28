# NEM Observer

Ingestion and query service for Australia's National Electricity Market.
Polls AEMO's public 5-minute dispatch feed, stores regional price and demand
as a time series, and serves it through a REST API and dashboard.

Status: in development.

## Stack
TypeScript · Node · PostgreSQL · Docker · GitHub Actions

## Data source
AEMO NEM summary feed, polled every 5 minutes.
Published by AEMO under its Copyright Permissions Notice.
The endpoint is public but undocumented; the schema may change without notice.
