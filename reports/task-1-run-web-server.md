# Task 1 - Run the web server

## What was done
- Created `.env.secret` from `.env.example`.
- Started the server with `uv run poe dev`.
- Verified `/status` endpoint.
- Stopped the server and confirmed endpoint becomes unavailable.

## Status response while running
```json
{"status":"ok","service":"course-materials"}
```

## Notes
- Local address used: `http://127.0.0.1:42000/status`.
