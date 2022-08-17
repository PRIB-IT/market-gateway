# Market Gateway

## How to run the application on docker

1. Build the market-gateway project
```cmd
  ./gradlew build
```

2. Build the docker image
```cmd
  docker build -t market-gateway .
```

3. Run the builded image
```cmd
  docker run -p 8080:8080 market-gateway
```