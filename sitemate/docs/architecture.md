# SITEMATE – Architecture Overview

## High-Level Architecture

```
Browser (Frontend)
       │
       ▼ HTTP / REST
  Backend API (Node.js)
       │
       ▼
   Database (SQLite / PostgreSQL)
```

## Components

### Frontend
- Plain HTML/CSS/JS (or React, TBD)
- Served as static files or via a development server
- Communicates with the backend via REST API

### Backend
- Node.js with Express (planned)
- RESTful API endpoints
- Handles business logic and database queries

### Database
- SQLite for local development
- Planned migration to PostgreSQL for production

## Planned Data Models

| Model   | Fields                                      |
|---------|---------------------------------------------|
| Site    | id, name, address, created_at               |
| Task    | id, site_id, title, status, due_date        |
| Issue   | id, site_id, description, severity, status  |
| User    | id, name, email, role                       |
