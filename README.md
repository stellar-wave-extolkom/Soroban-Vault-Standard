Project Description
The Stellar-Event-Indexer is a developer tool designed to solve the difficulty of querying historical smart contract data. It watches specific Soroban contracts, parses event logs into human-readable formats, and exposes them via a simple REST API.

Technical Architecture
Watcher Service: Polls Stellar RPC nodes to capture contract Events in real-time.

Parser Logic: Decodes complex XDR event data into JSON objects.

REST API: Lightweight Express server allowing frontends to query event history by address or type.

🌊 Drips Wave Program
This repository is an active participant in the Drips Wave Program.

Contributor Guide:

Register: Log in to Drips Wave with GitHub.

Claim an Issue:

Trivial (100 pts): Adding new event type definitions to the parser.

Medium (150 pts): Implementing API pagination or filtering logic.

High (200 pts): Adding Webhook support for real-time app notifications.

Submit & Earn: Once your PR is merged, your contribution points will be applied to the current Wave's reward pool.

Project Structure
Plaintext
├── src/
│   ├── services/    # Event listeners and parsers
│   ├── db/          # Prisma schema and migrations
│   └── api/         # Express routes and controllers
└── tests/           # Integration tests for data accuracy
