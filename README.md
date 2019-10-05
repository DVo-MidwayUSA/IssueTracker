# Issue Triage

## Purpose

Internal web application used to triage issues into next actions as presented to MidwayUSA EC Team.

## Success Measures

- Time to close (Cycle Time)
- Call to action (linking)

## Stack

- CSS Layout: Bulma.io
  - Documentation [https://bulma.io/documentation/](https://bulma.io/documentation/)
  - _Why?_ 100% CSS, responsive
- Client: React.js
  - Documentaiton [https://reactjs.org/docs/getting-started.html](https://reactjs.org/docs/getting-started.html)
  - _Why?_ Simple client state management, plan to modify DOM with design
- Server: Express.js
  - Documentation: [https://expressjs.com/en/4x/api.html](https://expressjs.com/en/4x/api.html)
  - _Why?_ Simple APIs, Isomorphic coding for Client and Server
- Pipeline:
  - Build: Webpack, Babel
    - Documentation: [https://webpack.js.org/api/](https://webpack.js.org/api/)
    - _Why?_ Works well for both React and Express, allows use for ES6, hot module replacement for faster development, dev server
  - Build Tools: Nodemon, npm-run-all
    - _Why?_ Run development build tools for api and website from one cmd interface
  - Packaging: GitLab
    - _Why?_ Experimentaion with small projects
  - Deployment: Octopus Deploy
- Data: SQLServer
  - Development Location: devsql.SQuaT.website
  - _Why?_ Easy to store, uses JSON storage
- Delivery: On-Premise, Internal users
  - _Why?_ Starting with on-site reporting, may extend to external site in the future

## Application User Flow

### Primary Actions

- Enter issues for triage
- Recommend next actions for an issue
- Browse issues by status
- Reports for measures

### Secondary Actions

- Search for an issue
- Calculate and communicate cost of an issue
- Conveniently generate work items for other systems

### Navigation Plan

#### Key Navigation Areas

- Triage an issue
- View issues
- View Reporting

#### Key Screens

- Issue Triage
- Issue Inventory
  - Issue Details
- Available Reports
  - Report Details
