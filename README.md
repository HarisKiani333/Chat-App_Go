# Chat-App_Go
Multi-User Chat Application Made Using GO,Gin and GorrillaMux
1. Clone the repository: git clone https://github.com/harisKiani333/Chat-App_Go
2. Build the Docker image: docker build -t chat-app .
3. Start a Postgres Docker container: docker run --name postgres-db -e POSTGRES_USER=root -e POSTGRES_PASSWORD=password-p 5433:5432 -d postgres:15-alpine
4. Start a Docker container for the application: docker run -p 8080:8080 --name chat-app --link postgres-db:postgres -d chat-app
5. Open your web browser and navigate to http://localhost:8080 to access the application.
