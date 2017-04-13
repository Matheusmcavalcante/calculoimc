# calculoimc

Calculadora do índice de massa corporal

## Ações para rodar o projeto

### Para fazer clone, utilize:

`git clone https://github.com/Matheusmcavalcante/calculoimc`

### Para rodar com o Tomcat.

`mvnw org.apache.tomcat.maven:tomcat7-maven-plugin:run`

### Caso apresente o erro

Error: JAVA_HOME not found in your environment. Execute:

`set JAVA_HOME=C:\Program Files\Java\jdk1.8.0_121`(onde o seu Java está instalado).

No Linux, use `./mvnw` ao invés de apenas `mvnw`, como no Windows. Além disso, pelo menos uma vez, é preciso dar permissão de execução ao arquivo de script **mvnw** com o comando `chmod +x mvnw`.

## Para acessar a aplicação

`http://localhost:8080/calculoimc` em qualquer navegador.