# Peter Kneale

**Software Engineer and Solution Architect** based in Sydney, Australia.

> Australian software engineer with more than 30 years of experience building reliable, production grade systems. My focus is using software as a force multiplier: codifying the expertise of global authorities into tools that clinicians can use, so children with genetic disorders get faster and more accurate diagnoses.

- **Location:** Sydney, Australia
- **Website:** [peterkneale.com](https://peterkneale.com)
- **GitHub:** [github.com/PeterKneale](https://github.com/PeterKneale)
- **LinkedIn:** [linkedin.com/in/knealepeter](https://www.linkedin.com/in/knealepeter)
- **Email:** peterkneale@gmail.com

<!-- Phone number intentionally omitted from the public source. Add it here if you want it on the site. -->

---

## Summary

Software engineer with more than 30 years of industry experience, including close to 15 years running an independent software consultancy alongside his employed roles, delivering robust and innovative technology solutions across legal, finance, insurance, aerial imagery and medical research.

I have a strong track record conceptualising and building large scale, commercially viable Software as a Service (SaaS) platforms, with deep expertise in cloud computing, microservices architecture and modern development practices. A recurring theme of my work is modernising ageing legacy architectures into performant, reliable and cost effective systems, and providing the technical leadership and mentoring to help teams get there.

Today I apply that engineering craft in genomics and clinical diagnostics, building the software platform, clinical decision support tooling and cloud infrastructure that turn cutting edge research into tools clinicians can trust.

---

## Work Experience

### Software Engineer, Children's Medical Research Institute and Sydney Children's Hospitals Network
**Feb 2023 - Present, Sydney (Hybrid)**

Building the software platform, clinical decision support tooling and cloud infrastructure that supports a connected genomics research and diagnostics ecosystem, helping turn cutting edge research into tools clinicians can trust.

**Main projects**

- **GENEie** ([geneie.frontiergenomics.com.au](https://geneie.frontiergenomics.com.au/)) - the first evidence based clinical decision support software for accurate, confident clinical interpretation of extended splice site variants, producing ACMG aligned evidence for genetic pathology professionals.
- **RNA Cloud** - a cloud based platform for clinical RNA sequencing analysis, covering orchestration, alignment, quality control and custom genome reference builds.

Supporting work:

- Lead engineer on data engineering pipelines that assemble curated, clinically relevant reference datasets from public sources such as Genomics England PanelApp, ClinVar and the Genome Reference Consortium.
- Built and containerised HTTP APIs and services that wrap scientific tooling (for example SpliceAI scoring and pedigree plotting) so research methods can be consumed reliably as production services.
- Works across Python, C#, R, Docker and modern DevOps tooling, providing the productionisation layer around science produced by research scientists.

### Owner, Simplicate Technology
**May 2008 - Feb 2023, Sydney**

Founded and ran an independent software consultancy providing hosted web applications and technical consulting services, operating alongside employed roles for close to 15 years.

- Advised clients on software architecture and cloud computing strategy.
- Introduced CI/CD pipelines and infrastructure as code to speed up and de risk delivery.
- Helped teams adopt higher quality software practices including automated testing, code review and modern development workflows.
- Provided technical leadership and mentoring.
- Built and hosted proof of concept web products as side projects.

### Software Architect, BizCover
**Dec 2018 - Feb 2023, Sydney (Hybrid)**

At one of Australia's premier online insurance providers, was chief architect of a platform that delivers insurance products priced by intricate rating algorithms.

- Designed rating algorithms involving dozens of parameters that return indicative pricing to customers within milliseconds.
- Architected the microservice platform that replaced BizCover's ageing legacy monolith.
- Shaped the overarching quality strategy, applying unit, integration, acceptance, functional and end to end testing to uphold high software quality.

### Software Engineer, CommSec
**Jan 2018 - Dec 2018, Sydney**

At the leading online stockbroking firm in Australia, an affiliate of the Commonwealth Bank, delivered enhancements to the trading platform.

- Implemented the Standard Portfolio Analysis of Risk (SPAN), which calculates the maximum potential loss for a portfolio of derivatives by product, reducing the bank's exposure to volatile markets and strengthening its financial resilience.

### Senior Software Engineer, Nearmap
**Oct 2014 - Nov 2017, Sydney**

- Contributed significantly to a large scale, cloud hosted solution using a wide range of AWS services.
- Introduced and expanded a modern C# .NET microservices architecture, phasing out a legacy monolith that was hampering the company's efforts to innovate and launch internationally.
- Designed and implemented a real time data collection workflow.
- Gained significant experience running C# on Linux via Mono.

### Technical Lead, Within Reach Software
**Aug 2013 - Sep 2014, North Sydney**

- Delivered projects across the superannuation and startup sectors.
- Provided solutions and technical advice to enterprise customers such as Gadens Lawyers and to startups such as Geepers.

### Tech Lead, Community Engine
**Mar 2011 - Dec 2012, Sydney**

- Led development of a social ecommerce platform.
- Built primarily with ASP.NET MVC 3 and 4, C#, MongoDB and jQuery.
- Used AppHarbor, TeamCity, AWS (EC2, S3, SQS, Route 53), Git and GitHub, with continuous integration enabling reliable automated fortnightly deployments.
- Coordinated delivery using Scrum and Kanban.

### Senior Developer, Blake Dawson
**Jan 2005 - Jan 2012, Sydney**

Worked on three tier web based solutions as a Senior Developer and Analyst Programmer at the law firm (now Ashurst).

- **SALT (Self Administered Legal Training):** helped design and implement a multi tenant SaaS application used by many blue chip companies, one of the first major implementations of ASP.NET 1.1 in Australia.
- **Matter Opening Automation:** integrated line of business systems to improve business workflows, using BizTalk 2004, InfoPath 2007 and SharePoint 2007.
- **Intranet:** implemented internal applications on SharePoint 2010.
- Worked across the Microsoft .NET Framework and related technologies including Reporting Services, SharePoint, BizTalk, InfoPath, Enterprise Library, AJAX, nHibernate, MVC, WCF and LINQ.

### Analyst Programmer, AMP (IT@AMP)
**2000 - 2003, Sydney**

- Worked on the high profile amp.com.au site within AMP's eBusiness team.

---

## Open Source and Current Work

Active on GitHub since 2011 with a large public portfolio spanning production ready starter architectures and command line tooling.

- **bioassert** (Rust) - flagship project. A bioinformatics assertion command line tool that validates pipeline outputs (BAM, VCF, FASTA, CSV, TSV, PSV and plain files) using a simple declarative syntax, then gates a workflow on the result via its exit code. First class Nextflow integration. Distributed on crates.io, a Homebrew tap, prebuilt binaries and Docker images on GHCR, and shipped as a Claude Code skill and plugin.
- **Genomics engineering at CMRI** - lead or co engineer on public tools including a clinically relevant genes data pipeline, a SpliceAI scoring API, a pedigree plotting API and an OUTRIDER expression outlier wrapper, across the Kids Neuroscience Centre, Frontier Genomics and RNA Cloud organisations.
- **Architecture reference projects** - a widely referenced set of .NET starter solutions demonstrating modular monoliths, microservices, domain driven design and multi tenancy.

---

## Selected Projects

A selection from [github.com/PeterKneale](https://github.com/PeterKneale). Star counts shown where notable.

**Bioinformatics and tooling**

| Project | Tech | What it is |
|---------|------|------------|
| **bioassert** | Rust | Bioinformatics assertion CLI for validating and gating pipeline outputs, with first class Nextflow integration |
| **nf-command-archiver** | Groovy | Nextflow tooling for archiving the commands run by pipeline tasks |
| **bioinformatics_knowledge_base** | Python | A curated knowledge base of bioinformatics notes and references |

**SaaS and multi tenancy**

| Project | Tech | What it is |
|---------|------|------------|
| **modular_monolith_saas** | C#, Postgres, HTMX | Modular monolith SaaS starter solution for medium to large products |
| **micro-saas** | C#, Postgres | Multi tenant modular monolith with DDD and tenant isolation via Postgres row level security |
| **HybridMicroOrm** | C# | A lightweight, JSON based micro ORM for PostgreSQL with built in multi tenant support |
| **multi-tenant-dapper-postgres-row-level-security** | C#, Dapper | Multi tenant data access using Dapper and Postgres row level security |
| **multi-tenant-grpc-postgres-row-level-security** | C#, gRPC | Multi tenant application using gRPC, Dapper and Postgres row level security |

**Microservices and cloud**

| Project | Tech | What it is |
|---------|------|------------|
| **k8s-dotnet-microservices-monorepo-saas** | C#, Kubernetes | .NET microservices in a monorepo, deployed to Kubernetes with GitHub Actions |
| **serverless-dotnet-microservices-monorepo-saas** | C#, AWS | Serverless .NET microservices in a monorepo SaaS |
| **microservices.chassis** | C# | A microservices chassis example providing reusable service scaffolding |
| **transactional_outbox** | C# | A demonstration of the transactional outbox pattern |
| **aws_lightsail_github_actions** | C#, AWS | Deploying a .NET application to AWS Lightsail with GitHub Actions |

**Patterns and domain driven design**

| Project | Tech | What it is |
|---------|------|------------|
| **ddd_ef_core_and_postgres** | C# | Domain driven design with EF Core and Postgres |
| **design_patterns** | C# | A collection of design pattern examples |
| **Envoy** | C# | A mediator pattern implementation |
| **Discounts** | C# | A microservice demonstrating how to handle discounts |

---

## Skills

**Languages:** C# and .NET (primary, 20+ years), Python, Rust, R, SQL, JavaScript, Groovy

**Cloud and DevOps:** AWS (Lambda, SNS, SQS, CloudFormation, EC2, S3, Route 53), Infrastructure as Code, Docker, Kubernetes, GitHub Actions, CI/CD pipelines, Terraform

**Architecture:** Modular monolith, microservices, domain driven design, CQRS, event sourcing, transactional outbox, clean architecture, multi tenant SaaS, subscription billing, serverless

**Data:** PostgreSQL, SQL Server, MongoDB, Entity Framework Core, Dapper, Marten, database design and migrations, isolation levels and performance tuning

**Web:** ASP.NET Core, minimal APIs, Razor Pages, HTMX, Web API, gRPC, YARP, jQuery, Vue

**Testing and quality:** Full SDLC, TDD, unit, integration, acceptance, functional and end to end testing, xUnit, NUnit, Moq, SpecFlow, Selenium

**Practices:** Agile, Scrum, Kanban, secure coding, data privacy and compliance, technical leadership, mentoring, solution architecture, consulting

**Bioinformatics:** Nextflow and nf-core, RNA sequencing pipelines, splice variant analysis, SpliceAI, VCF, BAM and FASTA tooling

---

## Education

**Bachelor of Science (Computing)**, University of Western Sydney, 2000
