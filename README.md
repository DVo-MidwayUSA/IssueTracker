# Issue Triage

## Purpose

Internal web application used to triage issues into next actions as presented to MidwayUSA EC Team.

## Success Measures

- Time to close (Cycle Time)
- Call to action (linking)

## Stack

- CSS Layout: Bulma.io
  - Documentation [https://bulma.io/documentation/](https://bulma.io/documentation/)
  - Why? 100% CSS, responsive
- Client: React.js
  - Documentaiton [https://reactjs.org/docs/getting-started.html](https://reactjs.org/docs/getting-started.html)
  - Why? Simple client state management, plan to modify DOM with design
- Server: Express.js
  - Documentation: [https://expressjs.com/en/4x/api.html](https://expressjs.com/en/4x/api.html)
  - Why? Simple APIs, Isomorphic coding for Client and Server
- Data: SQLServer
  - Development Location: devsql.SQuaT.website
  - Why? Easy to store, uses JSON storage
- Delivery: On-Premise, Internal users

## Application User Flow

### Primary Actions

- Enter issues for triage
- Recommend next actions for an issue
- Browse issues by status
- Reports for measures

### Secondary Actions

- Calculate and communicate cost of an issue
- Conveniently generate work items for other systems
