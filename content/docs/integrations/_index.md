---
title: Integrations
description: See all integrations available for Keptn and maintained by the community.
icon: setup
weight: 1001
hidechildren: true # this flag hides all sub pages in the sidebar-multicard.html
---

## Available integrations

Please find here a list of all *Keptn-services* and *SLI-providers* that are available for the last Keptn release. Feel free to install these integrations on a Keptn and to use them according to their documentation in the corresponding repository. The maintainers of those services are referenced in the CODEOWNERS file of each repo. Most of the repositories you can find in the [github.com/keptn-contrib](https://github.com/keptn-contrib) organization and are referenced below.  

- If you identify a bug you would like to report, please create an issue in the repository of the Keptn-service. 

- If you need more information on version compatibility, please go to the repository where a compatibility-matrix should be provided.

| Keptn-service | latest Release | supported Keptn | Repository  |
| -------------------------- | --- | --- | --- |
| **argo-service**      | [0.8.0](https://github.com/keptn-contrib/argo-service/releases/tag/0.8.0) | 0.8.3 | https://github.com/keptn-contrib/argo-service |
| **dynatrace-service**      | [0.14.0](https://github.com/keptn-contrib/dynatrace-service/releases/tag/0.14.0) | 0.8.3 | https://github.com/keptn-contrib/dynatrace-service |
| **neoload-service**        | [0.6.0](https://github.com/keptn-contrib/neoload-service/tree/0.6.0) | 0.6.0 | https://github.com/keptn-contrib/neoload-service |
| **notification-service**   | [0.3.1](https://github.com/keptn-contrib/notification-service/releases/tag/0.3.1) | 0.7.3 | https://github.com/keptn-contrib/notification-service |
| **prometheus-service** 1)    | [0.6.0](https://github.com/keptn-contrib/prometheus-service/releases/tag/0.6.0) | 0.8.3 | https://github.com/keptn-contrib/prometheus-service |
| **servicenow-service**     | [0.2.1](https://github.com/keptn-contrib/servicenow-service/releases/tag/0.2.1) | 0.6.2 | https://github.com/keptn-contrib/servicenow-service |
| **unleash-service**        | [0.3.1](https://github.com/keptn-contrib/unleash-service/releases/tag/0.3.1) | 0.8.3 | https://github.com/keptn-contrib/unleash-service | 



| SLI-provider | latest Release | supported Keptn | Repository  |
| -------------------------- | --- | --- | --- |
| **dynatrace-sli-service**  | [0.10.3](https://github.com/keptn-contrib/dynatrace-sli-service/releases/tag/0.10.3) | 0.8.3 | https://github.com/keptn-contrib/dynatrace-sli-service |
| **neoload-sli-provider**  | [0.6.0](https://github.com/keptn-contrib/neoload-sli-provider/tree/0.6.0) | 0.6.0 | https://github.com/keptn-contrib/neoload-sli-provider |
| **prometheus-sli-service** 1)  | [0.3.0](https://github.com/keptn-contrib/prometheus-sli-service/releases/tag/0.3.0) | 0.8.3 | https://github.com/keptn-contrib/prometheus-sli-service |

**Notes:**

* 1) The `prometheus-sli-service` has been merged with `prometheus-service`. The `prometheus-sli-service` is deprecated and has been set to read-only on the **9th of July, 2021**.

### Keptn Sandbox

A *Keptn-service* is classified as sandbox if it is under development and has not shown significant adoption yet. 
Each project in the Keptn Sandbox organization is maintained by one or more individuals that can be found in the respective CODEOWNERS file of the repository. Please reach out to them or open issues on the repository in case of any questions.
Sandbox projects can be found in [github.com/keptn-sandbox](https://github.com/keptn-sandbox).

Below are projects that have been shown in any Keptn community or developer meeting and thus have successfully fulfilled the requirements listed in the [contributing guide](https://github.com/keptn-sandbox/contributing) of Keptn Sandbox. 

| Keptn-service | in development for Keptn | Repository |
| --- | --- | --- | 
| **ansibletower-service** | 0.7.3 | https://github.com/keptn-sandbox/ansibletower-service |
| **artillery-service** | 0.8.4 | https://github.com/keptn-sandbox/artillery-service |
| **jenkins-service** | 0.6.1 | https://github.com/keptn-sandbox/jenkins-service |
| **job-executor-service** | 0.8.6 | https://github.com/keptn-sandbox/job-executor-service |
| **keptn-report** | 0.6.1 | https://github.com/keptn-sandbox/keptn-report |
| **litmus-service** | 0.8.4 | https://github.com/keptn-sandbox/litmus-service |
| **locust-service** | 0.8.4 | https://github.com/keptn-sandbox/locust-service |
| **slackbot-service** | 0.6.1 | https://github.com/keptn-sandbox/slackbot-service |
| **statistics-service** | 0.7.3 | https://github.com/keptn-sandbox/statistics-service |

Please find the exhaustive list of integrations in the [Keptn Sandbox Github organization](https://github.com/keptn-sandbox).

## How to write your own Keptn integration

1. There are multiple ways to **integrate your service with Keptn**. Learn [how to write a Keptn integration](../0.8.x/integrations/how_integrate/) by identifying the right integration method for your use-case.

2. Once you have developed your service, please consider **contributing** it to the Keptn sandbox by following the [contributions guide](https://github.com/keptn-sandbox/contributing) for contributing it to Keptn Sandbox.

3. **Share your integration** with the growing Keptn community in [Slack](https://slack.keptn.sh) or in one of our next [community meetings](/community/meetings)!
