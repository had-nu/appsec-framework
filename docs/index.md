# INDEX

### Licença e Distribuição
### Agradecimentos <!--mover para o README.md'-->
### Declaração de Integridade
### Lista de Imagens
### Lista de Tabelas
### Resumo e Abstract
### Sumário
### Lista de Acônimos e Terminologias

# PART I: RESEARCH METHODOLOGY AND THEORETICAL BASIS
- [Capítulo 1: Introdução](Part-I/1-Cap1Introducao.md)
    - [1.1 Enquadramento](Part-I/1-1-Enquadramento.md)
    - [1.2 Justificativa](Part-I/1-2-Justificativa.md)
    - [1.3 Objetivos](Part-I/1-3-Objetivos.md)
    - [1.4 Metodologia](Part-I/1-4-Metodologia.md)
        - [1.4.1 Método 1](Part-I/1-4-Metodologia.md/#Metodo1)
        - [1.4.2 Método 2](Part-I/1-4-Metodologia.md/#Metodo2)
    - [1.5 Estrutura do Documento](Part-I/1-5-Estrutura.md)

- [Capítulo 2: Revisão de Literatura](Part-I/2-Cap2LiteraturaRev.md)
    - [2.1 Conceitos Fundamentais da Segurança Cibernética](Part-I/2-1-CSFundamentos.md)
        - [2.1.1 C.I.A. Triad](Part-I/2-1-CSFundamentos.md#cia-triad)
        - [2.1.2 Threat](Part-I/2-1-CSFundamentos.md#threat)
        - [2.1.3 Vulnerability](Part-I/2-1-CSFundamentos.md#vulnerability)
        - [2.1.4 Risk](Part-I/2-1-CSFundamentos.md#risk)
        - [2.1.5 Likelihood vs Impact](Part-I/2-1-CSFundamentos.md#likelihood-vs-impact)
        - [2.1.6 Risk Tolerance vs Risk Appetite](Part-I/2-1-CSFundamentos.md#risk-tolerance-vs-risk-appetite)
        - [2.1.7 Cyber Security Architecture](Part-I/2-1-CSFundamentos.md#cyber-security-architecture)
            - [2.1.7.1 Zero Trust Architecture](Part-I/2-1-CSFundamentos.md#zero-trust-architecture)
            - [2.1.7.2 Well-Architected Framework (WAF)](Part-I/2-1-CSFundamentos.md#well-architected-framework-waf)
    - [2.2 Conceitos Fundamentais da Segurança de Aplicações](Part-I/2-2-AppSecFundamentals.md)
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
                    - [ii. CI/CD](Part-I/AppSecFundamentals.md#ci-cd)
                    - [iii. DevOps](Part-I/AppSecFundamentals.md#devops)
                    - [iv. Build Security in DevOps Pipelines - DevSecOps](Part-I/AppSecFundamentals.md#devsecops)
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
    [2.3 Secure Software Development Lifecycle Frameworks](Part-I/2-3-SSDLC-frameworks.md)
    <!--    
        - ISO/IEC 27034:2011-2018 - Application Security (encontrar este documento)
        - OWASP SAMM v2
        - BSIMM
        - NIST SSDF
        - Microsoft SDL
        - CIS
    -->

# PART II: APPLICATION SECURITY PROGRAM (ASP)
- [Capítulo 3: Secure Development Lifecycle Integrity and Management: How to build and release More-Secure Code?](Part-II/SDL-Man.md)
<!-- 
    - Application Security Toolbox (SAST, DAST, IAST, SCA, PENTESTING, RASP, WAF)
    - Application Security Orchestration and Correlation - ASOC
-->
- [Capítulo 4: Decentralized Security Responsibility Model](Part-II/Decentralized-security-responsibility-model.md)
<!-- 
    - Application Security Team Composition
        - Key-Functions
        - Key-Roles
            - The Security Champion Role
    - Security Education and Culture Building
    - Standards, Regulations, Requirements and Reference Architecture     
-->
- [Capítulo 5: Application Security as a Service (ASaaS)](Part-II/Application-security-as-a-service.md)
    - [5.1 Release-by-Risk](Part-II/Application-security-as-a-service.md/#Release-by-Risk)
<!-- 
    - Automation in Release-by-Risk Process
        - Bloqueio vs Habilitação Segura
    - Application Security as a Service Ecosystem
        - Secure Design
            - Just-in-Time Security Training
            - Threat Modelling
            - Reference Architecture
        - Automated Security Tools
            - SAST
            - SCA
            - DAST
            - IAST
            - Security Testing as a Service (STaaS)
            - Automated Vulnerability Management
            - API Security Management
        - Continuous Monitoring 
            - SIEM
            - IDS
            - Security Incident Correlation
            - Incident Response Automation
            - Runtime Protection Orchestration
            - Real-time Threat Intelligence Feeds
        - Indentity and Access Management (IAM)
            - Single Sign-On (SSO)
            - MFA
            - Session Management
        - Cryptography and Data Protection
            - Centralized Secrets Management
        - Governance and Compliance Orchestration
            - ISO/IEC 27001:2022
            - Policy Automation and Atuditing
            - Continuous Training for Security Culture Building 
-->

# PART III: APPLICATION SECURITY PROGRAM IMPLEMENTATION AND MANAGEMENT
- [Capítulo 6: Building The Application Security Roadmap (ASR)](Part-III/ASP.md#application-security-roadmap-asr)
<!--
    - Maturity Models and Security Posture
        - Security Low-Maturity Dealing
        - Identifing gaps to plan the future
-->

- [Capítulo 7: Training Paths](Part-III/ASP.md#training-paths)
<!--
    - Training Roadmaps    
        - Security Champions Training Program - SCTP
        - Training Roadmap for Devs
        - Training Roadmap for AppSec Team
    - Engineering and Security Alignment
-->

- [Capítulo 8: Application Security Posture Management System (ASPMS)](Part-III/ASP.md#application-security-posture-management-system-aspms)
<!--
    - Measure to Evolve
    - O que medir e como medir?
        - MTTR
        - KPIs
        - Feedback dos Pares
        - Security Scorecard
-->
# PART IV: FINAL CONSIDERATIONS
- [Resultados e Discussão](Part-IV/resultados-e-discussao.md)
- [Conclusão](Part-IV/Conclusao.md)
- [Próximos Passos e Trabalhos Futuros](Part-IV/ProximosPassos.md)
- [Referências](Part-IV/Referencias.md)
- [Bibliografia](Part-IV/Bibliografia.md)
- [Apêndices](Part-IV/Apendices.md)
- [Anexos](Part-IV/Anexo.md)