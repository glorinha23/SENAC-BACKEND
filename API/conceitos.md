## Conceitos
# API - (Application Programming Interface / Interface de Programação de Aplicativos)
```
- um conjunto de especificações que define de que forma as aplicações irão se comunicar.
- regras e protocolos para que softwares interajam entre si
- interface para que um sistema se comunique com outro sistema
- como se fosse um cardápio do restaurante que comunica o restaurante com o cliente.
```
# REST - (Representational State Transfer ou Transferencia Representacional de Estado)
```
- Restrição de arquitetura - é um estilo de arquiteura de software
- Conjunto de regras e convençoes que permite que dois sistemas se comuniquem pela internet
- mantem um padrao para front e backend.
- A arquitetura REST separa o backend do frontend
```
# RESTful - ()
```
- Utiliza metodos HTTP 
- Utiliza em nuvem
- Capacidade de aplicar os princípios de Rest
- segue o mínimo de regras especificas/necessárias que precisa ser conduzida para ser uma API RestFul.
```

# Maturidade de modelo RESTful
```
Nível 0
 - A API precisa utilizar o protocolo HTTP para a comunicação 
Nível 1
 - A API deve posssuir mapeamento de recursos bem definidos.
 Representando substantivos que fazem a correta utilização das URIs para os recursos respectivos.
Nível 2
- A API deve utilizar o protocolo HTTP de forma semântica com seus verbos HTTP com o uso das (requisições - GET, POST, PUT, DELETE) de acordo com a requisição.
Nível 3
- A API deve mostrar o seu estado atual de relacionamento com os demais recursos da API
 ```

# JSON (JavaScript Object Notation / Notação do objeto javascript)
```
- padrão de dados
- estruturar dados em formato de texto
- transferir informações entre servidor e o cliente

```
# Requisições HTTP
- O protocolo HTTP define um conjunto de métodos de requisição responsaveis por indicar a ação a ser executada para um dado recurso.
- GET, PUSH, DELETE, PUT, PATCH

# HEADERS HTTP
- Os cabeçalhos HTTP permitem que o cliente e o servidor transmitam informações adicionais com uma solicitação ou resposta HTTP. Normalmente formatação ou autorização que não tem relação com os dados em si: Authorization, Content, Type, Accept

# HTTP Codes
- 100 - 199: informativos
- 200 -299: sucesso
- 300 - 399: redirecionamento
- 400 - 499: erros do cliente
- 500 - 599: erros de servidor

# Framework
- biblioteca
- reune varios projetos provendo uma funcionalidade generica

#  ExpressJS - disponibiliza o HTTP
- framework para nodeJS
- fornece requisitos minimos para construção de servidores Web







