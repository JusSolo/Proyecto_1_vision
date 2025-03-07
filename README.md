# Proyecto 1 de visión por computadora

Proyecto 1 de visión por computadora

Integrantes:

- Juan Luis Solorzano
- Diego Andrés Alonzo Medinilla 20172
- Arturo Argueta 21527

## Montar el ambiente

```bash
docker build -t computer-vision-labs .
docker run --name computer-vision-labs -p 8888:8888 -v "$(pwd):/app" computer-vision-labs
docker start -i computer-vision-labs
```
