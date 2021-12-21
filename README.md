# Intro
The official MySQL 5.7 Docker image doesn't support multi arch. This one does.

# Build & push
`docker buildx build --push --tag renkosteenbeek/mysql:5.7 --platform linux/arm64/v7,linux/arm64/v8,linux/amd64 .`

# Build only
`docker buildx build --tag renkosteenbeek/mysql:5.7 --platform linux/arm64/v7,linux/arm64/v8,linux/amd64 .`