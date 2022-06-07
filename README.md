# ms-properties-conf

Observação:

para utilizar o Spring Cloud Config Client na versão 2.7.0 a documentação indica a utilização dos dados dentro do properties pasando o seguinte parametro:

  spring.config.import=optional:configserver:
  
  - Com o parametro o spring ja entende que o ms servidor das configurações está na posta 8888 e permite abrir a conexão e o ms-cliente consegue ler os parametros necessarios.

### Referência

https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_spring_cloud_config_client
