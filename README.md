# PRINCIPIOS SOLID API_REST NODEJS E TYPESCRIPT

###### Principios aplicados:
```
  . Providers (Princípio da substituição de Liskov, Princípio da substituição de Liskov)
  . Cada classe tem uma unica responsabilidade no codigo (Princípio de única responsabilidade)
      - CreateUserUseCase: Criacao do usuario. 
      - CreateUserController: Recebe a requisicao de criacao de usuario atraves do protocolo HTTP, processar essa requisicao atraves do CreateUserUseCase e devolver uma resposta.
      - CreateUserDTO: Determina como que vai ser a transmissao de menssagem entre o CreateUserController e CreateUserUseCase e etc...
```
###### Iniciar:
```
  . Necessario criar conta no MailTrap para testar o envio de e-mail.
```
