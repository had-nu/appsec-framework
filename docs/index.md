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
- [Capítulo 1: Introdução](Part-I/1-0-Cap1-Introducao.md) <!-- Última parte -->
    - [1.1 Enquadramento](Part-I/1-1-Enquadramento.md)
    - [1.2 Justificativa](Part-I/1-2-Justificativa.md)
    - [1.3 Objetivos](Part-I/1-3-Objetivos.md)
    - [1.4 Estrutura do Documento](Part-I/1-4-Estrutura.md)

- [Capítulo 2: Metodologia de Investigação](Part-I/2-0-Cap2-Metodologia.md) <!-- Última parte -->

- [Capítulo 3: Fundamentação Teórica](Part-I/3-0-Cap3-Literatura-Rev.md)
    - [3.1 Conceitos Fundamentais da Segurança Cibernética](Part-I/3-0-Cap3-Literatura-Rev.md#3-1-0-CS-Fundamentos.md)
        - [3.1.1 C.I.A. Triad](Part-I/3-1-CS-Fundamentos.md#cia-triad)
        - [3.1.2 Threat](Part-I/3-1-CS-Fundamentos.md#threat)
        - [3.1.3 Vulnerability](Part-I/3-1-CS-Fundamentos.md#vulnerability)
        - [3.1.4 Risk](Part-I/3-1-CS-Fundamentos.md#risk)
        - [3.1.5 Likelihood vs Impact](Part-I/3-1-CS-Fundamentos.md#likelihood-vs-impact)
        - [3.1.6 Risk Tolerance vs Risk Appetite](Part-I/3-1-CS-Fundamentos.md#risk-tolerance-vs-risk-appetite)
        - [3.1.7 Secure Software Development Lifecycle](Part-I/3-1-CS-Fundamentos.md#SSDLC)
        - [3.1.8 Cyber Security Architecture](Part-I/3-1-CS-Fundamentos.md#cyber-security-architecture)
            - [3.1.8.1 Zero Trust Architecture](Part-I/3-1-CS-Fundamentos.md#zero-trust-architecture)
            - [3.1.8.2 Well-Architected Framework (WAF)](Part-I/3-1-CS-Fundamentos.md#well-architected-framework-waf)
    - [3.2 Conceitos Fundamentais da Segurança de Aplicações](Part-I/3-2-0-AppSec-Fundamentals.md)
        - [3.2.1 Secure Development Principles](Part-I/3-2-0-AppSec-Fundamentals.md#3-2-1-0-secure-dev-principles.md)
            - [3.2.1.1 Secure Code Practices](Part-I/3-2-AppSec-Fundamentals#3-2-1-1-secure-code-practices.md)
                - [3.2.1.2.1 >: Why secure Code Metters?](Part-I/3-2-AppSec-Fundamentals.md#security-risks-for-code)
                - [3.2.1.2.2 Code Review](Part-I/3-2-AppSec-Fundamentals.md#code-review)
                - [3.2.1.2.3 Code Reuse](Part-I/3-2-AppSec-Fundamentals.md#code-reuse)
                - [3.2.1.2.4 Vulnerability Databases](Part-I/3-2-AppSec-Fundamentals.md#vulnerability-databases)
            - [3.2.1.3 Security Controls for Code](Part-I/3-2-AppSec-Fundamentals.md#security-controls-for-code)
            - [3.2.1.4 Security Integration](Part-I/3-2-AppSec-Fundamentals.md#security-integration)
                - [3.2.1.4.1 Development Strategy and Plan](Part-I/3-2-AppSec-Fundamentals.md#development-strategy-and-plan)
                    - [i. Development Models](Part-I/3-2-AppSec-Fundamentals.md#development-models)
                    - [ii. CI/CD](Part-I/3-2-ppSec-Fundamentals.md#ci-cd)
                    - [iii. DevOps](Part-I/3-2-AppSec-Fundamentals.md#devops)
                    - [iv. Build Security in DevOps Pipelines - DevSecOps](Part-I/AppSec-Fundamentals.md#devsecops)
                - [3.2.1.4.2 Test Cases](Part-I/3-2-AppSec-Fundamentals.md#test-cases)
                    - [i. Attack Surface Validation](Part-I/3-2-AppSec-Fundamentals.md#attack-surface-validation)
                    - [ii. Automation of Vulnerability Testing (SAST, DAST, IAST)](Part-I/3-2-AppSec-Fundamentals.md#automation-of-vulnerability-testing-sast-dast-iast)
                    - [iii. Orchestration and Correlation](Part-I/3-2-AppSec-Fundamentals.md#orchestration-and-correlation)
                    - [iv. Penetration Testing](Part-I/3-2-AppSec-Fundamentals.md#penetration-testing)
                    - [v. Fuzzing Testing](Part-I/3-2-AppSec-Fundamentals.md#fuzzing-testing)
                    - [vi. Simulations and Sandboxes](Part-I/3-2-AppSec-Fundamentals.md#simulations-and-sandboxes)
                    - [vii. Cryptography](Part-I/3-2-AppSec-Fundamentals.md#cryptography)
                    - [viii. Regression Testing](Part-I/3-2-AppSec-Fundamentals.md#regression-testing)
                    - [ix. Integration Testing](Part-I/3-2-AppSec-Fundamentals.md#integration-testing)
                    - [x. Continuous Testing](Part-I/3-2-AppSec-Fundamentals.md#continuous-testing)
                    - [xi. Misuse and Abuse Cases](Part-I/3-2-AppSec-Fundamentals.md#misuse-and-abuse-cases)
            - [3.2.1.5 Anti-Tampering (Code Signing, Obfuscation)](Part-I/3-2-AppSec-Fundamentals.md#anti-tampering-code-signing-obfuscation)
        - [3.2.2 Secure-by-Design Principles](Part-I/3-2-0-AppSec-Fundamentals.md#3-2-2-0-secure-design-principles.md)
            - [3.2.2.1 Da direita para a esquerda: introdução ao conceito de Shift-left]() <!-- marcar bem a importancia dessa abordagem -->
            - [3.2.1.2 Least Privilege](Part-I/3-2-AppSecFundamentals.md#least-privilege)
            - [3.2.1.3 Segregation of Duties (SoD)](Part-I/3-2-AppSecFundamentals.md#segregation-of-duties-sod)
            - [3.2.1.4 Defense in Depth](Part-I/3-2-AppSecFundamentals.md#defense-in-depth)
            - [3.2.1.5 Identity and Access Control Management (IAM)](Part-I/3-2-AppSecFundamentals.md#identity-and-access-control-management-iam)
            - [3.2.1.6 Open Design](Part-I/3-2-AppSecFundamentals.md#open-design)
            - [3.2.1.7 Security Requirements](Part-I/3-2-AppSecFundamentals.md#security-requirements)
            - [3.2.1.8 Infrastructure as Code (IaC)](Part-I/3-2-AppSecFundamentals.md#infrastructure-as-code-iac)
            - [3.2.1.9 Threat Modelling](Part-I/3-2-AppSecFundamentals.md#threat-modelling)
            - [3.2.1.10 API and Web Service](Part-I/3-2-AppSecFundamentals.md#api-and-web-service)
        - [3.2.3 Decentralized Security Responsability Approach](Part-I/3-2-AppSec-Fundamentals.md#decentralized-approach)
        - [3.2.4 Cyber Security Governance](Part-I/AppSec-Fundamentals.md#cyber-security-governance)
            - [3.2.4.1 Business Alignment](Part-I/AppSec-Fundamentals.md#business-alignment)
            - [3.2.4.2 Risk Insights](Part-I/AppSec-Fundamentals.md#risk-insights)
            - [3.2.4.3 Security Integration](Part-I/AppSec-Fundamentals.md#security-integration)
            - [3.2.4.4 Business Resilience](Part-I/AppSec-Fundamentals.md#business-resilience)
            - [3.2.4.5 Communication](Part-I/AppSec-Fundamentals.md#communication)
    - [3.3 Frameworks and Methodologies to Build More-Secured Applications](Part-I/3-3-0-SSDLC-frameworks-methods.md)
        - [3.3.1 ISO/IEC 27001:2022 - Information security, cybersecurity and privacy protection — Information security controls](Part-I/3-3-0-SSDLC-frameworks-methods.md#/3-3-1-ISO27001.md)
            - [3.3.1.1 ISO/IEC 27034:2011-2018 — Information technology — Security techniques — Application security](Part-I/3-3-0-SSDLC-frameworks-methods.md#3-3-1-1-0-ISO27034.md) 
        - [3.3.2 OWASP Software Assurance Maturity Model (OWASP SAMM)](Part-I/3-3-0-SSDLC-frameworks-methods.md#)
        - [3.3.3 NIST Secure Software Development Framework (SSDF)](Part-I/3-3-0-SSDLC-frameworks-methods.md#)
        - [3.3.4 Microsoft Secure Development Lifecycle (SDL)](Part-I/3-3-0-SSDLC-frameworks-methods.md#)
        - [3.3.5 Another Approachs](Part-I/3-3-0-SSDLC-frameworks-methods.md#)
            - [3.3.5.1 Building Security In Maturity Model (BSIMM)](Part-I/3-3-0-SSDLC-frameworks-methods.md#)     
            - [3.3.5.2 Center for Internet SecurityCIS](Part-I/3-3-0-SSDLC-frameworks-methods.md#)

# PART II: APPLICATION SECURITY PROGRAM (ASP)
- [Capítulo 4: Secure Development Lifecycle Integrity and Management: How to build and release More-Secure Code?](Part-II/4-0-Cap4-SDL-bases.md)
    - [4.1 Benefits of Early Security Integration]()
        - [Improved Compliance]()
            - [Applicaiton Security Controls Library]()
        - [Enhanced Security and Risk Management]()
        - [Faster Time to Market]()
        - [Cost Efficiency]()
        - [Strengthened Collaboration]()
        - [Client Trust and Reputation]()
    - [4.1 Application Security Toolbox](Part-II/4-Cap4-SDL-bases.md#) <!-- componente teórico -->
        - [4.1.1 SAST]()
        - [DAST]()
        - [IAST]()
        - [SCA]()
        - [PENTESTING]()
        - [RASP]()
        - [WAF]()
    - [4.2 Application Security Orchestration and Correlation - ASOC]()

- [Capítulo 5: Decentralized Security Responsibility Model](Part-II/5-0-Cap5-Decentralized-security-responsibility-model.md)
    - [5.1 Application Security Team Composition](Part-II/5-0-Cap5-Decentralized-security-responsibility-model.md#)
        - [5.1.1 Key-Functions and Roles](Part-II/5-0-Cap5-Decentralized-security-responsibility-model.md#)
        - [5.1.2 The Security Champion Role](Part-II/5-0-Cap5-Decentralized-security-responsibility-model.md#)
    - [5.2 Security Education and Culture Building](Part-II/5-0-Cap5-Decentralized-security-responsibility-model.md#)
    - [5.3 Standards, Regulations, Requirements and Reference Architecture](Part-II/5-0-Cap5-Decentralized-security-responsibility-model.md#5-3-0-Standards-Regulations-RefArchitecture.md)

- [Capítulo 6: Application Security as a Service (ASaaS)](Part-II/6-0-Cap6-AppSec-as-a-Service.md)
    - [6.1 Release-by-Risk](Part-II/6-0-Cap6-AppSec-as-a-Service.md/#Release-by-Risk)
        - [Automation in Release-by-Risk Process]()
            - [Bloqueio vs Habilitação Segura]()
    - [6.2 Application Security as a Service Ecosystem]()
        - [Secure Design]()
            - [Just-in-Time Security Training]()
            - [Threat Modelling]()
            - [Reference Architecture]()
        - [Automated Security Tools]() <!-- componente prático-->
            - [SAST]()
            - [SCA]()
            - [DAST]()
            - [IAST]()
            - [Security Testing as a Service (STaaS)]()
            - [Automated Vulnerability Management]()
            - [API Security Management]()
        - [Continuous Monitoring]()
            - [SIEM]()
            - [IDS]()
            - [Security Incident Correlation]()
            - [Incident Response Automation]()
            - [Runtime Protection Orchestration]()
            - [Real-time Threat Intelligence Feeds]()
        - [Indentity and Access Management (IAM)]()
            - [Single Sign-On (SSO)]()
            - [MFA]()
            - [Session Management]()
        - [Cryptography and Data Protection]()
            - [Centralized Secrets Management]()
        - [Governance and Compliance Orchestration]()
            - [ISO/IEC 27001:2022]()
            - [Policy Automation and Atuditing]()
            - [Continuous Training for Security Culture Building]()

# PART III: APPLICATION SECURITY PROGRAM IMPLEMENTATION AND MANAGEMENT
- [Capítulo 7: Building The Application Security Roadmap (ASR)](Part-III/7-0-Cap7-building-ASR.md#application-security-roadmap-asr)
    - [Maturity Models and Security Posture]()
        - [Security Low-Maturity Dealing]()
        - [Identifing gaps to plan the future]()

- [Capítulo 8: Training Paths](Part-III/8-0-Cap8-training-paths.md#)
    - [Training Roadmaps]()  
        - [Security Champions Training Program - SCTP]()
        - [Training Roadmap for Devs]()
        - [Training Roadmap for AppSec Team]()
    - [Engineering and Security Alignment]()

- [Capítulo 9: Application Security Posture Management System (ASPMS)](Part-III/9-0-Cap9-building-ASPMS.md#)
    - [9.1 Measure to Evolve](Part-III/9-0-Cap9-building-ASPMS.md#)
    - [9.2 O que medir e como medir?](Part-III/9-0-Cap9-building-ASPMS.md#)
        - [9.2.1 MTTR](Part-III/9-0-Cap9-building-ASPMS.md#)
        - [9.2.2 Key Performance Indicators - KPIs](Part-III/9-0-Cap9-building-ASPMS.md#)
        - [9.2.3 Continuous Feedback and Adaptation](Part-III/9-0-Cap9-building-ASPMS.md#)
        - [9.2.4 Continuous Assessment: Building a Security Scorecard](Part-III/9-0-Cap9-building-ASPMS.md#9-2-4-assessment-sec-score-card.md)
        - [9.2.5 Incident Response and Learning](Part-III/9-0-Cap9-building-ASPMS.md#)
- [Capítulo 10: Case Studies](Part-III/10-0-Cap10-case-studies.md)
    <!-- planear como trabalhar os cases
        verview of Industry Responses
        Cisco: Enhancing Network Security with Predictive Analytics
            <Challenge and Solution>
        Risk Management in Software Development
            <Early Integration of Security>
        Facebook: Learning from Risks
            <Adaptation and Growth>
        Threat Modeling and Continuous Improvement
            <Importance in Design Phases>
        Building Security into Development
            <Tools and Implementation>
    -->
- [Capítulo 11: Challenges and Limitations](Part-III/11-0-Cap11-Challenges-Limitations.md) <!-- marcar bem como supera-los -->
        - [Cultural Resistance]()
        - [Lack of Security Assurance]()
        - [Organizational Barriers]()
        - [Scope Creep]()
        - [Flexibility and Adaptation]()

# PART IV: FINAL CONSIDERATIONS
- [Resultados e Discussão](Part-IV/resultados-e-discussao.md)
- [Conclusão](Part-IV/Conclusao.md)
- [Future Trends](Part-IV/ProximosPassos.md)
- [Referências](Part-IV/Referencias.md)
- [Bibliografia](Part-IV/Bibliografia.md)
- [Apêndices](Part-IV/Apendices.md)
- [Anexos](Part-IV/Anexo.md)
