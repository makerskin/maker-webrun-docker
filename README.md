# Maker Webrun Docker

## Dicas

### Copiar o .war na pasta `webapps`

### Ajustar a versão do webrun no `Dockerfile`

### Fazer o build da nova imagem

    docker build -t "makerskin/webrun-bootstrap-utf8:latest" -t "makerskin/webrun-bootstrap-utf8:1.2.0.74"

### Subir a imagem atualizada

    docker push docker push "makerskin/webrun-bootstrap-utf8" --all-tags
