# .Net Core API

This is a sample project of how to use .Net Core for a Web API.
It uses MongoDB as a data storage service, it also uses `Swashbuckle` to autogenerate the API docs in Swagger format.

## How to run it
1. Execute `docker-compose up` on the `Docker` directory
2. Execute `dotnet build`
3. Execute `dotnet run`

## Usage
- Retrieve some books `curl --insecure https://localhost:5001/api/books`
- Get API docs `https://localhost:5001/swagger/index.html`

## How to run it (Docker)
1. Execute `docker build -t SampleAPI .`
2. Execute `docker run -p 8080:80 SampleAPI`
