** SCALING WEB APPLICATIONS NOTES **

scalability is the characteristic of a system adjusting itself to increase/decrease of environmental impact

scaling - ability to handle increased resource demand as traffic grows

scaling(regarding frontend apps) - app ability to allow multiple developers to work simultaneously on a large and complex project

architecture -- overall structure, communication and cordination of systems inside the app

design - structure and organization of code

---

Monolithic architecture - software model built as a unit, self-contained, all code located in one place

pros: - easy deployment - easy development in early stages - easier testing - easier debugging

cons: - complex and slower development - an error in any module could affect the entire application - scalability - technology adoption, changes in the framework or language affect the entire application - small change requires redeployment of the entire app

    use cases - small projects, projects with small team members

    anti use cases - large complex applications, projects that require different technologies

---

Micro-frontends - architecturale style where independent frontend apps are composed as a whole (cjelina)

pros: - evolving a large codebase without the need for a rewrite - independent deployment of micro-frontends

    cons:
        - performance issues, the more technologies are included the slower it may be on a users browser
        - complex architecture and deployment process
        - UX incompatibility

- we start considering micro-frontends only when scalability becomes a problem
