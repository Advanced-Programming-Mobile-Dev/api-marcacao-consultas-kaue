Estrutura do projeto:

``` 
src/
 └── main/
     └── java/
           └── com.fiap.ecb/
                     └── api_marcacao_consultas/
                         ├── controller/
                         │    └── UsuarioController.java
                         │    └── ConsultaController.java
                         │    └── EspecialidadeController.java
                         ├── model/
                         │    └── Usuario.java
                         │    └── Consulta.java
                         │    └── Especialidade.java
                         ├── repository/
                         │    └── UsuarioRepository.java
                         │    └── ConsultaRepository.java
                         │    └── EspecialidadeRepository.java
                         ├── service/
                         │    └── UsuarioService.java
                         │    └── ConsultaService.java
                         │    └── EspecialidadeService.java
                         ├── config/
                         │    └── SecurityConfig.java
                         ├── security/ 
                         │    └── JwtAuthenticationFilter.JAVA
                         │    └── JwtTokenProvider.java
                         ├── dto/
                         │    └── LoginRequest.java 
                         └── ApiMarcacaoConsultasApplication.java
```
