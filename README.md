\#API com Design Patterns (Gang of Four)



Este projeto foi desenvolvido como parte de estudos práticos sobre \*\*Padrões de Projeto (Design Patterns)\*\* baseados no catálogo clássico do \*\*Gang of Four (GoF)\*\*, aplicados em um ambiente backend em \*\*Java com Spring Boot\*\*.



O objetivo da aplicação é demonstrar a aplicação prática de padrões criacionais, estruturais e comportamentais para resolver problemas comuns de arquitetura e organização de código.



\---



\##Padrões de Projeto Implementados



O projeto contempla a implementação dos seguintes padrões:



1\. \*\*Singleton (Criacional):\*\*

&#x20;  \* Garante que uma classe tenha apenas uma instância e fornece um ponto global de acesso a ela. Utilizado para gerenciar recursos compartilhados ou estados globais na aplicação.

2\. \*\*Facade (Estrutural):\*\*

&#x20;  \* Fornece uma interface unificada para um conjunto de interfaces em um subsistema. Facilita o uso do sistema ao ocultar a complexidade de múltiplos serviços ou integrações (muito utilizado na camada de serviço para encapsular chamadas a APIs externas ou bancos de dados).

3\. \*\*Strategy (Comportamental):\*\*

&#x20;  \* Permite definir uma família de algoritmos, encapsular cada um deles em classes separadas e tornar os algoritmos intercambiáveis. O Strategy permite que o algoritmo varie independentemente dos clientes que o utilizam (ideal para regras de negócio condicionais complexas, como cálculos de frete, descontos ou formas de pagamento).



\---



\##Tecnologias Utilizadas



\* \*\*Java\*\* (versão 17+)

\* \*\*Spring Boot\*\*

\* \*\*Springdoc OpenAPI (Swagger)\*\* - Para documentação e testes interativos da API

\* \*\*Maven\*\* - Gerenciador de dependências



\---



\##Como Executar o Projeto



\### Pré-requisitos

Certifique-se de ter instalado em sua máquina:

\* \*\*Java Development Kit (JDK)

\* \*\*Maven\*\* (ou utilize a própria IDE com suporte ao Maven)





Documentação da API (Swagger)

Com a aplicação rodando localmente, você pode explorar e testar todos os endpoints disponíveis através do Swagger UI acessando a seguinte URL no seu navegador:



🔗 http://127.0.0.1:8080/swagger-ui.html

