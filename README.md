# Aquaculture 3.O

> Aquaculture 3.O is a full-stack project with a visible product surface and supporting service layer.

## The Story

Aquaculture 3.O starts with a simple goal: keep the product experience and the service layer visible in one place. Its shape tells the same story: the product interface and the service layer live close enough together that a maintainer can see the project as a whole before diving into individual folders.

## What It Includes

- A user-facing surface for the product, demo, dashboard, or static experience.
- A service layer for APIs, realtime behavior, bot logic, or server-side workflows.

## How It Is Put Together

| Path | Role |
| --- | --- |
| `.gitattributes` | project file or folder |
| `admin-interface` | frontend or dashboard application |
| `server` | service, bot, API, or realtime layer |
| `user-interface` | frontend or dashboard application |

## Local Development

```bash
git clone https://github.com/ENZOMOTIVE/Aquaculture-3.O.git
cd Aquaculture-3.O
```

```bash
cd admin-interface
npm install
npm start
```

```bash
cd server
npm install
```

```bash
cd user-interface
npm install
npm start
```

## Command Surface

| Area | Commands |
| --- | --- |
| `admin-interface/package.json` | `start`, `build`, `test`, `eject` |
| `server/package.json` | `test` |
| `user-interface/package.json` | `start`, `build`, `test`, `eject` |

## Configuration

- Document API ports, database URLs, third-party credentials, and service endpoints in `.env.example` before deployment.
- Keep wallet private keys, RPC URLs, mnemonics, and contract secrets outside version control.

## Quality Checks

- From `admin-interface`, run `npm test`.
- From `admin-interface`, run `npm run build`.
- From `server`, run `npm test`.
- From `user-interface`, run `npm test`.
- From `user-interface`, run `npm run build`.

## Where To Take It Next

- Add screenshots or a short user flow so visitors can see the interface before running it.
- Document the main API routes, bot events, or service responsibilities with example inputs and outputs.
- Keep setup commands current whenever dependencies, scripts, or deployment targets change.
- Record important product decisions here so the repository keeps its story as the code evolves.

## Project Metadata

| Field | Details |
| --- | --- |
| Repository | `ENZOMOTIVE/Aquaculture-3.O` |
| Categories | `Full Stack`, `Protocol` |
| Primary stack | React, Express, Node.js, JavaScript, HTML, CSS |


## License

No license file is currently committed. Add one before distributing this project publicly.
