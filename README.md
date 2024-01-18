# build image
docker build . -t <image_name>

# run container
docker run -dp 9090:8080 express-app:v0.0.1

# exec into container
- what is in /app directory?
- How did it get there?
- Are there uneccessary content?