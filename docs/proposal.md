# Quorumly

_AI-summarized, reputation-weighted governance voting for Solana DAOs_

## Summary

Quorumly is a governance dashboard that uses AI to summarize lengthy proposals into plain-language pros/cons, and weights voting influence partly by on-chain reputation (past participation, delegate track record) rather than just token holdings. This helps DAOs fight voter apathy and plutocratic capture.

## Target users

DAO members, governance delegates, and DAO tooling teams

## Problem

Low voter turnout and whale-dominated outcomes plague most on-chain DAOs, partly because proposals are long and hard to parse.

## Solution

Combine AI-generated proposal summaries with a reputation score derived from on-chain voting history to produce fairer, more engaged governance.

## MVP features

- Fetch live proposals from Realms and summarize with AI
- Compute reputation score from historical voting/delegation activity
- Blended voting weight combining token balance and reputation
- One-click vote casting directly from summarized proposal view
- Delegate leaderboard showing most active and effective voters

## Chains

Solana

## Tech

Realms SDK, Anchor, OpenAI API, React, TypeScript, Postgres

## Category

Infrastructure

## Why now

Solana's Realms ecosystem has hundreds of active DAOs but low participation; AI summarization plus reputation weighting is a timely fix as governance fatigue grows.

## Roadmap

- Integrate with more governance frameworks beyond Realms
- Open reputation score as a public API for other DAO tools
- Add delegate matching feature to connect passive holders with active voters
