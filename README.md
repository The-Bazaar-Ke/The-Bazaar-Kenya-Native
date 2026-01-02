# The Bazaar Kenya - Native Mobile

This repository contains the native mobile applications for The Bazaar Kenya, built with React Native and Expo.

## Architecture
- **Monorepo**: Powered by `pnpm` workspaces (Separate from the Web repository).
- **Mobile Stack**: Expo + Expo Router + NativeWind.
- **Contracts**: Typed API clients generated from the backend OpenAPI specifications.

## Projects
- `apps/main-app`: Customer-facing marketplace application.
- `apps/vendor-portal`: Dashboard for vendors to manage products and orders.

## Getting Started
1. Install dependencies: `pnpm install`
2. Start Main App: `pnpm main`
3. Start Vendor Portal: `pnpm vendor`

## Alignment Strategy
This repository aligns with the backend/web project via shared contracts. API types are generated from the central OpenAPI schema to ensure strict type safety without source-code coupling.
