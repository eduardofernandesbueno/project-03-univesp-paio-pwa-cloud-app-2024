# Paió Brechó — Mobile Web Application & Cloud Engineering

**UNIVESP Integrative Project III (2024)**

**Full-Stack Development · Progressive Web Applications · Cloud Computing · Relational Databases · CI/CD · Accessibility · Web Analytics**

**Academic Institution:** Virtual University of the State of São Paulo (UNIVESP), Brazil  
**Academic Programs:** Information Technology, Data Science, and Computer Engineering  
**Project:** Integrative Project III — First Semester 2024  
**Original Title:** *Aplicativo Móvel Paió: Brechó Sustentável*  
**Application Domain:** Sustainable Retail, Small Business Digitalization, and Customer Analytics  
**Project Type:** Collaborative Academic Software Engineering Project  
**Status:** Completed academic coursework; historical implementation and deployment

[Project Presentation](https://youtu.be/LHl9hPPkEwA) · [GitHub Profile](https://github.com/eduardofernandesbueno) · [Professional Portfolio](https://eduardofernandesbueno.github.io/)

---

## 1. Overview

**Paió Brechó** is a mobile-oriented web application developed as part of Integrative Project III at the Virtual University of the State of São Paulo (UNIVESP) in 2024.

The application was designed to support the digital transformation of Paió Brechó, a small second-hand retail business located in Capão Bonito, São Paulo, Brazil.

The project addressed practical challenges involving online product visibility, customer communication, customer data management, and digital business analytics.

The original solution combined:

- Responsive web development.
- Progressive Web Application (PWA) concepts.
- HTML5, CSS3, and JavaScript.
- PHP-based server-side processing.
- MySQL relational database integration.
- Microsoft Azure cloud infrastructure.
- Azure App Service and Azure Database for MySQL.
- Git and GitHub version control.
- GitHub Actions and CI/CD experimentation.
- Jenkins integration and automation experiments.
- Accessibility and usability evaluation.
- Software and database connectivity testing.
- Google Analytics for website audience analysis.

The application evolved from earlier web development work completed in Integrative Projects I and II.

Its final academic implementation was demonstrated in browsers and on mobile devices, including iOS and Android.

**Project maturity:** This repository documents a functional academic prototype from 2024. Its current cloud deployment, production availability, security configuration, and database connectivity have not been independently revalidated.

---

## 2. Business Problem

Paió Brechó is a small retail business focused on second-hand clothing and other products.

The original research identified operational challenges involving:

- Limited online product visibility.
- Dependence on social media and messaging applications.
- Lack of structured customer registration.
- Difficulty recovering customer contact information.
- Limited access to audience analytics.
- Insufficient digital integration between customer-facing interfaces and business data.

The project investigated how a low-cost mobile web application could improve communication between the business and its customers.

### Business Objectives

The application was designed to:

1. Provide an online storefront.
2. Display products available at the business.
3. Improve customer communication.
4. Enable customer registration.
5. Store customer information in a relational database.
6. Support customer-related analytical insights.
7. Provide a mobile-accessible interface.
8. Introduce cloud deployment and software engineering practices.

The project was an academic prototype, not a documented commercial e-commerce platform with verified payment processing or automated inventory management.

---

## 3. Academic Objectives

The UNIVESP Integrative Project III assignment required the development of a mobile application incorporating:

- Database integration.
- Data analysis.
- JavaScript-based web scripting.
- Cloud computing.
- Accessibility.
- Version control.
- Continuous integration.
- Software testing.

The Paió application was developed to investigate these requirements through an integrated software project.

### Methodology

The project used Design Thinking and iterative development activities, including:

- Stakeholder interviews.
- Business needs assessment.
- Questionnaires.
- Requirements analysis.
- MVP development.
- Prototype implementation.
- User feedback.
- Interface refinement.
- Testing.
- Technical-scientific documentation.

---

## 4. Technology Stack

The following technologies were documented in the 2024 academic report and associated source repository.

The stack is organized by implementation area.

### 4.1 Frontend and Mobile Web

| Technology | Role |
|---|---|
| HTML5 | Semantic web content and application pages |
| CSS3 | Styling and responsive presentation |
| JavaScript | Client-side functionality and web scripting |
| Progressive Web App | Mobile-oriented, installable web application approach |
| Web App Manifest | Application name, metadata, and installability configuration |
| Service Worker | Browser caching and background web functionality |
| Responsive Web Design | Presentation across desktop, tablet, and smartphone screens |
| Browser APIs | Web platform functionality |

The repository includes `manifest.json` and `service-worker.js`, providing evidence of PWA-related implementation work.

The academic report documents successful installation or access demonstrations on iPhone and Android tablet devices.

These demonstrations do not establish current compatibility with every modern browser or operating system.

### 4.2 Backend and Database

| Technology | Role |
|---|---|
| PHP | Server-side application and form processing |
| MySQL | Relational database management |
| SQL | Database creation, querying, and data retrieval |
| Azure Database for MySQL | Historical cloud-hosted database |
| MySQL Workbench | Database administration and inspection |
| Azure Data Studio | Database connectivity and development |
| HTML Forms | Customer registration data collection |

Representative source files include:

```text
formulario.php
formulario_mysql.php
processa_formulario.php
select.php
config.php
cadastro_de_clientes.sql
SQLQuery_1.sql
SQLQuery_2.sql
```

These files document backend and database-related development.

They should be reviewed before execution or public reuse because historical configuration files may contain sensitive database connection information.

### 4.3 Cloud Infrastructure

| Technology | Role |
|---|---|
| Microsoft Azure | Cloud infrastructure and hosting |
| Azure App Service | Historical application deployment |
| Azure Database for MySQL Flexible Server | Managed relational database |
| GitHub Pages | Static web deployment experiments |
| GitHub Actions | Repository-linked automation and deployment configuration |
| Azure deployment slots | Deployment configuration explored during the project |

The original report documented an Azure-hosted web application and a managed MySQL database.

The infrastructure was created for academic development and testing.

The current status of these historical resources is not confirmed.

### 4.4 DevOps, CI/CD, and Version Control

| Technology | Role |
|---|---|
| Git | Source version control |
| GitHub | Repository hosting and collaboration |
| GitHub Actions | Integration with deployment workflows |
| Jenkins | CI experimentation and SCM configuration |
| Visual Studio Code | Development and integration environment |
| Azure integration for VS Code | Cloud development and deployment support |
| Gradle | Build configuration present in the repository |

The academic report documents GitHub-to-Azure configuration and Jenkins installation with plugins and source-control settings.

**CI/CD scope:** These activities demonstrate cloud integration and automation experimentation. They do not establish that a current, fully tested CI/CD pipeline is operational.

### 4.5 Testing and Accessibility

| Tool / Method | Project Role |
|---|---|
| axe accessibility tools | Identification of accessibility issues |
| W3C Markup Validator | HTML validation |
| AChecker | Automated accessibility inspection |
| WCAG guidelines | Accessibility evaluation reference |
| JUnit | Java unit-testing experiment |
| Browser testing | Functional validation in supported browsers |
| Database connectivity tests | Verification of application-to-database communication |
| Mobile device testing | Historical iOS and Android demonstrations |
| User feedback | Usability-oriented improvements |

The original report documented accessibility findings and testing results.

Automated accessibility tools provide diagnostic evidence, but their results do not amount to a comprehensive accessibility certification.

### 4.6 Analytics

| Technology | Role |
|---|---|
| Google Analytics | Website audience measurement |
| Web Analytics | Visitor and device analysis |
| Audience segmentation | Exploratory understanding of access patterns |
| Real-time analytics | Observation of application visits during testing |

The report documented Google Analytics integration and demonstrations of visitor activity, device information, and geographic information.

These findings describe historical application testing in 2024, not current usage or verified business outcomes.

### 4.7 Development Environment

The academic report references:

- Visual Studio Code.
- Azure Data Studio.
- MySQL Workbench.
- PyCharm Education.
- GitHub.
- Microsoft Azure.
- Web browsers including Safari and Chrome.

The source repository also includes development configuration associated with Gradle and other experimental environments.

Not all development tools were essential runtime dependencies of the final mobile web application.

---

## 5. Application Architecture

### 5.1 Conceptual Architecture

The application followed a web-based client/server architecture.

```text
Mobile / Desktop Browser
        |
        v
HTML + CSS + JavaScript
        |
        +--> PWA Manifest / Service Worker
        |
        v
Web Application / PHP
        |
        v
MySQL Database
        |
        v
Customer Registration Records
```

Supporting integration and deployment activities involved:

```text
Git / GitHub
     |
     +--> GitHub Pages experiments
     |
     +--> GitHub Actions integration
     |
     +--> Azure App Service
     |
     +--> Azure Database for MySQL
```

Google Analytics provided a separate audience-observation layer for web traffic analysis.

### 5.2 Frontend

The frontend was responsible for displaying products, presenting business information, handling navigation, and providing access to customer registration.

The project used HTML, CSS, and JavaScript.

### 5.3 Backend

PHP scripts handled server-side form and database interactions.

### 5.4 Persistence

The database layer used MySQL and SQL queries to support customer-related information.

### 5.5 Hosting

Microsoft Azure was used for the historical web application and database deployment.

### 5.6 Analytics

Google Analytics was integrated to provide audience and device-related insights.

### Architecture Limitations

This is a conceptual representation of the historical implementation.

It should not be interpreted as an independently verified production architecture, secure deployment, or high-availability cloud system.

---

## 6. Progressive Web Application Development

The project investigated Progressive Web Application technologies to support a mobile-oriented experience.

### PWA Components

The repository includes:

```text
manifest.json
service-worker.js
index.html
script.js
```

The academic work explored:

- Mobile-friendly web navigation.
- Browser-based installation.
- Application metadata.
- Cached web resources.
- Smartphone and tablet compatibility.

### Historical Mobile Testing

The report includes demonstrations involving:

- Safari on iPhone.
- Android tablet access.
- Desktop browser execution.
- Application icons and mobile presentation.

### Limitations

PWA installability and offline behavior depend on browser support, correct service-worker configuration, secure contexts, and resource caching.

The presence of a service worker does not guarantee that all application features work offline, particularly server-dependent forms and database operations.

---

## 7. Application Features

The historical prototype contained several functional areas.

### 7.1 Home

The main page introduced Paió Brechó and its digital storefront.

### 7.2 Products

The product section presented merchandise and provided a digital display for the business.

### 7.3 Sell to Paió

The application included a page associated with customers interested in selling products to the shop.

### 7.4 Administration

An administrative area was developed as part of the broader customer-management workflow.

The historical documentation does not establish that this area had production-grade authentication, authorization, or access control.

### 7.5 Customer Registration

Customer-facing forms supported submission of information to the backend.

PHP and MySQL were used for data processing and persistence.

### 7.6 Business Analytics

Google Analytics was used to observe website access and explore customer-audience characteristics.

**Scope limitation:** The documented functionality does not establish a complete CRM, payment gateway, online checkout, or production inventory-management system.

---

## 8. Relational Database Implementation

The project used MySQL to investigate structured persistence.

The original report documents a database named:

```text
formulario-paio
```

and a customer-related table identified as:

```text
clientes
```

The application explored the flow:

**Customer Form → PHP Processing → SQL Operations → MySQL Database**

### Database Tools

- Azure Database for MySQL.
- MySQL Workbench.
- Azure Data Studio.
- SQL scripts.

### Historical Validation

The academic report contains screenshots demonstrating successful database connectivity and retrieval of submitted form data.

### Data Protection

The system involved customer information and therefore requires attention to:

- Privacy.
- Appropriate collection purposes.
- Access control.
- Secure database credentials.
- Input validation.
- SQL injection prevention.
- Transport encryption.
- Brazilian General Data Protection Law (LGPD).

Historical academic functionality should not be confused with independently verified LGPD compliance or security hardening.

---

## 9. Cloud Deployment — Microsoft Azure

### 9.1 Azure App Service

The 2024 academic report documented an Azure web application identified as:

```text
pi3-paio
```

Historical URL:

https://pi3-paio.azurewebsites.net/

It also referenced an earlier application endpoint:

https://app-movel-paio.azurewebsites.net/

### 9.2 Azure Database for MySQL

The original project used a MySQL Flexible Server identified as:

```text
server-paio-pi3
```

### 9.3 GitHub Integration

The team explored integration among:

- Visual Studio Code.
- GitHub.
- GitHub Actions.
- Microsoft Azure.

### Deployment Status

These were historical resources documented during the 2024 academic project.

No claim is made that the Azure application or database remains active or accessible in 2026.

**Security note:** Historical database server names are documentation references, not connection instructions. Credentials and other secrets must never be included in the public README.

---

## 10. Version Control and CI/CD

The project used GitHub for source control and collaborative development.

### GitHub

The repository preserved source-code revisions and development history.

### GitHub Pages

The report documents static deployment experiments using GitHub Pages.

The former GitHub username was `EddieFerb`.

The maintainer later renamed the GitHub account to `eduardofernandesbueno`.

Historical GitHub Pages URLs should not be assumed to remain valid after this account transition.

### GitHub Actions

The project documented integration between GitHub Actions and Azure deployment resources.

### Jenkins

Jenkins was installed and configured for exploratory CI activities, including source-code management integration.

### Engineering Interpretation

This project demonstrates experience setting up and investigating automation tools.

It does not claim:

- A currently functioning automated release pipeline.
- Continuous production monitoring.
- Full automated security scanning.
- Verified deployment rollback.
- Production-grade infrastructure automation.

These would require additional implementation evidence.

---

## 11. Accessibility Engineering

Accessibility was one of the formal academic requirements.

The project investigated web accessibility using automated analysis and manual development adjustments.

### Tools

- axe accessibility tools.
- W3C Markup Validator.
- AChecker.
- WCAG reference guidelines.

### Evaluated Areas

The work examined issues involving:

- HTML structure.
- Semantic elements.
- Accessibility errors.
- Markup validation.
- Web navigation.
- Interface usability.
- Compatibility considerations for users with disabilities.

### Results and Limitations

The report documents automated accessibility findings and adjustments.

A historical AChecker result classified the evaluated page at an AA level under the tested criteria.

This should not be interpreted as proof that the full application met WCAG AA requirements.

A complete accessibility assessment would require additional automated and manual testing across pages, interaction states, browsers, and assistive technologies.

---

## 12. Software Testing

The project included different forms of testing.

### 12.1 Functional Tests

Verification of page access and application navigation.

### 12.2 Database Connectivity

Testing communication between the PHP application and the MySQL database.

### 12.3 Mobile Device Tests

Historical demonstrations on iOS and Android devices.

### 12.4 Accessibility Tests

Automated inspection using accessibility tools.

### 12.5 Java / JUnit Experiment

The report also documents an exploratory Java test using JUnit.

This should be treated as testing coursework evidence rather than proof that the PHP application had a complete Java-based automated test suite.

### 12.6 Jenkins Experiments

Jenkins installation and SCM configuration were investigated.

### Testing Limitations

The historical report does not establish:

- Complete automated end-to-end testing.
- Quantified test coverage.
- Comprehensive security testing.
- Load testing.
- Reproducible CI test results for the current branch.

---

## 13. Google Analytics Integration

The application used Google Analytics to explore website traffic and audience characteristics.

The report includes evidence of:

- Analytics account configuration.
- Real-time access monitoring.
- Device-related information.
- Geographic access information.

This functionality supported the project's goal of understanding digital customer interactions.

### Privacy Considerations

Modern deployment should review analytics consent, transparency, data retention, and applicable privacy requirements before activating tracking.

Historical analytics screenshots must not be treated as current traffic or business-performance evidence.

---

## 14. Evolution Across UNIVESP Integrative Projects

Paió Brechó was not developed from scratch exclusively during PI3.

The project evolved through three academic stages.

### PI1 — Initial Web Project

The original work established an initial web-based application concept and implementation.

**Original contributors:**

- Cristiano Manoel dos Santos
- Débora Cristina Gonçalves dos Santos
- Eduardo Fernandes Bueno
- Raquel Virgínia Papini de Lucena Oliveira

### PI2 — Web Application Extension

The second stage continued the development of the Paió project, extending its web functionality and database-related experimentation.

**Contributors documented for PI2:**

- Eduardo Fernandes Bueno
- Luis Fellipe Grignoli da Silva
- Raquel Virgínia Papini de Lucena Oliveira
- Renan Aureliano Ferraz
- Paulo Sérgio da Silva

### PI3 — Mobile Web, Cloud Integration, and Testing

The third stage focused on mobile application requirements, cloud hosting, accessibility, version control, continuous integration, testing, and customer analytics.

The PI3 stage was documented in the 2024 final technical-scientific report.

### Academic Continuity

The evolution across PI1, PI2, and PI3 demonstrates iterative software development and reuse of prior project work.

Contributions from earlier academic teams must remain appropriately attributed.

---

## 15. Repository Structure

The public repository contains historical files and multiple development experiments.

Representative structure:

```text
.
├── .github/
├── .gradle/
├── .idea/
├── .vscode/
├── assets/
├── css/
├── img/
├── lib/
├── myApp/
├── paio-banco-de-dados/
├── projeto-api/
├── template/
├── web/
├── index.html
├── produtos.html
├── quero_vender.html
├── sobre.html
├── formulario.html
├── formulario.php
├── formulario_mysql.php
├── processa_formulario.php
├── config.php
├── cadastro_de_clientes.sql
├── SQLQuery_1.sql
├── SQLQuery_2.sql
├── script.js
├── service-worker.js
├── manifest.json
├── build.gradle
├── requirements.txt
└── README.md
```

This is a historical repository and includes materials from different academic and experimental stages.

It is not presented as a cleaned, standardized production monorepo.

### Additional Files

The repository also contains development configuration, legacy documents, media, experimental artifacts, and generated files.

A future engineering review should distinguish:

- Main application source code.
- Experimental prototypes.
- Academic documentation.
- Build artifacts.
- Local IDE configuration.
- Database configuration.
- Sensitive files.
- Generated outputs.

No destructive cleanup should be performed without preserving the historical repository.

---

## 16. Local Development

### Prerequisites

For the original web application, relevant tools may include:

- Git.
- A modern web browser.
- A local HTTP server for static content.
- PHP runtime for server-side components.
- MySQL for database-backed functionality.

Cloud-specific development additionally requires appropriately authorized Microsoft Azure resources.

### Clone the Repository

```bash
git clone https://github.com/eduardofernandesbueno/Projeto-Integrador-3-Univesp.git
cd Projeto-Integrador-3-Univesp
```

After a repository rename, update the clone URL and local directory name.

### Inspect the Project

```bash
git status
```

Review the README, frontend files, PHP scripts, database SQL files, and PWA configuration.

### Static Frontend Preview

For a frontend-only local inspection, a simple development server can serve static assets:

```bash
python3 -m http.server 8080
```

Then visit:

```text
http://localhost:8080/
```

This preview does not execute PHP or establish MySQL connectivity.

### PHP Development

PHP components require a compatible PHP runtime and appropriate database configuration.

Do not execute historical database scripts against a production database.

Do not reuse credentials found in legacy configuration files.

### Reproducibility Notice

The current branch has not been independently validated for complete local execution.

The historical Azure resources, database, or other dependencies may no longer be available.

---

## 17. Security and Data Governance

This project involved customer data collection and cloud database integration.

Before public promotion or reuse, the repository requires a security review.

### Priority Review Areas

- Database credentials in PHP files.
- Hardcoded connection strings.
- Azure configuration files.
- Certificates and private keys.
- Authentication and session handling.
- Customer-related data.
- SQL injection prevention.
- Form validation.
- Publicly accessible administrative pages.
- Git history and committed secrets.

### Important Repository Files to Audit

```text
config.php
formulario.php
formulario-ssl.php
formulario_mysql.php
processa_formulario.php
DigiCertGlobalRootCA.crt.pem
```

The presence of these files does not prove that credentials are exposed. They are identified as files requiring inspection because they are associated with database configuration or transport security.

### LGPD Considerations

The original academic project was developed in Brazil and involved customer registration.

Any current deployment must evaluate applicable LGPD requirements, including lawful processing, appropriate data minimization, security measures, transparency, and retention controls.

The original academic prototype should not be represented as independently certified for LGPD compliance.

---

## 18. Results and Engineering Experience

The original report documents a functional academic application and practical experiments involving:

- Web and mobile access.
- PWA installation.
- Product and customer-facing pages.
- PHP form processing.
- MySQL persistence.
- Azure cloud deployment.
- GitHub integration.
- Accessibility testing.
- Jenkins experimentation.
- Google Analytics integration.

The academic project therefore provides evidence of early experience in several software engineering disciplines.

### Frontend Engineering

Responsive interface implementation using HTML, CSS, JavaScript, and PWA components.

### Backend Engineering

Server-side PHP development and database interactions.

### Database Engineering

Relational database configuration, SQL queries, and MySQL connectivity.

### Cloud Engineering

Historical deployment and configuration using Microsoft Azure.

### DevOps

Version control, deployment integration, and CI experimentation.

### Software Quality

Functional testing, accessibility inspection, and user feedback.

### Analytics

Basic website traffic and audience analysis using Google Analytics.

---

## 19. Limitations

### Software Architecture

The project combined multiple experimental approaches and did not follow a fully standardized production architecture.

### Cloud Availability

Historical Azure resources may have expired or been deactivated.

### Security

The repository requires a source-code and historical-secret audit before further public deployment.

### Data Protection

The academic project does not demonstrate independently certified privacy or regulatory compliance.

### CI/CD

The report demonstrates configuration and testing activities, not a presently validated automated delivery pipeline.

### Accessibility

Automated accessibility checks do not establish complete conformance.

### Business Outcomes

No independently validated increase in sales, customer retention, conversion, or operational efficiency is claimed.

---

## 20. Future Engineering Improvements

The following improvements are proposed rather than completed:

- Audit and rotate any exposed credentials.
- Remove secrets from active configuration.
- Review historical Git commits for sensitive material.
- Introduce environment-based configuration.
- Improve PHP input validation.
- Implement parameterized SQL queries wherever missing.
- Review authentication and administrative authorization.
- Refactor duplicated frontend and backend code.
- Improve project organization.
- Establish a reproducible local development environment.
- Add automated frontend and backend tests.
- Verify PWA installability and offline behavior.
- Revalidate accessibility using current standards.
- Document a reproducible CI workflow.
- Modernize dependencies where necessary.
- Deploy a demonstration using synthetic customer data.
- Preserve historical academic evidence.

A future public demonstration should avoid depending on live customer records or abandoned cloud credentials.

---

## 21. Academic Context and Contributors

**Original title:**

*Aplicativo Móvel Paió: Brechó Sustentável*

**English translation:**

*Paió Sustainable Thrift Store — Mobile Application*

**Institution:** Virtual University of the State of São Paulo (UNIVESP)  
**Academic Programs:** Information Technology, Data Science, and Computer Engineering  
**Year:** 2024  
**Academic Format:** Integrative Project III — Technical and Scientific Report

### PI3 Team

The final academic report identifies:

- Eduardo Fernandes Bueno
- Guilherme da Silva Wanderley
- José Edinaldo da Silva Júnior
- Paulo Sérgio da Silva
- Raquel Virgínia Papini de Lucena Oliveira
- Renan Aureliano Ferraz
- Robson Aparecido Soares

**Academic Tutor:** Prof. Dr. Miriam Batista dos Santos

### Attribution

The project was developed collaboratively.

The GitHub repository is maintained by Eduardo Fernandes Bueno, but repository ownership should not be interpreted as sole authorship.

The earlier PI1 and PI2 teams are acknowledged separately because their contributions supported the project's evolution.

---

## 22. Professional Context — Eduardo Fernandes Bueno

Eduardo Fernandes Bueno is a Data Engineer, Data Scientist, and M.Sc. candidate in Computer Science at the State University of Londrina (UEL), Brazil.

He contributes to Research & Development activities at the university's Information Technology Office (**ATI/UEL**).

His broader academic and engineering interests include:

- Data Engineering.
- Data Architecture.
- Software Engineering.
- Full-Stack Development.
- Cloud Computing.
- Data Integration.
- Machine Learning.
- Data Governance.
- Scientific Research.
- Responsible AI.
- Privacy and Regulatory Compliance.

His academic background includes degrees in Information Technology, Data Science, and Law.

### Institutional Clarification

This repository documents a collaborative UNIVESP undergraduate project completed in 2024.

Eduardo's subsequent ATI/UEL affiliation is professional context only.

The Paió project was not an official ATI/UEL or UNIDATA software deliverable, and no such endorsement is claimed.

---

## 23. Academic Reference

BUENO, Eduardo Fernandes; WANDERLEY, Guilherme da Silva; SILVA JÚNIOR, José Edinaldo da; SILVA, Paulo Sérgio da; OLIVEIRA, Raquel Virgínia Papini de Lucena; FERRAZ, Renan Aureliano; SOARES, Robson Aparecido. *Aplicativo Móvel Paió: Brechó Sustentável*. Technical and Scientific Report, Integrative Project III, Virtual University of the State of São Paulo (UNIVESP), 2024.

**Academic Tutor:** Prof. Dr. Miriam Batista dos Santos.

**Presentation video:**

https://youtu.be/LHl9hPPkEwA

This is an undergraduate academic project report, not a peer-reviewed journal or conference publication.

---

## 24. Licensing and Responsible Reuse

The public availability of source code does not automatically grant unrestricted rights to all content, academic materials, photographs, business information, customer records, and third-party assets.

Any licensing changes should respect the rights of contributors and external stakeholders.

Do not reuse real customer data or database credentials in public demonstrations.

---

## 25. Professional and Academic Links

**Eduardo Fernandes Bueno**

- **GitHub:** https://github.com/eduardofernandesbueno
- **Professional Portfolio:** https://eduardofernandesbueno.github.io/
- **LinkedIn:** https://www.linkedin.com/in/eduardofernandesbueno/
- **ORCID:** https://orcid.org/0009-0000-8620-0211
- **Curriculum Lattes:** http://lattes.cnpq.br/8716619580595259

---

## 26. Project Summary

The Paió Brechó application documents a collaborative academic experience integrating frontend, backend, relational databases, cloud infrastructure, testing, automation, and digital analytics.

Its engineering value includes:

**Frontend:** HTML5, CSS3, JavaScript, responsive web development, and PWA components.

**Backend:** PHP server-side processing and application-to-database integration.

**Databases:** MySQL, SQL, Azure Database for MySQL, and database administration tools.

**Cloud:** Microsoft Azure and historical application deployment.

**DevOps:** Git, GitHub, GitHub Actions, Jenkins, and experimental CI/CD configuration.

**Quality:** Accessibility checks, markup validation, functional testing, and mobile-device testing.

**Analytics:** Google Analytics audience measurement.

**Software Engineering:** Requirements gathering, Design Thinking, iterative development, MVP implementation, integration, and technical documentation.

The project represents an important early stage in the development of full-stack software engineering and cloud integration skills.

Its historical value lies in the integration of multiple software components to address a real small-business problem, while preserving transparent documentation of implementation maturity and limitations.

---

**UNIVESP — Integrative Project III, 2024**

*Full-Stack Development · Mobile Web · PWA · PHP · MySQL · Azure · CI/CD · Analytics*

**Academic project maintained by Eduardo Fernandes Bueno — currently R&D at ATI/UEL, Brazil.**
