# Docker Compose
## Build and run your app with Compose
    
    docker-compose -f docker-compose.yml --build
    docker-compose -f docker-compose.yml up

## Run your services in the background

    docker-compose up -d
    
## See what is currently running:
    
    docker-compose ps 
    
## Run one-off commands for your services

to see what environment variables are available to the `web` service
    
    docker-compose run web env
 
## Stop your services

    docker-compose stop
 
## Bring everything down, removing the containers entirely

    docker-compose down --volumes