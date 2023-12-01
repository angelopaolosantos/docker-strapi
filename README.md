# Run Strapi on Docker

###Create Strapi App
Strapi files was created using the command below. Dockerfile and docker-compose.yml are then created after
```
npx create-strapi-app@latest docker-strapi --ts --no-run  
```

### Run docker compose
```
docker-compose -f ./docker-compose.yml up -d
```

### Clean up
```
docker-compose -f ./docker-compose.yml down -v --rmi all
```

