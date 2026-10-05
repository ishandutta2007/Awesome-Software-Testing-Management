# Awesome-Software-Testing-Management

# Top Software Testing Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Test Case Organization, Execution Tracking & QA Reporting*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Software Testing Management**. These tools help QA teams organize test cases, plan test runs, track execution results, and generate reports — replacing spreadsheets with structured, traceable test management workflows.

**Examples** include Azure Test Plans, TestRail, Zephyr, Xray, PractiTest, qTest, Qase, SpiraTest, Testmo, and Kualitee (the category leaders).

**Open-source emphasis**: Test management is a strong open-source domain. **Kiwi TCMS** leads with over 2 million Docker Hub pulls and adoption by Argentina's university system . **TestLink** remains a veteran choice with decades of deployment experience . Newer projects like **UnitTCMS**, **QA Studio**, and **TestHub** bring modern UX and API-first design to self-hosted test management. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Azure Test Plans](https://azure.microsoft.com/en-us/products/devops/test-plans/)**  
  Microsoft's test management solution integrated with Azure DevOps. Test plans, suites, and cases with traceability to work items, plus manual and automated test execution. **Best for organizations already using Azure DevOps** for development and CI/CD.

- **[TestRail](https://www.testrail.com/)**  
  One of the most widely adopted test management platforms with test case organization, execution tracking, and extensive integrations with Jira, CI/CD tools, and automation frameworks. **The industry standard for manual test management** at mid-to-large organizations.

- **[Zephyr](https://www.zephyr.com/)**  
  Test management for Jira with multiple editions (Scale, Squad, Enterprise). **The most popular Jira-native test management solution** — test cases, cycles, and reporting directly within the Atlassian ecosystem.

- **[Xray](https://www.getxray.app/)**  
  Jira-native test management with strong support for manual, automated, and exploratory testing. **The most complete Jira test management solution** — deep traceability from requirements through execution.

- **[PractiTest](https://www.practitest.com/)**  
  Cloud-based test management with AI-powered insights, customizable reports, and end-to-end traceability. **Strong for mid-to-large enterprises** in Agile, DevOps, or hybrid environments .

- **[qTest](https://www.tricentis.com/products/qtest-test-management/)**  
  Tricentis's test management platform with test case organization, execution, and integration into the Tricentis automation ecosystem.

- **[Qase](https://qase.io/)**  
  Modern test management with a clean interface, API-first design, and integrations with popular CI/CD and issue tracking tools. **Best for teams wanting a modern alternative to legacy test managers**.

- **[SpiraTest](https://www.inflectra.com/SpiraTest/)**  
  Inflectra's test management with requirements traceability, test case management, and defect tracking. **Strong for regulated industries** needing audit trails.

- **[Testmo](https://www.testmo.com/)**  
  Unified test management for manual and automated testing with a focus on developer experience and CI/CD integration.

- **[Kualitee](https://kualitee.com/)**  
  Test management with AI-powered features, Jira integration, and support for manual and automated testing workflows.

## Open-Source GitHub Projects

- **[Kiwi TCMS](https://github.com/kiwitcms/Kiwi)**  
  **The leading open-source test management system**, GPL-2.0 licensed with 1,250+ GitHub stars and **over 2 million Docker Hub pulls** . IEEE 829 compatible, designed for both manual and automated testing with **bug tracker integration, search pages, powerful access control, test automation framework plugins, visual reports, and a rich API layer** . **Adopted by Argentina's University Information System (SIU)** to centralize test cases, plans, and executions across projects . Docker deployment with `docker exec -it kiwi_web /Kiwi/manage.py initial_setup` for first-time configuration . Version-tagged container images available to subscribers . **The de facto open-source TestRail alternative** — mature, actively maintained, and production-proven at organizational scale.

- **[TestLink](https://github.com/TestLinkOpenSourceTRMS/testlink-code)**  
  **The veteran open-source test management system**, used since 2003 and deployed in teams of 20+ engineers managing 1,000+ test cases . **Web-based with requirements tracking, test plans, builds, milestones, and user role management** . Integrates with Bugzilla, Jira, Mantis, and other defect trackers. **Test case organization in hierarchical suites with keyword support, testing prioritization, and reporting** . Supports OAuth and LDAP authentication since 1.9.16 . **Note**: UI is dated compared to modern alternatives, and setup requires technical expertise . **Best for smaller teams with technical resources and limited budgets** .

- **[UnitTCMS](https://github.com/kimatata/unittcms)**  
  **Modern, self-hosted test case management system** designed for environments with strict security requirements . **Project-based organization with dashboard views, folder hierarchies, and test run management** . Supports three roles: Manager, Developer, and Reporter. **Docker Compose deployment** with `docker-compose up --build` . **The best choice for teams wanting a modern UI with self-hosted security** — built because proprietary tools are cloud-only and open-source tools often have outdated interfaces .

- **[QA Studio](https://github.com/QAStudio-Dev/studio)**  
  **Modern test management platform built by QA engineers, for QA engineers**, with a focus on speed and API-first design . **SvelteKit 5 frontend, PostgreSQL database, comprehensive REST API, hierarchical test suites, and rich media attachments** (screenshots, videos, logs) . Self-hosted with bcrypt authentication and session management. **Note**: requires Vercel Blob storage for attachments (or a custom adapter for S3/MinIO/local filesystem) . **Best for teams wanting a fast, modern, self-hosted alternative with full API access**.

- **[TestHub](https://www.npmjs.com/package/testhub-app)**  
  **Local-first test management tool** — lightweight alternative to cloud platforms . **Zero configuration**: `npx testhub-app` starts everything; data stored in `~/.testhub/` SQLite database . **Full REST API** for projects, test cases, plans, and execution, with an **AI-agent-friendly skill.md guide and OpenAPI spec** . Web UI for organizing test cases in directories with tags and executing test plans . **Best for individual developers and small teams** wanting frictionless local test management with AI agent integration.

- **[QuAck](https://github.com/sillstest/dokimion)**  
  **Open-source test management service** with a unique feature: **test case trees are built dynamically from test case attributes** — no fixed hierarchy required . **Pluggable architecture** for custom authentication providers and integrations with tracking and test execution systems . Docker deployment with `docker-compose up` . **Best for teams wanting flexible test case organization** without rigid tree structures.

- **[Tuleap](https://www.tuleap.org/)**  
  **Open-source project and application lifecycle management platform** that includes **test management integrated with requirements traceability, issue tracking, and software delivery** . **Self-hosted deployment** for control over data and infrastructure. **Configurable trackers and workflows** allow defining fields, statuses, permissions, and approval steps . **Best for regulated engineering groups** where requirements, development, and test results must remain connected .

- **[Gwirian](https://github.com/TheAcmada/gwirian)**  
  **Modern test scenario management platform** with a **BDD approach** for QA engineers and managers . **Rails 8, SQLite, Tailwind, htmx** stack with **magic link authentication** (passwordless) . **MCP integration** for AI assistant access, workspace-scoped API tokens, and Elasticsearch full-text search . Docker Compose for Elasticsearch and Mailhog . **Best for BDD-focused teams** wanting modern architecture and AI integration.

- **[BASIL](https://github.com/kartben/BASIL)**  
  **Software quality management tool** focused on **traceability between software component specifications, work items, and source code** . **Web UI and REST API** for integration into automated workflows . **Own test infrastructure** using `tmt` metadata files to run test cases against containers, VMs, or physical hardware . **Traces tests from external infrastructures** including GitLab CI, GitHub Actions, KernelCI, and Testing Farm . **Exports DESIGN SBOM** based on SPDX Model 3 . **Best for teams needing rigorous traceability and specification coverage analysis**.

### Additional Strong Open-Source Options

- **Nitrate** — Red Hat's original test case management system (now forked as Kiwi TCMS), Python/Django based with XML-RPC API .
- **Leantime** — Open-source project management with test management capabilities, self-hosted, visual planning focus .
- **noob-test-manager** — CLI-launched local test manager with AI workspace, Git repo integration, and TestMu import support .
- **Test Lah!** — Client-side QA management with interactive mindmaps and AI-powered test generation .

**Frameworks for building custom test management solutions**: Combine **Kiwi TCMS** for a production-proven, mature foundation with Docker deployment and IEEE 829 compatibility . Use **UnitTCMS** for a modern self-hosted UI with project-based organization and strict security requirements . Choose **TestHub** for local-first simplicity with AI agent integration via REST API and skill.md . Deploy **QA Studio** for a SvelteKit-based modern platform with rich media attachments and full API access . Note that true enterprise test management with AI-powered insights, audit-ready compliance, and deep Jira/Azure DevOps integration remains primarily commercial territory; open-source stacks provide strong test case organization, execution tracking, and API foundations that require integration for complete QA workflows.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Test management tools handle sensitive QA data and potentially bug details. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **Open-source test managers vary significantly in UI modernity and feature depth** — Kiwi TCMS and TestLink are mature but may have dated interfaces, while UnitTCMS, QA Studio, and TestHub prioritize modern UX .
- **Kiwi TCMS enterprise features require subscription** — version-tagged container images are available only to subscribers .
- The open-source ecosystem provides strong test organization, execution tracking, and API foundations, but **AI-powered insights, audit-ready compliance, and deep commercial tool integration** remain primarily commercial offerings.

---

**Made for QA engineers, test managers, and development teams.**
Let's make software testing management more open, transparent, and effective.
