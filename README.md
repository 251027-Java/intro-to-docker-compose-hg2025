# Lab: Full Stack Compose

## Goal
Orchestrate a Spring Boot API and a Postgres Database using Docker Compose.

## Requirements
1.  **Java App**:
    -   Create a Spring Boot app with `Spring Data JPA` and `PostgreSQL Driver`.
    -   In `application.properties`, use URL: `jdbc:postgresql://postgres-db:5432/mydb`.
    -   Create a `Dockerfile` for this app.
2.  **Compose**:
    -   Create `docker-compose.yml`.
    -   Service 1: `app` (Build from current dir). Depends on `db`.
    -   Service 2: `db` (Image `postgres`). Set default password.
3.  **Run**:
    -   `docker-compose up`.
    -   Verify the app connects to the DB without errors in the logs.

## Starter Code
-   `docker-compose.yml` (Template).
-   `Dockerfile` (Template).
