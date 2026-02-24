# SITEMATE – API Reference

> Status: **Planned / Not yet implemented**

## Base URL

```
http://localhost:3000/api/v1
```

## Endpoints

### Sites

| Method | Path          | Description          |
|--------|---------------|----------------------|
| GET    | /sites        | List all sites       |
| POST   | /sites        | Create a new site    |
| GET    | /sites/:id    | Get a site by ID     |
| PUT    | /sites/:id    | Update a site        |
| DELETE | /sites/:id    | Delete a site        |

### Tasks

| Method | Path                      | Description              |
|--------|---------------------------|--------------------------|
| GET    | /sites/:id/tasks          | List tasks for a site    |
| POST   | /sites/:id/tasks          | Create a task for a site |
| PUT    | /sites/:id/tasks/:taskId  | Update a task            |
| DELETE | /sites/:id/tasks/:taskId  | Delete a task            |

### Issues

| Method | Path                          | Description               |
|--------|-------------------------------|---------------------------|
| GET    | /sites/:id/issues             | List issues for a site    |
| POST   | /sites/:id/issues             | Log a new issue           |
| PUT    | /sites/:id/issues/:issueId    | Update an issue           |
| DELETE | /sites/:id/issues/:issueId    | Delete an issue           |

---

*This document will be updated as the API is implemented.*
