# Application Security Framework (ASF)

## Context

This repository is the final deliverable of my master's project, centered on developing an Application Security Framework (ASF). The goal is to establish a comprehensive strategy for embedding secure practices throughout the Software Development Lifecycle (SDLC). The project was implemented in the automotive retail sector, within an organization that demonstrated a low level of security maturity.

## Repository Purpose

This repository hosts the Application Security Program (ASP), part of the ASF, defining the vision, objectives, and strategies to ensure the development of secure, resilient applications by proactively addressing threats and minimizing vulnerabilities. It consolidates policies, processes, best practices, and tools aimed at embedding security throughout the entire application lifecycle. 

## Scope

The scope includes integrating security practices across the SDLC for both internally developed and third-party applications. This involves evaluating the maturity of existing security practices, defining a target security maturity level, and creating an implementation strategy that promotes a decentralized securty responsability sense, security training and culture building, and adherence to security policies throughout the organization.

## Success Criteria

To succeed, the program must ensure security practices are integrated from the planning and analysis phases, design, coding, testing, through the end of life. This includes implementing best practices as Threat Modeling and Application Risk Assessment, as well as introducing technologies for automating and orchestrating security testing tools (e.g., SAST, DAST, IAST). Additionally, the program must involve continuous verification of code components and supply chain dependencies to proactively identify and mitigate vulnerabilities post-release.

## Audience

Technology Managers, Executives, Product Owners, Development Teams, and Information Security Professionals.

# ASF Components

This framework consists of a structured set of guidelines, standards, and policies outlining how security should be integrated and managed in applications at a strategic level. It is designed to provide a consistent and repeatable foundation for implementing security across all stages of the **Secure Development Lifecycle (SDL)**, regardless of architecture (cloud, hybrid, client, or mobile). Its scope includes the processes and practices that support the **Application Security Program (ASP)**, serving as the technical and procedural basis for scalable and repeatable security initiatives.

The ASF is composed of an **Application Security Program (ASP)**, an **Application Security Roadmap (ASR)**, and an **Application Security Posture Management System (ASPMS)**, which operationalizes the final SDL implementation and maintenance.

- ### Application Security Program (ASP)

    The ASP is a broad, strategic initiative within the organization aimed at implementing policies, processes, and technologies to reduce the intake of vulnerabilities in applications during their development lifecycle. It is by nature more expansive and strategic, focusing on fostering a security culture and implementing organizational policies and processes, while the ASPMS addresses its operationalization.
    
    Through this, the organization can establish governance standards and metrics for application security, build a strong and widespread security culture, define and organize security resources, model threats, and review security designs. Additionally, it implements best practices for secure coding, testing, and deployment, integrating security throughout the SDLC and ensuring its robustness until decommissioning.

- ### Application Security Roadmap (ASR)

    The ASR is essentially a detailed strategic plan guiding the organization in adopting and implementing the ASP. It acts as a tactical plan, serving as a roadmap for evolving application security within the organization. The ASR not only identifies the necessary steps for implementation but also sets timelines, resources, and responsibilities for each task. It operationalizes everything from the initial assessment of existing security practices to the deployment of new policies, processes, and tools proposed in the ASP. While the ASP defines the overarching framework, the ASR outlines the specific actions to be taken.

    The main function of the ASR is to ensure a smooth and structured transition from SDLC to SDL, minimizing internal resistance and ensuring collaboration among all stakeholders, including developers, project managers, and security teams. Additionally, it helps manage the impact of changes, ensuring they are implemented with minimal disruption to existing operations.

- ### Application Security Posture Management System (ASPMS)

    The ASPMS is the operational approach to the ASR, using a set of tools focused on the continuous management and monitoring of application security throughout its lifecycle. This system ensures that the security measures established during ASR implementation are not only maintained but also continuously improved. It involves the identification and management of risks and vulnerabilities, remediation, compliance monitoring, regular audits, and security reporting, all automated and integrated with DevSecOps practices.

    It provides centralized visibility into the security posture of all applications, enabling proactive risk-based management. The focus is on the continuous and operational management of application security, with an emphasis on real-time detection and mitigation of vulnerabilities. In other words, the ASPMS allows the organization to not only respond quickly to new threats but also adapt its security practices as needed, ensuring the security posture remains robust in the face of evolving threats and software development.

    The ASPMS is closely aligned with the **DevSecOps** culture, ensuring that all personnel involved in the development process are aware of and continuously trained to follow the established security practices, tailored to the needs of each project.

This approach allows the organization to establish a resilient and adaptable security cycle, where each component of the Application Security Framework (ASF) works in an integrated manner to ensure the confidentiality, integrity, and continuous availability of applications and data.

Through the **Application Security Roadmap (ASR)**, the organization can align the strategic goals of the **Application Security Program (ASP)** with specific tactical actions, ensuring that security practices are adopted in a coordinated and efficient manner. This not only facilitates the transition to a **Secure Development Lifecycle (SDL)** but also ensures that necessary changes are implemented without significant disruption to daily operations.

Finally, the **Application Security Posture Management System (ASPMS)** offers a layer of continuous governance, maintaining clear, centralized visibility over application security. By automating the detection and mitigation of vulnerabilities and ensuring constant compliance with established security policies, the ASPMS strengthens the organization’s ability to adapt quickly to new threats and maintain resilience in an ever-changing threat landscape.

# Compliance with Standards and Regulations

This Application Security Framework project is aligned with the key standards and regulations relevant to data protection and cybersecurity, including ISO 27001:2022, Portuguese legislation, and the General Data Protection Regulation (GDPR) of the European Union.

### Portuguese Legislation

The project considers the following legislation:

- **Law No. 58/2019**: Law implementing the GDPR in Portugal, which adapts the national legal framework to the GDPR, complementing and specifying some provisions.
- **Law No. 46/2018**: Cybersecurity Law, which establishes the legal framework for cybersecurity in Portugal.
- **Law No. 109/2009**: Cybercrime Law, which defines computer crimes and the rules for evidence collection and international cooperation in criminal matters.
- **Resolution of the Council of Ministers No. 41/2018**: Approves the minimum technical requirements for the networks and information systems that essential service operators must adopt.

### Relevant Articles of the GDPR

The following GDPR articles are particularly relevant to the project:

- **Article 5**: Principles relating to the processing of personal data, including lawfulness, fairness, transparency, data minimization, and integrity.
- **Article 25**: Data protection by design and by default, requiring organizations to implement appropriate technical and organizational measures.
- **Article 32**: Security of processing, which requires the implementation of adequate measures to ensure a level of security appropriate to the risk.
- **Article 33**: Notification of a personal data breach to the supervisory authority.
- **Article 35**: Data protection impact assessment, mandatory when processing is likely to result in a high risk to the rights of individuals.
- **Article 37**: Designation of the data protection officer (DPO).

<!--
### Compliance Considerations

To ensure compliance with the mentioned legislation, the project implements the following measures:

- **Data Mapping**: Identifying where personal data is stored and processed.
- **Risk Assessment**: Conducting regular security risk assessments.
- **Security Policies**: Documenting robust security policies.
- **Access Controls**: Establishing strict access controls for sensitive data.
- **Encryption**: Utilizing encryption to protect data at rest and in transit.
- **Monitoring and Logging**: Implementing systems to detect and investigate security incidents.
- **Incident Response Plan**: Developing and maintaining an effective incident response plan.
- **Training**: Providing regular training on security and data protection for all staff.
-->



While practices may vary depending on the specific needs of each organization, there is a well-defined set of best practices common to many frameworks, providing broader coverage in executing a security program.

