# Awesome-Real-User-Monitoring-Rum

## Top Real User Monitoring (RUM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Frontend Performance, Core Web Vitals & Self-Hosted RUM Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial Real User Monitoring platforms** and **open-source projects** that capture actual user experiences — page load times, Core Web Vitals, JavaScript errors, session replays, and user journeys — across browsers and devices.



**Examples** include AWS RUM, Datadog RUM, New Relic Browser, Dynatrace Digital Experience, Sentry Performance, Raygun RUM, LogRocket, SpeedCurve, AppDynamics Browser RUM, and Splunk RUM (the category leaders).



**Open-source emphasis**: RUM is a growing open-source domain. **OpenTelemetry** provides the standard for browser instrumentation, **Grafana Faro** delivers a complete browser observability stack, **Sentry** offers self-hosted performance monitoring, and **Elastic RUM** integrates with the Elastic Stack. **Grafana Pyroscope** and **Tempo** complement with profiling and tracing. **Umami** and **Matomo** cover privacy-friendly analytics. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Datadog RUM](https://www.datadoghq.com/product/real-user-monitoring/)**  

  **The leading commercial RUM platform** — session replay, Core Web Vitals, error tracking, and user journeys . **Integrated with Datadog's observability platform** . **Best for full-stack observability** .



- **[New Relic Browser](https://newrelic.com/platform/browser-monitoring)**  

  **New Relic's RUM** — page load timing, AJAX requests, JavaScript errors, and session traces . **Best for New Relic users** .



- **[Dynatrace Digital Experience](https://www.dynatrace.com/)**  

  **AI-powered RUM** — automatic issue detection and root cause analysis . **Best for enterprise digital experience** .



- **[Sentry Performance](https://sentry.io/)**  

  **Application performance monitoring** — see Open-Source section for self-hosted option.



- **[Raygun RUM](https://raygun.com/)**  

  **Real user monitoring** — performance metrics and error tracking . **Best for SMBs** .



- **[LogRocket](https://logrocket.com/)**  

  **Session replay and RUM** — watch user sessions and debug issues . **Best for product teams** .



- **[SpeedCurve](https://speedcurve.com/)**  

  **Performance monitoring** — synthetic and RUM with Core Web Vitals . **Best for performance engineers** .



- **[AWS RUM](https://aws.amazon.com/cloudwatch/features/rum/)**  

  **AWS CloudWatch RUM** — real user monitoring integrated with CloudWatch . **Best for AWS-native applications** .



- **[AppDynamics Browser RUM](https://www.appdynamics.com/)**  

  **Browser monitoring** — integrated with AppDynamics APM . **Best for AppDynamics users** .



- **[Splunk RUM](https://www.splunk.com/)**  

  **Real user monitoring** — integrated with Splunk Observability . **Best for Splunk users** .



## Open-Source GitHub Projects



### Complete RUM Platforms



- **[Grafana Faro](https://github.com/grafana/faro)**  

  **The leading open-source RUM platform**, Apache-2.0 licensed with **1,500+ GitHub stars** . **Complete browser observability stack** — web SDK collects telemetry and sends to Faro receiver . **Integrates with Grafana Loki, Tempo, and Pyroscope** . **Core Web Vitals, errors, logs, traces, and performance metrics** . **The de facto open-source Datadog RUM alternative** . **Best for self-hosted RUM** .



- **[Sentry](https://github.com/getsentry/sentry)**  

  **Open-source error and performance monitoring**, FSL licensed (self-hosted available) with **35,000+ GitHub stars** . **Browser performance monitoring with Core Web Vitals** . **Session replay, error tracking, and trace view** . **Self-hosted Docker deployment** . **Best for error and performance monitoring** .



- **[Elastic RUM](https://github.com/elastic/apm-agent-rum-js)**  

  **Elastic APM RUM agent**, Apache-2.0 licensed . **Real user monitoring integrated with Elastic Stack** . **Page load, route changes, and user interactions** . **Best for Elastic Stack users** .



- **[OpenTelemetry Browser](https://github.com/open-telemetry/opentelemetry-js)**  

  **OpenTelemetry instrumentation for browsers**, Apache-2.0 licensed . **Vendor-neutral browser telemetry** — send to any OpenTelemetry backend . **The standard for browser instrumentation** . **Best for OpenTelemetry-native RUM** .



### Frontend Performance Monitoring



- **[web-vitals](https://github.com/GoogleChrome/web-vitals)**  

  **Google's Core Web Vitals library**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Measure LCP, INP, CLS, FCP, and TTFB** . **The standard for Core Web Vitals measurement** . **Best for performance measurement** .



- **[Perfume.js](https://github.com/Zizzamia/perfume.js)**  

  **Web performance library**, MIT licensed . **Core Web Vitals, navigation timing, and resource timing** . **Best for performance metrics** .



- **[Boomerang](https://github.com/akamai/boomerang)**  

  **Akamai's RUM library**, Apache-2.0 licensed . **Page load, bandwidth, and user experience metrics** . **Best for custom RUM** .



- **[Lighthouse](https://github.com/GoogleChrome/lighthouse)**  

  **Automated performance auditing**, Apache-2.0 licensed with **30,000+ GitHub stars** . **Core Web Vitals, SEO, and accessibility** . **Best for performance auditing** .



- **[Lighthouse CI](https://github.com/GoogleChrome/lighthouse-ci)**  

  **Automated Lighthouse audits in CI/CD**, Apache-2.0 licensed . **Performance budgets** . **Best for CI performance testing** .



### Session Replay & Analytics



- **[OpenReplay](https://github.com/openreplay/openreplay)**  

  **Open-source session replay**, AGPL-3.0 licensed with **10,000+ GitHub stars** . **Session replay, co-browsing, and dev tools** . **Self-hosted or cloud** . **The leading open-source LogRocket alternative** . **Best for session replay** .



- **[Umami](https://github.com/umami-software/umami)**  

  **Privacy-friendly analytics**, MIT licensed with **25,000+ GitHub stars** . **Simple, fast, and privacy-focused** . **Best for privacy-first analytics** .



- **[Matomo](https://github.com/matomo-org/matomo)**  

  **Open-source web analytics**, GPL-3.0 licensed with **20,000+ GitHub stars** . **Full-featured with session recording and heatmaps** . **Best for comprehensive analytics** .



- **[Plausible](https://github.com/plausible/analytics)**  

  **Lightweight and privacy-friendly analytics**, AGPL-3.0 licensed . **No cookies, no tracking** . **Best for simple analytics** .



### APM & Tracing



- **[SigNoz](https://github.com/SigNoz/signoz)**  

  **Open-source observability platform**, Apache-2.0 licensed with **23,000+ GitHub stars** . **Logs, traces, and metrics with RUM support** . **Best for unified observability** .



- **[Uptrace](https://github.com/uptrace/uptrace)**  

  **Open-source APM**, AGPL-3.0 licensed . **Distributed tracing, metrics, and logs** . **Best for cost-effective APM** .



- **[Jaeger](https://github.com/jaegertracing/jaeger)**  

  **Distributed tracing platform**, Apache-2.0 licensed with **22,000+ GitHub stars** . **End-to-end tracing** . **Best for distributed tracing** .



- **[Tempo](https://github.com/grafana/tempo)**  

  **Grafana's tracing backend**, AGPL-3.0 licensed . **Trace storage with Grafana integration** . **Best for Grafana users** .



### Additional Strong Open-Source Options



- **Grafana** — Visualization and dashboards .

- **Prometheus** — Metrics collection .

- **Loki** — Log aggregation .

- **Pyroscope** — Continuous profiling .

- **ParCa** — Continuous profiling .

- **Zipkin** — Distributed tracing .

- **SkyWalking** — APM with browser monitoring .

- **Pinpoint** — APM with browser monitoring .

- **RUM Archive** — Open RUM data archive .

- **CrUX** — Chrome User Experience Report .



**Frameworks for building custom RUM solutions**: Combine **Grafana Faro** for complete browser observability with Grafana integration . Use **OpenTelemetry Browser** for vendor-neutral instrumentation . Deploy **Sentry** for error and performance monitoring . Choose **web-vitals** for Core Web Vitals measurement . Integrate **OpenReplay** for session replay . Use **Umami** or **Plausible** for privacy-friendly analytics . Note that true managed RUM with global CDN, automatic scaling, and vendor-supported SLAs (Datadog RUM, New Relic Browser, Dynatrace) remains primarily commercial territory; open-source stacks provide strong browser instrumentation, performance monitoring, and session replay foundations that require integration for complete real user monitoring.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- RUM platforms collect sensitive user data including browsing behavior, device information, and potentially PII. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA).

- **Session replay raises privacy concerns** — ensure proper consent, mask sensitive data, and comply with privacy regulations. OpenReplay and LogRocket provide masking options .

- **License considerations**: Grafana Faro uses Apache-2.0, Sentry uses FSL (self-hosted available), OpenReplay uses AGPL-3.0, and Umami uses MIT. Verify licensing against your use case before committing .

- **Core Web Vitals are Google ranking signals** — LCP, INP, and CLS impact SEO. Monitor and optimize continuously .

- The open-source ecosystem provides strong browser instrumentation, performance monitoring, and session replay foundations, but **global CDN, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for frontend engineers, performance teams, and organizations seeking RUM sovereignty.**  

Let's make real user monitoring more open, transparent, and privacy-respecting.
