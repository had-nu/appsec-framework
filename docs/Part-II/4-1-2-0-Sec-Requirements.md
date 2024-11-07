## 4.1.2 Security Requirements <!-- lembre-se que há o conjunto de requisitos de segurança provenientes dos SLC e da conformidade, e os requisitos de segurança específicos de cada projeto levantados durante a modelação de ameaças. Isso deve ficar muito bem marcado. O mapeamento de requisitos feito para o ASVS deve estar na parte prática -->

`[...]` A partir das diretrizes apontadas pela ISO 27002 é possível estabelecer um conjunto primário de requisitos de segurança, além de métricas de resultados alinhados com as práticas recomendadas para a implementação de um SDL e pertinentes ao negócio. Para isso, o OWASP Application Security Verification Standard (ASVS) é uma ferramenta valiosa, uma vez que se trata de um padrão detalhado e abrangente para a verificação de segurança de aplicações. Ele é projetado para fornecer um framework estruturado que ajuda as organizações a desenvolver e manter aplicações seguras, além de permitir que fornecedores de serviços e ferramentas de segurança alinhem seus requisitos e ofertas.

O ASVS fornece requisitos com declarações básicas verificáveis que podem ser expandidas com user stories e casos de uso indevido,  o que permite vincular a aplicação precisamente ao que um agente de ameaças faz com o sistema, ao invés de descrever o que o sistema oferece ao usuário.  

Por exemplo, ao expandirmos o requisito 1.1.2 da seção “V1 Arquitetura, Design e Modelagem de Ameaças”, do ASVS 4.0.3, que foca no Ciclo de Vida de Desenvolvimento Seguro:

| 1.1.2       | Verificar o uso da modelagem de ameaças para cada alteração de design ou planejamento de sprint para identificar ameaças, planejar contramedidas, facilitar respostas apropriadas a riscos e orientar testes de segurança.     |
| ------------- |:-------------|

Ao trazer o requisito para a perspectiva do usuário ou administrador, através de `user stories` ou `casos de uso`, é possível descrever a funcionalidade com base no que o usuário quer que o sistema faça por ele:

**User Stories/Use Cases**

```
Como desenvolvedor, eu devo ser capaz de utilizar a Modelação de Ameaças para cada alteração de design, 
para identificar ameaças potenciais e planear contramedidas eficazes.

Como gerente de projetos, eu devo ser capaz de incluir a Modelação de Ameaças no planeamento de cada sprint, 
para garantir que as ameaças sejam identificadas e tratadas proativamente.

Como testador de segurança, eu devo ser capaz de utilizar os resultados da Modelação de Ameaças 
para orientar meus testes de segurança, 
para facilitar as respostas apropriadas aos riscos identificados.
```

Ao trazer o requisito para a perspectiva do agente de ameaça, temos um `caso de uso indevido` ou `caso de abuso`:

**Misuse/Abuse Cases**

```
Como invasor, eu devo ser capaz de explorar uma alteração de design 
que não passou por uma modelagem de ameaças, 
para comprometer a segurança do sistema.

Como invasor, eu devo ser capaz de explorar uma falha não testada 
devido à falta de testes de segurança direcionados pela modelagem de ameaças, 
para explorar as falhas que foram mal endereçadas.
```


## Section References

1. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
2. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
3. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
4. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
5. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->