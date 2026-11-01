# Stellar Risk Scan

A TypeScript + React wallet risk scanner for the Stellar network. It reads public account data from Stellar Horizon and provides transparent, heuristic risk indicators. It never asks for a secret key or signs transactions.

## Stack
- React + TypeScript + Vite
- Stellar SDK for public-key validation
- Stellar Horizon public API
- Responsive custom CSS

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Notes
Risk indicators are informational heuristics, not proof of fraud or a guarantee of safety. Account data is fetched from the public Stellar network. This project does not connect a wallet or request secret keys.
