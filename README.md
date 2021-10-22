# Teste de Validação do Jenkins MIA para realização no amibente openstack EVEO
Teste para validação do Jenkins MIA.
  - Ubuntu 20.04 ou Debian 10
  - Docker version 20.10.9, build c2ea9bc
  - Docker Compose version 1.29.2, build 5becea4c
  - Imagem do Jenkins Utilizada em 22/10/2021: jenkins/jenkins:latest
    - DIGEST:sha256:d554ea9020aaa14198403320ee9b7f33c38610860a87bf018700f7fe785b73a6

## Requisitos
 - 1) Preferencialmente usar o Ubuntu 20.04 na versão server.
 - 2) Instalar a última versão do docker (Seguindo a documentação oficial)
 - 3) Realizar as etapas de "Post instalallations" (seguindo a documentação oficial)
 - 4) Instalar a última versão do docker-compose (Seguindo a documentação oficial)
 - 5) Clonar este repositório.
 - 6) Acessar a pasta clonada, e executar os comandos abaixo.

## Comandos
´
docker-compose down --remove-orphans
docker-compose up
´
### Repetição do Teste
Basta executar os dois comandos novamente para iniciar os testes do início.

## Procedimento no Jenkins
 - 1) Acessar a URL exposta da máquina ubuntu (Firewall desabilitado, portas abertas)
 - 2) Copiar o código gerado na console ao executar o comando "docker-compose up"
 - 3) Colar na tela front do Jenkins, e avançar.
 - 4) Clicar no botão para instalar os plugins sugeridos.
 - 5) Nesta eatapa ele não está instalando os plugins e dando erro na console.

Duvidas estou a disposição.
Cristiano José dos Reis
