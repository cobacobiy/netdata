# netdata

Netdata monitoring stack for the ARM node (Docker Compose).

## Deploy

    cp .env.example .env   # adjust values
    docker network create proxy  # if not exists
    docker compose up -d

Dashboard: http://<host-ip>:19999 (LAN / NetBird)
