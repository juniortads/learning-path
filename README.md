# Continuous learning.
## Introdução

- Sabemos que bons profissionais de T.I de maneira geral nunca param de estudar :), logo a ideia aqui é mostrar um caminho de assuntos e tópicos e quem sabe te ajudar a incluir algum deles no teu roadmap pessoal de estudo. 

- https://hackernoon.com/what-habits-made-me-a-better-software-engineer-47e7d54b8fa este artigo traz alguns pontos simples que você pode considerar de maneira macro para melhorar o teu aprendizado. Resumindo, são eles:

1. Pense sempre em arquitetura antes de começar qualquer coisa.
2. Escreva artigos, blogs etc sobre o que você tem aprendido.
3. Utilize o git ou qualquer outro sistema de versionamento.
4. Controle teu roadmap de estudos (kanban board).
5. Tente analisar um problema em diferentes ângulos.
6. Faça exercícios, PoCs.
7. Leia livros.

### Se sinta a vontade para contribuir :)

## Desenvolvimento & Arquitetura

- Clean Architecture & Clean Code <br>
    Robert C. Martin "Uncle Bob" conhecido como autor do Clean Code que também escreveu sobre Clean Architecture que aborda uma visão mais ampla sobre como criar um software. Não é algo nada novo mas é importante você entender.
    
    Leia: <br>
    https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html
    https://github.com/diegodocs/CleanArchitecture
    https://github.com/diegosmorf/CleanArchitecture.API.Template/blob/master/README.md

- SOLID <br>
        É um acrônimo dos cinco primeiros princípios da programação orientada a objetos e design de código identificados por  Robert C. Martin, novamente não é algo novo mas bem importante para no dia-dia você não cometer erros básicos quando a abordagem for OOP, onde os principais pontos são:
    - Single Responsibility Principle (SRP)
    - Open Closed Principle (OCP)
    - Liskov Substitution Principle (LSP)
    - Interface Segregation Principle (ISP)
    - Dependency Inversion Principle (DIP)    
    
    Leia: <br>
    https://blog.caelum.com.br/principios-do-codigo-solido-na-orientacao-a-objetos/
    
- Microservices <br>
    É uma técnica de desenvolvimento de software - uma variante do estilo arquitetônico de arquitetura orientada a serviços que estrutura um aplicativo como uma coleção de serviços fracamente acoplados. MAS Antes de estudar esse padrão aconselho você a estudar antes "Monolithic Architecture". Isso é importante porque precisa entender se você realmente precisa de utilizar uma arquitetura distribuída. Depois que você entendeu é bem interessante você entender algumas falácias em torno desse buzzword. "rsrs". <br>
    
    1. A rede é confiável
    2. A latência é zero
    3. A largura de banda é infinita
    4. A rede é segura
    5. Topologia não muda
    6. Existe um administrador
    7. Custo de transporte é zero
    8. A rede é homogênea <br>
    
    
    
    Leia: <br>
    https://microservices.io/patterns/monolithic.html
    https://microservices.io/patterns/index.html
    https://martinfowler.com/articles/microservices.html
    https://medium.com/netflix-techblog/tagged/microservices
    https://medium.com/building-nubank/microservices-at-nubank-an-overview-2ebcb336c64d
    https://www.atlassian.com/continuous-delivery/microservices/building-microservices
    
    Assista: <br>
    https://www.youtube.com/watch?v=wgdBVIX9ifA&t=38s <br>
    https://www.youtube.com/watch?v=X0tjziAQfNQ
    
- Reactive Systems <br>
    ### https://www.reactivemanifesto.org/

## Cloud Native

- Docker
- Orquestração de containers 
    - Kubernetes
- Service Mesh
    - Istio
- YAML
- Helm Charts
