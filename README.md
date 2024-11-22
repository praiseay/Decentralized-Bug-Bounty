# Decentralized Reputation System

## Overview
A Stacks blockchain smart contract for managing user reputations across different applications with privacy controls.

## Key Features
- Reputation Tracking
- Multi-Application Scoring
- Privacy Settings
- Reputation Accumulation

## Contract Functions

### Reputation Management
- `add-reputation`: Add reputation score for a specific application
- `get-reputation`: Retrieve reputation score
- `get-app-reputation`: Get reputation for a specific app

### Privacy Controls
- `set-privacy`: Configure reputation visibility
- `get-privacy`: Check user's privacy settings

## Reputation Mechanism
- Scores are tracked per user, per application
- Reputation is cumulative
- Block height tracks last update

## Error Handling
- Custom error codes for not found scenarios
- Owner-only access control

## Requirements
- Stacks blockchain
- Compatible wallet
