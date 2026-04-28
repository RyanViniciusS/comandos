### Ver containers
```bash
docker ps
```

### Ver todos containers
```bash
docker ps -a
```

### Parar container
```bash
docker stop CONTAINER_ID
```

#### Formatar os nomes
```bash
docker ps --format "{{.Names}}\t{{.Image}}"
```

#### Fazer o build
```bash
docker build -t desenvolvimentorscrm/rscrm_evo:1.0.12 .
```

#### Publicar no dockerhub
```bash
docker push desenvolvimentorscrm/rscrm_evo:1.0.12
```