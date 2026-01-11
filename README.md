# liquibaseMastery

### 1. Start everything (app + Postgres)
`docker compose -f docker-compose.yml -f docker-compose.local.yml up --build
`
### 2. Stop everything (keep volumes)
`docker compose -f docker-compose.yml -f docker-compose.local.yml down
`
### 3. Stop and DELETE all data (clean slate)
`docker compose -f docker-compose.yml -f docker-compose.local.yml down -v
`
### 4. View logs only
`docker compose -f docker-compose.yml -f docker-compose.local.yml logs -f
`
### 5. Run specific service
`docker compose -f docker-compose.yml -f docker-compose.local.yml up app
`
