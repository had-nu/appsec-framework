## 4.1.2 Security Requirements <!-- lembre-se que há o conjunto de requisitos de segurança provenientes dos SLC e da conformidade, e os requisitos de segurança específicos de cada projeto levantados durante a modelação de ameaças. Isso deve ficar muito bem marcado -->

`[...]` A partir das diretrizes apontadas pela ISO 27002 é possível estabelecer um conjunto primário de requisitos de segurança, além de métricas de resultados alinhados com as práticas recomendadas para a implementação de um SDL e pertinentes ao negócio. Para isso, o OWASP Application Security Verification Standard (ASVS) é uma ferramenta valiosa, uma vez que se trata de um padrão detalhado e abrangente para a verificação de segurança de aplicações. Ele é projetado para fornecer um framework estruturado que ajuda as organizações a desenvolver e manter aplicações seguras, além de permitir que fornecedores de serviços e ferramentas de segurança alinhem seus requisitos e ofertas.

O ASVS fornece requisitos com declarações básicas verificáveis que podem ser expandidas com user stories e casos de uso indevido,  o que permite vincular a aplicação precisamente ao que um agente de ameaças faz com o sistema, ao invés de descrever o que o sistema oferece ao usuário.  

Por exemplo, ao expandirmos o requisito 1.1.2 da seção “V1 Arquitetura, Design e Modelagem de Ameaças”, do ASVS 4.0.3, que foca no Ciclo de Vida de Desenvolvimento Seguro:

| 1.1.2       | Verificar o uso da modelagem de ameaças para cada alteração de design ou planejamento de sprint para identificar ameaças, planejar contramedidas, facilitar respostas apropriadas a riscos e orientar testes de segurança.     |
| ------------- |:-------------|

Ao trazer o requisito para a perspectiva do usuário, administrador ou agente de ameaça através de user stories é possível descrever a funcionalidade com base no que o usuário quer que o sistema faça por ele:

```
Como desenvolvedor, eu devo ser capaz de utilizar a Modelação de Ameaças para cada alteração de design, 
para identificar ameaças potenciais e planear contramedidas eficazes.

Como gerente de projetos, eu devo ser capaz de incluir a Modelação de Ameaças no planeamento de cada sprint, 
para garantir que as ameaças sejam identificadas e tratadas proativamente.

Como testador de segurança, eu devo ser capaz de utilizar os resultados da Modelação de Ameaças para orientar meus testes de segurança, 
para facilitar as respostas apropriadas aos riscos identificados.
```

Ao trazer o requisito para a perspectiva do agente de ameaça, temos um caso de uso indevido:

| Misuse/Abuse Cases  |
| :-------------|
| *Como invasor, eu devo ser capaz de explorar uma alteração de design que não passou por uma modelagem de ameaças, para comprometer a segurança do sistema.*   |
| *Como invasor, eu devo ser capaz de explorar uma falha não testada devido à falta de testes de segurança direcionados pela modelagem de ameaças, para explorar as falhas que foram mal endereçadas.*  |

Cada requisito do ASVS é identificado por um código no formato `<chapter>.<section>.<requirement>`. Por exemplo, o requisito 1.11.3 se refere a um controle específico dentro da seção 11 do capítulo 1 (Arquitetura). Esta estrutura ajudará a mapear claramente os requisitos de segurança para capacidades específicas que os desenvolvedores devem incorporar nas aplicações.

O ASVS define três níveis de verificação de segurança, cada um com um grau crescente de profundidade e rigor:

* Nível 1 - Primeiros passos, automação e visão completa do portfólio (Básico): para atingir o nível 1, uma aplicação deve ser capaz de defender-se adequadamente contra vulnerabilidades de segurança de aplicações que são fáceis de descobrir e mitigar, incluídas no OWASP Top 10 e/ou outras listas de verificação. Este é o mínimo que todas as aplicações devem buscar.
* Nível 2 - Maioria das aplicações (Padrão): para atingir o nível 2, uma aplicação deve ser capaz de se defender adequadamente contra a maioria dos riscos associados a softwares atualmente. Deve ser capaz de garantir que os controles de segurança sejam eficazes, estejam vigor e incorporados nas aplicações. Este nível é adequado para aplicações que lidam com transações business-to-business significativas, que implementam funcionalidades críticas ou confidenciais do negócio, ou processam outros ativos críticos.
* Nível 3 - Alto valor, alta garantia e alta segurança (Adaptável): uma aplicação de nível 3 requer um alto grau de aprofundamento de verificação e análise de segurança (arquitetura, codificação e testes), uma vez que executam funções críticas, onde a falha compromete substancialmente as operações da organização, ou mesmo sua capacidade de sobrevivência. Tecnologia militar, infraestrutura crítica e saúde são bons exemplos de áreas onde o nível 3 é exigido para aplicações.

A lista de verificações e as métricas a seguir estão organizadas com base na estrutura do OWASP Application Security Verification Standard (ASVS) e fornecem uma visão estruturada e específica de medir a eficácia das práticas de segurança em uma organização, alinhando-se aos requisitos da ISO 27002 de modo a compor a linha de base dos requisitos de segurança e garantir a melhoria contínua dos processos de segurança. 

Após a avaliação de maturidade, será possível estabelecer os requisitos de segurança consoante o nível de maturidade atual identificado e a meta para elevação. Para um maior detalhamento acerca das listas de verificação, deve-se consultar a documentação do OWASP ASVS (ver. Referências).

## Section References

1. <a name="ref-?"></a>[NOME DA REFERENCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
2. <a name="ref-?"></a>[NOME DA REFERENCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
3. <a name="ref-?"></a>[NOME DA REFERENCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
4. <a name="ref-?"></a>[NOME DA REFERENCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
5. <a name="ref-?"></a>[NOME DA REFERENCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->