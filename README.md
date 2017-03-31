# W-is-forweb
Exercicio ara o Laboratório de Desenvolvimento de Software para a Web de 2017/1.

## Obtendo o projeto

`git clone https://github.com/jorgetbruno/W-is-for-web`

## Executando a aplicação

`mvn org.apache.tomcat.maven:tomcat7-maven-plugin:run -Dmaven.tomcat.port=9090`

## Acessando a aplicação

Acesse `http://localhost:8080/W-is-for-web/` em qualquer navegador.

## Como o projeto foi construído

### "Embutindo" o Maven

Para que não seja necessário instalar e configurar o Maven, ele foi embutido no projeto com o seguinte comando:

`mvn io.takari:maven:0.3.3:wrapper -Dmaven=3.3.9`

## Pendências na documentação

* Documentar instalação do Git no Windows.
* Documentar instalação do Git no Linux.
* Documentar instalação do Java no Windows.
* Documentar instalação do Java no Linux.
