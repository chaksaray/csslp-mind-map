---
title: CSSLP - Certified Secure Software Lifecycle Professional
markmap:
  colorFreezeLevel: 2
  maxWidth: 0
  embedAssets: true
  initialExpandLevel: 2
---

## 01. Secure Software Concept (12%)
### Understand Core Concepts
#### Confidentiality
- Encryption
#### Integrity
- Hashing
- Digital signature
- Code signing
- Reliability
- Modifications
- Authenticity
#### Availability
- Redundancy
- Replication
- Clustering
- Scalability
- Resiliency
#### Authentication
- Multi-factor authentication (MFA)
- Identity & access management (IAM)
- Single sign-on (SSO)
- Federated identity
- Biometrics
#### Authorization
- Access controls
- Permissions
- Entitlements
#### Accountability
- Auditing
- Logging
#### Nonrepudiation
- Digital signatures
- Block chain
#### Governance, risk and compliance (GRC) standards
- Regulatory authority
- Legal
- Idustry
### Understand Security Design Principles
#### Least privilege
- Access control
- Need-to-know
- Run-time previleges
- Zero trust
<!-- - [Website](https://markmap.js.org/)
- [GitHub](https://github.com/gera2ld/markmap) -->
#### Segregation of duties(SoD)
- Multi-party control
- Secret sharing
- Split knowledge
#### Defense in depth/layer defense
- Layered controls
- Geographical diversity
- Technical diversity
- Distributed systems
#### Resiliency
- Fail safe
- Fail secure
- No single point of failure
- Failover
#### Economy of mechanism
- Single sign-on(SSO)
- Password vaults
- Resource efficiency
#### Complete mediation
- Cookie management
- Session management
- Caching of credentials
#### Open design
- Kerckhoff's principle
- Peer review
- Open source
- Crowd source
#### Least common mechanism
- Compartmentalization/isolation
- Allow/accept list
#### Psychological acceptability
- Password complexity
- Passwordless authentication
- Screen layouts
- Completely Automated Pulibic Turing test to tell Computers and Humans Apart (CAPTCHA)
#### Component reuse
- Common controls
- Libraries

## 02. Secure Software Lifecycle Management (11%)
### Manage security within a software development methodology
#### Agile
#### Waterfall
### Identify and adopt security standards
#### Implementing security frameworks
#### Promoting security awareness
### Outline strategy and roadmap
#### Security milestones and checkpoints
- Control gate
- Break/build criteria
### Define and develop security documentation
### Define security matrics
#### Criticality level
#### Average remediation time
#### Complexity
#### Key Performance Indicators (KPI)
#### Objectives and key result
### Decommission applications
#### End of Life (EOL) policies
- Credential removal
- Configuration removal
- License concellation
- Archiving
- Service-level Agreements (SLA)
#### Data disposition
- Retention
- Destruction
- Dependencies
### Create security reporting mechanisms
#### Report
#### Dashboard
#### Feedback loops
### Incorporate integrated risk management methods
#### Regulations, standard and guidelines
- International Organization for Standardization (ISO)
- Payment Card Industry (PCI)
- National Institute of Standards and Technology (NIST)
- Open Web Application Security Project (OWASP)
- Software Assurance Forum for Excellence in Code (SAFECode)
- Software Assurance Maturity Model (SAMM)
- Building Security in Maturity Model (BSIMM)
#### Legal
- Intellectual property
- Breach notification
#### Risk management
- Risk accessment
- Risk analysis
#### Technical risk vs. business risk
### Implement secure operation practices
#### Change management process
#### Incident response plan
#### Verification and validation
#### Assessment and Authorization (A&A) process

## 03.Secure Software Requirement (13%)
### Define software security requirements
#### Functional
- Business requirements
- Use cases
- Stories
#### Non-functional
- Security
- Operational
- Continuity
- Deployment
### Identity compliance requirements
#### Regulatory authority
#### Legal
#### Industry-specific
- Defense
- Healthcare
- Commercial
- Financial
- Payment Card Industry (PCI)
### Identity data classification requirements
#### Data ownership
- Data dictionary
- Data owner
- Data custodian
#### Data labeling
- Sensitivity
- Impact
#### Data types
- Structured
- Unstructured
#### Data lifecycle
- Generation
- Storage
- Retention
- Disposal
#### Data handling
- Personally indentifiable information (PII)
- Publicly available information
### Identify privacy requirements
#### Data collection scope
#### Data anonymization
- Pseudo-anonymous
- Fully anonymous
#### User rights (legal) and preferences
- Data disposal
- Right to be forgotten
- Marketing preferences
- Sharing and using third parties
- Terms of service
#### Data retention
- How long
- Where
- What

#### Cross-border requirements
- Data residency
- Jurisdiction
- Multi-national processing boundaries
### Define data access provisioning
#### User provisioning
#### Service accounts
#### Reapproval process
### Develop security requirement traceability matrix
### Define third-party vendor security requirements

## 04. Secure Software Architecture and Design (15%)
### Define the security architecture
#### Secure architecture and design patterns
- Sherwood Applied Business Security Architecture (SABSA)
- Security chain of responsibility
- Federated identity
#### Security controls identification and prioritization
#### Distributed computing
- Client server
- Peer-to-peer (P2P)
- Message queuing
- N-tier
#### Service-oriented architecture (SOA)
- Enterprise service bus
- Web services
- Microservices
#### Rich internet applications
- Client-side exploits or threats
- Remote code execution
- Constant connectivity
#### Pervasive/ubiquitous computing
- Internet of Things (IoT)
- Wireless
- Location-based
- Radio-Frequency Indentification (RFID)
- Near Field Communication (NFC)
- Sensor networks
- Mesh
#### Embedded software
- Secure boot
- Secure memory
- Secure update
#### Cloud architectures
- Software as a Service (SaaS)
- Platform as a Service (PaaS)
- Infrastructure as a Service (IaaS)
#### Mobile applications
- Implicit data collection privacy
#### Hardware platform concerns
- Side-channel mitigation
- Speculative execution mitigation
- Secure element
- Firmware
- Drivers
#### Cognitive computing
- Artificial intelligence (AI)
- Virtual reality
- Augmented reality
#### Industrial Internet of Things (IoT)
- Facility-related
- Automotive
- Robotics
- Medical devices
- Software-defined production processes
### Perform secure interface design
#### Security mangement interfaces
#### Out-of-band management
#### Log inerfaces
#### Upstream/downstream dependencies
- Key and data sharing between apps
#### Protocol design choices
- Application programming interfaces (API)
- Weeknesses
- State
- Models
### Evaluate and select reusable technologies
#### Credential management
- X.509
- Single sign-on (SSO)
#### Flow control
- Proxies
- Firewalls
- Protocols
- Queuing
#### Data loss prevention (DLP)
#### Virtualization
- Infrastructure as code (IaC)
- Hypervisor
- Containers
#### Trusted computing
- Trusted Platform Module (TPM)
- Trusted Computing Base (TCB)
#### Database security
- Encryption
- Triggers
- Views
- Privilege management
- Secure connections
#### Programming language environment
- Common language runtime
- Java virtual machine (JVM)
- Python
- PowerShell
#### Operating system (OS) controls and services
#### Secure backup and restoration planning
#### Secure data retention, retrieval, and destruction
### Perform threat modeling
#### Threat modeling mothodologies
- 
    | STRIDE | Security Attribute |
    |-|-|
    | Spoofing | Authenticity |
    | Tampering | Integrity |
    | Repudiation | Non-Repudiation |
    | Information Disclosure |  Confidentiality|
    | Denial of Service | Availability |
    | Elevation of Privilege | Authorization |
- Process for Attack Simulation and Threat Analysis (PASTA)
- Hybrid Threat Modeling Method
- Common Vulnerability Scoring System (CVSS)
#### Common threats
- Advanced persistent threat (APT)
- Insider theat
- Common malware
- Third-party suppliers
#### Attack surface evaluation
#### Threat analysis
#### Threat intelligence
- Identify credible relevant threats
- Predict
### Perform architectural risk assessment and design reviews
### Model (Non-Funtional) Security Properties and Constraints
### Define secure operational architecture
#### Deployment topology
#### Operational interfaces
#### Continuous Integration and Continuous Delivery (CI/CD)

## 05. Secure Software Implementation (14%)
### Adhere to relevant secure coding practices (standards, guidelines, regulations)
#### Declarative versus imperative (programmatic) security
#### Concurrency
- Threat safety
- Database concurrency controls
#### Input validation and sanitization
#### Error and execption handling
#### Output sanitization
- Encoding
- Obfuscation
#### Secure logging and auditing
- Confidentiality
- Privacy
#### Session management
#### Trusted/untrusted application programming interface (API), and libraries
#### Resource management
- Compute
- Storage
- Network
- Memory management
#### Secure configuration management
- Baseline security configuration
- Credentials management
#### Tokenization
#### Isolation
- Sandboxing
- Virtualization
- Containerization
- Separation Kernel Protection Profiles
#### Cryptography
- Payload
- Field level
- Transport
- Storage
- Agility
- Encryption
- Algorithm selection
#### Access control
- Trust zone
- Function permissions
- Role-base access control (RBAC)
- Discretionaly access control (DAC)
- Mandatory access control (MAC)
#### Processor microarchitecture security extensions
### Analyze code for security risks
#### Secure code reuse
#### Vulnerability databases/lists
- Open Web Application Security Project (OWASP) Top 10
- Common Weakness Enumerations (CWE)
- SANS Top 25 Most Dangerous Software Errors
#### Static Application Security Testing (SAST)
- Automated code coverage
- Linting
#### Manual code review
- Peer review
#### Inspect for malicious code
- Backdoor
- Logic bombs
- High entropy
### Implement security controls (watchdogs, file integrity monitoring, anti-malware)
### Address the identified security risks (risk strategy)
### Evaluate and integrate components
#### Systems-of-systems integration
- Trust contracts
- Security testing
- Analysis
#### Reusing third-party code or open-source libraries in a secure manner
- Software composition analysis
### Apply security during the build process
#### Anti-tampering techniques
- Code signing
- Obfuscation
#### Compiler switches
#### Address compiler warnings

## 06. Secure Software Testing (14%)
### Develop security testing strategy and plan
#### Standards
- International Organization for Standardization (ISO)
- Open Source Security Testing Methodology Manual
- Software Engineering Institute
#### Functional security testing
- Logic
#### Nonfunctional security testing
- Reliability
- Performance
- Scalability
#### Testing techniques
- Known environment testing
- Unknown environment testing
- Functional testing
- Acceptance testing
#### Testing environment
- Interoperability
- Test harness
#### Security researcher outreach
- Bug bounties
### Develop security test cases
#### Attack surface validation
#### Automated vulnerability testing
- Dynamic application security testing (DAST)
- Interactive application security testing (IAST)
#### Penetration tests
- Security controls
- Known vulnerabilities
- Known malware
#### Fuzzing
- Generated
- Mutated
#### Simulation
- Simulating production environment and production data
- Synthetic transactions
#### Failure
- Fault injection
- Stress testing
- Break testing
#### Cryptographic validation
- Pseudorandom number generators
- Entropy
#### Unit testing and code coverage
#### Regression tests
#### Integration tests
#### Continuous testing
#### Misuse and abuse test cases
### Verify and validate documentation
#### Installation adn setup instructions
#### Error messages
#### User guides
#### Release notes
### Identify undocumented functionality
### Analyze security implications of test results
#### Impact on product management
#### Prioritization
#### Break/build criteria
### Classify and track security errors
#### Bug tracking
- Defects
- Errors and vulnerabilities
#### Risk scoring
- Common Vulnerability Scoring System (CVSS)
### Secure test data
#### Generate test data
- Referential integrity
- Statistical quality
- Production representative
#### Reuse of production data
- Obfucation
- Sanitization
- Anonymization
- Tokenization
- Data aggregation mitigation
### Perform verification and validation testing
#### Independent/internal verification and validation
#### Acceptance test

## 07. Secure Software Deployment, Operations, Maintenance (11%)
### Perform operational risk analysis
#### Deployment environment
- Staging
- Production
- Quality assurance (QA)
#### Personnel training
- Administrators vs. users
#### Legal compliance
- Adherence to guidelines
- Regulations
- Privacy laws
- Copyright
#### System integration
### Secure configuration and version control
#### Hardware
#### Baseline configuration
#### Version control/patching
#### Documentation practices
### Release software security
#### Secure Continuous Integration and Continuous Delivery (CI/CD) pipeline
- DevSecOps
#### Application security toolchain
#### Build artifact verification
- Code signing
- Hashes
### Store and manage security data
#### Credentials
#### Secrets
#### Keys/certificates
#### Configurations
### Ensure secure installation
#### Secure boot
- Key generation
- Access
- Management
#### Least privilege
#### Environment hardening
- Configuration hardening
- Secure patch/updates
- Firewall
#### Secure provisioning
- Credentials
- Configuration
- Licensing
- Infrastructure as code (IaC)
#### Security policy implementation
### Obtain security approval to operate
#### Risk acceptance
#### Sign-off at appropriate level
### Perform information security continuous monitoring
#### Observable data
- Logs
- Events
- Telemetry
- Trace data
- Metrics
#### Threat intelligence
#### Intrusion detection/response
#### Regulation and privacy changes
#### Integration analysis
- Security information and event management (SIEM)
### Execute the incident response plan
#### Incident triage
#### Forensics
#### Remediation
#### Root cause analysis
### Perform patch management
#### Secure release
#### Testing
### Perform vulnerability management
#### Tracking
#### Triaging
#### Common Vulnerabilities and Exposures (CVE)
### Incorporate runtime protection
#### Runtime Application Self Protection (RASP)
#### Web application firewall (WAF)
#### Address Space Layout Randomization (ASLR)
#### Dynamic execution prevention
### Support continuity operations
#### Backup, archiving, retention
#### Disaster recovery plan (DRP)
#### Resiliency
- Operational redundancy
- Erasure code
- Survivability
- Denial-of-service (DoS)
#### Business continuity plan (BCP)
### Integrate service level objectives and service level agreements (SLA)
#### Maintenance
#### Performance
#### Availability
#### Qualified personnel

## 08. Secure Software Supply Chain (10%)
### Implement software supply chain risk management
#### Identification and selection of the components
#### Risk assessment of the components
- Mitigate
- Accept
#### Maintaining third-party components list
- Software bill of materials
#### Monitoring for changes and vulnerabilities
### Analyze security of third-party software
#### Certifications
#### Assessment reports
- Cloud controls matrix
#### Original and support
### Verify pendigree and provenance
#### Secure transfer
- Chain of custody
- Authenticity
- Integrity
#### System sharing/interconnections
#### Code repository security
#### Build environment security
#### Cryptographically-hashed, digitally-signed components
#### Right to audit
### Ensure and verify supplier security requirements in the acquisition process
#### Audit of security policy compliance
- Secure software development practices
#### Vulnerability/incident notification, response, coordination, and reporting
#### Maintenance and support structure
- Community versus commercial
- Licensing
#### Security track record
#### Scope of testing
- Shared responsibility model
#### Log integration into security information and event management (SIEM)
### Support contractual requirements
#### Intellectual property ownership
#### Code escrow
#### Liability
#### Warranty
#### End-User License Agreement (EULA)
#### Service-level agreements (SLA)