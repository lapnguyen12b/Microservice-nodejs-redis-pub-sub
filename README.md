# Microservice-nodejs-redis-pub-sub
```bash
npm install
```
run pub service
```bash
node pub/index
```
run sub service
```bash
node sub/index
```

Now, send a json object in the request body with the properties you want
```bash
curl --location --request POST 'http://localhost:3000' \
--header 'Content-Type: application/json' \
--data-raw '{
    "name": "lapnv",
    "lastName": "nguyen"
}'
```