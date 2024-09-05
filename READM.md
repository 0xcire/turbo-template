# TT ( turbo template )

A monorepo SaaS template set up for the following:

- Next.js marketing page
- Multi-tenent React SPA
- Nest.js api

## Features

- attempt to build a repo config builder cli in Rust

## Tech

### Client

- TypeScript
- Tailwind CSS
- Radix UI / Shadcn UI
- React
- React Query

### Server

- TypeScript
- Express/TS-Rest
- Drizzle ORM
- Lucia Auth

### DB

- Postgres
- Redis

### Common

- TurboRepo
- [`ts-rest`](https://ts-rest.com/)

## Getting Started

### Prerequisites

Install Docker pls

### Init DB

To run this entire template, you will need Docker installed. Once that is done, first, run `docker compose --profile postgres up -d`, then run the db init scripts `create-db & create-user.sh`
You'll then be able to bring up the entire application stack,

### Init Server

### Init Client

## Deploying

I recommend a $4 [Digital Ocean Droplet](https://www.digitalocean.com/pricing/droplets)