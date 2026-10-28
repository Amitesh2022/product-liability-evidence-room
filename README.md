# Product Liability Evidence Room

## One-sentence benefit
Helps producers, insurers and consumer-protection teams coordinate consistent digital-era product liability evidence.

## Live demo
Run the Java service and Angular application locally to use the complete experience.

## Screenshots
![product liability evidence coordination workspace](docs/screenshot.png)

## Main features
Search evidence cases, create a regional rollout, progress readiness actions and monitor approval and high-priority gaps.

## Technology used
Angular, TypeScript, signals, computed state, server rendering, Spring Boot and Java.

## Installation instructions
Start the backend with `cd backend && mvn spring-boot:run`. In another terminal run `npm install && npm start`.

## Commercial licensing/contact
Commercial licensing and implementation support are available through the repository owner.

## Business problem and users
Producers, software teams, insurers, lawyers and consumer authorities need shared evidence for defects, damage records and causal evidence.

## Key workflows
Teams can find an evidence case, add a validated review and advance remediation work to approval.

## Angular framework highlights
The interface uses standalone components, signals, computed values, OnPush change detection, built-in control flow and SSR-safe loading.

## Java backend highlights
The Spring Boot service provides real list, search, create and update endpoints, validation, clear errors, health reporting and tests.

## Architecture and state flow
Angular HttpClient connects signal-based state to the Java API and updates the visible board after every write.

## Accessibility and responsive behaviour
Semantic structure, labelled controls, visible focus, high contrast and compact responsive tables support varied users and devices.

## Verification commands
Use `npm test -- --watch=false`, `npm run build`, and `cd backend && mvn test package`.

## Structure
`src` contains the Angular experience, `backend` contains the Java service, and `docs` contains verified media.

## Tradeoffs
Records are held in memory for demonstration speed; operational use would add identity, durable storage, claims systems and product-data integrations.

## Roadmap
Add software-version evidence, repair histories, expert reports, claimant communication and audit-ready persistence.
