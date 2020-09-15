# GrocerU 🛒

**groceru** aims to be a service that allows customers to select products from their local grocery stores, enabling scheduled delivery at a time that works best for you. Drawing inspiration from the [InstaCart](https://www.instacart.com/) and [DoorDash](https://www.doordash.com/) services, **groceru** is designed for an optimal user experience and simple reliability.

## Technologies

- **Database:** _TBD_
- **Back-End Server:** Spring Boot
- **Front-End Web Application:** ReactJS

## Goals

Some specific accomplishments for groceru development are presented below.

- **Performance:** lightweight page design & swift data transmission.
- **Simplicity:** a clean user experience for shopping or browsing.
- **Testable:** unit & integration tests to verify development functionality.

## Hurdles

Some anticipated challenges for groceru development are denoted below.

- **Reliability:** how to anticipate problems, fallback, and recover quickly?
- **Scalability:** how to prepare for databases with thousands of entries?

## Milestones

- v0.1: Bare-bones back-end & front-end structure with basic API communication.
  - databases
    - products database (MongoDB?)
      - plaintext & images
      - product name, appearance & details summary
      - product ingredients
      - product instructions
    - user database (SQL?)
      - plaintext
      - user details
        - name
        - age
        - address
      - order history
  - back-end server
    - Java
    - Spring Boot
  - front-end web application
    - JavaScript
    - ReactJS
    - additional frameworks?
      - NextJS
      - Gatsby
- v0.2: User roles, permissions, authentication & application security.
  - "Shopper", "Grocer" and "Admin" role hierarchy.
  - Users must be logged in to progress past the landing page.
- v0.3: Users can register accounts and login.
- v0.4: Management dashboard.
  - "Grocer" users can **create, update & delete** stock.
  - "Admin" users can perform **CRUD** operations on stock & users.
- v0.5: 📌 **Users can make basic orders** by selecting from available stock.
- v0.6: Enhanced error handling.
  - processing errors
  - network communications
  - If item not present while shopping...?
  - If grocer unavailable...?
  - If unexpected situation while delivering...?
- v0.7: Browser notifications.
  - order status notifications
  - account status notifications
  - error notifications
- v0.8: Technical support communications between clients and admins.
  - in-application
  - via email
  - via text message
- v0.9: Any outstanding refactoring, technical debt cleanup and backlog reduction.
- **_v1.0:_** The **groceru** service has all basic functionality implemented.

---

### Extended Development

- v1.1: Payment processing & refunds.
