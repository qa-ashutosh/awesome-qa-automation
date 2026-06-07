# Awesome QA Automation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools, frameworks, and resources for QA engineers and test automation professionals.

---

## Contents

- [🌐 UI Test Automation](#-ui-test-automation)
- [🔌 API Testing](#-api-testing)
- [📱 Mobile Testing](#-mobile-testing)
- [⚡ Performance Testing](#-performance-testing)
- [🔒 Security Testing](#-security-testing)
- [♿ Accessibility Testing](#-accessibility-testing)
- [🧪 Unit and Integration Testing](#-unit-and-integration-testing)
- [👁 Visual Regression Testing](#-visual-regression-testing)
- [📋 Test Management and Reporting](#-test-management-and-reporting)
- [🔧 CI/CD and Test Infrastructure](#-cicd-and-test-infrastructure)
- [🤖 AI-Assisted Testing](#-ai-assisted-testing)
- [💥 Contract and Chaos Testing](#-contract-and-chaos-testing)
- [📚 Learning Resources](#-learning-resources)
- [💀 Hall of QA Failures](#-hall-of-qa-failures)

---

## 🌐 UI Test Automation

### Multi-Browser Frameworks

- [Playwright](https://github.com/microsoft/playwright) - Cross-browser automation for Chromium, Firefox, and WebKit with auto-waiting and parallel execution.
- [Cypress](https://github.com/cypress-io/cypress) - Browser-based end-to-end testing framework with real-time reloading and time-travel debugging, primarily Chrome-first with experimental WebKit support.
- [Selenium](https://github.com/SeleniumHQ/selenium) - Browser automation framework supporting multiple languages and all major browsers.
- [WebdriverIO](https://github.com/webdriverio/webdriverio) - Node.js automation framework supporting WebDriver, Chrome DevTools, and WebDriver BiDi protocols.
- [Nightwatch.js](https://github.com/nightwatchjs/nightwatch) - W3C WebDriver-based testing framework for Node.js with built-in test runner and assertions.
- [Puppeteer](https://github.com/puppeteer/puppeteer) - Node.js library for controlling Chrome and Firefox via DevTools Protocol and WebDriver BiDi.
- [TestCafe](https://github.com/DevExpress/testcafe) - Node.js end-to-end testing framework with cross-browser support that requires no browser drivers or plugins.

### BDD and Keyword-Driven

- [Cucumber.js](https://github.com/cucumber/cucumber-js) - BDD framework that runs Gherkin feature files in Node.js, connecting plain-language specs to step definitions.
- [Robot Framework](https://github.com/robotframework/robotframework) - Keyword-driven acceptance testing framework with human-readable syntax and extensive library support.
- [CodeceptJS](https://github.com/codeceptjs/CodeceptJS) - End-to-end testing framework with a human-friendly API built on top of Playwright and WebdriverIO.

### Low-Code and All-in-One

- [Katalon Studio](https://katalon.com) - Low-code automation platform for web, mobile, and API testing with built-in IDE and CI/CD integrations.

---

## 🔌 API Testing

### Clients and GUI Tools

- [Postman](https://github.com/postmanlabs/postman-app-support) - API platform for building, testing, and documenting APIs with support for REST, GraphQL, and SOAP.
- [Bruno](https://github.com/usebruno/bruno) - Git-native, offline-first API client that stores collections as plain-text files directly in your repository.
- [Hoppscotch](https://github.com/hoppscotch/hoppscotch) - Lightweight, web-based API development suite supporting REST, GraphQL, WebSocket, and MQTT protocols.
- [Insomnia](https://github.com/Kong/insomnia) - Open-source API client for REST, GraphQL, gRPC, and SOAP with environment management and test scripting.

### CLI and Automation

- [Newman](https://github.com/postmanlabs/newman) - Command-line collection runner for Postman that integrates with CI/CD pipelines.
- [Hurl](https://github.com/Orange-OpenSource/hurl) - Command-line tool for running HTTP requests defined in plain text files, with built-in assertions.

### Code-Based Frameworks

- [REST Assured](https://github.com/rest-assured/rest-assured) - Java DSL for writing readable and maintainable tests for REST APIs with BDD-style syntax.
- [Karate DSL](https://github.com/karatelabs/karate) - Unified framework combining API testing, mocking, performance testing, and UI automation in a single BDD syntax.
- [Supertest](https://github.com/ladjs/supertest) - Node.js library for testing HTTP servers using a fluent API, built on top of SuperAgent.

### Mock Servers

- [WireMock](https://github.com/wiremock/wiremock) - Flexible API mocking tool for stubbing and proxying HTTP services in test environments.
- [MockServer](https://github.com/mock-server/mockserver) - Tool for mocking HTTP and HTTPS systems via expectations, proxying, and request verification.

---

## 📱 Mobile Testing

### Cross-Platform

- [Appium](https://github.com/appium/appium) - Cross-platform automation framework for native, hybrid, and mobile web apps on iOS, Android, and Windows using the W3C WebDriver protocol.
- [Maestro](https://github.com/mobile-dev-inc/maestro) - Simple and reliable mobile UI testing framework using YAML-based syntax with built-in handling for flaky UI elements.
- [Detox](https://github.com/wix/Detox) - Gray-box end-to-end testing framework for React Native apps on iOS and Android with automatic synchronization.

### Android

- [Espresso](https://developer.android.com/training/testing/espresso) - Google's official Android UI testing framework with fast, reliable test execution and tight integration with Android Studio.
- [UIAutomator2](https://github.com/appium/appium-uiautomator2-driver) - Appium driver leveraging Android's UIAutomator2 framework for black-box UI automation across apps and system dialogs.
- [Kaspresso](https://github.com/KasperskyLab/Kaspresso) - Android UI test framework built on top of Espresso and UIAutomator with DSL wrappers, interceptors, and Allure reporting support.

### iOS

- [XCUITest](https://developer.apple.com/documentation/xctest) - Apple's native UI testing framework bundled with Xcode for writing and running tests on iOS, iPadOS, and macOS.
- [EarlGrey 2](https://github.com/google/EarlGrey/tree/earlgrey2) - Google's iOS UI automation framework that combines white-box testing capabilities with XCUITest for reliable, synchronized test execution.

---

## ⚡ Performance Testing

### Load Testing Frameworks

- [k6](https://github.com/grafana/k6) - Developer-friendly load testing tool by Grafana Labs with JavaScript scripting, CI/CD integration, and real-time Grafana dashboards.
- [Apache JMeter](https://github.com/apache/jmeter) - Battle-tested Java-based load testing tool with a GUI test plan builder supporting HTTP, JDBC, FTP, SOAP, and more protocols.
- [Gatling](https://github.com/gatling/gatling) - Code-first load testing tool with a Scala/Java/Kotlin DSL, built for high-throughput simulations and CI/CD pipelines.
- [Locust](https://github.com/locustio/locust) - Python-based distributed load testing tool with a real-time web UI and native OpenTelemetry integration.

### Developer CLI Tools

- [Artillery](https://github.com/artilleryio/artillery) - Modern load testing toolkit supporting HTTP, GraphQL, WebSocket, and gRPC with YAML-based scripts and Playwright browser integration.
- [Vegeta](https://github.com/tsenart/vegeta) - Go-based HTTP load testing tool designed for constant-rate request testing with composable pipelines and detailed latency histograms.
- [autocannon](https://github.com/mcollina/autocannon) - Fast HTTP/1.1 benchmarking tool written in Node.js with support for HTTP pipelining, HTTPS, and real-time latency histograms.

---

## 🔒 Security Testing

### DAST Scanners

- [OWASP ZAP](https://github.com/zaproxy/zaproxy) - Open-source DAST tool with automated scanning, intercepting proxy, fuzzer, and a YAML automation framework for CI/CD pipeline integration.
- [Burp Suite Community](https://portswigger.net/burp/communitydownload) - Industry-standard web security testing platform with an intercepting proxy, repeater, and manual penetration testing tools.

### Penetration Testing

- [Nikto](https://github.com/sullo/nikto) - Web server scanner that detects dangerous files, outdated software, and common misconfigurations across over 6,700 checks.
- [SQLMap](https://github.com/sqlmapproject/sqlmap) - Automated penetration testing tool that detects and exploits SQL injection vulnerabilities across all major database engines.

### SAST and Dependency Scanning

- [Semgrep](https://github.com/semgrep/semgrep) - Fast, lightweight static analysis tool supporting 30+ languages with customizable rules for catching security vulnerabilities early in CI/CD.
- [Trivy](https://github.com/aquasecurity/trivy) - Comprehensive vulnerability scanner for containers, filesystems, Git repositories, Kubernetes, and IaC configurations.
- [Snyk](https://snyk.io) - Developer security platform for scanning open-source dependencies, containers, and IaC for vulnerabilities with fix suggestions and CI/CD integration.

---

## ♿ Accessibility Testing

### Automated Testing Engines

- [axe-core](https://github.com/dequelabs/axe-core) - Accessibility testing engine by Deque that integrates with Selenium, Playwright, Cypress, and Jest to catch WCAG violations automatically.
- [Lighthouse](https://github.com/GoogleChrome/lighthouse) - Google's open-source tool for auditing web page accessibility, performance, SEO, and best practices with CI integration via Lighthouse CI.

### CLI Tools

- [Pa11y](https://github.com/pa11y/pa11y) - Node.js-based accessibility testing tool that runs WCAG audits via command line with support for axe and HTML CodeSniffer runners.
- [Pa11y CI](https://github.com/pa11y/pa11y-ci) - CI-centric accessibility test runner built on Pa11y for testing against lists of URLs or sitemaps in automated pipelines.

### Browser Extensions

- [WAVE](https://wave.webaim.org) - WebAIM's browser extension that visually annotates accessibility issues directly on the page for quick manual audits.
- [IBM Equal Access Toolkit](https://github.com/IBMa/equal-access) - IBM's open-source accessibility checker with browser extension and CI integration, powered by IBM's accessibility rule engine.
- [Accessibility Insights](https://github.com/microsoft/accessibility-insights-web) - Microsoft's browser extension for fast checks and guided WCAG 2.1 AA assessments with detailed step-by-step evaluation workflows.

---

## 🧪 Unit and Integration Testing

### JavaScript

- [Jest](https://github.com/jestjs/jest) - Zero-configuration JavaScript testing framework by Meta with built-in code coverage, snapshot testing, and parallel test execution.
- [Vitest](https://github.com/vitest-dev/vitest) - Vite-native testing framework with Jest-compatible API, instant watch mode, and native code coverage via v8 or Istanbul.
- [Mocha](https://github.com/mochajs/mocha) - Flexible JavaScript test framework running on Node.js with async support and compatibility with any assertion library.

### Python

- [Pytest](https://github.com/pytest-dev/pytest) - Full-featured Python testing framework with simple syntax, powerful fixtures, parameterized testing, and a vast plugin ecosystem.

### Java

- [JUnit 5](https://github.com/junit-team/junit5) - The standard unit testing framework for Java with parameterized tests, nested test classes, and a flexible extension model.
- [TestNG](https://github.com/testng-org/testng) - Java testing framework inspired by JUnit with support for data-driven testing, parallel execution, and flexible test configuration via XML.
- [Mockito](https://github.com/mockito/mockito) - Most popular Java mocking framework for creating and verifying test doubles with a clean, readable API.

### .NET

- [NUnit](https://github.com/nunit/nunit) - Mature, open-source unit testing framework for all .NET languages with rich assertion support and parallel test execution.
- [xUnit](https://github.com/xunit/xunit) - Community-focused unit testing framework for .NET emphasizing simplicity, extensibility, and clean test isolation.

### Integration Testing

- [Testcontainers](https://github.com/testcontainers/testcontainers-java) - Library for spinning up real Docker containers in tests for databases, browsers, and any other dependency, with official SDKs for Java, Node.js, Python, Go, .NET, and Rust.

---

## 👁 Visual Regression Testing

### Framework-Agnostic Tools

- [BackstopJS](https://github.com/garris/BackstopJS) - Purpose-built visual regression tool using headless Chrome to capture and compare screenshots across viewport sizes with an interactive before/after scrubber report.
- [reg-suit](https://github.com/reg-viz/reg-suit) - Flexible visual regression testing toolkit that handles comparison, baseline storage in S3 or GCS, and PR reporting independent of your screenshot tool.

### Framework-Native

- [Playwright Screenshots](https://playwright.dev/docs/screenshots) - Built-in screenshot and visual comparison API for Playwright with `toHaveScreenshot()` assertion and zero additional dependencies.
- [jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot) - Jest matcher for image comparisons using structural similarity, written by American Express with configurable diff thresholds.

### Platforms with Free Tier

- [Lost Pixel](https://github.com/lost-pixel/lost-pixel) - Open-source visual regression platform supporting Storybook, Ladle, Histoire, and full-page screenshots with a self-hostable option.
- [Argos](https://github.com/argos-ci/argos) - Open-source visual testing platform that integrates with CI pipelines and provides a collaborative UI review workflow for approving visual changes.
- [Percy](https://percy.io) - Cloud visual testing platform by BrowserStack with AI-powered diffing, cross-browser rendering, and a free tier of 5,000 screenshots per month.
- [Chromatic](https://www.chromatic.com) - Visual testing and review platform built by the Storybook team, turning every Storybook story into an automated visual test with a free tier for open source projects.

---

## 📋 Test Management and Reporting

### Test Management Platforms

- [Kiwi TCMS](https://github.com/kiwitcms/Kiwi) - Modern open-source test case management platform with a markdown editor, CI integration, JSON/XML-RPC API, and Docker-based deployment with over 2 million pulls.
- [TestLink](https://github.com/TestLinkOpenSourceTRMS/testlink-code) - Established open-source web-based test management system for creating test cases, managing test plans, tracking execution, and generating reports with bug tracker integrations.
- [Squash TM](https://github.com/flzara/squash-tm) - Open-core test management platform with requirements traceability, structured test plans, execution tracking, and automation linkage for compliance-heavy teams.

### Reporting Tools

- [Allure Report](https://github.com/allure-framework/allure2) - Flexible, multi-language test reporting tool that generates detailed graphical reports with steps, attachments, timings, and history across all major test frameworks.
- [ReportPortal](https://github.com/reportportal/reportportal) - AI-powered test reporting platform with real-time dashboards, failure analysis, log aggregation, and integrations for JUnit, TestNG, Cucumber, Pytest, and more.
- [ExtentReports](https://github.com/extent-framework/extentreports-java) - Java-based test reporting library that generates interactive HTML reports with logs, screenshots, tags, and system info for Selenium and TestNG-based suites.
- [Mochawesome](https://github.com/adamgruber/mochawesome) - HTML/JSON reporter for Mocha test runs with a clean, browser-based interface showing test context, pass/fail breakdowns, and inline screenshots.

---

## 🔧 CI/CD and Test Infrastructure

### CI/CD Platforms

- [GitHub Actions](https://docs.github.com/en/actions) - Native CI/CD platform for GitHub repositories with YAML-based workflows, a marketplace of reusable actions, and free tier for public repositories.
- [GitLab CI/CD](https://docs.gitlab.com/ee/ci/) - Built-in CI/CD system for GitLab with pipeline-as-code, parallel jobs, environments, and integrated security scanning — all in one platform.
- [Jenkins](https://github.com/jenkinsci/jenkins) - Self-hosted, open-source automation server with a massive plugin ecosystem supporting build, test, and deployment pipelines for any language or platform.
- [CircleCI](https://circleci.com) - Cloud and self-hosted CI/CD platform with fast container-based builds, test splitting, parallelism, and a free tier for open source projects.

### Browser and Test Infrastructure

- [Docker Selenium](https://github.com/SeleniumHQ/docker-selenium) - Official Docker images for running Selenium Grid with Chrome, Firefox, and Edge in containers, enabling scalable parallel cross-browser test execution.
- [Playwright Docker](https://playwright.dev/docs/docker) - Official Docker images maintained by Microsoft for running Playwright tests in isolated, pre-configured containers across all supported browsers.

---

## 🤖 AI-Assisted Testing

### AI Test Generation

- [Qodo](https://www.qodo.ai) - AI coding agent (formerly CodiumAI) that generates meaningful unit tests, reviews pull requests, and suggests code improvements directly inside VS Code and JetBrains IDEs.
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer by GitHub and OpenAI with a free tier that generates, completes, and explains test code across all major languages and IDEs.

### AI Code Review and Static Analysis

- [PR-Agent](https://github.com/qodo-ai/pr-agent) - Open-source AI tool for automated pull request reviews, test suggestions, and code analysis supporting GPT, Claude, Gemini, and self-hosted LLMs.
- [SonarQube Community](https://github.com/SonarSource/sonarqube) - Leading open-source static analysis platform detecting bugs, vulnerabilities, and code smells across 30+ languages with CI/CD integration and a free self-hosted community edition.

---

## 💥 Contract and Chaos Testing

### Consumer-Driven Contract Testing

- [Pact](https://github.com/pact-foundation/pact-reference) - Cross-language consumer-driven contract testing framework that lets API consumers define expected interactions which providers verify independently, eliminating brittle integration tests.
- [Pact Broker](https://github.com/pact-foundation/pact_broker) - Central hub for sharing and verifying Pact contracts across teams, with can-i-deploy gates, versioning, and CI/CD pipeline integration.
- [Spring Cloud Contract](https://github.com/spring-cloud/spring-cloud-contract) - Consumer-driven contract testing framework for Spring Boot microservices that auto-generates provider tests and WireMock stubs from Groovy DSL or YAML contracts.

### Schema-Based Contract Testing

- [Schemathesis](https://github.com/schemathesis/schemathesis) - Property-based contract testing tool that auto-generates and runs test cases from OpenAPI and GraphQL schemas, catching edge cases standard tests miss.
- [Specmatic](https://github.com/znsio/specmatic) - Contract-driven development tool that turns OpenAPI, AsyncAPI, and gRPC specs into executable contracts for both testing and service virtualisation.

### Kubernetes Chaos Engineering

- [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh) - CNCF chaos engineering platform for Kubernetes that supports fault injection across pods, nodes, network, storage, and JVM with a visual dashboard.
- [LitmusChaos](https://github.com/litmuschaos/litmus) - CNCF-hosted chaos engineering platform with a library of Kubernetes fault experiments, a ChaosHub for sharing experiments, and an MCP server for AI-powered chaos workflows.
- [ChaosBlade](https://github.com/chaosblade-io/chaosblade) - Alibaba's open-source chaos engineering toolkit supporting fault injection at host, Kubernetes, JVM, C++, and Node.js levels with a CLI and REST API.

### Network and Application Chaos

- [Toxiproxy](https://github.com/Shopify/toxiproxy) - Shopify's TCP proxy for simulating network chaos including latency, bandwidth limits, packet loss, slow connections, and timeouts in test environments.
- [Chaos Monkey](https://github.com/Netflix/chaosmonkey) - Netflix's pioneering chaos engineering tool that randomly terminates instances to test system resilience — the tool that started the chaos engineering discipline.

---

## 📚 Learning Resources

### Official Docs

- [Playwright Docs](https://playwright.dev/docs/intro) - Official getting started guide and full API reference for Playwright, covering all languages, browsers, and CI/CD integration.
- [Selenium Docs](https://www.selenium.dev/documentation/) - Official Selenium documentation covering WebDriver, Grid, IDE, and best practices across all supported languages.
- [Cypress Docs](https://docs.cypress.io) - Official Cypress documentation with guides, API reference, and real-world recipes for end-to-end testing.
- [Appium Docs](https://appium.io/docs/en/latest/) - Official Appium documentation covering drivers, clients, plugins, and ecosystem tools for mobile automation.
- [k6 Docs](https://grafana.com/docs/k6/latest/) - Official k6 documentation with scripting guides, metrics reference, and CI/CD integration examples for performance testing.

### Free Tutorials and Blogs

- [Test Automation University](https://testautomationu.applitools.com) - Free community-driven platform with 70+ courses by industry experts covering Playwright, Selenium, Cypress, API testing, and more.
- [Martin Fowler — Testing Guide](https://martinfowler.com/testing/) - Authoritative articles on test architecture, the test pyramid, continuous delivery, and software design by Martin Fowler.
- [Ministry of Testing](https://www.ministryoftesting.com) - The largest community platform for software testers with articles, tutorials, courses, forums, and live events.
- [Google Testing Blog](https://testing.googleblog.com) - Engineering blog from Google's testing teams sharing practices, tools, and philosophies used at scale.

### Videos and Courses

- [Playwright YouTube Channel](https://www.youtube.com/@Playwrightdev) - Official Playwright channel with tutorials, feature walkthroughs, and conference talks from the core team.
- [Automation Step by Step](https://www.youtube.com/c/AutomationStepByStep) - Free YouTube channel by Raghav Pal covering Selenium, Playwright, Cypress, API testing, and CI/CD for all experience levels.
- [SDET Unicorns](https://www.youtube.com/@SDETUnicorns) - Practical automation testing tutorials focused on real-world projects, framework building, and interview preparation.

### Books

- [The Art of Software Testing](https://www.wiley.com/en-us/The+Art+of+Software+Testing%2C+3rd+Edition-p-9781118031964) - Glenford Myers' foundational book on software testing principles, test design, and debugging — essential reading for every QA professional.
- [Agile Testing](https://www.addison-wesley.com/9780321534460) - Lisa Crispin and Janet Gregory's definitive guide to testing in agile teams covering testing quadrants, automation strategy, and team collaboration.
- [How Google Tests Software](https://www.pearson.com/en-us/subject-catalog/p/how-google-tests-software/P200000009086) - Inside look at Google's testing philosophy, roles, and practices by James Whittaker, Jason Arbon, and Jeff Carollo.
- [Continuous Delivery](https://continuousdelivery.com) - Jez Humble and Dave Farley's essential guide to building reliable software release pipelines through automated testing and deployment.

### Communities and Newsletters

- [Ministry of Testing Community](https://www.ministryoftesting.com/community) - Active forum and community platform where testers discuss tools, practices, career advice, and share resources.
- [r/QualityAssurance](https://www.reddit.com/r/QualityAssurance/) - Reddit community for QA professionals discussing testing practices, tools, career questions, and industry news.
- [r/softwaretesting](https://www.reddit.com/r/softwaretesting/) - Reddit community focused on software testing methodologies, automation, and tooling discussions.
- [Software Testing Weekly](https://softwaretestingweekly.com) - Weekly newsletter curating the best articles, tools, and discussions from across the software testing community.

---

## 💀 Hall of QA Failures

> Real-world production bugs, outages, and failures - each mapped to the specific test type that would have prevented it. Every entry is sourced from official postmortems, root cause analyses, and independent investigations.

---

### Therac-25 Radiation Overdoses (1985-1987)

**What happened:** A race condition bug in the Therac-25 radiation therapy machine caused at least 6 patients to receive radiation doses up to 100x the prescribed amount. Three patients died. The bug was triggered when experienced operators typed commands quickly, causing safety checks to be skipped due to a timing conflict between concurrent processes. Hardware interlocks present in earlier models had been removed in favour of software-only controls - masking the same defect that existed in previous machines.

**Root cause:** Race condition in concurrent input handling. Software reused from earlier models without re-testing in the new hardware context. No independent software safety verification. AECL claimed 2,760 hours of testing which turned out to mean 2,760 hours of usage - not formal validation.

**What test would have caught it:**
- **Concurrency testing** - testing rapid sequential inputs under timing stress would have exposed the race condition.
- **Negative testing** - testing invalid state transitions would have caught the missing safety check.
- **Integration testing** - testing software against the actual hardware configuration rather than assuming hardware interlocks would compensate.
- **Independent safety verification** - a third-party test audit would have caught the absence of formal test plans.

**Source:** [An Investigation of the Therac-25 Accidents - Leveson & Turner, IEEE Computer 1993](https://ieeexplore.ieee.org/document/274940)

---

### Knight Capital $440M Trading Loss (2012)

**What happened:** Knight Capital deployed new trading software to 8 production servers but missed one. That server still ran a dormant 9-year-old legacy function called Power Peg which was accidentally reactivated by a reused flag bit in the new code. For 45 minutes the rogue server executed millions of unintended trades across 154 stocks, buying high and selling low automatically. Knight Capital lost $440 million - roughly its entire net worth - and was acquired within weeks.

**Root cause:** Inconsistent deployment across production servers. Dead legacy code not removed from the codebase. No circuit breaker or automated kill switch to halt runaway trading. No environment parity validation between servers before go-live.

**What test would have caught it:**
- **Deployment validation testing** - verifying identical software state across all servers before go-live.
- **Environment parity testing** - automated checks confirming no server diverges from the expected deployment state.
- **Integration testing** - testing the interaction between new flag bits and existing legacy code paths.
- **Chaos engineering** - simulating a rogue server scenario would have exposed the missing circuit breaker.

**Source:** [Knight Capital SEC Filing August 2012](https://www.sec.gov/Archives/edgar/data/0001060749/000119312512332176/d391111dex991.htm) · [PRMIA Case Study](https://prmia.org/common/Uploaded%20files/eAI/PRMIA%20Case%20study%20-%20Knight%20Trading.pdf)

---

### Amazon S3 US-EAST-1 Outage (2017)

**What happened:** An AWS engineer debugging a billing slowdown mistyped a single integer in a maintenance console command, accidentally removing a far larger set of servers than intended. Two critical S3 subsystems - the index subsystem and the placement subsystem - were taken offline. Because S3's own status dashboard was hosted on S3, it showed green throughout the outage. Recovery took over 4 hours because core subsystems had not been restarted in so long that the restart process itself was slow and unfamiliar. Slack, Netflix, Reddit, and hundreds of thousands of other sites were affected.

**Root cause:** No minimum capacity guardrail on the removal command. No input validation preventing a single command from exceeding safe blast radius. Status page dependency on the same infrastructure it was monitoring. Infrequent restart cycles leaving recovery procedures untested.

**What test would have caught it:**
- **Input validation testing** - the command tool had no bounds check preventing removal of more than a safe threshold of capacity.
- **Chaos engineering** - a controlled subsystem removal drill would have exposed both the blast radius and the slow restart recovery time.
- **Resilience testing** - testing the status dashboard's independence from the services it monitors.
- **Disaster recovery testing** - regularly rehearsing large-scale restarts would have made recovery faster and more familiar.

**Source:** [AWS Official Postmortem](https://aws.amazon.com/message/41926/)

---

### Boeing 737 MAX MCAS Crashes (2018-2019)

**What happened:** Boeing's MCAS (Maneuvering Characteristics Augmentation System) was designed to correct the 737 MAX's tendency to pitch up due to repositioned engines. MCAS relied on input from a single angle-of-attack (AoA) sensor with no redundancy. When that sensor failed and provided erroneous data on Lion Air Flight 610 and Ethiopian Airlines Flight 302, MCAS repeatedly forced the nose down against pilot resistance. Both crews were not informed MCAS existed. 346 people died across the two crashes. The 737 MAX was grounded for 20 months - the longest grounding in US aviation history - costing Boeing over $20 billion.

**Root cause:** Single point of failure - MCAS relied on one sensor with no cross-check against a second. Safety analysis assumed pilots would recognise and respond to MCAS activation within 4 seconds - an assumption never validated through realistic simulator testing. Boeing's internal QA was compromised by schedule and cost pressures. The FAA delegated significant certification authority back to Boeing.

**What test would have caught it:**
- **Failure mode and effects testing (FMEA)** - systematically testing what happens when each sensor fails individually would have exposed the single-sensor dependency.
- **Simulation testing under stress** - testing pilot response times under realistic cockpit load would have invalidated the 4-second recovery assumption.
- **Sensor redundancy testing** - validating system behaviour with conflicting AoA sensor inputs.
- **Independent safety verification** - third-party test audit rather than self-certification would have caught the missing redundancy.

**Source:** [IEEE Spectrum - How the Boeing 737 MAX Disaster Looks to a Software Developer](https://spectrum.ieee.org/how-the-boeing-737-max-disaster-looks-to-a-software-developer) · [House Transportation Committee Final Report 2020](https://transportation.house.gov/imo/media/doc/2020.09.16%20FINAL%20737%20MAX%20Report%20for%20Public%20Release.pdf)

---

### Facebook Global Outage (2021)

**What happened:** A routine BGP configuration change at Facebook accidentally withdrew the BGP routes that told the rest of the internet how to find Facebook's DNS nameservers. Facebook, Instagram, WhatsApp, and Oculus went completely dark for approximately 6 hours. Facebook's own internal tools used the same infrastructure, so engineers could not remotely access systems to apply a fix and had to physically travel to datacenters. Roughly 3.5 billion people lost access to the services simultaneously.

**Root cause:** A configuration change command issued during routine maintenance had an unintended side effect of taking down all BGP route advertisements simultaneously. No staged rollout. The internal tooling used to audit and roll back configuration changes relied on the same network connectivity that had just been severed.

**What test would have caught it:**
- **Configuration change testing** - validating configuration commands in a staging environment mirroring production BGP topology before applying to live.
- **Canary deployment testing** - rolling out network configuration changes to a small subset of infrastructure before global propagation.
- **Resilience testing** - testing whether internal tooling remains accessible when core network infrastructure is degraded.
- **Blast radius testing** - verifying that a single configuration command cannot affect all regions simultaneously.

**Source:** [Facebook Engineering Blog - More Details About the October 4 Outage](https://engineering.fb.com/2021/10/05/networking-traffic/outage-details/)

---

### CrowdStrike Global Outage (2024)

**What happened:** CrowdStrike deployed a content configuration update (Channel File 291) for its Falcon sensor on July 19, 2024. The update contained an IPC Template Instance that specified 21 input fields, but the sensor code only supplied 20. The Content Validator had a logic error and did not catch the mismatch, partly because all previous test instances used wildcard matching on the 21st field. The sensor's Content Interpreter attempted an out-of-bounds memory read when processing the 21st parameter, causing the Windows kernel to crash. 8.5 million Windows devices showed the Blue Screen of Death globally. Banking, healthcare, airlines, and emergency services were disrupted for up to 72 hours. Estimated financial damage exceeded $3 billion.

**Root cause:** Off-by-one parameter mismatch between the Template Type definition (21 fields) and the sensor code (20 fields). Content Validator logic error allowed the mismatch through. Test instances used wildcard matching on the 21st field - meaning the specific non-wildcard failure scenario was never exercised before production. No staged rollout - the update was pushed globally simultaneously.

**What test would have caught it:**
- **Boundary value testing** - explicitly testing the 21st parameter with non-wildcard values would have triggered the out-of-bounds read in a test environment.
- **Input validation testing** - a strict schema check verifying field count parity between Template Type definition and sensor input.
- **Staged rollout testing** - a canary deployment to 1% of sensors would have contained the blast radius to thousands rather than millions of devices.
- **Content validation testing** - automated regression tests covering every Template Instance with concrete non-wildcard values before production release.

**Source:** [CrowdStrike External Technical Root Cause Analysis - Channel File 291, August 6 2024](https://www.crowdstrike.com/wp-content/uploads/2024/08/Channel-File-291-Incident-Root-Cause-Analysis-08.06.2024.pdf)

---

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
