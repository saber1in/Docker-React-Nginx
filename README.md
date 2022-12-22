#DEVELOPMENT
CMD -> docker compose -f docker-compose.yml -f docker-compose-dev.yml up -d --build

#PRODUCTION
CMD -> docker compose -f docker-compose.yml -f docker-compose-prod.yml up -d --build
