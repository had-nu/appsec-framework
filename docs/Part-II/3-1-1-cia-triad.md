### 3.1.1 C.I.A. Triad

Em um espectro mais amplo e em última análise, o objetivo final de qualquer projeto de segurança cibernética é garantir e resguardar a Confidentiality, a Integrity and a Availability (C.I.A). A ISC2, International Information Systems Security Certification Consortium, diz que tais termos servem objetivamente para descrever a segurança de forma mais compreensível, e dá uma breve definição:

* **Confidencialidade**: Protege e mantém a privacidade de informações confidenciais de usuários não autorizados, ao mesmo tempo em que protege as informações contra divulgação indevida;
* **Integridade**: É a propriedade da informação pela qual ela é registrada, usada e mantida de forma a garantir sua integridade, precisão, consistência interna e utilidade para um propósito declarado;
* **Disponibilidade**: Significa que os sistemas e dados deverão estar acessíveis no momento em que os usuários precisam deles.

[imagem]

**Security Domains and Capabilities**


**Security Principles and Practices**

Para garantir a segurança e a conformidade, e para prevenir que ameaças impactem a Confidencialidade, Integridade e Disponibilidade, é essencial que organizações promovam um esforço consciente, planeado e estruturado de segurança cibernética. A proposta da IBM para uma estrutura de arquitetura bem protegida (Well-Architected Framework) descreve cinco domínios de segurança que devem ser considerados em um programa de segurança cibernética robusto, nomeadamente: Segurança de Aplicativos, Segurança de Dados, Gestão de Identidade e Acesso, Segurança de infraestrutura e Endpoint, e Detecção e Resposta. Essa estrutura possui um conjunto de princípios, práticas e recursos suficientemente abrangentes para cobrir todos os controlos de segurança, e será detalhada mais adiante (ver Imagem 5).

Embora não exista um conjunto único e universalmente aceito, a IBM, Red Hat e outras empresas especializadas em tecnologia defendem um conjunto de princípios comuns de segurança que são particularmente relevantes para o desenvolvimento de código aberto e segurança de software em geral.

**Defense in Depth**
Este princípio enfatiza a importância de múltiplas camadas de segurança. A Red Hat define isso como: "Falha ou comprometimento de uma única camada ou componente de um sistema não deve comprometer o sistema como um todo".A IBM também menciona este princípio em seu modelo de segurança.

**Security by Design**
A Red Hat afirma que "A segurança não é um complemento, uma reflexão posterior ou uma lista de verificação". A IBM também enfatiza este princípio, afirmando que "Projetar soluções para serem seguras desde o início ajuda a garantir um equilíbrio apropriado entre usabilidade, interoperabilidade, resiliência e segurança para a solução final".

**Least Privilege**
Este princípio é defendido tanto pela Red Hat quanto pela IBM. A Red Hat o define como: "Indivíduos, identidades de sistema, funções, entidades ou contextos de execução, sejam humanos ou automação, devem ser limitados a incluir apenas o acesso aos recursos necessários para concluir a tarefa atribuída e esperada ou deveres comerciais".

**Minimize Attack Surface**
Este princípio envolve reduzir os pontos de entrada potenciais para ataques, limitando as funcionalidades expostas e restringindo o acesso apenas ao necessário.

**Assume Breach**
Este princípio parte do pressuposto de que uma violação já ocorreu. A IBM afirma que "uma organização assume que uma violação foi realizada por um ator de ameaça".  O objetivo é detectar ameaças o mais cedo possível, mesmo que um comprometimento tenha contornado o controle de fronteira. Isso requer detecção interna proativa, busca por sinais de alerta precoce e uso de procedimentos comprovados.

**Separation of Duty**
Tanto a Red Hat quanto a IBM defendem este princípio. A Red Hat afirma que "Nenhuma pessoa, entidade ou identidade do sistema deve ter controle total ou acesso a todos os elementos de uma política, processo ou sistema".

**Security by Default**
A Red Hat define isso como: "A configuração padrão do sistema deve ter todos os controles de segurança razoáveis ativados e todos os serviços e recursos não necessários para a operação básica desativados". A OWASP também menciona este princípio como "Fail Safe Defaults".

**Understand the Threat**
A Red Hat enfatiza a importância de "considerar a natureza da ameaça ou risco real que está sendo mitigado ou defendido para que as respostas apropriadas sejam utilizadas".

**Continuous Compliance**
A IBM define este princípio como "a configuração de segurança do sistema é constantemente verificada, começando com o desenvolvimento do sistema até o sistema em execução contínua". O objetivo é encontrar problemas de segurança e vulnerabilidades antes que os atores de ameaças o façam. Idealmente, as verificações de conformidade são todas automatizadas e cobrem todas as configurações de segurança, incluindo a plataforma em nuvem, a plataforma de contêineres, middleware e imagens de computação.

**Transparency**
A Red Hat enfatiza que "O princípio de código aberto de transparência também deve se aplicar a questões e dados de segurança, incluindo designs, algoritmos e código-fonte, todos os quais devem estar livremente disponíveis quando razoável". Este princípio está alinhado com o conceito de "Open Design" mencionado pela OWASP.

## Section References

1. <a name="ref-1"></a>[Red Hat's security principles](https://www.redhat.com/en/solutions/security-approach) <!-- REF-? -->
2. <a name="ref-2"></a>[IBM Well-Architected - Security and Compliance](https://www.ibm.com/architectures/well-architected/security) <!-- REF-? -->
3. <a name="ref-3"></a>[Principles of Security](owasp.org/www-project-developer-guide/draft/foundations/security_principles/) <!-- REF-? -->
4. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
5. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
6. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
7. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
8. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
9. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->
10. <a name="ref-?"></a>[NOME DA REFERÊNCIA](LINK PARA A REFERÊNCIA) <!-- REF-? -->