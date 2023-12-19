## Execucao do primeiro Container e explicação do funcionamento

Primeiro Comando utilizado no docker (Teste-Aprendizado)

```sh
docker container run hello-world
```

O Resultado sera a imagem abaixo

[Clique Aqui](imagens/docker-run-hello.jpg)

Após utilizar qualquer comando "docker" EX: (docker container run hello-wolrd) é necessário quatro etapas para a conclusão

1 - O Comando "docker" se comunica com o daemon do Docker informando a ação desejada
2 - O daemon do Docker verifica se a imagem "hello-world" existe em seu host, caso ainda nao, o Docker faz o download da imagem diretamente do Docker Hub
3 - O daemon do Docker cria um novo container utilizando a imagem que voce acabou de baixar
4 - O daemon do Docker envia a saída para o comando "docker", que imprimi a mensagem em seu terminal

------

## Consultando as imagens que ja temos em nosso host

Comando utilizado para verificar as imagens que tem no host

```sh
docker image ls
```

O resultado sera a imagem abaixo

[Clique Aqui](imagens/docker-visualicao-imagens.jpg)

