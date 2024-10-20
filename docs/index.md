# Índice da Dissertação

### Licença e Distribuição
### Agradecimentos <!--mover para o README.md'-->
### Declaração de Integridade
### Lista de Imagens
### Lista de Tabelas
### Resumo e Abstract
### Sumário
### Lista de Acônimos e Terminologias

## Part I: RESEARCH METHODOLOGY AND THEORETICAL BASIS
- [Capítulo 1: Introdução](Part-I/Introducao.md)
    - [1.1 Enquadramento](Part-I/Enquadramento.md)
    - [1.2 Justificativa](Part-I/Justificativa.md)
    - [1.3 Objetivos](Part-I/Objetivos.md)
    - [1.4 Metodologia](Part-I/Metodologia.md)
        - [1.4.1 Método 1](Part-I/Metodologia/Método1.md)
        - [1.4.2 Método 2](Part-I/Metodologia/Método2.md)
    - [1.5 Estrutura do Documento](Part-I/Estrutura.md)

- [Capítulo 2: Revisão de Literatura](Part-I/LiteraturaRev.md)
    - [2.1 Conceitos Fundamentais da Segurança Cibernética](Part-I/CSFundamentos.md)
        - [2.1.1 C.I.A. Triad](Part-I/CSFundamentos.md#cia-triad)
        - [2.1.2 Threat](Part-I/CSFundamentos.md#threat)
        - [2.1.3 Vulnerability](Part-I/CSFundamentos.md#vulnerability)
        - [2.1.4 Risk](Part-I/CSFundamentos.md#risk)
        - [2.1.5 Likelihood vs Impact](Part-I/CSFundamentos.md#likelihood-vs-impact)
        - [2.1.6 Risk Tolerance vs Risk Appetite](Part-I/CSFundamentos.md#risk-tolerance-vs-risk-appetite)
        - [2.1.7 Cyber Security Architecture](Part-I/CSFundamentos.md#cyber-security-architecture)
            - [2.1.7.1 Zero Trust Architecture](Part-I/CSFundamentos.md#zero-trust-architecture)
            - [2.1.7.2 Well-Architected Framework (WAF)](Part-I/CSFundamentos.md#well-architected-framework-waf)
    - [2.2 Conceitos Fundamentais da Segurança de Aplicações](Part-I/AppSecFundamentals.md)
        - [2.2.1 Secure Design Principles](Part-I/AppSecFundamentals.md#secure-design-principles)
            - [2.2.1.1 Least Privilege](Part-I/AppSecFundamentals.md#least-privilege)
            - [2.2.1.2 Segregation of Duties (SoD)](Part-I/AppSecFundamentals.md#segregation-of-duties-sod)
            - [2.2.1.3 Defense in Depth](Part-I/AppSecFundamentals.md#defense-in-depth)
            - [2.2.1.4 Identity and Access Control Management (IAM)](Part-I/AppSecFundamentals.md#identity-and-access-control-management-iam)
            - [2.2.1.5 Open Design](Part-I/AppSecFundamentals.md#open-design)
            - [2.2.1.6 Security Requirements](Part-I/AppSecFundamentals.md#security-requirements)
            - [2.2.1.7 Infrastructure as Code (IaC)](Part-I/AppSecFundamentals.md#infrastructure-as-code-iac)
            - [2.2.1.8 Threat Modelling](Part-I/AppSecFundamentals.md#threat-modelling)
            - [2.2.1.9 API and Web Service](Part-I/AppSecFundamentals.md#api-and-web-service)
        - [2.2.2 Secure Code](Part-I/AppSecFundamentals.md#secure-code)
            - [2.2.2.1 Secure Code Practices](Part-I/AppSecFundamentals.md#secure-code-practices)
            - [2.2.2.2 Security Risks for Code](Part-I/AppSecFundamentals.md#security-risks-for-code)
                - [2.2.2.2.1 Code Review](Part-I/AppSecFundamentals.md#code-review)
                - [2.2.2.2.2 Code Reuse](Part-I/AppSecFundamentals.md#code-reuse)
                - [2.2.2.2.3 Vulnerability Databases](Part-I/AppSecFundamentals.md#vulnerability-databases)
            - [2.2.2.3 Security Controls for Code](Part-I/AppSecFundamentals.md#security-controls-for-code)
            - [2.2.2.4 Security Integration](Part-I/AppSecFundamentals.md#security-integration)
                - [2.2.2.4.1 Development Strategy and Plan](Part-I/AppSecFundamentals.md#development-strategy-and-plan)
                    - [i. Development Models](Part-I/AppSecFundamentals.md#development-models)
                    - [ii. DevOps](Part-I/AppSecFundamentals.md#devops)
                    - [iii. DevSecOps](Part-I/AppSecFundamentals.md#devsecops)
                - [2.2.2.4.2 Test Cases](Part-I/AppSecFundamentals.md#test-cases)
                    - [i. Attack Surface Validation](Part-I/AppSecFundamentals.md#attack-surface-validation)
                    - [ii. Automation of Vulnerability Testing (SAST, DAST, IAST)](Part-I/AppSecFundamentals.md#automation-of-vulnerability-testing-sast-dast-iast)
                    - [iii. Orchestration and Correlation](Part-I/AppSecFundamentals.md#orchestration-and-correlation)
                    - [iv. Penetration Testing](Part-I/AppSecFundamentals.md#penetration-testing)
                    - [v. Fuzzing Testing](Part-I/AppSecFundamentals.md#fuzzing-testing)
                    - [vi. Simulations and Sandboxes](Part-I/AppSecFundamentals.md#simulations-and-sandboxes)
                    - [vii. Cryptography](Part-I/AppSecFundamentals.md#cryptography)
                    - [viii. Regression Testing](Part-I/AppSecFundamentals.md#regression-testing)
                    - [ix. Integration Testing](Part-I/AppSecFundamentals.md#integration-testing)
                    - [x. Continuous Testing](Part-I/AppSecFundamentals.md#continuous-testing)
                    - [xi. Misuse and Abuse Cases](Part-I/AppSecFundamentals.md#misuse-and-abuse-cases)
            - [2.2.2.5 Anti-Tampering (Code Signing, Obfuscation)](Part-I/AppSecFundamentals.md#anti-tampering-code-signing-obfuscation)
        - [2.2.3 Cyber Security Governance](Part-I/AppSecFundamentals.md#cyber-security-governance)
            - [2.2.3.1 Business Alignment](Part-I/AppSecFundamentals.md#business-alignment)
                - [2.2.3.1.1 Risk Insights](Part-I/AppSecFundamentals.md#risk-insights)
                - [2.2.3.1.2 Security Integration](Part-I/AppSecFundamentals.md#security-integration)
                - [2.2.3.1.3 Business Resilience](Part-I/AppSecFundamentals.md#business-resilience)
                - [2.2.3.1.4 Communication](Part-I/AppSecFundamentals.md#communication)

## Parte II: INTEGRIDADE E GESTÃO DO CICLO DE VIDA DE DESENVOLVIMENTO SEGURO
- [Capítulo 3: Releasing More-Secure Code](Part-II/ASDomains.md#releasing-more-secure-code)
- [Capítulo 4: Decentralized Security Responsibility Model](Part-II/SDL-Man.md#decentralized-security-responsibility-model)
- [Capítulo 5: Application Security as a Service (ASaaS)](Part-II/SDL-Man.md#application-security-as-a-service-asaas)
    - [5.1 ](Part-II/SDL-Man.md/#)

## Parte III: IMPLEMENTAÇÃO E GESTÃO DO PROGRAMA DE SEGURANÇA APLICATIVA
- [Capítulo 6: Maturity Models and Security Posture](Part-III/ASP.md#maturity-models-and-security-posture)
- [Capítulo 7: Application Security Roadmap (ASR)](Part-III/ASP.md#application-security-roadmap-asr)
- [Capítulo 8: Application Security Posture Management System (ASPMS)](Part-III/ASP.md#application-security-posture-management-system-aspms)
- [Capítulo 9: Measure to Evolve](Part-III/ASP.md#measure-to-evolve)
- [Capítulo 10: Training Paths](Part-III/ASP.md#training-paths)

## Parte IV: CONSIDERAÇÕES FINAIS
- [Resultados e Discussão](Part-IV/#resultados-e-discussao)
- [Conclusão](Part-IV/Conclusao.md#conclusao)
- [Referências](Part-IV/Referencias.md#referencias)
