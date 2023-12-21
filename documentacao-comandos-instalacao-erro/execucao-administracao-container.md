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

Após a consulta nas imagens nos trouxe 5 colunas 

| Coluna | Definicao |
| ------ | ------ |
| REPOSITORY | Nome da imagem |
| TAG | A versão da imagem |
| IMAGE ID | Identificacao da imagem |
| CREATED | Quando ela foi criada |
| SIZE | Tamanho da imagem |

-------

**OBS:** Quando executamos o comando "docker container run hello world" ele criou o container, imprimiu a mensagem na tela e depois o container foi finalizado. (Fez a tarefa que era imprimir a mensagem e foi finalizado).

Para verificar quais container estão em execução ou não foram finalizados é só digitar:

```sh
docker container ls
```

O resultado sera a imagem abaixo (Nesse caso não temos nenhum container em execucao)

[Clique Aqui](imagens/verificacao-container-execucao.jpg)

Ap´os a verificação nos trouxe 7 colunas

| Coluna | Definicao |
| ------ | ------ |
| CONTAINER ID | Identificacao unica do container |
| IMAGE | A imagem que foi utilizada para a execucao do container |
| COMMAND | O comando em execucao |
| CREATED | Quando ele foi criado |
| STATUS | O Seu status atual |
| PORTS | A porta do Container e do host que esse container utiliza |
| NAMES | O Nome do container

------

## Utilizando o parametro -a



