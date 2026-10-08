# GuildForge

_On-chain reputation and auto-payout tool for gaming and DAO guilds_

## Summary

GuildForge lets gaming guilds, DAOs, and hackathon teams track member contributions and automatically split on-chain rewards based on verifiable on-chain activity. It replaces spreadsheets and manual trust with transparent smart contracts and soulbound reputation NFTs. The MVP covers guild creation, contribution logging, and automated SOL/USDC payout splitting.

## Target users

Gaming guilds, DAO contributors, hackathon and freelance teams

## Problem

Teams and guilds struggle to fairly and transparently split rewards based on actual contribution, often relying on manual trust or spreadsheets.

## Solution

GuildForge issues soulbound reputation tokens for logged contributions and uses a Solana program to auto-split incoming funds proportionally among members.

## MVP features

- Create a guild and invite members with wallet addresses
- Log contributions (tasks, commits, matches won) on-chain
- Soulbound NFT reputation badges per contribution type
- Automated proportional payout splitting via Solana program
- Public guild profile page showing reputation and history

## Chains

Solana

## Tech

Anchor, Metaplex, Next.js, Solana Program Library, Supabase, Phantom Wallet Adapter

## Category

DAO

## Why now

Guilds and distributed teams are scaling fast but still lack trustworthy, low-fee on-chain tools for fair reward distribution.

## Roadmap

- Integrate with Discord/game APIs for automatic contribution tracking
- Add dispute resolution via community voting
- Expand to cross-guild reputation portability
