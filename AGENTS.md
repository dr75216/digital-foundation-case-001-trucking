# Agent Guidelines

## Rules

- `organization.yaml` is the source of truth.
- Never fabricate business claims.
- Prefer plain HTML, CSS, and vanilla JavaScript.
- No framework, database, backend, or unnecessary dependencies without approval.
- Site must remain static and Cloudflare-deployable.
- Use accessible semantic HTML.
- Mobile first.

## Test Data

- Files under test-data/ contain fictional or simulated information used only for development and testing.
- Never treat test-data as verified customer information.
- Never publish information from test-data to a production website unless explicitly instructed for a simulation.
- `organization.yaml` remains the source of truth for approved organization-specific facts.
- Simulated data must be clearly labeled as fictional.
- Never silently copy simulated information into `organization.yaml`.
- Real customer information and simulated test information must remain distinguishable.
