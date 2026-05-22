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

> *Coming soon — contributions welcome.*

---

## 💥 Contract and Chaos Testing

> *Coming soon — contributions welcome.*

---

## 📚 Learning Resources

### Official Docs

> *Coming soon — contributions welcome.*

### Free Tutorials and Blogs

> *Coming soon — contributions welcome.*

### Videos and Courses

> *Coming soon — contributions welcome.*

### Books

> *Coming soon — contributions welcome.*

### Communities and Newsletters

> *Coming soon — contributions welcome.*

---

## 💀 Hall of QA Failures

> Real-world production bugs, outages, and failures — each mapped to the specific test type that would have prevented it.

> *Coming soon — contributions welcome.*

---

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
