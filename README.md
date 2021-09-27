# conversao-temperatura

## Docker Build

```bash
docker image build -t roanfranklin/conversaotemperatura:v1 .
```

## Docker Run

```bash
docker run -d -p 8081:8080 --rm --name conversaotemperatura roanfranklin/conversaotemperatura:v1
```
