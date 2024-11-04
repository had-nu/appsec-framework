## 4.3.3 Interseções Críticas entre OWASP Top 10 e CWE Top 25 para Vulnerabilidades de Segurança em Aplicações Web <!-- colocar na planilha de referências do Notero; verificar itens individualmente -->

Ao cruzar as listas atualizadas das vulnerablidades mais comuns do OWASP Top 10 (2021) e do CWE Top 25 (2023),[[1](#ref-1)] [[2](#ref-2)] é possível ter uma visão unificada dos riscos mais críticos para a segurança de aplicações, o que permite que desenvolvedores e arquitetos priorizem controles adequadamente. A tabela a seguir alinha as entradas relevantes do CWE Top 25 com a lista do OWASP Top 10, fornecendo uma visão abrangente de como as duas listas se relacionam entre si para fornecer insights sobre as fraquezas de segurança mais críticas no desenvolvimento de software.

| OWASP Vulnerability | OWASP Description | CWE (2023) | CWE Description | CWE Rank |
|---------------------|-------------------|------------|-----------------|----------|
| A01 Broken Access Control | Access controls enforce policies so that users cannot act outside of their intended permissions. Failures typically lead to unauthorized information disclosure or modification, destruction of data, or performing a business function outside the user's limits. | CWE-862 | Missing Authorization | 11 |
| | | CWE-306 | Missing Authentication for Critical Function | 20 |
| | | CWE-269 | Improper Privilege Management | 22 |
| | | CWE-863 | Incorrect Authorization | 24 |
| A02 Cryptographic Failures | Previously known as Sensitive Data Exposure, Cryptographic Failures involve protecting data in transit and at rest. This includes passwords, credit card numbers, health records, personal information, and business secrets that require extra protection, especially if that data falls under privacy laws or regulations. | CWE-798 | Use of Hard-coded Credentials | 18 |
| A03 Injection | Injection occurs when untrusted data is sent to an interpreter as part of a command or query, tricking the interpreter into executing unintended commands or accessing data without proper authorization. | CWE-79 | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting') | 2 |
| | | CWE-89 | Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') | 3 |
| | | CWE-78 | Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection') | 5 |
| | | CWE-77 | Improper Neutralization of Special Elements used in a Command ('Command Injection') | 16 |
| | | CWE-94 | Improper Control of Generation of Code ('Code Injection') | 23 |
| A04 Insecure Design | A new category focusing on risks related to design flaws. It requires using threat modeling, secure design patterns and principles, and reference architectures. | CWE-20 | Improper Input Validation | 6 |
| | | CWE-787 | Out-of-bounds Write | 1 |
| | | CWE-416 | Use After Free | 4 |
| | | CWE-125 | Out-of-bounds Read | 7 |
| | | CWE-476 | NULL Pointer Dereference | 12 |
| | | CWE-190 | Integer Overflow or Wraparound | 14 |
| | | CWE-119 | Improper Restriction of Operations within the Bounds of a Memory Buffer | 17 |
| A05 Security Misconfiguration | This includes missing security hardening, improperly configured permissions, unnecessary features enabled, and unchanged default accounts or passwords. | CWE-276 | Incorrect Default Permissions | 25 |
| A06 Vulnerable and Outdated Components | This includes any software that is vulnerable, unsupported, or out of date. | CWE-502 | Deserialization of Untrusted Data | 15 |
| | | CWE-79 | Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting') | 2 |
| | | CWE-89 | Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') | 3 |
| | | CWE-20 | Improper Input Validation | 6 |
| | | CWE-787 | Out-of-bounds Write | 1 |
| | | CWE-416 | Use After Free | 4 |
| A07 Identification and Authentication Failures | This occurs when a user's identity, authentication, or session management is not properly handled, allowing attackers to exploit passwords, keys, or session tokens. | CWE-287 | Improper Authentication | 13 |
| | | CWE-798 | Use of Hard-coded Credentials | 18 |
| A08 Software and Data Integrity Failures | This refers to code and infrastructure that fails to protect against integrity violations, including software updates, critical data, and CI/CD pipelines without verification. | CWE-502 | Deserialization of Untrusted Data | 15 |
| | | CWE-20 | Improper Input Validation | 6 |
| A09 Security Logging and Monitoring Failures | This includes errors in detecting, escalating, and responding to active breaches. Without proper logging and monitoring, breaches cannot be detected. | - | - | - |
| A10 Server Side Request Forgery (SSRF) | SSRF occurs when a web application fetches a remote resource without validating the user-supplied URL, potentially allowing attackers to coerce the application to send crafted requests to unexpected destinations. | CWE-918 | Server-Side Request Forgery (SSRF) | 19 |
| - | - | CWE-22 | Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') | 8 |
| - | - | CWE-352 | Cross-Site Request Forgery (CSRF) | 9 |
| - | - | CWE-434 | Unrestricted Upload of File with Dangerous Type | 10 |
| - | - | CWE-362 | Concurrent Execution using Shared Resource with Improper Synchronization ('Race Condition') | 21 |

É importante observar que, embora não haja uma correspondência direta com algumas vulnerablidades do OWASP Top 10,  algumas entradas do CWEs perpassam uma mesma categoria. Por exemplo, CWEs de natureza arquitetural e de lógica, que envolvem falhas estruturais e arquiteturais desde o início do desenvolvimento, podem se relacionar com Design Inseguro (A04). Embora o "Design Inseguro" seja um conceito amplo, o foco está em vulnerabilidades onde a causa raiz está na falta de consideração de princípios de segurança durante o projeto do sistema. Por exemplo, é possível relacionar "Out-of-bounds Write" (CWE-787) e "Use After Free" (CWE-416) com a categoria A04 Insecure Design, pois ambas as vulnerabilidades são frequentemente resultado de decisões de design tomadas durante o processo de desenvolvimento de software.[[3](#ref-3)] Elas representam falhas fundamentais na forma como a memória é gerenciada e acessada, e são frequentemente introduzidas devido à falta de consideração de segurança durante o design.[[4](#ref-4)]

Outra observação importante diz respeito à categoria A09 (Security Logging and Monitoring Failures), do OWASP Top 10 2021, que não tem correspondência direta no CWE Top 25 de 2023 principalmente porque aborda práticas de segurança operacional em vez de vulnerabilidades de código específicas. A09 foca em processos como configuração de logging e monitoramento, que são difíceis de capturar em uma única fraqueza de código. Essas falhas geralmente não são diretamente exploráveis, mas sua ausência ou falha pode dificultar a detecção e a resposta a ataques em andamento.[[5](#ref-5)] [[6](#ref-6)] Por exemplo, se um sistema não estiver registrando eventos críticos, um ataque pode passar despercebido, permitindo que um invasor atue sem ser notado.  

O CWE Top 25 prioriza fraquezas técnicas mensuráveis, enquanto o OWASP inclui A09 para destacar a importância dessas práticas operacionais. Embora existam CWEs relacionadas, como CWE-778 (Insufficient Logging), elas não figuram no Top 25 atual. Entretanto, a ausência de uma correspondência à A09 no CWE Top 25 não diminui sua importância crítica para a segurança geral dos sistemas. A inclusão da A09 no OWASP Top 10 ressalta a importância de uma abordagem holística para a segurança. Apenas corrigir vulnerabilidades conhecidas não é suficiente se as organizações não tornarem uma prática contínua o monitoramento de suas aplicações e de sua infraestrutura para atividades suspeitas. [[5](#ref-5)] 


## Section References

1. <a name="ref-1"></a>[OWASP Top 10](https://owasp.org/Top10/) <!-- REF-? -->
2. <a name="ref-2"></a>[CWE TOP 25 Most Dangerous Software Errors](https://www.sans.org/top25-software-errors/) <!-- REF-? -->
3. <a name="ref-3"></a>[SoK: Eternal War in Memory](https://ieeexplore.ieee.org/document/6547101) <!-- REF-? -->
4. <a name="ref-4"></a>[Memory Errors: The Past, the Present, and the Future](https://link.springer.com/chapter/10.1007/978-3-642-33338-5_5) <!-- REF-? -->
5. <a name="ref-5"></a>[Logging and Log Management: The Authoritative Guide to Understanding the Concepts Surrounding Logging and Log Management](https://www.sciencedirect.com/book/9781597496353/logging-and-log-management) <!-- REF-? -->
6. <a name="ref-6"></a>[Guide to Computer Security Log Management. NIST Special Publication 800-92.](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-92.pdf) <!-- REF-? -->