# Sense

Sense is a ClimateTech company founded in 2013 that provides home energy intelligence through a high-resolution electrical monitoring device installed in residential electrical panels. The Sense platform uses machine learning to disaggregate whole-home power consumption into individual device-level signatures, enabling homeowners to understand exactly which appliances consume electricity and when. The company announced in late 2025 that it would stop selling the standalone Sense Monitor, pivoting to embed its technology directly into next-generation smart meters deployed by utility partners across the United States.

## APIs

The Sense platform exposes two primary API surfaces for programmatic access to energy data:

**Sense Client API** — A REST API at `https://api.sense.com/apiservice/api/v1/` providing access to historical trend data, device detection results, monitor health, and account information. Supports time scales of day, week, month, year, and billing cycle.

**Sense Realtime API** — A WebSocket feed at `wss://clientrt.sense.com/monitors/{monitor_id}/realtimefeed` delivering live electricity usage data including whole-home wattage, solar production, grid exchange, and real-time device on/off status.

## Authentication

Both APIs use bearer token authentication. Clients authenticate with username and password credentials against the Client API to receive an access token and refresh token. The access token is passed as an `Authorization: bearer {token}` header for REST calls and as a query parameter for the WebSocket connection. Multi-factor authentication (MFA) is supported.

## Status

- Status Page: https://status.sense.com
- Support: https://help.sense.com
- Blog: https://blog.sense.com

## Links

- Website: https://sense.com
- LinkedIn: https://www.linkedin.com/company/senseenergy
- X: https://x.com/sense
- GitHub (community API library): https://github.com/scottbonline/sense

## Maintainers

**Kin Lane** — kin@apievangelist.com
