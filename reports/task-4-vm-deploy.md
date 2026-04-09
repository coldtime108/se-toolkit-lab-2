# Task 4 - Deploy to VM

## What was done
- Connected to VM over SSH.
- Cloned repository on VM and prepared `.env.docker.secret`.
- Deployed with Docker Compose in detached mode.
- Verified `/status` from VM and from laptop.

## Status response while running
```json
{"status":"ok","service":"course-materials"}
```

## Notes
- VM host resolved via SSH config: `10.93.26.30`.
- In this environment, deployed caddy on `42012` because `42002` was occupied by another running stack.
