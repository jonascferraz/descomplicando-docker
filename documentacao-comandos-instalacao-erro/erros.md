## Erros que documentei referente ao Docker

## Erro apresentado ao executar o Docker pela primeira vez no Windows

```sh
docker: error during connect: In the default daemon configuration on Windows, the docker client must be run with elevated privileges to connect.: Post "http://%2F%2F.%2Fpipe%2Fdocker_engine/v1.24/containers/create": open //./pipe/docker_engine: The system cannot find the file specified.
```

**Correcao**

- No "Ativar e desativar recursos do Windows" habilite o Hyper-V

[Clique Aqui](imagens/hyper-v.jpg)

**OBS: So funciona Win 10Pro/Enterprise e em alguns casos tem que habilitar o recurso de virtualização na BIOS**

Após habilitar na BIOS verificar no "Ativar e desativar recursos do Windows" as informações passadas na imagem abaixo

[Clique Aqui](imagens/hyper-v1.jpg)