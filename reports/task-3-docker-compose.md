# Task 3 - Run using Docker Compose

## What was done
- Created `.env.docker.secret` from `.env.docker.example`.
- Started services with Docker Compose.
- Verified `/status` endpoint from app and caddy addresses.
- Stopped services and confirmed endpoint becomes unavailable.

## Status response while running
```json
{"status":"ok","service":"course-materials"}
```

## Notes
- In this environment, free host ports used were `42101` and `42102` due to local port conflicts.
