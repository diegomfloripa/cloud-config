# Cloud-Config
Serviço responsável por prover configurações para outros serviços, possibilitando alteração dessas configurações em tempo de execução

## Pré requisitos
- [Java8](https://www.java.com/pt_BR/download)
- [Maven](https://maven.apache.org)
- [Spring Cloud Config](https://cloud.spring.io/spring-cloud-config/multi/multi__spring_cloud_config_server.html)
- [Lombok](https://projectlombok.org) - Plugin necessário para abrir projeto na IDE

## Instalação
efetue um clone desse repositório para sua máquina
```
git clone https://github.com/diegomfloripa/cloud-config.git
```

Abra a pasta do projeto
````
cd cloud-config
````
rodar com maven
```
mvn spring-boot:run
```
Nesse momento já é possível acesssar a aplicação através de sua API Rest
http://localhost:8888/service-discovery/default

## Autor
 - Diego Melo
