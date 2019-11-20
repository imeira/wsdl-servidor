# Servidor WebService SOAP
Servidor web utilizando SOAP com Java e Spring Boot.
### Como executar a aplicação
Certifique-se de possuir o Git instalado.
```
git clone https://github.com/imeira/wsdl-servidor.git
cd wsdl-servidor
./mvnw clean install -DskipTests
./mvnw spring-boot:run
Acesse o endpoint contendo o arquivo WSDL através da url http://localhost:8080/ws

para testar via linha de comando na raiz do projeto:
curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws
```
