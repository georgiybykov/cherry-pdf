## Chrome-headless pdf generator based on Ruby on Rails

### Usage

```
docker-compose up -d
```

```
curl --location --request POST 'localhost:3003/html_to_pdf' \
--header 'Content-type: application/json' \
--data-raw '{"content": "<h1> Awesome! </h1>", "scale": 0.5, "landscape": true}'
```

### Todo

- Readme
- More options
- Specs
