## For Dockerfile
# Build image
docker build . -t express-js-app

# Run application
docker run -p 3000:3000 -d express-js-app


## For docker-compose
# Build image
docker-compose build

# Run application
docker-compose up
 