# EnergyIA.AR — MCP connector

Connect your AI assistant to **official Argentine energy and mining data**: oil & gas production by field and operator, royalties, mining projects and exports, power plants and installed capacity, fuel prices, energy trade with export prices by company, RIGI investment projects, tenders for suppliers, and macro context (CPI, exchange rate). Every answer comes normalized and cited with its source and period.

- **Server (remote, HTTP):** `https://energyia.ar/conectar-mi-ia`
- **Auth:** OAuth — you sign in with the email of your EnergyIA account and a 6-digit code. Nothing to install, no API keys.
- **Access:** create a free account at [energyia.ar](https://energyia.ar). During the beta, access to the assistant connector is approved by request.
- **Read-only:** every tool is a query; nothing writes to your data or ours.

## Install

**Cursor / Grok Build:** install this plugin from the marketplace, or add the server from `.mcp.json`.

**Any MCP client:** add a remote HTTP server with the URL above. Step-by-step guides (ChatGPT, Claude, Grok, CLI clients): https://energyia.ar/conectar.md

## Data

Coverage, sources and periods: ask the `cobertura` and `fuentes` tools, or see https://energyia.ar/energydata. Data is informational and is not investment advice.

---

Este repositorio sólo contiene la configuración del conector (no el código del servicio). Sitio: https://energyia.ar
