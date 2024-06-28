# Term 02 - 2024 June - August

Status: Planning

Mentorship duration - three months (12 weeks - full-time schedule)

### Timeline

| activity | date |
| --- | --- |
| project proposals | Monday April 8 - Wed May 8, 2024, 5:00 PM PDT |
| mentee applications open | Monday May 13 - Tues May 28, 5:00 PM PDT |
| application review/admission decisions | Wed May 29 - Tues June 11, 5:00 PM PDT |
| selection notifications | Wed June 12, 5:00 PM PDT |
| Mentorship program begins with the initial work assignments | Monday June 17 (Week 1) |
| Midterm mentee evaluations and first stipend payments | Wednesday July 24 (Week 6) |
| Final mentee evaluations and mentee feedback/blog submission due, second and final stipend payment approvals | Wed Aug 28, 5:00 PM PST (Week 12) |
| Last day of term | Friday Aug 30 |

### Project Instructions

Project maintainers and potential mentors are welcome to propose their mentoring project ideas via submitting a PR to GitHub here https://github.com/cncf/mentoring/blob/main/programs/lfx-mentorship/2024/02-Jun-Aug/project_ideas.md, by April 24, 2024.

### Application instructions

Mentee application instructions can be found on the [Program Guidelines](https://github.com/cncf/mentoring/blob/main/programs/lfx-mentorship/README.md#program-guidelines) page.

---

## Accepted projects

- [Cilium](#cilium)
  - [Cilium Technical Outcomes](#cilium-technical-outcomes)
- [Copacetic](#copacetic)
  - [Add new scenarios to Copa's existing image patching features](#add-new-scenarios-to-copas-existing-image-patching-features)
- [Crossplane](#crossplane)
  - [Make Crossplane Easy - Improving the Developer Experience](#make-crossplane-easy---improving-the-developer-experience)
- [Harbor](#harbor)
  - [Harbor CLI](#harbor-cli)
  - [Harbor Satellite](#harbor-satellite)
- [in-toto](#in-toto)
  - [Add GUAC support](#add-guac-support)
  - [Documentation Boost!](#documentation-boost)
  - [Sigstore support for in-toto-jenkins](#sigstore-support-for-in-toto-jenkins)
- [Jaeger](#jaeger)
  - [Jaeger-V2 Observability and Healthchecks](#jaeger-v2-observability-and-healthchecks)
  - [Jaeger-V2 Service Performance Monitoring](#jaeger-v2-service-performance-monitoring)
  - [Jaeger-V2 Kafka-based architecture](#jaeger-v2-kafka-based-architecture)
- [Karmada](#karmada)
  - [Certificate Lifecycle Management](#certificate-lifecycle-management)
- [KCL](#kcl)
  - [KCL Package Management Dependencies Sparse Checkout](#kcl-package-management-dependencies-sparse-checkout)
  - [Optimization of KCL LSP prompt information](#optimization-of-kcl-lsp-prompt-information)
  - [Supports tree-sitter for KCL](#supports-tree-sitter-for-kcl)
- [Knative](#knative)
  - [Improve Knative Eventing Onboarding](#improve-knative-eventing-onboarding)
  - [Knative - applying pre-prepared website design](#knative---applying-pre-prepared-website-design)
- [KubeArmor](#kubearmor)
  - [Improve System Test Coverage and Pratices for KubeArmor](#improve-system-test-coverage-and-pratices-for-kubearmor)
- [KubeEdge](#kubeedge)
  - [Iterating Enhancement for KubeEdge Dashboard](#iterating-enhancement-for-kubeedge-dashboard)
  - [Router Manager Support HA](#router-manager-support-ha)
  - [KubeEdge test cases enhancement](#kubeedge-test-cases-enhancement)
  - [KubeEdge Documentation Improvement](#kubeedge-documentation-improvement)
- [Kubernetes](#kubernetes)
  - [Update Image Signing to Meet New Infra Requirements](#update-image-signing-to-meet-new-infra-requirements)
- [Kubescape](#kubescape)
  - [Advanced Kubescape plugin features for VSCode](#advanced-kubescape-plugin-features-for-vscode)
  - [Backstage plugin that adheres to the new plugin system](#backstage-plugin-that-adheres-to-the-new-plugin-system)
- [KWOK](#kwok)
  - [Enhancement of Test Cases](#enhancement-of-test-cases)
  - [Enhancement of Technical Outcomes](#enhancement-of-technical-outcomes)
- [LitmusChaos](#litmuschaos)
  - [Revamp Litmus Helm Agent, UBI migration of Images](#revamp-litmus-helm-agent-ubi-migration-of-images)
  - [Enhancements in Chaoscenter: GitOps Support for Azure Git, Group Chaos Infra by Environments in Infrastructure Selection Modal](#enhancements-in-chaoscenter-gitops-support-for-azure-git-group-chaos-infra-by-environments-in-infrastructure-selection-modal)
  - [Implementing Upgrade Agent Support in Litmus 3.x](#implementing-upgrade-agent-support-in-litmus-3x)
- [OpenKruise](#openkruise)
  - [Enhancement for Kruise-Game Dashboard](#enhancement-for-kruise-game-dashboard)
- [Prometheus](#prometheus)
  - [Prometheus Remote Write Benchmarking Capabilities](#prometheus-remote-write-benchmarking-capabilities)
  - [Mark Out-of-order ingestion as stable](#mark-out-of-order-ingestion-as-stable)
- [Thanos](#thanos)
  - [Compactor: Display TODO plan in UI](#compactor-display-todo-plan-in-ui)
- [TUF](#tuf)
  - [Documentation analysis and improvements](#documentation-analysis-and-improvements)
- [Vitess](#vitess)
  - [Improve the website of our automated-benchmarking tool (migrate to shadcn ui and typescript)](#improve-the-website-of-our-automated-benchmarking-tool-migrate-to-shadcn-ui-and-typescript)
  - [Community building and engagement](#community-building-and-engagement)
- [WasmEdge](#wasmedge)
  - [Support piper as a new backend of the WASI-NN WasmEdge plugin](#support-piper-as-a-new-backend-of-the-wasi-nn-wasmedge-plugin)
  - [Enabling LLM fine tuning in the WASI-NN ggml plugin](#enabling-llm-fine-tuning-in-the-wasi-nn-ggml-plugin)
  - [Create a search-enabled API server for local LLMs](#create-a-search-enabled-api-server-for-local-llms)
  - [Finetune LLM models for Rust coding assistance](#finetune-llm-models-for-rust-coding-assistance)

### Cilium

#### Cilium Technical Outcomes

- Description: On the Cilium [homepage](https://cilium.io), we want to document technical outcomes from using Cilium. Think of these technical outcomes as aggregating some of cilium features to achieve a high level technical goal. These are the current ones we have in mind: Zero Trust Networking, Network Automation, Distributed Firewalling, Cost and Carbon Savings, Multi-cloud Connectivity.
- Expected Outcome: A section of the Cilium website detailing these technical outcomes. This section on the website can include any supporting materials from the Cilium community i.e blogs, videos, talks, illustrations, etc.
- Recommended Skills: Technical Writing, some basic working knowlegde of Cilium or the willingness to quickly ramp up, Kubernetes, general familiarity with the cloud native ecosystem, basic React.js(the cilium webiste is built with Gatsby).
- Mentor(s):
    - Paul Arah(paularah, <paul.arah@isovalent.com>)
    - Bill Mulligan(xmulligan, <bill.mulligan@isovalent.com>)
- Upstream Issue: <https://github.com/cilium/cilium.io/issues/492>
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9ab5c6dc-4735-4dfb-99c0-d00e86aeae60


### CNCF TAG Network

#### Mapping CNCF Landscape one Relationship-at-a-time

- Description: While the OpenAPI specifications for Kubernetes offer a taxonomy, integrating a graph data model with formalized ontologies unlocks a multitude of capabilities. Among these, enabling inferencing necessary for natural language processing stands out as a straightforward application. This, in turn, facilitates the possibility of a human-centric query/response interaction. Importantly, advancing to a knowledge semantic graph from a connected systems' graph data model opens the door to building more sophisticated systems.

- Expected Outcome:
  - Identifying new technologies from CNCF landscape and creating new YAML-formatted definitions of one or more relationships.
  - Documentation of each relationship - per component.
  - Development of new types of genealogies - new types of ways in which resources relate to one another and how these relationships might be visualized.

- Recommended Skills: Familiarity with Helm charts and Artifact Hub, basic familiarity with Kubernetes, and familiarity with CNCF different projects would be helpful
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Uzair Shaikh (@muzairs15, muzair.shaikh810@gmail.com)
- Upstream Issue: https://github.com/cncf/tag-network/issues/39
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/bec63054-bc32-4444-b6c5-2b427f527e16

#### Technical Content Creation CNCF Challenges

- Description: On a periodic basis, the CNCF would like to present a public challenge to those that are interested in participating (e.g. “Challenge: Distributed Tracing with Jaeger”).

Your mission in this internship is technical content creation of said challenges through use of markdown, Meshery, and any number of other CNCF projects. Challenges will be created using the Meshery Playground and potentially published in the proposed CNCF Hub. They will be similar too, but slightly different from these [example tutorials](https://docs.meshery.io/guides/tutorials/).

Understand that your challenges will be promoted through CNCF channels, reviewed by various project maintainers, and that each challenger (participant) will receive a certain number of points, depending upon whether or not they successfully complete the challenges that you create and in what timeframe they complete those challenges (the faster, the more points). Your challenges will need to vary in level of difficulty.

- Expected Outcome:
  - 10+ new challenges published in CNCF Hub (and Meshery Catalog and Artifact Hub).
  - Challenges can contain more than one objective. Points are earned for each objective completed.
  - Bonus: Extend one or more of Meshery’s Learning Paths.

- Recommended Skills: written English, Kubernetes, DevOps, and familiarity with any number of other CNCF projects, like Prometheus, CoreDNS, Istio, Jaeger, Helm, Harbor, OPA, Rook, SPIFEE, Flux, Argo, Flux, Falco, etc., Jekyll, strong organizational skills
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Nic Jackson (@nicholasjackson), jackson.nic@gmail.com)
- Upstream Issue: https://github.com/cncf/tag-network/issues/40
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1a620529-f2be-4a6f-8b4d-0562731cb840


### Copacetic

#### Add new scenarios to Copa's existing image patching features
- Description: This project will focus on a series of initial TODOs that are present in the codebase and that have been recently added as issues in GitHub. The issues range from adding custom image repos, to handling custom configuration at the package and system level.
- Expected Outcome: Added features as suggested by current TODOs in code to enhance Copacetic user experience and features.
- Recommended Skills: Go, Linux Package Management tools, container images, distroless images, Trivy, knowledge of Copacetic codebase would be useful.
- Mentors(s):
    - Ashna Mehrotra (@ashnamehrotra, asmehrotra@microsoft.com)
    - Robert Kielty (@RobertKielty, robert.kielty@cncf.io)
- Upstream Issues: https://github.com/project-copacetic/copacetic/issues/611
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/955a5956-de58-44ea-8760-d606feb82165

### Crossplane

#### Make Crossplane Easy - Improving the Developer Experience

- Description: Crossplane is in use at scale in many production environments, but we get often get feedback that there are many obstacles to learn Crossplane and get to a successfully built production-ready control plane. A major reason for this learning curve is the lack of supporting tools and experiences on top of core Crossplane that could accelerate the community’s attempts to successfully build their platforms. These higher level experiences have recently become a focus for the project and we want to keep delivering awesome experiences that make Crossplane easier to use.
- Expected Outcome: We expect the mentee to design and code multiple improvements to the Crossplane tooling from the issue linked below. We will start with smaller scoped issues to ramp up and then focus on a bigger deliverable such as adding [validation for Crossplane Functions](https://github.com/crossplane/crossplane/issues/5094). By the end of the term, the mentee will have multiple code PRs merged into the Crossplane codebase.
- Recommended Skills: Go, Kubernetes, Crossplane, CLI tools, passion for DevEx
- Mentor(s):
    - Jared Watts (primary) (@jbw976, jbw976@gmail.com)
    - Ezgi Demirel (secondary) (@ezgidemirel, ezgi@upbound.io)
- Upstream Issue: https://github.com/crossplane/crossplane/issues/3957
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/87e81040-eb5e-4628-babd-820ef23cd261

### Harbor

#### Harbor CLI

- Description: Harbor is a popular and widely adopted container registry. We have developed an initial CLI (https://github.com/goharbor/harbor-cli) that we would like to extend and implement additional functionality, and common workflows that are currently only present in the Web UI. We are seeking a Golangs experienced manatee who can work on the project independently.
- Expected Outcome: Working Golang Harbor CLI which can be used in the CI/CD implementations that compliment the Web UI covering the typical workflows of Harbor administrators and users. Familiarity with Golang library spf13/cobra and REST/Open API. Well-documented CLI that users love to use, and with the corresponding architectural diagrams under the Harbor. Working CI/CD with GitHub actions that create multi architecture binaries and containers.
- Recommended Skills: Golang, spf13/cobra
- Mentor(s):
    - Vadim Bauer (@vad1mo, vb@container-registry.com)
    - Yan Wang (@wy65701436, yan-yw.wang@broadcom.com)
    - Orlin Vasilev (@OrlinVasilev, orlin@orlix.org)
- Upstream Issue: https://github.com/goharbor/harbor-cli/issues/41
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a8a71ad1-4a1b-422e-9928-01c153ac2daf

#### Harbor Satellite

- Description: In recent years, containers have extended beyond their traditional cloud environments, becoming increasingly prevalent in remote and edge computing contexts. These environments often lack reliable internet connectivity, posing significant challenges in managing and running containerized applications due to difficulties in fetching container images. To address this, the project aims to decentralize container registries, making them more accessible to edge devices. The need for a satellite that can operate independently, store images on disk, and run indefinitely with stored data is crucial for maintaining operations in areas with limited or no internet connectivity.
  Harbor Satellite aims to bring Harbor container registries to edge locations, ensuring consistent, available, and integrity-checked images for edge computing environments. This proposal outlines the development of a stateful, standalone satellite that can function as a primary registry for edge locations and as a fallback option if the central Harbor registry is unavailable.
- Expected Outcome:
  The goal is to extend the proof of concept
  and demonstrate that such a solution practically works.
  Candidates should be able understanding and implementing the [image](https://github.com/opencontainers/image-spec) and [distribution spec](https://github.com/opencontainers/distribution-spec)
  to replicate images from a central registry to a registry on the edge location.
- Recommended Skills: Golang, Container, Image-spec, Distribution-spec
- Mentor(s):
    - Vadim Bauer (@vad1mo, vb@container-registry.com)
    - Yan Wang (@wy65701436, yan-yw.wang@broadcom.com)
    - Orlin Vasilev (@OrlinVasilev, orlin@orlix.org)
- Upstream Issue: https://github.com/goharbor/harbor/issues/20404
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/93a94aec-8026-4587-b840-52c96ab25020

### in-toto

### Add GUAC support

- Description: The project aims to integrate Graph for Understanding Artifact Composition (GUAC) with in-toto, a framework safeguarding software supply chain integrity. [Graph for Understanding Artifact Composition (GUAC)](https://guac.sh/) aggregates software security metadata into a high fidelity graph database—normalizing entity identities and mapping standard relationships between them. This project seeks to extend in-toto's capabilities by incorporating GUAC, enabling users to query GUAC with Package URLs (purls) and retrieve pertinent attestations.
- Expected Outcome: Adds functionality to query GUAC, retrieve and parse relevant attestations for the specified artifact.
- Recommended Skills: Go, Python
- Mentor(s):
    - Santiago Torres-Arias (@SantiagoTorres, santiagotorres@purdue.edu)
    - Pradyumna Krishna (@PradyumnaKrishna, git@onpy.in)
- Upstream Issue: https://github.com/in-toto/attestation-verifier/issues/29
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/abfb7093-b057-40da-8be1-c67bd8839698

#### Documentation Boost!

- Description:
    - Help contributors get started with improving the documentation of CNCF projects and TAGs.  To start, we'd like mentees to help to
      improve both the documentation of a project, and also encourage them to contribute to other projects.  So, view the issues as a starting
      point to help start your career in open source.
- Expected Outcome:
    - Develop effective documentation for CNCF projects.  As a start, the CNCF project in-toto has a fairly clear set of requirements for what
      documentation changes are needed.
- Recommended Skills:
    - Technical writing
    - Basic understanding of cloud native projects (or a desire to learn!)
- Mentor(s):
    - Justin Cappos @JustinCappos jcappos@nyu.edu
    - Patrice Chalin @chalin chalin@cncf.io
    - Lukas Pühringer @lukpueh lukas.puehringer@nyu.edu
- Upstream Issues:
    -   https://github.com/in-toto/docs/issues/85
    -   https://github.com/in-toto/docs/issues/90
    -   https://github.com/in-toto/docs/issues/91
    -   https://github.com/in-toto/docs/issues/92
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/34314eb1-0fc3-4802-ab04-2265418c2e48

#### Sigstore support for in-toto-jenkins

- Description: The [in-toto Jenkins plugin](https://github.com/in-toto/in-toto-jenkins-plugin) allows users to generate metadata in their build pipelines. Currently keys or credentials must be provided to the plugin to sign the metadata, whereas Sigstore offers keyless signing and verification. The addition of Sigstore transport will allow seamless uploading of metadata to Rekor transparency log. This project aims to enhance the Jenkins plugin by adding [Sigstore](https://www.sigstore.dev) support, allowing keyless signing and adding Sigstore transport.
- Expected Outcome: in-toto-jenkins plugins gets support for Sigstore
- Recommended Skills: Java, Jenkins
- Mentor(s):
    - Santiago Torres-Arias (@SantiagoTorres, santiagotorres@purdue.edu)
    - Pradyumna Krishna (@PradyumnaKrishna, git@onpy.in)
- Upstream Issue: https://github.com/in-toto/in-toto-jenkins-plugin/issues/6
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/fd34fe37-e736-47bb-b0d5-54a2a0d9875a

### Jaeger

#### Jaeger-V2 Observability and Healthchecks

- Description: Jaeger is a distributed tracing platform. Jaeger V2 is a major new version where we rebase all Jaeger backend components (agent, collector, ingester, and query) on top of the OpenTelemetry Collector. (1) Currently jaeger-v2 components are initialized without observability clients. We need to instantiate appropriate logging, tracing, and metrics clients and pass them to the components. The existing code uses internal metrics API, which needs to be bridged to OTEL metrics to minimize code changes. (2) Jaeger-v1 components can report their readiness using an internal health check API that is connected to the healthcheck endpoint on the admin port. We need to implement similar capability in Jaeger-v2.
- Expected Outcome: Achieve parity in observability of jaeger-v2 compared to jaeger-v1
- Recommended Skills: Go, scripting, CI/CD
- Mentor(s):
    - Yuri Shkuro (@yurishkuro, github@ysh.us)
    - Jonah Kowall (@jkowall, jkowall@kowall.net)
    - Yash Sharma (yashrsharma44@meta.com)
- Upstream Issue: https://github.com/jaegertracing/jaeger/issues/5240
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/bd752f55-9080-4826-af09-ad86d3614ab2

#### Jaeger-V2 Service Performance Monitoring

- Description: Jaeger is a distributed tracing platform. Jaeger V2 is a major new version where we rebase all Jaeger backend components (agent, collector, ingester, and query) on top of the OpenTelemetry Collector. Jaeger-v1 implements a functionality known as [SPM](https://www.jaegertracing.io/docs/latest/spm/), but it requires a separately running OpenTelemetry Collector to produce metrics out of spans using [SpanMetrics Connector](https://pkg.go.dev/github.com/open-telemetry/opentelemetry-collector-contrib/connector/spanmetricsconnector#section-readme). Since Jaeger-v2 is built on top of OTEL Collector, we can run SpanMetrics Connector directly in the Jaeger binary and simplify the setup for the users.
- Expected Outcome: Achieve parity in SPM of jaeger-v2 compared to jaeger-v1. Implement integration tests. Update documentation accordingly.
    - Extra credit: implement metrics reader directly on top of Elasticsearch/Opensearch and bypass the need for Prometheus.
- Recommended Skills: Go, scripting, CI/CD
- Mentor(s):
    - Yuri Shkuro (@yurishkuro, github@ysh.us)
    - Jonah Kowall (@jkowall, jkowall@kowall.net)
    - Yash Sharma (yashrsharma44@meta.com)
- Upstream Issue: https://github.com/jaegertracing/jaeger/issues/5240
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/574c4759-09fa-468d-9cfd-4fbb0fb98c09

#### Jaeger-V2 Kafka-based architecture

- Description: Jaeger is a distributed tracing platform. Jaeger V2 is a major new version where we rebase all Jaeger backend components (agent, collector, ingester, and query) on top of the OpenTelemetry Collector. The goal is to implement a deployment mode (supported in Jaeger-v1) that uses Kafka as an intermediate buffer for spans between collector and ingester. It should use the latest version of ibm/sarama driver ([related issue](https://github.com/jaegertracing/jaeger/issues/4591)) and support both original Jaeger formats as well as OpenTelemetry OTLP. It may be possible to utilize the Kafka exporter/receiver from OTEL contrib.
- Expected Outcome: Achieve parity for Kafka-based deployment jaeger-v2 compared to jaeger-v1, including internal observability. Implement integration tests. Update documentation accordingly.
- Recommended Skills: Go, scripting, CI/CD
- Mentor(s):
    - Yuri Shkuro (@yurishkuro, github@ysh.us)
    - Jonah Kowall (@jkowall, jkowall@kowall.net)
    - Yash Sharma (yashrsharma44@meta.com)
- Upstream Issue: https://github.com/jaegertracing/jaeger/issues/5240
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/6c6181c6-030a-4053-af29-18f09e5e2c4f

### Karmada

#### Certificate Lifecycle Management

- Description: The Karmada Certificate Lifecycle Management project addresses user challenges in certificate management, focusing on mitigating service disruptions and security risks due to expirations. Key goals include implementing a feature for real-time monitoring of certificates with advance notification for upcoming expirations; creating a comprehensive manual for manual replacement with best practices and visuals; allowing configurable certificate validity during deployment via CLI, Helm charts, and Operator; and designing an automated certificate rotation system to streamline certificate maintenance and ensure continuous security across Karmada environments.
- Expected Outcome: Certificate Visibility Tool/Feature, Manual Certificate Replacement Guide, Updated Installation Tools with Customizable Certificate Validity, and Automated Certificate Rotation Solution Design or Integration
- Recommended Skills: Golang, Kubernetes Admin, certificate management, Helm.
- Mentor(s):
    - Hongcai Ren (@RainbowMango, qdurenhongcai@gmail.com)
    - Zhen Chang (@XiShanYongYe-Chang, changzhen5@huawei.com)
- Upstream Issue: https://github.com/karmada-io/community/issues/69
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9120164b-feef-4a5a-bd2a-d9ac42bb8d4a

### KCL

#### KCL Package Management Dependencies Sparse Checkout

- Description: `kpm` is a package management tool for KCL. When the scale of KCL project becomes larger and larger, and the external packages that KCL project relies on become more and more, `kpm` will become slow due to the need to download a large number of third-party dependencies. `kpm` needs to support `Sparse-Checkout`, which means downloading specific dependencies as needed rather than all of them, to improve the performance of the kpm.
- Expected Outcome: When kpm requests dependencies, it can request specific content based on the actual use of the required dependencies, but not all of them.
- Recommended Skills: golang, rust
- Mentor(s):
    - Zhe Zong (@zong-zhe, zongzhe1024@163.com)
    - Pengfei Xu (@Peefy, xpf6677@gmail.com)
- Upstream Issue (URL): https://github.com/kcl-lang/kpm/issues/304
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/09391266-0de5-426b-9e11-ceb4c28202ef

#### Optimization of KCL LSP prompt information

- Description: Optimize KCL LSP(language server protocol) prompt information, including the implementation of type inlayhint and optimization of hover content rendering. Currently, KCL’s hover content is in plain text format and needs to be rendered into a more beautiful style.
- Expected Outcome: Added type inlayhint in KCL IDE and optimize hover content render.
- Recommended Skills: rust, LSP
- Mentor(s):
    - Pengfei Xu (@Peefy, xpf6677@gmail.com)
    - Zheng Zhang (@He1pa, he1pa404@gmail.com)
- Upstream Issue (URL): https://github.com/kcl-lang/kcl/issues/1244
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/6d85e491-332b-4667-9b57-6ec052310494

#### Supports tree-sitter for KCL

- Description: Tree-sitter is a parser generator tool and an incremental parsing library. In order to support more features of the IDE, we need a more complete syntax tree, and for easy integration with the community, we intend to use tree-sitter to build a more complete parser system for KCL.

- Expected Outcome: Supports all of the current KCL syntax, which can pass all test cases.
- Recommended Skills: rust, LSP
- Mentor(s):
    - Zheng Zhang (@He1pa, he1pa404@gmail.com)
    - Zhe Zong (@zong-zhe, zongzhe1024@163.com)
- Upstream Issue (URL): https://github.com/kcl-lang/tree-sitter-kcl/issues/2
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/47661e9d-d390-45d8-b05e-0fb3a30612f4

### Knative

#### Improve Knative Eventing Onboarding

- Description:
  Onboarding new end users into a sophisticated system like Knative Eventing presents significant challenges, especially as it involves understanding not only the operational components but also a distinct architectural style - event driven architecture (EDA). These issues are also seen in the current documentation which is often too technical and not geared towards practical guidance.  This project seeks to perform a thorough investigation into the barriers that prevent smooth user onboarding and sustained engagement. By identifying these obstacles and developing clearer, more actionable onboarding materials, we aim to enhance the ease of entry and ongoing use of Knative Eventing for all users.

- Expected Outcome:
1. Produce a detailed report based on user research that outlines the current onboarding experience for new users of Knative Eventing. This report will highlight key barriers and challenges in the documentation and setup process, and recommend actionable improvements to make the onboarding process more user-friendly and less technically daunting.

2. Implement the proposed changes within the Knative community by developing comprehensive onboarding materials and enhancing existing documentation to better support new users.

- Recommended Skills: User Research, Communication, Technical Writing, Content Design

- Mentor(s):
    - Leo Li (@Leo6Leo,leoli@redhat.com)
    - Mariana Mejia (@mmejia02, mariana.mejia@ocadu.ca )

- Upstream Issue:
  https://github.com/knative/ux/issues/130
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1da7e3d2-b170-4236-a2c6-0fa4b0e792e3

#### Knative - applying pre-prepared website design

- Description: Current design of the Knative website (https://knative.dev) does not look modern and contains inconsistent style. Knative UX working group has prepared a new design for the website. We would like to get this design implemented on the website. We also want to ensure with this implementation that the figures in the website include alt text descriptions. We are not looking for full WCAG compliance though.Also, currently the website is not really responsive and doesn’t look good on a mobile device. The group also has a design for the mobile. Finally we have many diagrams on the website that have different styles. We would like to have these diagrams more cohesive. This part is an extended goal though.

- Expected Outcome: New design applied to website; website is made responsive; diagrams look and feel more cohesive.

- Recommended Skills: HTML, CSS, Markdown, SVG, Material for Mkdocs, Figma

- Mentor(s):
    - Ali Ok (@aliok, aliok@redhat.com)
    - Calum Murray (@cali0707, cmurray@redhat.com)
    - Zainab Husain (@zainabhusain227, zainabhusain227@gmail.com)

- Upstream Issue: https://github.com/knative/ux/issues/137
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e18d5c08-312d-4fc1-884c-47c676c12c87

### KubeArmor

#### Improve System Test Coverage and Pratices for KubeArmor

- Description: KubeArmor supports securing many environments ranging from Kubernetes, unorchestrated containers, bare metal and virtual machines. Our testing matrix however doesn't cover many of these completely. In this project, we plan to improve this coverage by introducing automated testing of some of these environments and imrove the scenarios covered in some existing ones. These tests would be written using the Ginkgo framework and automated via GitHub workflows. The matrix we'll target can be found in the upstream issue.
- Expected Outcome: Improved test coverage; Standards for writing tests for KubeArmor; Stabilization of KubeArmor
- Recommended Skills: Go, Scripting, Kubernetes, CI/CD (GitHub Actions)
- Mentor(s):
    - Barun Acharya (@daemon1024, barun1024@gmail.com)
    - Rudraksh Pareek (@DelusionalOptimist, rudrakshpareek3601@gmail.com)
    - Anurag Kumar (@kranurag7, kranurag7@linux.com)
    - Prashant Mishra (@primalpimmy, prashant20.pm@gmail.com)
- Upstream Issue: https://github.com/kubearmor/KubeArmor/issues/1749
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a6a22ae5-856d-472f-9a11-17a2375b86ba

### KubeEdge

#### Iterating Enhancement for KubeEdge Dashboard

- Description: Based on the previous release of KubeEdge, a version of the dashboard has been implemented. With the iterative updates of the backend API, the current dashboard may have several issues. In this project, we aim to iterate and update the dashboard to ensure its compatibility with the latest version of KubeEdge. Additionally, we want to refactor the dashboard using more mainstream frameworks such as Material and optimize the user experience of the dashboard.
- Expected Outcome: new release Dashboard which supports new KubeEgde APIs.
- Recommended Skills: KubeEdge, Front-end, nodejs
- Mentor(s):
    - Hongbing Zhang (@HongbingZhang, hongbing.zhang@daocloud.io)
    - Shelley Bao (@Shelley-BaoYue, baoyue2@huawei.com)
- Upstream Issue: https://github.com/kubeedge/dashboard/issues/22
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/174db042-047a-4036-a523-1598fa386325

#### Router Manager Support HA

- Description: Users need to communicate between the cloud and the edge. For example, the cloud calls the rest interface of the edge service. In this case, the routing management function of KubeEdge can be used. Currently, routing management function of KubeEdge has some problems in the case of multiple CloudCore copies. The main problem is that when there are multiple copies of CloudCore, whether the cloud sends messages to the edge or reports the message to the cloud, it is not known which CloudCore is sent to it for processing, and there is confusion in message management in the cloud. In this project, we hope router manager can be optimized to support multi-CloudCore scenario.
- Expected Outcome: Support using router manager in multi-CloudCore scenario.
- Recommended Skills: Golang, KubeEdge
- Mentor(s):
    - Shelley Bao (@Shelley-BaoYue, baoyue2@huawei.com)
    - jiawei (@JiaweiGithub, jiawei.liu@daocloud.io)
- Upstream Issue: https://github.com/kubeedge/kubeedge/issues/5561
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0cf43d24-c7f3-4792-81c9-bff4aa01a96e

#### KubeEdge test cases enhancement

- Description: Testing is an important task to ensure project stability, security, and other aspects. Since KubeEdge is built on top of native Kubernetes, in this project, we aim to integrate Kubernetes end-to-end (E2E) test cases into KubeEdge's CI. This integration will help ensure the native compatibility and usability of KubeEdge. Additionally, we also aim to improve the unit tests and increase the coverage of integration tests for KubeEdge.
- Expected Outcome: Improve KubeEdge test coverage scenarios
- Recommended Skills: Golang, KubeEdge
- Mentor(s):
    - Fisher Xu (@fisherxu, fisherxu1@gmail.com)
    - Shelley Bao (@Shelley-BaoYue, baoyue2@huawei.com)
- Upstream Issue: https://github.com/kubeedge/kubeedge/issues/5562
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ea773daf-d755-46ec-a80c-1eb5f8bbaf16

#### KubeEdge Documentation Improvement

- Description: Recently, we have updated the directory and structure of the community's official website documentation. We have listed some documentation improvement tasks. In this project, we would like you to have a thorough understanding of KubeEdge and complete these documentation optimization tasks to help users or developers gain a better understanding of and utilize KubeEdge effectively.
- Expected Outcome: Document optimization of setup, usage guide, and developer guide, adding more FAQs, etc.
- Recommended Skills: Kubernetes, KubeEdge, docs
- Mentor(s):
    - zhiying (@zhiyingfang2022, zhiying.fang@daocloud.io)
    - wbc6080 (@wbc6080, wangbincheng4@huawei.com)
- Upstream Issue: https://github.com/kubeedge/website/issues/433
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0add127b-8504-4940-97ac-ad989f58e109

### Kubernetes

#### Update Image Signing to Meet New Infra Requirements

- Description: The process that signs with Sigstore all container images released on community
  infra was designed for a different serving architecture. When the community
  moved to [registry.k8s.io](https://kubernetes.io/blog/2022/11/28/registry-k8s-io-faster-cheaper-ga/)
  and increased 10x the number of registries, the replication of signatures broke
  due to rate limits imposed on the new registries. As part of the project, you will
  be instrumental in implementing the new signing process currently being designed
  by the Kubernetes Release Engineering team. This project will involve heavy rewrites and
  refactoring of parts of the [Image Promoter](https://github.com/kubernetes-sigs/promo-tools),
  the tool that releases community images.
- Expected Outcome: Implementation of the new signing process, ideally we'll fix
  all inconsistent signatures across community registries.
- Recommended Skills: Go programming, strong container architecture and registry
  fundamentals, familiarity with [sigstore](https://www.sigstore.dev/),
  [go-containerregistry](https://github.com/google/go-containerregistry) and infrastructure (GCP & AWS).
- Mentor(s):
    - Adolfo García Veytia (@puerco, puerco@stacklok.com)
    - Jeremy Rickard (@jeremyrickard jrickard@microsoft.com)
    - Marko Mudrinić (@xmudrii, mudrinic.mare@gmail.com)
    - Meha Bhalodiya (@mehabhalodiya, mehabhalodiya@gmail.com)
- Upstream Issues:
    - https://github.com/kubernetes/registry.k8s.io/issues/187
    - https://github.com/kubernetes/release/issues/2962
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/b17b4e21-0c42-4418-91a0-2db3579ffb52

### Kubescape


#### Advanced Kubescape plugin features for VSCode


- Description: Kubescape has a VSCode plugin to facilitate applying configuration fixes that harden Kubernetes infrastrcutture without creating a burden of context switching on engineers tasked with security scanning and implementing their results.
- Expected Outcome: Inetgrating container image scanning capabilities in the Kubescape VSCode plugin and implementing
  Kubescape's ability to apply fixes for configuration issues to YAML files or Helm charts directly within their development environment.

- Recommended Skills: Javascript, some familiarity with the inner workings of the VSCode plugin system.
- Mentor(s):
    - Ben Hirschberg (@slashben, ben@armosec.io)
    - David Wertenteil (@dwertent, dwertent@armosec.io)
- Upstream Issue: [kubescape/Kubescape#1666](https://github.com/kubescape/kubescape/issues/1666)
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/b846284b-76e6-45f1-85da-cd36b9bb489e


#### Backstage plugin that adheres to the new plugin system


- Description: Backstage has become a popular option for an internal portal that provides information for engineers in different capacities. Creating a backstage plugin for Kubescape will ultimately help users achieve their goal of hardening Kubernetes clusters, by being able to view security posture information on Backstage and without context switching.
- Expected Outcome: A Kubescape plugin for Backstage in which users will be able to get information about their security posture and highest risk workloads at a glance within the orgnizational portal.

- Recommended Skills: Typescript, React, some familiarity with new Backstage plugin system.
- Mentor(s):
    - Rotem Refael (@rotemamsa, rotem@armosec.io)
    - Matthias Bertschy (@matthyx, matthiasb@armosec.io)
- Upstream Issue: [kubescape/Kubescape#1667](https://github.com/kubescape/kubescape/issues/1667)
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1e20bf55-4bcf-40ef-afee-d2b73948cd79


### Kubespray

#### Kubernetes SIG Project Kubespray: bug fixes & enhance helm support for add-ons

- Description: Kubespray is a sig project of Kubernetes. It helps deploy a production-ready Kubernetes cluster with Ansible. The project wants maintainers to help fix bugs and enhance the new features, as shown in the following link: https://github.com/kubernetes-sigs/kubespray/issues/5432. The project will start by tackling some 'help wanted' issues related to bug fixes and documentation. This initial involvement will help the mentee understand the Kubespray implementation and pave the way for potential maintainership.
- Expected Outcome: Bug fix and enhancement of the helm support for add-ons.
- Recommended Skills: Ansible, Kubernetes
- Mentor(s):
    - Kay Yan (yankay, <kay.yan@daocloud.io>)
    - Mohamed Zaian (mzaian, <mohamedzaian@gmail.com> )
- Upstream Issue: https://github.com/kubernetes-sigs/kubespray/issues/5432
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/22b0ef86-d390-4ea2-b302-79e819dcbdfc


### KWOK

#### Enhancement of Test Cases

- Description: KWOK (Kubernetes WithOut Kubelet) is a toolkit that enables setting up a cluster of thousands of Nodes in seconds. KWOK is currently being used by a number of projects for testing and performance. It is crucial that KWOK itself behaves consistently. The following tests are currently being considered: Unit Test, E2E Test, Edge Cases.
- Expected Outcome: Improved test coverage for KWOK.
- Recommended Skills: Golang, Kubernetes
- Mentor(s):
    - Shiming Zhang (wzshiming, <wzshiming@hotmail.com>)
    - Zhenghao Zhu (Zhuzhenghao, <zhenghao.zhu@daocloud.io>)
- Upstream Issue: https://github.com/kubernetes-sigs/kwok/issues/1062
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1969ce6c-5468-4842-89a2-06c020bd2ad1

#### Enhancement of Technical Outcomes

- Description: KWOK (Kubernetes WithOut Kubelet) is a toolkit that enables setting up a cluster of thousands of Nodes in seconds. On the KWOK homepage (https://kwok.sigs.k8s.io/), we aim to document the technical outcomes of using KWOK. These outcomes represent the aggregation of some of KWOK's features to achieve a high-level technical goal. Currently, we have the following areas of focus: Chaos Testing, Performance, Simulation, and Scalability.
- Expected Outcome: A section of the KWOK website detailing these technical outcomes.
- Recommended Skills: Kubernetes, Technical Writing
- Mentor(s):
    - Shiming Zhang (wzshiming, <wzshiming@hotmail.com>)
    - Zhenghao Zhu (Zhuzhenghao, <zhenghao.zhu@daocloud.io>)
- Upstream Issue: https://github.com/kubernetes-sigs/kwok/issues/1063
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ef8e7637-2eb6-4672-8f6c-c9f9f0677da0

### LitmusChaos

#### Revamp Litmus Helm Agent, UBI migration of Images

- Description: The Litmus Helm Agent, one of the microservice in Litmus, requires modernization for compatibility with Litmus 3.x API changes. Simultaneously, migrating Litmus Chaos container images to Red Hat's Universal Base Image (UBI) enhances security and compatibility. This project aims to revitalize the Helm Agent and streamline image management, ensuring seamless integration and robust deployment in containerized environments.
- Expected Outcome:
    - Seamless Integration: The Litmus Helm Agent will seamlessly support Litmus 3.x API changes, ensuring compatibility and uninterrupted functionality within the ecosystem.
    - Enhanced Security: Migrating Litmus Chaos container images to Red Hat's Universal Base Image (UBI) will bolster security and compatibility, optimizing deployment in diverse containerized environments.
- Recommended Skills: Golang, Kubernetes
- Mentor(s):
    - Sayan Mondal (@S-ayanide, sayan.mondal@harness.io)
    - Vedant Shrotria (@Jonsy13, vedant.shrotria@harness.io)
    - Raj Babu Das (@imrajdas, mail.rajdas@gmail.com)
- Upstream Issue: https://github.com/litmuschaos/litmus/issues/4634
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/98777e02-dc5b-4380-b6cb-c57603b56e37

### Enhancements in Chaoscenter: GitOps Support for Azure Git, Group Chaos Infra by Environments in Infrastructure Selection Modal

- Description: In this project, we aim to implement GitOps support specifically for Azure Git within Chaoscenter. Additionally, we will enhance the Infrastructure Selection Modal by introducing the capability to group chaos infrastructure based on environments, ensuring better organization and management.
- Expected Outcome:
    - Seamless integration with Azure Git for GitOps workflows.
    - Introduction of environment-based grouping in the Infrastructure Selection Modal.
    - Improved chaos infrastructure management and user experience in Chaoscenter.
- Recommended Skills: Golang, Kubernetes, ReactJS
- Mentors(s):
    - Shubham Chaudhary (@ispeakc0de, shubham.chaudhary@harness.io)
    - Amit Das (@amityt, amit.das@harness.io)
    - Sahil Kumar (@SahilKr24, sahil.kumar@harness.io)
- Upstream Issue: https://github.com/litmuschaos/litmus/issues/4633
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e9bf62a9-a7f6-41bb-be7a-e16b7a35a58a

### Implementing Upgrade Agent Support in Litmus 3.x

- Description: Integrating an upgrade agent into Litmus 3.x streamlines Chaoscenter upgrades, eliminating the need for fresh installations. This feature ensures seamless transitions between versions, especially useful when facing significant changes.
- Expected Outcome:
    - Seamless Upgrades: Integration of the Upgrade Agent ensures smooth transitions during Chaoscenter upgrades, removing the necessity for fresh installations.
    - Simplified Process: Users can upgrade from one version to another without the hassle of reinstallation, saving time and effort.
- Recommended Skills: Golang, Kubernetes
- Mentors(s):
    - Saranya Jena (@Saranya-jena, saranya.jena@harness.io)
    - Sarthak Jain (@SarthakJain26, sarthak.jain@harness.io)
- Upstream Issue: https://github.com/litmuschaos/litmus/issues/4632
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9ac6f8b4-4f76-41d0-b02b-89c79534e619


### Meshery

#### Meshery: Meshery: Project tutorials, design patterns, & publish reference architectures

- Description: Meshery the CNCF’s 10th fastest growing project. As a cloud native manager, Meshery [integrates with 250+ projects](https://meshery.io/integrations) and technologies. For each CNCF project integrated with Meshery, tutorials, sample designs, and deployment patterns with reference architectures need to be created. For the earnest, DevOps-minded intern, this internship represents a vast opportunity to learn, document, and publish tutorials and best practices not only around Meshery, but for any number of the other CNCF projects, too. You will use the [Meshery Playground](https://play.meshery.io)

- Expected Outcome:
  - 25+ new design patterns published in Meshery Catalog and Artifact Hub.
  - 5 new Meshery tutorials published in Meshery Docs.
  - Bonus: Extend one or more of Meshery’s Learning Paths.

- Recommended Skills: written English, Kubernetes, DevOps, and familiarity with any number of other CNCF projects, like Jaeger, Helm, Harbor, Flux, Argo, Flux, Falco, etc., Jekyll, strong organizational skills
- Mentor(s): Yash Sharma (@Yahsharma1911, yashsharma2572@gmail.com), Lee Calcote (@leecalcote, leecalcote@gmail.com)
- Upstream Issue: https://github.com/meshery/meshery/issues/10888
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/7ec5139b-fca8-43db-bafc-bdb2faa58047

#### Meshery: End-to-End Testing with Playwright

- Description: Meshery integrates with many other CNCF projects and technologies. Sustaining those integrations is only possible through automation. End-to-end testing with Playwright, GitHub Workflows, and self-documenting test reports is the means to the end of maintaining a healthy state of each of these [Meshery integrations](https://meshery.io/integrations).

- Expected Outcome:
  - Successful migration of E2E tests from Cypress to the Playwright test library within the Meshery project.
  - Implementation of robust and reliable test cases using Playwright to cover a wide range of Meshery's E2E scenarios.
  - Documentation detailing the migration process, and guidelines for future contributions to maintain test quality.
  - Integration of Playwright test suite into the Meshery CI/CD pipeline to ensure continuous testing and reliability of the platform.
- Recommended Skills: JavaScript, Playwright, GitHub Workflows, Jekyll, Markdown, familiarity with React or Nextjs would be helpful, CI/CD
  - Mentor Name: Aabid Sofi (@aabidsofi19, mailtoaabid01@gmail.com), Lee Calcote (@leecalcote, leecalcote@gmail.com),
- Upstream Issue: https://github.com/meshery/meshery/issues/10890
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/62f4866e-9461-490d-890d-9f221a3941b4

#### Meshery: Support versioning for Meshery designs

- Description: Meshery design is a common practice of both configuring and operating cloud native infrastructure functionality in a single, universal file. We are seeking to enhance Meshery's capabilities by supporting automatic versioning of Meshery designs based on user sessions. This functionality will enable users to track changes made to their designs by individuals, facilitating the ability to rollback changes at any time.

- Expected Outcome:
  - Update Meshery server and pattern engine to support Meshery design versioning.
  - Update UI to allow users to perform actions related to design versioning.
  - Document changes made in pattern engine and server.

- Recommended Skills: Golang, Kubernetes, Meshery, Familiarity with Helm charts and Artifact Hub, familiarity with React, Nextjs would be helpful
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Uzair Shaikh (@muzairs15, muzair.shaikh810@gmail.com)
- Upstream Issue: https://github.com/meshery/meshery/issues/10889
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/8e1ab317-9043-4f29-8b83-9b9ffa2b8b40


### OpenKruise

#### Enhancement for Kruise-Game Dashboard

- Description: The OpenKruiseGame Dashboard is presently in its basic form, and we aim to significantly expand its functionality going forward. We plan to introduce features such as the ability to filter game servers and perform batch updates on them.
- Expected Outcome: new release Dashboard which supports searching, querying, updating objects in batch.
- Recommended Skills: Kubernetes, nodejs, javascript
- Mentor(s):
    - Qiuyang Liu (@chrisliu1995, chrisliu1995@163.com)
    - Zhongwei Liu (@ringtail, zhongwei.lzw@alibaba-inc.com)
- Upstream Issue: https://github.com/openkruise/kruise-game/issues/139
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/3967228d-75a7-4963-b092-f2e92fcd57c8

### Prometheus

#### Prometheus Remote Write Benchmarking Capabilities

- Description: Prometheus remote write allows users to send their metrics to other time series databases. Though the [Prombench tool](https://github.com/prometheus/test-infra/tree/master/prombench) has existed for a number of years, it has never been extended to support performance testing of Remote Write in a realistic production like environment. With the upcomming Remote Write 2.0 changes to both the underlying implementation as well as the wire format, the need for benchmarking of remote write beyond static Go bechmark tests has increased.
- Expected Outcome: Build additional (or extends existing) tooling, similar to Prombench’s [load-generator](https://github.com/prometheus/test-infra/tree/master/tools/load-generator) and [avalanche](https://github.com/prometheus-community/avalanche), to support scenarios under which remote write should be performance tested. For example; allowing gradual increases/decreases in # of active series, sudden spikes in active series, various amounts of latency in the server receiving the remote write data, etc. Time permitted, extend Prombench's test suite to include a set of Remote Write tests that can be run via a new command.
- Recommended Skills: Go, some familiarity with Prometheus or metrics, basic Docker knowledge
- Mentor(s):
    - Callum Styan (@cstyan, callumstyan@gmail.com),
    - Jesús Vázquez (@jesusvazquez, jesusvzpg@gmail.com)
    - Nico Pazos and Alex Greenbank from Grafana also available to help
- Upstream Issue: https://github.com/prometheus/prometheus/issues/13995
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0462446f-aeea-4a19-9bd6-f4241ee5e8f2

#### Mark Out-of-order ingestion as stable

- Description: Prometheus is known by not accepting out-of-order samples during ingestion, but recently (2 years ago) [support was added behind a feature-flag](https://github.com/prometheus/prometheus/pull/11075). Since then, many improvements have been made to out-of-order ingestion and it has become one of the requirements for OTLP ingestion in Prometheus. We want to deliver Prometheus 3.0 in a few months, and that requires marking out-or-order ingestion as a stable feature. In this project we will clean up several smaller issues around out-of-order ingestion, hopefully marking it as stable by the end of the mentorship.
- Recommended Skills: Go, familiarity with Prometheus TSDB.
- Mentor(s):
    - Bryan Boreham (@bboreham, bjboreham@gmail.com)
    - Jesus Vazquez (@jesusvazquez, jesusvzpg@gmail.com)
- Upstream Issue: https://github.com/prometheus/prometheus/issues/12631
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/454caa5a-6fd5-4e27-bde4-7649abf6d8ca


### Service Mesh Performance

#### Service Mesh Performance: Convergence of Network and Graph topologies

- Description: Opens the door to leveraging algorithms in the areas of Centrality, Community Detection, Pathfinding, Topological Link Prediction, etc. Bringing to bear advances made in Machine Learning / AI / recommendation systems, fraud detection could really help to derive meaning and comprehension for future tools. Another example is how ML + graph approaches are used to find and determine the optimal molecular structure of atoms such that desired physical properties are targeted. This approach could be applied to the problem of workload sizing and estimation for service mesh operators and would-be adopters.

- Expected outcome:
  - Use Neo4j's ability to create graph projections, which copy a subgraph to RAM so that algorithms can be efficiently run.
- Recommended Skills: Golang, familiarity with Service Mesh, grpc, docker, kubernetes
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Xin Huang (@gyohuangxin, xin1.huang@intel.com)
- Upstream Issue: https://github.com/service-mesh-performance/service-mesh-performance/issues/422
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/c605139b-8736-477a-835a-c6b45112bee4


### Thanos

#### Compactor: Display TODO plan in UI

- Description: In the Thanos Compactor UI there is visibility of the global block list and loaded block list. But it would be useful to also have a list of planned and currently running compaction groups in order to see what exactly is in progress. This way it would be easier to diagnose what the Thanos Compactor is currently working on, and possibly what is delaying the progress of compactions. This is especially useful if you have large TSDB blocks in S3 buckets that take time to get compacted.
- Expected Outcome: We have an endpoint in Compactor that details compaction plan, and this is also visualized in a Compactor UI page.
- Recommended Skills: Go, React, some familiarity with Prometheus and Thanos
- Mentor(s):
    - Michael Hoffmann (@MichaHoffmann, mhoffm@posteo.de)
    - Saswata Mukherjee (@saswatamcode, saswataminsta@yahoo.com)
- Upstream Issue: https://github.com/thanos-io/thanos/issues/7285
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/05b3d261-f874-4b8c-bd7e-c4fa83c979b4

### TUF

#### Documentation analysis and improvements

- Description:
    - Open source projects need help with their documentation!  The TUF project is a good place to start.  We'd welcome help from others to help here
      and become contributors to other projects / TAGs later in the project period.  The mentee will (with minimal guidance from the CNCF team and TUF project) do a [CNCF analysis](https://github.com/cncf/techdocs/blob/main/docs/analysis/howto.md) for the TUF documentation
- Expected Outcome:
    - Both an improvement of project docs and the development of a new contributor.  A mentee will understand how to do technical writing for an open source project.
- Recommended Skills:
    - Technical writing
    - Basic understanding of security principles
- Mentor(s):
    - Justin Cappos @JustinCappos jcappos@nyu.edu
    - Patrice Chalin @chalin chalin@cncf.io
    - Lukas Pühringer @lukpueh lukas.puehringer@nyu.edu
- Upstream Issues:
    - https://github.com/cncf/techdocs/issues/162
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e35f28f9-f333-47a8-a76a-119567cf10ca

### Vitess

#### Improve the website of our automated-benchmarking tool (migrate to shadcn ui and typescript)

- Description:
    - Vitess uses arewefastyet to automatically benchmark its codebase and ensure no performance regression is introduced. This tool benchmarks Vitess every day, and is used to visualize the results of those benchmarks. It is an important tool in the development cycle of Vitess and is used by its maintainers and adopters.
    - [Arewefastyet' website](https://benchmark.vitess.io) has changed quite a lot over the last year, we want to continue improving it by finishing the migration to TypeScript and by using Shadcn components.
    - Moreover, we want to make the website responsive and have a proper Figma that serves as a reference for current and future contributors.
- Expected Outcome:
    - The mentee is expected to produce a Figma with the design of the website that will be co-authored with the mentor.
    - Re-vamp most of the pages using Shadcn and the design defined with the mentor at the start of the internship period.
    - Add type information for all/most components using TypeScript.
- Recommended Skills:
    - Be skilled in React/Vite/TypeScript.
    - Must know how to simply use Docker and docker-compose.
    - Experience with Figma is a big plus.
    - Experience with Rest APIs and Golang is a plus too.
- Mentor(s):
    - Florent Poinsard @frouioui florent@planetscale.com
    - Frances Thai @notfelineit frances@planetscale.com
- Upstream Issue (URL): https://github.com/vitessio/arewefastyet/issues/525
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/cba8a6c6-4b09-4618-98f7-bf24391e8c9e

#### Community building and engagement

- Description:
    - [Vitess](https://vitess.io) is a CNCF project that has been around for a while. It has a strong community of users and contributors. We want to continue growing this community and make sure that everyone feels welcome and included.
- Expected Outcome:
    - The mentee is expected to evaluate contributor ladder schemes and rewards and produce a recommendation for the Vitess maintainers.
    - Once a decision is made, the mentee is expected to implement the decisions from the maintainer team.
    - The mentee is expected to collect data about Vitess usage from the community and publish the highlights as a blog post.
    - The mentee is expected to review the [Getting Started docs on the Vitess website](https://vitess.io/docs/20.0/get-started/) and enhance them to improve the onboarding experience.
    - The mentee is expected to research and recommend marketing opportunities for Vitess. These could be guest blog posts, podcasts, live streams etc.
- Recommended Skills:
    - Excellent verbal and written communication skills.
    - Prior experience participating in an open source community is a plus.
    - Should be able to install and run Vitess according to the user guides.
    - Website development skills are a plus.
- Mentor(s):
    - Deepthi Sigireddi @deepthi deepthi@planetscale.com
    - Florent Poinsard @frouioui florent@planetscale.com
- Upstream Issue (URL): https://github.com/vitessio/vitess/issues/15895
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1e395914-9adb-4254-a02d-08e6e03e3b93

### WasmEdge

#### Support piper as a new backend of the WASI-NN WasmEdge plugin

- Description: WasmEdge supports PyTorch, TensorFlow Lite, llama.cpp, and more NN backend. Dealing with the text-to-voice is a big thing that we want to achieve. To make it possible, we would like to integrate [piper](https://github.com/rhasspy/piper), A fast, local neural text-to-speech system in C++ as a new [WASI-NN](https://github.com/second-state/wasmedge-wasi-nn) backend.
- Expected Outcome:
    - A new plugin provides a piper [WASI-NN](https://github.com/second-state/wasmedge-wasi-nn) backend
    - A test suite for validating the plugin
    - Documents and examples for explaining how to use the plugin.
- Recommended Skills: C++, Wasm
- Mentor(s):
    - Hung-Ying Tai (@hydai, hydai@secondstate.io)
    - dm4 (@dm4, dm4@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/3381
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/61014739-ac16-4188-bdab-c87c0a502470

#### Enabling LLM fine tuning in the WASI-NN ggml plugin

- Description: WasmEdge is a lightweight and cross-platform runtime for LLM applications. It allows developers to create LLM apps on a Mac or Windows dev machine, compile them to Wasm, and deploy them on Nvidia machines without any changes to the binary app. It achieves application portability across CPUs and GPUs by supporting a W3C standard API called  [WASI-NN](https://github.com/second-state/wasmedge-wasi-nn), which abstracts GPU-related AI functions as high-level APIs. At this stage, however, only inference functions are supported. In this project, we aim to support fine-tuning features in WasmEdge. It will improve the developer experience for WasmEdge-enabled LLM tools. To achieve this, we plan to extend the current WASI-NN spec by adding a set of extra APIs, and then implement them by delegating to corresponding functions in llama.cpp embedded in the WasmEdge GGML plugin.
- Expected Outcome:
    - Use llama2-7b as the base LLM for fine-tuning; the final implementation should handle it correctly.
    - Extend the [WASI-NN](https://github.com/second-state/wasmedge-wasi-nn) spec if needed to support the fine-tuning feature.
    - Implement the fine-tuning functions inside [WASI-NN ggml plugin](https://github.com/WasmEdge/WasmEdge/blob/master/plugins/wasi_nn/ggml.h). They will call the corresponding functions in llama.cpp, as the inference functions do.
    - Implement the LoRA-related functions inside the WASI-NN ggml plugin to load the pre-trained LoRA and verify the fine-tuned model.
    - Documentation, examples, tutorials, and demonstration are required.
- Recommended Skills: C++, WebAssembly, LLM fine-tuning
- Mentor(s):
    - Hung-Ying Tai (@hydai, hydai@secondstate.io)
    - dm4 (@dm4, dm4@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/3209
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/41c5a3df-0b84-4b78-b343-bacfc2a3c4ff

#### Create a search-enabled API server for local LLMs

- Description: WasmEdge is a lightweight inference runtime for AI and LLM applications. The [LlamaEdge project](https://github.com/LlamaEdge) has developed an [OpenAI-compatible API server](https://github.com/LlamaEdge/LlamaEdge/tree/main/api-server) and a [server-side RAG app](https://llamaedge.com/docs/category/server-side-rag) based on WasmEdge. In this project, we aim to use the LlamaEdge components to build a new API server that incorporates real-time Internet search results into LLM answers.
- Expected Outcome: An OpenAI-compatible local LLM API server that uses Google Search for supplemental context
- Recommended Skills:
    - Rust language
    - LlamaEdge
- Mentor(s):
    - Michael Yuan (@juntao, michael@secondstate.io)
    - Hung-Ying Tai (@hydai, hydai@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/3372
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0a4e08a1-3404-46fc-b0d0-5117ec4ec119

#### Finetune LLM models for Rust coding assistance

- Description: WasmEdge is a lightweight inference runtime for AI and LLM applications. We want to build specialized and finetuned models for WasmEdge community. The model should be supported by WasmEdge and its applications should benefit the WasmEdge community.
  In this project, we will build and compare two finetuned model for Rust coding assistance.
    * A code review model. It aims to be a new backend for the [PR review bot](https://github.com/flows-network/github-pr-summary/) we currently use in the community.
    * A QA model. It should be able to answer user questions about the Rust language and provide explanations. Our goal is to provide an alternative to our [Learn Rust](https://flows.network/learn-rust) app.
- Expected Outcome: Two finetuned models based on Llama3-8b for Rust code review and QA.
- Recommended Skills:
    - Rust language
    - ChatGPT and Claude
    - LlamaEdge
    - llama.cpp
- Mentor(s):
    - Michael Yuan (@juntao, michael@secondstate.io)
    - Hung-Ying Tai (@hydai, hydai@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/3371
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/d52d172e-598d-4817-be97-3338d5b96432

-----------------------

# Term 02 - 2024 June - August

Status: Planning

Mentorship duration - three months (12 weeks - full-time schedule)

### Timeline

| activity | date |
| --- | --- |
| project proposals | Monday April 8 - Wed May 8, 2024, 5:00 PM PDT |
| mentee applications open | Monday May 13 - Tues May 28, 5:00 PM PDT |
| application review/admission decisions | Wed May 29 - Tues June 11, 5:00 PM PDT |
| selection notifications | Wed June 12, 5:00 PM PDT |
| Mentorship program begins with the initial work assignments | Monday June 17 (Week 1) |
| Midterm mentee evaluations and first stipend payments | Wednesday July 24 (Week 6) |
| Final mentee evaluations and mentee feedback/blog submission due, second and final stipend payment approvals | Wed Aug 28, 5:00 PM PST (Week 12) |
| Last day of term | Friday Aug 30 |

### Project Instructions

Project maintainers and potential mentors are welcome to propose their mentoring project ideas via submitting a PR to GitHub here https://github.com/cncf/mentoring/blob/main/programs/lfx-mentorship/2024/02-Jun-Aug/project_ideas.md, by April 24, 2024.

### Application instructions

Mentee application instructions can be found on the [Program Guidelines](https://github.com/cncf/mentoring/blob/main/programs/lfx-mentorship/README.md#program-guidelines) page.

---

## Accepted projects

- [Cilium](#cilium)
  - [Cilium Technical Outcomes](#cilium-technical-outcomes)
- [Copacetic](#copacetic)
  - [Add new scenarios to Copa's existing image patching features](#add-new-scenarios-to-copas-existing-image-patching-features)
- [Crossplane](#crossplane)
  - [Make Crossplane Easy - Improving the Developer Experience](#make-crossplane-easy---improving-the-developer-experience)
- [Harbor](#harbor)
  - [Harbor CLI](#harbor-cli)
  - [Harbor Satellite](#harbor-satellite)
- [in-toto](#in-toto)
  - [Add GUAC support](#add-guac-support)
  - [Documentation Boost!](#documentation-boost)
  - [Sigstore support for in-toto-jenkins](#sigstore-support-for-in-toto-jenkins)
- [Jaeger](#jaeger)
  - [Jaeger-V2 Observability and Healthchecks](#jaeger-v2-observability-and-healthchecks)
  - [Jaeger-V2 Service Performance Monitoring](#jaeger-v2-service-performance-monitoring)
  - [Jaeger-V2 Kafka-based architecture](#jaeger-v2-kafka-based-architecture)
- [Karmada](#karmada)
  - [Certificate Lifecycle Management](#certificate-lifecycle-management)
- [KCL](#kcl)
  - [KCL Package Management Dependencies Sparse Checkout](#kcl-package-management-dependencies-sparse-checkout)
  - [Optimization of KCL LSP prompt information](#optimization-of-kcl-lsp-prompt-information)
  - [Supports tree-sitter for KCL](#supports-tree-sitter-for-kcl)
- [Knative](#knative)
  - [Improve Knative Eventing Onboarding](#improve-knative-eventing-onboarding)
  - [Knative - applying pre-prepared website design](#knative---applying-pre-prepared-website-design)
- [KubeArmor](#kubearmor)
  - [Improve System Test Coverage and Pratices for KubeArmor](#improve-system-test-coverage-and-pratices-for-kubearmor)
- [KubeEdge](#kubeedge)
  - [Iterating Enhancement for KubeEdge Dashboard](#iterating-enhancement-for-kubeedge-dashboard)
  - [Router Manager Support HA](#router-manager-support-ha)
  - [KubeEdge test cases enhancement](#kubeedge-test-cases-enhancement)
  - [KubeEdge Documentation Improvement](#kubeedge-documentation-improvement)
- [Kubernetes](#kubernetes)
  - [Update Image Signing to Meet New Infra Requirements](#update-image-signing-to-meet-new-infra-requirements)
- [Kubescape](#kubescape)
  - [Advanced Kubescape plugin features for VSCode](#advanced-kubescape-plugin-features-for-vscode)
  - [Backstage plugin that adheres to the new plugin system](#backstage-plugin-that-adheres-to-the-new-plugin-system)
- [KWOK](#kwok)
  - [Enhancement of Test Cases](#enhancement-of-test-cases)
  - [Enhancement of Technical Outcomes](#enhancement-of-technical-outcomes)
- [LitmusChaos](#litmuschaos)
  - [Revamp Litmus Helm Agent, UBI migration of Images](#revamp-litmus-helm-agent-ubi-migration-of-images)
  - [Enhancements in Chaoscenter: GitOps Support for Azure Git, Group Chaos Infra by Environments in Infrastructure Selection Modal](#enhancements-in-chaoscenter-gitops-support-for-azure-git-group-chaos-infra-by-environments-in-infrastructure-selection-modal)
  - [Implementing Upgrade Agent Support in Litmus 3.x](#implementing-upgrade-agent-support-in-litmus-3x)
- [OpenKruise](#openkruise)
  - [Enhancement for Kruise-Game Dashboard](#enhancement-for-kruise-game-dashboard)
- [Prometheus](#prometheus)
  - [Prometheus Remote Write Benchmarking Capabilities](#prometheus-remote-write-benchmarking-capabilities)
  - [Mark Out-of-order ingestion as stable](#mark-out-of-order-ingestion-as-stable)
- [Thanos](#thanos)
  - [Compactor: Display TODO plan in UI](#compactor-display-todo-plan-in-ui)
- [TUF](#tuf)
  - [Documentation analysis and improvements](#documentation-analysis-and-improvements)
- [Vitess](#vitess)
  - [Improve the website of our automated-benchmarking tool (migrate to shadcn ui and typescript)](#improve-the-website-of-our-automated-benchmarking-tool-migrate-to-shadcn-ui-and-typescript)
  - [Community building and engagement](#community-building-and-engagement)
- [WasmEdge](#wasmedge)
  - [Support piper as a new backend of the WASI-NN WasmEdge plugin](#support-piper-as-a-new-backend-of-the-wasi-nn-wasmedge-plugin)
  - [Enabling LLM fine tuning in the WASI-NN ggml plugin](#enabling-llm-fine-tuning-in-the-wasi-nn-ggml-plugin)
  - [Create a search-enabled API server for local LLMs](#create-a-search-enabled-api-server-for-local-llms)
  - [Finetune LLM models for Rust coding assistance](#finetune-llm-models-for-rust-coding-assistance)

### Cilium

#### Cilium Technical Outcomes

- Description: On the Cilium [homepage](https://cilium.io), we want to document technical outcomes from using Cilium. Think of these technical outcomes as aggregating some of cilium features to achieve a high level technical goal. These are the current ones we have in mind: Zero Trust Networking, Network Automation, Distributed Firewalling, Cost and Carbon Savings, Multi-cloud Connectivity.
- Expected Outcome: A section of the Cilium website detailing these technical outcomes. This section on the website can include any supporting materials from the Cilium community i.e blogs, videos, talks, illustrations, etc.
- Recommended Skills: Technical Writing, some basic working knowlegde of Cilium or the willingness to quickly ramp up, Kubernetes, general familiarity with the cloud native ecosystem, basic React.js(the cilium webiste is built with Gatsby).
- Mentor(s):
    - Paul Arah(paularah, <paul.arah@isovalent.com>)
    - Bill Mulligan(xmulligan, <bill.mulligan@isovalent.com>)
- Upstream Issue: <https://github.com/cilium/cilium.io/issues/492>
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9ab5c6dc-4735-4dfb-99c0-d00e86aeae60


### CNCF TAG Network

#### Mapping CNCF Landscape one Relationship-at-a-time

- Description: While the OpenAPI specifications for Kubernetes offer a taxonomy, integrating a graph data model with formalized ontologies unlocks a multitude of capabilities. Among these, enabling inferencing necessary for natural language processing stands out as a straightforward application. This, in turn, facilitates the possibility of a human-centric query/response interaction. Importantly, advancing to a knowledge semantic graph from a connected systems' graph data model opens the door to building more sophisticated systems.

- Expected Outcome:
  - Identifying new technologies from CNCF landscape and creating new YAML-formatted definitions of one or more relationships.
  - Documentation of each relationship - per component.
  - Development of new types of genealogies - new types of ways in which resources relate to one another and how these relationships might be visualized.

- Recommended Skills: Familiarity with Helm charts and Artifact Hub, basic familiarity with Kubernetes, and familiarity with CNCF different projects would be helpful
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Uzair Shaikh (@muzairs15, muzair.shaikh810@gmail.com)
- Upstream Issue: https://github.com/cncf/tag-network/issues/39
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/bec63054-bc32-4444-b6c5-2b427f527e16

#### Technical Content Creation CNCF Challenges

- Description: On a periodic basis, the CNCF would like to present a public challenge to those that are interested in participating (e.g. “Challenge: Distributed Tracing with Jaeger”).

Your mission in this internship is technical content creation of said challenges through use of markdown, Meshery, and any number of other CNCF projects. Challenges will be created using the Meshery Playground and potentially published in the proposed CNCF Hub. They will be similar too, but slightly different from these [example tutorials](https://docs.meshery.io/guides/tutorials/).

Understand that your challenges will be promoted through CNCF channels, reviewed by various project maintainers, and that each challenger (participant) will receive a certain number of points, depending upon whether or not they successfully complete the challenges that you create and in what timeframe they complete those challenges (the faster, the more points). Your challenges will need to vary in level of difficulty.

- Expected Outcome:
  - 10+ new challenges published in CNCF Hub (and Meshery Catalog and Artifact Hub).
  - Challenges can contain more than one objective. Points are earned for each objective completed.
  - Bonus: Extend one or more of Meshery’s Learning Paths.

- Recommended Skills: written English, Kubernetes, DevOps, and familiarity with any number of other CNCF projects, like Prometheus, CoreDNS, Istio, Jaeger, Helm, Harbor, OPA, Rook, SPIFEE, Flux, Argo, Flux, Falco, etc., Jekyll, strong organizational skills
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Nic Jackson (@nicholasjackson), jackson.nic@gmail.com)
- Upstream Issue: https://github.com/cncf/tag-network/issues/40
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1a620529-f2be-4a6f-8b4d-0562731cb840


### Copacetic

#### Add new scenarios to Copa's existing image patching features
- Description: This project will focus on a series of initial TODOs that are present in the codebase and that have been recently added as issues in GitHub. The issues range from adding custom image repos, to handling custom configuration at the package and system level.
- Expected Outcome: Added features as suggested by current TODOs in code to enhance Copacetic user experience and features.
- Recommended Skills: Go, Linux Package Management tools, container images, distroless images, Trivy, knowledge of Copacetic codebase would be useful.
- Mentors(s):
    - Ashna Mehrotra (@ashnamehrotra, asmehrotra@microsoft.com)
    - Robert Kielty (@RobertKielty, robert.kielty@cncf.io)
- Upstream Issues: https://github.com/project-copacetic/copacetic/issues/611
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/955a5956-de58-44ea-8760-d606feb82165

### Crossplane

#### Make Crossplane Easy - Improving the Developer Experience

- Description: Crossplane is in use at scale in many production environments, but we get often get feedback that there are many obstacles to learn Crossplane and get to a successfully built production-ready control plane. A major reason for this learning curve is the lack of supporting tools and experiences on top of core Crossplane that could accelerate the community’s attempts to successfully build their platforms. These higher level experiences have recently become a focus for the project and we want to keep delivering awesome experiences that make Crossplane easier to use.
- Expected Outcome: We expect the mentee to design and code multiple improvements to the Crossplane tooling from the issue linked below. We will start with smaller scoped issues to ramp up and then focus on a bigger deliverable such as adding [validation for Crossplane Functions](https://github.com/crossplane/crossplane/issues/5094). By the end of the term, the mentee will have multiple code PRs merged into the Crossplane codebase.
- Recommended Skills: Go, Kubernetes, Crossplane, CLI tools, passion for DevEx
- Mentor(s):
    - Jared Watts (primary) (@jbw976, jbw976@gmail.com)
    - Ezgi Demirel (secondary) (@ezgidemirel, ezgi@upbound.io)
- Upstream Issue: https://github.com/crossplane/crossplane/issues/3957
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/87e81040-eb5e-4628-babd-820ef23cd261

### Harbor

#### Harbor CLI

- Description: Harbor is a popular and widely adopted container registry. We have developed an initial CLI (https://github.com/goharbor/harbor-cli) that we would like to extend and implement additional functionality, and common workflows that are currently only present in the Web UI. We are seeking a Golangs experienced manatee who can work on the project independently.
- Expected Outcome: Working Golang Harbor CLI which can be used in the CI/CD implementations that compliment the Web UI covering the typical workflows of Harbor administrators and users. Familiarity with Golang library spf13/cobra and REST/Open API. Well-documented CLI that users love to use, and with the corresponding architectural diagrams under the Harbor. Working CI/CD with GitHub actions that create multi architecture binaries and containers.
- Recommended Skills: Golang, spf13/cobra
- Mentor(s):
    - Vadim Bauer (@vad1mo, vb@container-registry.com)
    - Yan Wang (@wy65701436, yan-yw.wang@broadcom.com)
    - Orlin Vasilev (@OrlinVasilev, orlin@orlix.org)
- Upstream Issue: https://github.com/goharbor/harbor-cli/issues/41
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a8a71ad1-4a1b-422e-9928-01c153ac2daf

#### Harbor Satellite

- Description: In recent years, containers have extended beyond their traditional cloud environments, becoming increasingly prevalent in remote and edge computing contexts. These environments often lack reliable internet connectivity, posing significant challenges in managing and running containerized applications due to difficulties in fetching container images. To address this, the project aims to decentralize container registries, making them more accessible to edge devices. The need for a satellite that can operate independently, store images on disk, and run indefinitely with stored data is crucial for maintaining operations in areas with limited or no internet connectivity.
  Harbor Satellite aims to bring Harbor container registries to edge locations, ensuring consistent, available, and integrity-checked images for edge computing environments. This proposal outlines the development of a stateful, standalone satellite that can function as a primary registry for edge locations and as a fallback option if the central Harbor registry is unavailable.
- Expected Outcome:
  The goal is to extend the proof of concept
  and demonstrate that such a solution practically works.
  Candidates should be able understanding and implementing the [image](https://github.com/opencontainers/image-spec) and [distribution spec](https://github.com/opencontainers/distribution-spec)
  to replicate images from a central registry to a registry on the edge location.
- Recommended Skills: Golang, Container, Image-spec, Distribution-spec
- Mentor(s):
    - Vadim Bauer (@vad1mo, vb@container-registry.com)
    - Yan Wang (@wy65701436, yan-yw.wang@broadcom.com)
    - Orlin Vasilev (@OrlinVasilev, orlin@orlix.org)
- Upstream Issue: https://github.com/goharbor/harbor/issues/20404
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/93a94aec-8026-4587-b840-52c96ab25020

### in-toto

### Add GUAC support

- Description: The project aims to integrate Graph for Understanding Artifact Composition (GUAC) with in-toto, a framework safeguarding software supply chain integrity. [Graph for Understanding Artifact Composition (GUAC)](https://guac.sh/) aggregates software security metadata into a high fidelity graph database—normalizing entity identities and mapping standard relationships between them. This project seeks to extend in-toto's capabilities by incorporating GUAC, enabling users to query GUAC with Package URLs (purls) and retrieve pertinent attestations.
- Expected Outcome: Adds functionality to query GUAC, retrieve and parse relevant attestations for the specified artifact.
- Recommended Skills: Go, Python
- Mentor(s):
    - Santiago Torres-Arias (@SantiagoTorres, santiagotorres@purdue.edu)
    - Pradyumna Krishna (@PradyumnaKrishna, git@onpy.in)
- Upstream Issue: https://github.com/in-toto/attestation-verifier/issues/29
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/abfb7093-b057-40da-8be1-c67bd8839698

#### Documentation Boost!

- Description:
    - Help contributors get started with improving the documentation of CNCF projects and TAGs.  To start, we'd like mentees to help to
      improve both the documentation of a project, and also encourage them to contribute to other projects.  So, view the issues as a starting
      point to help start your career in open source.
- Expected Outcome:
    - Develop effective documentation for CNCF projects.  As a start, the CNCF project in-toto has a fairly clear set of requirements for what
      documentation changes are needed.
- Recommended Skills:
    - Technical writing
    - Basic understanding of cloud native projects (or a desire to learn!)
- Mentor(s):
    - Justin Cappos @JustinCappos jcappos@nyu.edu
    - Patrice Chalin @chalin chalin@cncf.io
    - Lukas Pühringer @lukpueh lukas.puehringer@nyu.edu
- Upstream Issues:
    -   https://github.com/in-toto/docs/issues/85
    -   https://github.com/in-toto/docs/issues/90
    -   https://github.com/in-toto/docs/issues/91
    -   https://github.com/in-toto/docs/issues/92
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/34314eb1-0fc3-4802-ab04-2265418c2e48

#### Sigstore support for in-toto-jenkins

- Description: The [in-toto Jenkins plugin](https://github.com/in-toto/in-toto-jenkins-plugin) allows users to generate metadata in their build pipelines. Currently keys or credentials must be provided to the plugin to sign the metadata, whereas Sigstore offers keyless signing and verification. The addition of Sigstore transport will allow seamless uploading of metadata to Rekor transparency log. This project aims to enhance the Jenkins plugin by adding [Sigstore](https://www.sigstore.dev) support, allowing keyless signing and adding Sigstore transport.
- Expected Outcome: in-toto-jenkins plugins gets support for Sigstore
- Recommended Skills: Java, Jenkins
- Mentor(s):
    - Santiago Torres-Arias (@SantiagoTorres, santiagotorres@purdue.edu)
    - Pradyumna Krishna (@PradyumnaKrishna, git@onpy.in)
- Upstream Issue: https://github.com/in-toto/in-toto-jenkins-plugin/issues/6
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/fd34fe37-e736-47bb-b0d5-54a2a0d9875a

### Jaeger

#### Jaeger-V2 Observability and Healthchecks

- Description: Jaeger is a distributed tracing platform. Jaeger V2 is a major new version where we rebase all Jaeger backend components (agent, collector, ingester, and query) on top of the OpenTelemetry Collector. (1) Currently jaeger-v2 components are initialized without observability clients. We need to instantiate appropriate logging, tracing, and metrics clients and pass them to the components. The existing code uses internal metrics API, which needs to be bridged to OTEL metrics to minimize code changes. (2) Jaeger-v1 components can report their readiness using an internal health check API that is connected to the healthcheck endpoint on the admin port. We need to implement similar capability in Jaeger-v2.
- Expected Outcome: Achieve parity in observability of jaeger-v2 compared to jaeger-v1
- Recommended Skills: Go, scripting, CI/CD
- Mentor(s):
    - Yuri Shkuro (@yurishkuro, github@ysh.us)
    - Jonah Kowall (@jkowall, jkowall@kowall.net)
    - Yash Sharma (yashrsharma44@meta.com)
- Upstream Issue: https://github.com/jaegertracing/jaeger/issues/5240
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/bd752f55-9080-4826-af09-ad86d3614ab2

#### Jaeger-V2 Service Performance Monitoring

- Description: Jaeger is a distributed tracing platform. Jaeger V2 is a major new version where we rebase all Jaeger backend components (agent, collector, ingester, and query) on top of the OpenTelemetry Collector. Jaeger-v1 implements a functionality known as [SPM](https://www.jaegertracing.io/docs/latest/spm/), but it requires a separately running OpenTelemetry Collector to produce metrics out of spans using [SpanMetrics Connector](https://pkg.go.dev/github.com/open-telemetry/opentelemetry-collector-contrib/connector/spanmetricsconnector#section-readme). Since Jaeger-v2 is built on top of OTEL Collector, we can run SpanMetrics Connector directly in the Jaeger binary and simplify the setup for the users.
- Expected Outcome: Achieve parity in SPM of jaeger-v2 compared to jaeger-v1. Implement integration tests. Update documentation accordingly.
    - Extra credit: implement metrics reader directly on top of Elasticsearch/Opensearch and bypass the need for Prometheus.
- Recommended Skills: Go, scripting, CI/CD
- Mentor(s):
    - Yuri Shkuro (@yurishkuro, github@ysh.us)
    - Jonah Kowall (@jkowall, jkowall@kowall.net)
    - Yash Sharma (yashrsharma44@meta.com)
- Upstream Issue: https://github.com/jaegertracing/jaeger/issues/5240
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/574c4759-09fa-468d-9cfd-4fbb0fb98c09

#### Jaeger-V2 Kafka-based architecture

- Description: Jaeger is a distributed tracing platform. Jaeger V2 is a major new version where we rebase all Jaeger backend components (agent, collector, ingester, and query) on top of the OpenTelemetry Collector. The goal is to implement a deployment mode (supported in Jaeger-v1) that uses Kafka as an intermediate buffer for spans between collector and ingester. It should use the latest version of ibm/sarama driver ([related issue](https://github.com/jaegertracing/jaeger/issues/4591)) and support both original Jaeger formats as well as OpenTelemetry OTLP. It may be possible to utilize the Kafka exporter/receiver from OTEL contrib.
- Expected Outcome: Achieve parity for Kafka-based deployment jaeger-v2 compared to jaeger-v1, including internal observability. Implement integration tests. Update documentation accordingly.
- Recommended Skills: Go, scripting, CI/CD
- Mentor(s):
    - Yuri Shkuro (@yurishkuro, github@ysh.us)
    - Jonah Kowall (@jkowall, jkowall@kowall.net)
    - Yash Sharma (yashrsharma44@meta.com)
- Upstream Issue: https://github.com/jaegertracing/jaeger/issues/5240
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/6c6181c6-030a-4053-af29-18f09e5e2c4f

### Karmada

#### Certificate Lifecycle Management

- Description: The Karmada Certificate Lifecycle Management project addresses user challenges in certificate management, focusing on mitigating service disruptions and security risks due to expirations. Key goals include implementing a feature for real-time monitoring of certificates with advance notification for upcoming expirations; creating a comprehensive manual for manual replacement with best practices and visuals; allowing configurable certificate validity during deployment via CLI, Helm charts, and Operator; and designing an automated certificate rotation system to streamline certificate maintenance and ensure continuous security across Karmada environments.
- Expected Outcome: Certificate Visibility Tool/Feature, Manual Certificate Replacement Guide, Updated Installation Tools with Customizable Certificate Validity, and Automated Certificate Rotation Solution Design or Integration
- Recommended Skills: Golang, Kubernetes Admin, certificate management, Helm.
- Mentor(s):
    - Hongcai Ren (@RainbowMango, qdurenhongcai@gmail.com)
    - Zhen Chang (@XiShanYongYe-Chang, changzhen5@huawei.com)
- Upstream Issue: https://github.com/karmada-io/community/issues/69
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9120164b-feef-4a5a-bd2a-d9ac42bb8d4a

### KCL

#### KCL Package Management Dependencies Sparse Checkout

- Description: `kpm` is a package management tool for KCL. When the scale of KCL project becomes larger and larger, and the external packages that KCL project relies on become more and more, `kpm` will become slow due to the need to download a large number of third-party dependencies. `kpm` needs to support `Sparse-Checkout`, which means downloading specific dependencies as needed rather than all of them, to improve the performance of the kpm.
- Expected Outcome: When kpm requests dependencies, it can request specific content based on the actual use of the required dependencies, but not all of them.
- Recommended Skills: golang, rust
- Mentor(s):
    - Zhe Zong (@zong-zhe, zongzhe1024@163.com)
    - Pengfei Xu (@Peefy, xpf6677@gmail.com)
- Upstream Issue (URL): https://github.com/kcl-lang/kpm/issues/304
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/09391266-0de5-426b-9e11-ceb4c28202ef

#### Optimization of KCL LSP prompt information

- Description: Optimize KCL LSP(language server protocol) prompt information, including the implementation of type inlayhint and optimization of hover content rendering. Currently, KCL’s hover content is in plain text format and needs to be rendered into a more beautiful style.
- Expected Outcome: Added type inlayhint in KCL IDE and optimize hover content render.
- Recommended Skills: rust, LSP
- Mentor(s):
    - Pengfei Xu (@Peefy, xpf6677@gmail.com)
    - Zheng Zhang (@He1pa, he1pa404@gmail.com)
- Upstream Issue (URL): https://github.com/kcl-lang/kcl/issues/1244
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/6d85e491-332b-4667-9b57-6ec052310494

#### Supports tree-sitter for KCL

- Description: Tree-sitter is a parser generator tool and an incremental parsing library. In order to support more features of the IDE, we need a more complete syntax tree, and for easy integration with the community, we intend to use tree-sitter to build a more complete parser system for KCL.

- Expected Outcome: Supports all of the current KCL syntax, which can pass all test cases.
- Recommended Skills: rust, LSP
- Mentor(s):
    - Zheng Zhang (@He1pa, he1pa404@gmail.com)
    - Zhe Zong (@zong-zhe, zongzhe1024@163.com)
- Upstream Issue (URL): https://github.com/kcl-lang/tree-sitter-kcl/issues/2
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/47661e9d-d390-45d8-b05e-0fb3a30612f4

### Knative

#### Improve Knative Eventing Onboarding

- Description:
  Onboarding new end users into a sophisticated system like Knative Eventing presents significant challenges, especially as it involves understanding not only the operational components but also a distinct architectural style - event driven architecture (EDA). These issues are also seen in the current documentation which is often too technical and not geared towards practical guidance.  This project seeks to perform a thorough investigation into the barriers that prevent smooth user onboarding and sustained engagement. By identifying these obstacles and developing clearer, more actionable onboarding materials, we aim to enhance the ease of entry and ongoing use of Knative Eventing for all users.

- Expected Outcome:
1. Produce a detailed report based on user research that outlines the current onboarding experience for new users of Knative Eventing. This report will highlight key barriers and challenges in the documentation and setup process, and recommend actionable improvements to make the onboarding process more user-friendly and less technically daunting.

2. Implement the proposed changes within the Knative community by developing comprehensive onboarding materials and enhancing existing documentation to better support new users.

- Recommended Skills: User Research, Communication, Technical Writing, Content Design

- Mentor(s):
    - Leo Li (@Leo6Leo,leoli@redhat.com)
    - Mariana Mejia (@mmejia02, mariana.mejia@ocadu.ca )

- Upstream Issue:
  https://github.com/knative/ux/issues/130
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1da7e3d2-b170-4236-a2c6-0fa4b0e792e3

#### Knative - applying pre-prepared website design

- Description: Current design of the Knative website (https://knative.dev) does not look modern and contains inconsistent style. Knative UX working group has prepared a new design for the website. We would like to get this design implemented on the website. We also want to ensure with this implementation that the figures in the website include alt text descriptions. We are not looking for full WCAG compliance though.Also, currently the website is not really responsive and doesn’t look good on a mobile device. The group also has a design for the mobile. Finally we have many diagrams on the website that have different styles. We would like to have these diagrams more cohesive. This part is an extended goal though.

- Expected Outcome: New design applied to website; website is made responsive; diagrams look and feel more cohesive.

- Recommended Skills: HTML, CSS, Markdown, SVG, Material for Mkdocs, Figma

- Mentor(s):
    - Ali Ok (@aliok, aliok@redhat.com)
    - Calum Murray (@cali0707, cmurray@redhat.com)
    - Zainab Husain (@zainabhusain227, zainabhusain227@gmail.com)

- Upstream Issue: https://github.com/knative/ux/issues/137
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e18d5c08-312d-4fc1-884c-47c676c12c87

### KubeArmor

#### Improve System Test Coverage and Pratices for KubeArmor

- Description: KubeArmor supports securing many environments ranging from Kubernetes, unorchestrated containers, bare metal and virtual machines. Our testing matrix however doesn't cover many of these completely. In this project, we plan to improve this coverage by introducing automated testing of some of these environments and imrove the scenarios covered in some existing ones. These tests would be written using the Ginkgo framework and automated via GitHub workflows. The matrix we'll target can be found in the upstream issue.
- Expected Outcome: Improved test coverage; Standards for writing tests for KubeArmor; Stabilization of KubeArmor
- Recommended Skills: Go, Scripting, Kubernetes, CI/CD (GitHub Actions)
- Mentor(s):
    - Barun Acharya (@daemon1024, barun1024@gmail.com)
    - Rudraksh Pareek (@DelusionalOptimist, rudrakshpareek3601@gmail.com)
    - Anurag Kumar (@kranurag7, kranurag7@linux.com)
    - Prashant Mishra (@primalpimmy, prashant20.pm@gmail.com)
- Upstream Issue: https://github.com/kubearmor/KubeArmor/issues/1749
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a6a22ae5-856d-472f-9a11-17a2375b86ba

### KubeEdge

#### Iterating Enhancement for KubeEdge Dashboard

- Description: Based on the previous release of KubeEdge, a version of the dashboard has been implemented. With the iterative updates of the backend API, the current dashboard may have several issues. In this project, we aim to iterate and update the dashboard to ensure its compatibility with the latest version of KubeEdge. Additionally, we want to refactor the dashboard using more mainstream frameworks such as Material and optimize the user experience of the dashboard.
- Expected Outcome: new release Dashboard which supports new KubeEgde APIs.
- Recommended Skills: KubeEdge, Front-end, nodejs
- Mentor(s):
    - Hongbing Zhang (@HongbingZhang, hongbing.zhang@daocloud.io)
    - Shelley Bao (@Shelley-BaoYue, baoyue2@huawei.com)
- Upstream Issue: https://github.com/kubeedge/dashboard/issues/22
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/174db042-047a-4036-a523-1598fa386325

#### Router Manager Support HA

- Description: Users need to communicate between the cloud and the edge. For example, the cloud calls the rest interface of the edge service. In this case, the routing management function of KubeEdge can be used. Currently, routing management function of KubeEdge has some problems in the case of multiple CloudCore copies. The main problem is that when there are multiple copies of CloudCore, whether the cloud sends messages to the edge or reports the message to the cloud, it is not known which CloudCore is sent to it for processing, and there is confusion in message management in the cloud. In this project, we hope router manager can be optimized to support multi-CloudCore scenario.
- Expected Outcome: Support using router manager in multi-CloudCore scenario.
- Recommended Skills: Golang, KubeEdge
- Mentor(s):
    - Shelley Bao (@Shelley-BaoYue, baoyue2@huawei.com)
    - jiawei (@JiaweiGithub, jiawei.liu@daocloud.io)
- Upstream Issue: https://github.com/kubeedge/kubeedge/issues/5561
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0cf43d24-c7f3-4792-81c9-bff4aa01a96e

#### KubeEdge test cases enhancement

- Description: Testing is an important task to ensure project stability, security, and other aspects. Since KubeEdge is built on top of native Kubernetes, in this project, we aim to integrate Kubernetes end-to-end (E2E) test cases into KubeEdge's CI. This integration will help ensure the native compatibility and usability of KubeEdge. Additionally, we also aim to improve the unit tests and increase the coverage of integration tests for KubeEdge.
- Expected Outcome: Improve KubeEdge test coverage scenarios
- Recommended Skills: Golang, KubeEdge
- Mentor(s):
    - Fisher Xu (@fisherxu, fisherxu1@gmail.com)
    - Shelley Bao (@Shelley-BaoYue, baoyue2@huawei.com)
- Upstream Issue: https://github.com/kubeedge/kubeedge/issues/5562
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ea773daf-d755-46ec-a80c-1eb5f8bbaf16

#### KubeEdge Documentation Improvement

- Description: Recently, we have updated the directory and structure of the community's official website documentation. We have listed some documentation improvement tasks. In this project, we would like you to have a thorough understanding of KubeEdge and complete these documentation optimization tasks to help users or developers gain a better understanding of and utilize KubeEdge effectively.
- Expected Outcome: Document optimization of setup, usage guide, and developer guide, adding more FAQs, etc.
- Recommended Skills: Kubernetes, KubeEdge, docs
- Mentor(s):
    - zhiying (@zhiyingfang2022, zhiying.fang@daocloud.io)
    - wbc6080 (@wbc6080, wangbincheng4@huawei.com)
- Upstream Issue: https://github.com/kubeedge/website/issues/433
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0add127b-8504-4940-97ac-ad989f58e109

### Kubernetes

#### Update Image Signing to Meet New Infra Requirements

- Description: The process that signs with Sigstore all container images released on community
  infra was designed for a different serving architecture. When the community
  moved to [registry.k8s.io](https://kubernetes.io/blog/2022/11/28/registry-k8s-io-faster-cheaper-ga/)
  and increased 10x the number of registries, the replication of signatures broke
  due to rate limits imposed on the new registries. As part of the project, you will
  be instrumental in implementing the new signing process currently being designed
  by the Kubernetes Release Engineering team. This project will involve heavy rewrites and
  refactoring of parts of the [Image Promoter](https://github.com/kubernetes-sigs/promo-tools),
  the tool that releases community images.
- Expected Outcome: Implementation of the new signing process, ideally we'll fix
  all inconsistent signatures across community registries.
- Recommended Skills: Go programming, strong container architecture and registry
  fundamentals, familiarity with [sigstore](https://www.sigstore.dev/),
  [go-containerregistry](https://github.com/google/go-containerregistry) and infrastructure (GCP & AWS).
- Mentor(s):
    - Adolfo García Veytia (@puerco, puerco@stacklok.com)
    - Jeremy Rickard (@jeremyrickard jrickard@microsoft.com)
    - Marko Mudrinić (@xmudrii, mudrinic.mare@gmail.com)
    - Meha Bhalodiya (@mehabhalodiya, mehabhalodiya@gmail.com)
- Upstream Issues:
    - https://github.com/kubernetes/registry.k8s.io/issues/187
    - https://github.com/kubernetes/release/issues/2962
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/b17b4e21-0c42-4418-91a0-2db3579ffb52

### Kubescape


#### Advanced Kubescape plugin features for VSCode


- Description: Kubescape has a VSCode plugin to facilitate applying configuration fixes that harden Kubernetes infrastrcutture without creating a burden of context switching on engineers tasked with security scanning and implementing their results.
- Expected Outcome: Inetgrating container image scanning capabilities in the Kubescape VSCode plugin and implementing
  Kubescape's ability to apply fixes for configuration issues to YAML files or Helm charts directly within their development environment.

- Recommended Skills: Javascript, some familiarity with the inner workings of the VSCode plugin system.
- Mentor(s):
    - Ben Hirschberg (@slashben, ben@armosec.io)
    - David Wertenteil (@dwertent, dwertent@armosec.io)
- Upstream Issue: [kubescape/Kubescape#1666](https://github.com/kubescape/kubescape/issues/1666)
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/b846284b-76e6-45f1-85da-cd36b9bb489e


#### Backstage plugin that adheres to the new plugin system


- Description: Backstage has become a popular option for an internal portal that provides information for engineers in different capacities. Creating a backstage plugin for Kubescape will ultimately help users achieve their goal of hardening Kubernetes clusters, by being able to view security posture information on Backstage and without context switching.
- Expected Outcome: A Kubescape plugin for Backstage in which users will be able to get information about their security posture and highest risk workloads at a glance within the orgnizational portal.

- Recommended Skills: Typescript, React, some familiarity with new Backstage plugin system.
- Mentor(s):
    - Rotem Refael (@rotemamsa, rotem@armosec.io)
    - Matthias Bertschy (@matthyx, matthiasb@armosec.io)
- Upstream Issue: [kubescape/Kubescape#1667](https://github.com/kubescape/kubescape/issues/1667)
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1e20bf55-4bcf-40ef-afee-d2b73948cd79


### Kubespray

#### Kubernetes SIG Project Kubespray: bug fixes & enhance helm support for add-ons

- Description: Kubespray is a sig project of Kubernetes. It helps deploy a production-ready Kubernetes cluster with Ansible. The project wants maintainers to help fix bugs and enhance the new features, as shown in the following link: https://github.com/kubernetes-sigs/kubespray/issues/5432. The project will start by tackling some 'help wanted' issues related to bug fixes and documentation. This initial involvement will help the mentee understand the Kubespray implementation and pave the way for potential maintainership.
- Expected Outcome: Bug fix and enhancement of the helm support for add-ons.
- Recommended Skills: Ansible, Kubernetes
- Mentor(s):
    - Kay Yan (yankay, <kay.yan@daocloud.io>)
    - Mohamed Zaian (mzaian, <mohamedzaian@gmail.com> )
- Upstream Issue: https://github.com/kubernetes-sigs/kubespray/issues/5432
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/22b0ef86-d390-4ea2-b302-79e819dcbdfc


### KWOK

#### Enhancement of Test Cases

- Description: KWOK (Kubernetes WithOut Kubelet) is a toolkit that enables setting up a cluster of thousands of Nodes in seconds. KWOK is currently being used by a number of projects for testing and performance. It is crucial that KWOK itself behaves consistently. The following tests are currently being considered: Unit Test, E2E Test, Edge Cases.
- Expected Outcome: Improved test coverage for KWOK.
- Recommended Skills: Golang, Kubernetes
- Mentor(s):
    - Shiming Zhang (wzshiming, <wzshiming@hotmail.com>)
    - Zhenghao Zhu (Zhuzhenghao, <zhenghao.zhu@daocloud.io>)
- Upstream Issue: https://github.com/kubernetes-sigs/kwok/issues/1062
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1969ce6c-5468-4842-89a2-06c020bd2ad1

#### Enhancement of Technical Outcomes

- Description: KWOK (Kubernetes WithOut Kubelet) is a toolkit that enables setting up a cluster of thousands of Nodes in seconds. On the KWOK homepage (https://kwok.sigs.k8s.io/), we aim to document the technical outcomes of using KWOK. These outcomes represent the aggregation of some of KWOK's features to achieve a high-level technical goal. Currently, we have the following areas of focus: Chaos Testing, Performance, Simulation, and Scalability.
- Expected Outcome: A section of the KWOK website detailing these technical outcomes.
- Recommended Skills: Kubernetes, Technical Writing
- Mentor(s):
    - Shiming Zhang (wzshiming, <wzshiming@hotmail.com>)
    - Zhenghao Zhu (Zhuzhenghao, <zhenghao.zhu@daocloud.io>)
- Upstream Issue: https://github.com/kubernetes-sigs/kwok/issues/1063
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ef8e7637-2eb6-4672-8f6c-c9f9f0677da0

### LitmusChaos

#### Revamp Litmus Helm Agent, UBI migration of Images

- Description: The Litmus Helm Agent, one of the microservice in Litmus, requires modernization for compatibility with Litmus 3.x API changes. Simultaneously, migrating Litmus Chaos container images to Red Hat's Universal Base Image (UBI) enhances security and compatibility. This project aims to revitalize the Helm Agent and streamline image management, ensuring seamless integration and robust deployment in containerized environments.
- Expected Outcome:
    - Seamless Integration: The Litmus Helm Agent will seamlessly support Litmus 3.x API changes, ensuring compatibility and uninterrupted functionality within the ecosystem.
    - Enhanced Security: Migrating Litmus Chaos container images to Red Hat's Universal Base Image (UBI) will bolster security and compatibility, optimizing deployment in diverse containerized environments.
- Recommended Skills: Golang, Kubernetes
- Mentor(s):
    - Sayan Mondal (@S-ayanide, sayan.mondal@harness.io)
    - Vedant Shrotria (@Jonsy13, vedant.shrotria@harness.io)
    - Raj Babu Das (@imrajdas, mail.rajdas@gmail.com)
- Upstream Issue: https://github.com/litmuschaos/litmus/issues/4634
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/98777e02-dc5b-4380-b6cb-c57603b56e37

### Enhancements in Chaoscenter: GitOps Support for Azure Git, Group Chaos Infra by Environments in Infrastructure Selection Modal

- Description: In this project, we aim to implement GitOps support specifically for Azure Git within Chaoscenter. Additionally, we will enhance the Infrastructure Selection Modal by introducing the capability to group chaos infrastructure based on environments, ensuring better organization and management.
- Expected Outcome:
    - Seamless integration with Azure Git for GitOps workflows.
    - Introduction of environment-based grouping in the Infrastructure Selection Modal.
    - Improved chaos infrastructure management and user experience in Chaoscenter.
- Recommended Skills: Golang, Kubernetes, ReactJS
- Mentors(s):
    - Shubham Chaudhary (@ispeakc0de, shubham.chaudhary@harness.io)
    - Amit Das (@amityt, amit.das@harness.io)
    - Sahil Kumar (@SahilKr24, sahil.kumar@harness.io)
- Upstream Issue: https://github.com/litmuschaos/litmus/issues/4633
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e9bf62a9-a7f6-41bb-be7a-e16b7a35a58a

### Implementing Upgrade Agent Support in Litmus 3.x

- Description: Integrating an upgrade agent into Litmus 3.x streamlines Chaoscenter upgrades, eliminating the need for fresh installations. This feature ensures seamless transitions between versions, especially useful when facing significant changes.
- Expected Outcome:
    - Seamless Upgrades: Integration of the Upgrade Agent ensures smooth transitions during Chaoscenter upgrades, removing the necessity for fresh installations.
    - Simplified Process: Users can upgrade from one version to another without the hassle of reinstallation, saving time and effort.
- Recommended Skills: Golang, Kubernetes
- Mentors(s):
    - Saranya Jena (@Saranya-jena, saranya.jena@harness.io)
    - Sarthak Jain (@SarthakJain26, sarthak.jain@harness.io)
- Upstream Issue: https://github.com/litmuschaos/litmus/issues/4632
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9ac6f8b4-4f76-41d0-b02b-89c79534e619


### Meshery

#### Meshery: Meshery: Project tutorials, design patterns, & publish reference architectures

- Description: Meshery the CNCF’s 10th fastest growing project. As a cloud native manager, Meshery [integrates with 250+ projects](https://meshery.io/integrations) and technologies. For each CNCF project integrated with Meshery, tutorials, sample designs, and deployment patterns with reference architectures need to be created. For the earnest, DevOps-minded intern, this internship represents a vast opportunity to learn, document, and publish tutorials and best practices not only around Meshery, but for any number of the other CNCF projects, too. You will use the [Meshery Playground](https://play.meshery.io)

- Expected Outcome:
  - 25+ new design patterns published in Meshery Catalog and Artifact Hub.
  - 5 new Meshery tutorials published in Meshery Docs.
  - Bonus: Extend one or more of Meshery’s Learning Paths.

- Recommended Skills: written English, Kubernetes, DevOps, and familiarity with any number of other CNCF projects, like Jaeger, Helm, Harbor, Flux, Argo, Flux, Falco, etc., Jekyll, strong organizational skills
- Mentor(s): Yash Sharma (@Yahsharma1911, yashsharma2572@gmail.com), Lee Calcote (@leecalcote, leecalcote@gmail.com)
- Upstream Issue: https://github.com/meshery/meshery/issues/10888
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/7ec5139b-fca8-43db-bafc-bdb2faa58047

#### Meshery: End-to-End Testing with Playwright

- Description: Meshery integrates with many other CNCF projects and technologies. Sustaining those integrations is only possible through automation. End-to-end testing with Playwright, GitHub Workflows, and self-documenting test reports is the means to the end of maintaining a healthy state of each of these [Meshery integrations](https://meshery.io/integrations).

- Expected Outcome:
  - Successful migration of E2E tests from Cypress to the Playwright test library within the Meshery project.
  - Implementation of robust and reliable test cases using Playwright to cover a wide range of Meshery's E2E scenarios.
  - Documentation detailing the migration process, and guidelines for future contributions to maintain test quality.
  - Integration of Playwright test suite into the Meshery CI/CD pipeline to ensure continuous testing and reliability of the platform.
- Recommended Skills: JavaScript, Playwright, GitHub Workflows, Jekyll, Markdown, familiarity with React or Nextjs would be helpful, CI/CD
  - Mentor Name: Aabid Sofi (@aabidsofi19, mailtoaabid01@gmail.com), Lee Calcote (@leecalcote, leecalcote@gmail.com),
- Upstream Issue: https://github.com/meshery/meshery/issues/10890
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/62f4866e-9461-490d-890d-9f221a3941b4

#### Meshery: Support versioning for Meshery designs

- Description: Meshery design is a common practice of both configuring and operating cloud native infrastructure functionality in a single, universal file. We are seeking to enhance Meshery's capabilities by supporting automatic versioning of Meshery designs based on user sessions. This functionality will enable users to track changes made to their designs by individuals, facilitating the ability to rollback changes at any time.

- Expected Outcome:
  - Update Meshery server and pattern engine to support Meshery design versioning.
  - Update UI to allow users to perform actions related to design versioning.
  - Document changes made in pattern engine and server.

- Recommended Skills: Golang, Kubernetes, Meshery, Familiarity with Helm charts and Artifact Hub, familiarity with React, Nextjs would be helpful
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Uzair Shaikh (@muzairs15, muzair.shaikh810@gmail.com)
- Upstream Issue: https://github.com/meshery/meshery/issues/10889
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/8e1ab317-9043-4f29-8b83-9b9ffa2b8b40


### OpenKruise

#### Enhancement for Kruise-Game Dashboard

- Description: The OpenKruiseGame Dashboard is presently in its basic form, and we aim to significantly expand its functionality going forward. We plan to introduce features such as the ability to filter game servers and perform batch updates on them.
- Expected Outcome: new release Dashboard which supports searching, querying, updating objects in batch.
- Recommended Skills: Kubernetes, nodejs, javascript
- Mentor(s):
    - Qiuyang Liu (@chrisliu1995, chrisliu1995@163.com)
    - Zhongwei Liu (@ringtail, zhongwei.lzw@alibaba-inc.com)
- Upstream Issue: https://github.com/openkruise/kruise-game/issues/139
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/3967228d-75a7-4963-b092-f2e92fcd57c8

### Prometheus

#### Prometheus Remote Write Benchmarking Capabilities

- Description: Prometheus remote write allows users to send their metrics to other time series databases. Though the [Prombench tool](https://github.com/prometheus/test-infra/tree/master/prombench) has existed for a number of years, it has never been extended to support performance testing of Remote Write in a realistic production like environment. With the upcomming Remote Write 2.0 changes to both the underlying implementation as well as the wire format, the need for benchmarking of remote write beyond static Go bechmark tests has increased.
- Expected Outcome: Build additional (or extends existing) tooling, similar to Prombench’s [load-generator](https://github.com/prometheus/test-infra/tree/master/tools/load-generator) and [avalanche](https://github.com/prometheus-community/avalanche), to support scenarios under which remote write should be performance tested. For example; allowing gradual increases/decreases in # of active series, sudden spikes in active series, various amounts of latency in the server receiving the remote write data, etc. Time permitted, extend Prombench's test suite to include a set of Remote Write tests that can be run via a new command.
- Recommended Skills: Go, some familiarity with Prometheus or metrics, basic Docker knowledge
- Mentor(s):
    - Callum Styan (@cstyan, callumstyan@gmail.com),
    - Jesús Vázquez (@jesusvazquez, jesusvzpg@gmail.com)
    - Nico Pazos and Alex Greenbank from Grafana also available to help
- Upstream Issue: https://github.com/prometheus/prometheus/issues/13995
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0462446f-aeea-4a19-9bd6-f4241ee5e8f2

#### Mark Out-of-order ingestion as stable

- Description: Prometheus is known by not accepting out-of-order samples during ingestion, but recently (2 years ago) [support was added behind a feature-flag](https://github.com/prometheus/prometheus/pull/11075). Since then, many improvements have been made to out-of-order ingestion and it has become one of the requirements for OTLP ingestion in Prometheus. We want to deliver Prometheus 3.0 in a few months, and that requires marking out-or-order ingestion as a stable feature. In this project we will clean up several smaller issues around out-of-order ingestion, hopefully marking it as stable by the end of the mentorship.
- Recommended Skills: Go, familiarity with Prometheus TSDB.
- Mentor(s):
    - Bryan Boreham (@bboreham, bjboreham@gmail.com)
    - Jesus Vazquez (@jesusvazquez, jesusvzpg@gmail.com)
- Upstream Issue: https://github.com/prometheus/prometheus/issues/12631
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/454caa5a-6fd5-4e27-bde4-7649abf6d8ca


### Service Mesh Performance

#### Service Mesh Performance: Convergence of Network and Graph topologies

- Description: Opens the door to leveraging algorithms in the areas of Centrality, Community Detection, Pathfinding, Topological Link Prediction, etc. Bringing to bear advances made in Machine Learning / AI / recommendation systems, fraud detection could really help to derive meaning and comprehension for future tools. Another example is how ML + graph approaches are used to find and determine the optimal molecular structure of atoms such that desired physical properties are targeted. This approach could be applied to the problem of workload sizing and estimation for service mesh operators and would-be adopters.

- Expected outcome:
  - Use Neo4j's ability to create graph projections, which copy a subgraph to RAM so that algorithms can be efficiently run.
- Recommended Skills: Golang, familiarity with Service Mesh, grpc, docker, kubernetes
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Xin Huang (@gyohuangxin, xin1.huang@intel.com)
- Upstream Issue: https://github.com/service-mesh-performance/service-mesh-performance/issues/422
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/c605139b-8736-477a-835a-c6b45112bee4


### Thanos

#### Compactor: Display TODO plan in UI

- Description: In the Thanos Compactor UI there is visibility of the global block list and loaded block list. But it would be useful to also have a list of planned and currently running compaction groups in order to see what exactly is in progress. This way it would be easier to diagnose what the Thanos Compactor is currently working on, and possibly what is delaying the progress of compactions. This is especially useful if you have large TSDB blocks in S3 buckets that take time to get compacted.
- Expected Outcome: We have an endpoint in Compactor that details compaction plan, and this is also visualized in a Compactor UI page.
- Recommended Skills: Go, React, some familiarity with Prometheus and Thanos
- Mentor(s):
    - Michael Hoffmann (@MichaHoffmann, mhoffm@posteo.de)
    - Saswata Mukherjee (@saswatamcode, saswataminsta@yahoo.com)
- Upstream Issue: https://github.com/thanos-io/thanos/issues/7285
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/05b3d261-f874-4b8c-bd7e-c4fa83c979b4

### TUF

#### Documentation analysis and improvements

- Description:
    - Open source projects need help with their documentation!  The TUF project is a good place to start.  We'd welcome help from others to help here
      and become contributors to other projects / TAGs later in the project period.  The mentee will (with minimal guidance from the CNCF team and TUF project) do a [CNCF analysis](https://github.com/cncf/techdocs/blob/main/docs/analysis/howto.md) for the TUF documentation
- Expected Outcome:
    - Both an improvement of project docs and the development of a new contributor.  A mentee will understand how to do technical writing for an open source project.
- Recommended Skills:
    - Technical writing
    - Basic understanding of security principles
- Mentor(s):
    - Justin Cappos @JustinCappos jcappos@nyu.edu
    - Patrice Chalin @chalin chalin@cncf.io
    - Lukas Pühringer @lukpueh lukas.puehringer@nyu.edu
- Upstream Issues:
    - https://github.com/cncf/techdocs/issues/162
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e35f28f9-f333-47a8-a76a-119567cf10ca

### Vitess

#### Improve the website of our automated-benchmarking tool (migrate to shadcn ui and typescript)

- Description:
    - Vitess uses arewefastyet to automatically benchmark its codebase and ensure no performance regression is introduced. This tool benchmarks Vitess every day, and is used to visualize the results of those benchmarks. It is an important tool in the development cycle of Vitess and is used by its maintainers and adopters.
    - [Arewefastyet' website](https://benchmark.vitess.io) has changed quite a lot over the last year, we want to continue improving it by finishing the migration to TypeScript and by using Shadcn components.
    - Moreover, we want to make the website responsive and have a proper Figma that serves as a reference for current and future contributors.
- Expected Outcome:
    - The mentee is expected to produce a Figma with the design of the website that will be co-authored with the mentor.
    - Re-vamp most of the pages using Shadcn and the design defined with the mentor at the start of the internship period.
    - Add type information for all/most components using TypeScript.
- Recommended Skills:
    - Be skilled in React/Vite/TypeScript.
    - Must know how to simply use Docker and docker-compose.
    - Experience with Figma is a big plus.
    - Experience with Rest APIs and Golang is a plus too.
- Mentor(s):
    - Florent Poinsard @frouioui florent@planetscale.com
    - Frances Thai @notfelineit frances@planetscale.com
- Upstream Issue (URL): https://github.com/vitessio/arewefastyet/issues/525
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/cba8a6c6-4b09-4618-98f7-bf24391e8c9e

#### Community building and engagement

- Description:
    - [Vitess](https://vitess.io) is a CNCF project that has been around for a while. It has a strong community of users and contributors. We want to continue growing this community and make sure that everyone feels welcome and included.
- Expected Outcome:
    - The mentee is expected to evaluate contributor ladder schemes and rewards and produce a recommendation for the Vitess maintainers.
    - Once a decision is made, the mentee is expected to implement the decisions from the maintainer team.
    - The mentee is expected to collect data about Vitess usage from the community and publish the highlights as a blog post.
    - The mentee is expected to review the [Getting Started docs on the Vitess website](https://vitess.io/docs/20.0/get-started/) and enhance them to improve the onboarding experience.
    - The mentee is expected to research and recommend marketing opportunities for Vitess. These could be guest blog posts, podcasts, live streams etc.
- Recommended Skills:
    - Excellent verbal and written communication skills.
    - Prior experience participating in an open source community is a plus.
    - Should be able to install and run Vitess according to the user guides.
    - Website development skills are a plus.
- Mentor(s):
    - Deepthi Sigireddi @deepthi deepthi@planetscale.com
    - Florent Poinsard @frouioui florent@planetscale.com
- Upstream Issue (URL): https://github.com/vitessio/vitess/issues/15895
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1e395914-9adb-4254-a02d-08e6e03e3b93

### WasmEdge

#### Support piper as a new backend of the WASI-NN WasmEdge plugin

- Description: WasmEdge supports PyTorch, TensorFlow Lite, llama.cpp, and more NN backend. Dealing with the text-to-voice is a big thing that we want to achieve. To make it possible, we would like to integrate [piper](https://github.com/rhasspy/piper), A fast, local neural text-to-speech system in C++ as a new [WASI-NN](https://github.com/second-state/wasmedge-wasi-nn) backend.
- Expected Outcome:
    - A new plugin provides a piper [WASI-NN](https://github.com/second-state/wasmedge-wasi-nn) backend
    - A test suite for validating the plugin
    - Documents and examples for explaining how to use the plugin.
- Recommended Skills: C++, Wasm
- Mentor(s):
    - Hung-Ying Tai (@hydai, hydai@secondstate.io)
    - dm4 (@dm4, dm4@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/3381
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/61014739-ac16-4188-bdab-c87c0a502470

#### Enabling LLM fine tuning in the WASI-NN ggml plugin

- Description: WasmEdge is a lightweight and cross-platform runtime for LLM applications. It allows developers to create LLM apps on a Mac or Windows dev machine, compile them to Wasm, and deploy them on Nvidia machines without any changes to the binary app. It achieves application portability across CPUs and GPUs by supporting a W3C standard API called  [WASI-NN](https://github.com/second-state/wasmedge-wasi-nn), which abstracts GPU-related AI functions as high-level APIs. At this stage, however, only inference functions are supported. In this project, we aim to support fine-tuning features in WasmEdge. It will improve the developer experience for WasmEdge-enabled LLM tools. To achieve this, we plan to extend the current WASI-NN spec by adding a set of extra APIs, and then implement them by delegating to corresponding functions in llama.cpp embedded in the WasmEdge GGML plugin.
- Expected Outcome:
    - Use llama2-7b as the base LLM for fine-tuning; the final implementation should handle it correctly.
    - Extend the [WASI-NN](https://github.com/second-state/wasmedge-wasi-nn) spec if needed to support the fine-tuning feature.
    - Implement the fine-tuning functions inside [WASI-NN ggml plugin](https://github.com/WasmEdge/WasmEdge/blob/master/plugins/wasi_nn/ggml.h). They will call the corresponding functions in llama.cpp, as the inference functions do.
    - Implement the LoRA-related functions inside the WASI-NN ggml plugin to load the pre-trained LoRA and verify the fine-tuned model.
    - Documentation, examples, tutorials, and demonstration are required.
- Recommended Skills: C++, WebAssembly, LLM fine-tuning
- Mentor(s):
    - Hung-Ying Tai (@hydai, hydai@secondstate.io)
    - dm4 (@dm4, dm4@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/3209
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/41c5a3df-0b84-4b78-b343-bacfc2a3c4ff

#### Create a search-enabled API server for local LLMs

- Description: WasmEdge is a lightweight inference runtime for AI and LLM applications. The [LlamaEdge project](https://github.com/LlamaEdge) has developed an [OpenAI-compatible API server](https://github.com/LlamaEdge/LlamaEdge/tree/main/api-server) and a [server-side RAG app](https://llamaedge.com/docs/category/server-side-rag) based on WasmEdge. In this project, we aim to use the LlamaEdge components to build a new API server that incorporates real-time Internet search results into LLM answers.
- Expected Outcome: An OpenAI-compatible local LLM API server that uses Google Search for supplemental context
- Recommended Skills:
    - Rust language
    - LlamaEdge
- Mentor(s):
    - Michael Yuan (@juntao, michael@secondstate.io)
    - Hung-Ying Tai (@hydai, hydai@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/3372
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0a4e08a1-3404-46fc-b0d0-5117ec4ec119

#### Finetune LLM models for Rust coding assistance

- Description: WasmEdge is a lightweight inference runtime for AI and LLM applications. We want to build specialized and finetuned models for WasmEdge community. The model should be supported by WasmEdge and its applications should benefit the WasmEdge community.
  In this project, we will build and compare two finetuned model for Rust coding assistance.
    * A code review model. It aims to be a new backend for the [PR review bot](https://github.com/flows-network/github-pr-summary/) we currently use in the community.
    * A QA model. It should be able to answer user questions about the Rust language and provide explanations. Our goal is to provide an alternative to our [Learn Rust](https://flows.network/learn-rust) app.
- Expected Outcome: Two finetuned models based on Llama3-8b for Rust code review and QA.
- Recommended Skills:
    - Rust language
    - ChatGPT and Claude
    - LlamaEdge
    - llama.cpp
- Mentor(s):
    - Michael Yuan (@juntao, michael@secondstate.io)
    - Hung-Ying Tai (@hydai, hydai@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/3371
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/d52d172e-598d-4817-be97-3338d5b96432


---------------
# Term 03 - 2023 September - November

Status: Completed

Mentorship duration - three months (12 weeks - full-time schedule)

### Timeline

| activity | date |
| --- | --- |   
| project proposals | Thur July 27, 5:00 PM PDT |
| mentee applications open | Wed Aug 2 - Tues 15, 5:00 PM PDT |
| application review/admission decisions | Wed Aug 16 - Tues Aug 29, 5:00 PM PDT |
| Mentorship program begins with the initial work assignments | Mon Sept 4 (Week 1) | 
| Midterm mentee evaluations and first stipend payments | Wed Oct 11 (Week 6) |
| Final mentee evaluations and mentee feedback/blog submission due, second and final stipend payment approvals | Wed Nov 22, 5:00 PM PST (Week 12) |
| Last day of term | Thur Nov 30 |

### Project Instructions

Project maintainers and potential mentors are welcome to propose their mentoring project ideas via submitting a PR to GitHub here https://github.com/cncf/mentoring/blob/main/programs/lfx-mentorship/2023/03-Sep-Nov/project_ideas.md, by Thursday, July 27, 2023.

### Application instructions

Mentee application instructions can be found on the [Program Guidelines](https://github.com/cncf/mentoring/blob/main/programs/lfx-mentorship/README.md#program-guidelines) page.

---

## Table of Contents

- [Carvel](#carvel)
  * [kctrl to support exporting package repository as tar](#kctrl-to-support-exporting-package-repository-as-tar)
- [CRI-O](#cri-o)
  * [Add additional log drivers to conmon-rs](#add-additional-log-drivers-to-conmon-rs)
  * [CRI stats KEP](#cri-stats-kep)
- [Istio](#istio)
  * [Implement performance testing](#implement-performance-testing)
  * [Documentation for Ambient Mesh](#documentation-for-ambient-mesh)
- [Jaeger](#jaeger)
  * [Upgrade Jaeger UI to the latest version of React.js](#upgrade-jaeger-ui-to-the-latest-version-of-reactjs)
  * [Combine three distinct graph views in Jaeger UI into one](#combine-three-distinct-graph-views-in-jaeger-ui-into-one)
  * [Build official support in Jaeger for Elasticsearch 8](#build-official-support-in-jaeger-for-elasticsearch-8)
- [Karmada](#karmada)
  * [Karmada supports promote dependent resources automatically](#karmada-supports-promote-dependent-resources-automatically)
  * [Add Karmada API documentation on the website](#add-karmada-api-documentation-on-the-website)
- [Konveyor](#konveyor)
  * [Extend use-case of detecting deprecated Kubernetes API usage](#extend-use-case-of-detecting-deprecated-kubernetes-api-usage)
  * [Move2Kube: Compile Move2Kube to WASM/WASI and run it in the browser](#move2kube--compile-move2kube-to-wasm-wasi-and-run-it-in-the-browser)
  * [Move2Kube: WASM Transformers](#move2kube--wasm-transformers)
  * [Move2Kube: Advanced Resources support - ArgoCD, Tekton, Stateful Set, etc.](#move2kube--advanced-resources-support---argocd--tekton--stateful-set--etc)
- [KubeArmor](#kubearmor)
  * [Implement DNS visibility with KubeArmor II](#implement-dns-visibility-with-kubearmor-ii)
  * [Extend Support Matrix and Document Usecases](#extend-support-matrix-and-document-usecases)
- [KubeEdge](#kubeedge)
  * [Add case study center in website](#add-case-study-center-in-website)
  * [Support latest version in keink and run demo on keink](#support-latest-version-in-keink-and-run-demo-on-keink)
  * [Support latest version installation demo in killercoda](#support-latest-version-installation-demo-in-killercoda)
- [Kubernetes](#kubernetes)
  * [Build a Go library and CLI for interacting with OpenBuildService](#build-a-go-library-and-cli-for-interacting-with-openbuildservice)
- [Kubescape](#kubescape)
  * [Build an admission controller for Kubescape](#build-an-admission-controller-for-kubescape)
  * [Upgrade the documentation publishing pipeline for Kubescape controls](#upgrade-the-documentation-publishing-pipeline-for-kubescape-controls)
- [KubeVela](#kubevela)
  * [Support auto generation of multiple languages SDK from CUE II](#support-auto-generation-of-multiple-languages-sdk-from-cue-ii)
- [Kyverno](#kyverno)
  * [Pod Security Admission Integrations II](#pod-security-admission-integrations-ii)
  * [Policy Exceptions 2.0](#policy-exceptions-20)
  * [Kyverno Kuttl Enhancements](#kyverno-kuttl-enhancements)
- [LitmusChaos](#litmuschaos)
  * [Improve litmusctl UX and codebase and add new functionalities to litmusctl](#improve-litmusctl-ux-and-codebase-and-add-new-functionalities-to-litmusctl)
  * [Improve Chaoscenter Web and Authentication Server: Add Unit Test Cases, Enhance GQL APIs, Update API Documentation](#improve-chaoscenter-web-and-authentication-server--add-unit-test-cases--enhance-gql-apis--update-api-documentation)
- [Meshery](#meshery)
  * [Overhaul UX Design System](#overhaul-ux-design-system)
  * [Package Meshery Catalog Artifacts as OCI Images](#package-meshery-catalog-artifact-as-oci-images)
  * [WASM-based OPA policy evaluation with Rego](#wasm-based-opa-policy-evaluation-with-rego)
- [Thanos](#thanos)
  * [Implement fan-out query observability in Thanos](#implement-fan-out-query-observability-in-thanos)
  * [Release the distributed query engine in Thanos](#release-the-distributed-query-engine-in-thanos)
- [Vitess](#vitess)
  * [Continue the migration to React and enhance existing frontend UI](#continue-the-migration-to-react-and-enhance-existing-frontend-ui)
- [OpenKruise](#openkruise)
  * [Integrate Openkruise workload with ArgoCD and Helm](#integrate-openkruise-workload-with-argocd-and-helm)
- [Volcano](#volcano)
  * [Support NPU accelerator scheduling in Volcano](#support-npu-accelerator-scheduling-in-volcano)
  * [Build a new elastic resource quota mechinism in Volcano](#build-a-new-elastic-resource-quota-mechinism-in-volcano)
  * [Add user guidance for jobflow](#add-user-guidance-for-jobflow)
  * [Fix bugs for jobflow to enhance its stability](#fix-bugs-for-jobflow-to-enhance-its-stability)
- [WasmEdge](#wasmedge)
  * [Add matrix operations for OpenCVMini-Wasm-Plugin](#add-matrix-operations-for-opencvmini-wasm-plugin)
  * [Support AOT mode in proxy-wasm](#support-aot-mode-in-proxy-wasm)
  * [Create a Rust crate for YOLO model](#create-a-rust-crate-for-yolo-model)
  * [Create a ffmpeg plugin](#create-a-ffmpeg-plugin)

---

## Accepted projects

### Carvel

#### kctrl to support exporting package repository as tar

- Description: While generating Package Repository kctrl to create the tar version of the Package Repository instead of pushing the OCI Image to a registry. 
- Expected Outcome: 
    - Proposal containing design discussions and options considered.
    - Function Implementation to support a flag which allows to export the package repo to tar
    - Documentation changes as required 
- Recommended Skills: Golang
- Mentor(s): 
    - Soumik Majumder (@100mik, soumik712@gmail.com)
    - Renu Yarday (@renuy, ryarday@vmware.com)
- Upstream Issue (URL): https://github.com/carvel-dev/kapp-controller/issues/1277
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/91398424-f095-4b85-bb0f-e7c56e777ea0

### CRI-O

#### Add additional log drivers to conmon-rs

- Description: conmon-rs is a container monitor written in Rust, used by CRI-O to monitor a container's lifecycle. Part of its responsibilities is log forwarding--taking the output of the container and writing that output to various places. Currently, conmon-rs supports one format: the one required by the Kubernetes CRI. The goal of this proposal is to add new log formats from the list of standardized ones, like JSON, Splunk, Journald.
- Expected outcome: A JSON log driver and Journald log driver are added to conmon-rs. A stretch goal of adding a Splunk log driver is also within scope.
- Recommended Skills: Rust, familiarity with containers
- Mentor(s):
  - Peter Hunt, haircommander, pehunt@redhat.com
  - Sascha Grunert, saschagrunert, mail@saschagrunert.de
- Upstream Issue (URL): https://github.com/containers/conmon-rs/issues/1126
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/99274b1a-694b-4af5-b7ca-39311f38a646

#### CRI stats KEP

- Description: [CRI stats KEP](https://github.com/kubernetes/enhancements/issues/2371) is an effort to take the container stats and metrics collection from cAdvisor and move it to the CRI implementations. CRI-O will soon have support for stats and metrics collected through CRI, but work needs to be done to verify and validate these fields, and make sure their collection is performant as possible.
- Expected outcome: A test suite verifying the correctness of CRI-O's stats and metrics collection, as well as data verifying performance regressions are minimal at worst.
- Recommended Skills: Golang, familiarity with containers
- Mentor(s):
  - Peter Hunt, haircommander, pehunt@redhat.com
  - Sohan Kunkerkar, sohankunkerkar, skunkerk@redhat.com
- Upstream Issue (URL): https://github.com/cri-o/cri-o/issues/7175
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/cb189d71-3943-450a-9d5f-d71bd66d73c9

### Istio

#### Implement performance testing

- Description: Up until version 1.16, [Istio](https://istio.io/) published [performance and scale testing results](https://istio.io/v1.16/docs/ops/deployment/performance-and-scalability/). These should be returned to service, and updated to support ambient mesh. Third-party benchmarking tools should be updated to support testing the performance of ambient mesh.
- Expected Outcome: Performance testing pages are returned to istio.io, and include both sidecar and ambient mesh results.
- Recommended Skills:
  - Python
  - Networking
- Mentors:
  - Lin Sun (@linsun, lin.sun@solo.io)
  - Andrea Y Ma	(@andream12345,	ayma@us.ibm.com)
- Upstream Issue: https://github.com/istio/istio/issues/44009
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/bbebd511-1a3e-4c4f-b106-2f09690825c5

#### Documentation for Ambient Mesh

- Description: [Istio](https://istio.io/) is working on [a new operating mode called ambient mesh](https://istio.io/latest/blog/2022/introducing-ambient-mesh/). As this moves from experimental to the recommended method of operating a service mesh, we will need to revise our documentation to discuss the new model, explain the tradeoffs, and tell users how to choose.
- Expected Outcome: Revisions to Istio's documentation to reflect the availability of ambient mesh.  These will be maintained in a parallel branch of istio.io that can be pulled from when Ambient is in Beta or GA.
- Recommended Skills: 
  - Technical writing
  - Developer advocacy
- Mentors:
  - Lin Sun (lin.sun@solo.io)
- Upstream Issue: https://github.com/istio/istio.io/issues/13481
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/89ee4357-dd58-4e15-a601-c411742a587c

### Jaeger

#### Upgrade Jaeger UI to the latest version of React.js

- Description: Jaeger UI is built on React. While we are seemingly already on v18.x of React, the upgrade was not done across the board and some other dependencies are still lagging behind, e.g. `"@types/react": "16.8.7"`. It's also blocking upgrades of other dependencies. This project is likely to involve a substantial amount of code contribution, as certain upgrade require fixing the code to use the new APIs, and sometimes we may run into dependencies that are EOL and need to be replaced altogether.
- Expected Outcome: Ideal outcome is to have _all_ dependencies upgraded to the latest versions (with the help of @dependabot) and fix all deprecation warnings during the build. But incremental progress towards that goal is also acceptable.
- Recommended Skills: Javascript, Typescript, NPM, Yarn, Vite.js
- Mentor(s):
  - Yuri Shkuro (@yurishkuro, github@ysh.us)
- Upstream Issue: https://github.com/jaegertracing/jaeger-ui/issues/998
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/83cc55fe-b97a-4195-8dd2-cc9aed7e509c

#### Combine three distinct graph views in Jaeger UI into one

- Description: Jaeger UI provides several views to visualize service dependencies, also known as service topology maps. However, these views are using different drawing libraries, resulting in very different look & feel and inconsistent experience. One of the views is using a `plexus` library that was purposely built as part of Jaeger UI that provides rich capabilities for displaying graphs, which may be a good candidate for the other views.
- Expected Outcomes:
  - Remove the dependency on react-vis library (https://github.com/jaegertracing/jaeger-ui/issues/1597).
  - Use a single library for graph visualizations.
  - Provide consistent look and feel of different graph views.
- Recommended Skills: Javascript, Typescript, NPM, Yarn, Vite.js, web worker
- Mentor(s):
  - Yuri Shkuro (@yurishkuro, github@ysh.us)
  - Yash Sharma (yashrsharma44@meta.com)
- Upstream Issue: https://github.com/jaegertracing/jaeger-ui/issues/1466
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1e67c90b-de3e-4c4e-a2be-a5583a948864

#### Build official support in Jaeger for Elasticsearch 8

- Description: Jaeger has always supported Elasticsearch (ES) as an official backend. Unfortunately, the Go driver we are using, `olivere/elastic`, does not support ESv8 and not planning to release any new versions. Despite the licensing changes, Elasticsearch remains a popular choice and v8 support question often comes up. In this project we want to add official support for ESv8. However, we also want to take this opportunity to do a better alignment with the OpenTelemetry Collector, which already has an [ESv8 exporter](https://github.com/open-telemetry/opentelemetry-collector-contrib/tree/main/exporter/elasticsearchexporter), perhaps we can use it directly and minimize the amount of code.
- Expected Outcomes:
  - Use OTEL ESv8 exporter from Jaeger, if possible, otherwise build internal implementation
  - Stretch goal: use ES data as the source for Jaeger SPM views
- Recommended Skills: Go, Elasticsearch
- Mentor(s):
  - Yuri Shkuro (@yurishkuro, github@ysh.us)
- Upstream Issue: https://github.com/jaegertracing/jaeger/issues/4600
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/37cf2714-668d-4014-ac44-953f70f9dc8e

### Karmada

#### Karmada supports promote dependent resources automatically

- Description: Provide an automatic promotion mechanism for dependent resources in karmadactl. When promoting a resource, all the resources that it depends on will be automatically promoted as well. For example, promoting the Secret that is dependent by a Deployment.
- Expected Outcome:
  - Technical Documentation: design description and analysis
  - Function Implementation: support promote the dependent resources automatically
  - Test coverage: add test cases to cover new functions
- Recommended Skills:
  - Go
  - Cloud Native
- Mentor(s):
  - Wei Jiang (@jwcesign, jiangwei115@huawei.com)
  - Hongcai Ren(@RainbowMango, qdurenhongcai@gmail.com)
- Upstream Issue: https://github.com/karmada-io/karmada/issues/3842
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/60b43efd-79e0-457e-989f-d4d59d55d8a6

#### Add Karmada API documentation on the website

- Description: Add the Karmada API documentation on the [website](https://github.com/karmada-io/website),and complete the script for automatic document generation.
- Expected Outcome:
  - Technical Documentation: design description and analysis
  - Script Complete: automatic document generation
  - Maintaining Documentation: add maintaining document on the website
- Recommended Skills:
  - Go
  - Cloud Native
- Mentor(s):
  - Zhen Chang (@XiShanYongYe-Chang, changzhen5@huawei.com)
  - Hongcai Ren(@RainbowMango, qdurenhongcai@gmail.com)
- Upstream Issue: https://github.com/karmada-io/karmada/issues/3843
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/54940f04-54b8-41ee-94bf-153f977b31e7

### Konveyor

#### Extend use-case of detecting deprecated Kubernetes API usage

- Description: [Konveyor](https://www.konveyor.io/) provides a [unified experience](https://github.com/konveyor/enhancements/tree/master/enhancements/unified_experience) of tools to help organizations modernize their applications at scale to Kubernetes and cloud-native technologies. We are looking for help on extending a use-case of detecting usage of [deprecated and removed Kubernetes APIs](https://kubernetes.io/docs/reference/using-api/deprecation-guide/) in applications.  This work will involve determining what API resources have been deprecated or removed in each version of Kubernetes and then building [Analyzer Rules](https://github.com/konveyor/analyzer-lsp/blob/main/docs/rules.md) to be contributed to our [Rulesets repository](https://github.com/konveyor/rulesets), curation or development of sample applications in Golang, Java, and YAML to aid test scenarios, and documentation to help show a guided walkthrough of this capability.  You can see the beginning of this use-case being addressed with a [sample rule](https://github.com/konveyor/analyzer-lsp/blob/main/rule-example.yaml#L42-L45) in this [demo of analyzer-lsp](https://github.com/konveyor/analyzer-lsp/tree/main#quick-demo). The development environment is based on Golang and Kubernetes. A minikube instance will work well for local development on Linux or Mac systems.
- Expected Outcome:
  - [Rules](https://github.com/konveyor/analyzer-lsp/blob/main/docs/rules.md) contributed to [konveyor/rulesets](https://github.com/konveyor/rulesets) to detect usage of deprecated or removed Kubernetes APIs.  Coverage for YAML, Golang, and Java source code, addition of this scenario into the project's automated test suite, and documentation of a guided scenario showing usage of these rules via a curated set of application source code examples.
- Recommended Skills:
  - Go
  - Basic understanding of interaction with Kubernetes via kubectl
  - Basic software development skills (command line, git)
- Mentor(s):
  - Emily McMullan (@eemcmullan, eemcmullan92@gmail.com)
  - Jonah Sussman (@JonahSussman, jsussman@redhat.com)
  - John Matthews (@jwmatthews, jwmatthews@gmail.com)
- Upstream Issue:
  - https://github.com/konveyor/operator/issues/251
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/989d0ad3-976a-4514-b2fc-34e9e6081567

#### Move2Kube: Compile Move2Kube to WASM/WASI and run it in the browser

- Description: Move2Kube is a command-line tool for automating creation of Infrastructure as code (IaC) artifacts. It has inbuilt support for creating IaC artifacts for replatforming to Kubernetes/OpenShift. We want to compile targetting WASM/WASI and run the resulting WASM module in the browser. This will help up showcase Move2Kube for demos and allow users to quickly try out Move2Kube without having to install it or any of its dependencies.
- Expected Outcome:
  - Run Move2Kube CLI in the browser using WebAssembly.
- Recommended Skills:
  - Golang
  - WASM
- Mentor(s):
  - Harikrishnan Balagopal (@HarikrishnanBalagopal, harikrishnan.balagopal@ibm.com)
  - Mehant Kammakomati (@kmehant, mehant.kammakomati2@ibm.com)
- Upstream Issue: https://github.com/konveyor/move2kube/issues/1062
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/c2b5f721-2666-4d9e-85d6-7bedae27e144

#### Move2Kube: WASM Transformers

- Description: Move2Kube is a command-line tool for automating creation of Infrastructure as code (IaC) artifacts. It has inbuilt support for creating IaC artifacts for replatforming to Kubernetes/OpenShift. Move2Kube has a very plugin friendly architecture, users can write custom logic in the form of "Transformers" that Move2Kube can integrate seamlessly into its transformation pipeline. So far we have support for both Starlark and container image based transformers. We would like to support writing transformers as WASM modules that Move2Kube can run. WASM provides extensive sandboxing for security, it allows writing transformers in different language stacks like Rust, C/C++, etc. other than Golang, and WASM is just as lightweight and fast as Starlark.
- Expected Outcome:
  - Implement a feature in Move2Kube CLI to allow running WASM modules as custom transformers.
- Recommended Skills:
  - Golang
  - WASM
- Mentor(s):
  - Harikrishnan Balagopal (@HarikrishnanBalagopal, harikrishnan.balagopal@ibm.com)
  - Mehant Kammakomati (@kmehant, mehant.kammakomati2@ibm.com)
- Upstream Issue: https://github.com/konveyor/move2kube/issues/1061
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ec286a9e-e48d-4c83-a991-9c79a4ec213a

#### Move2Kube: Advanced Resources support - ArgoCD, Tekton, Stateful Set, etc.

- Description: Move2Kube is a command-line tool for automating creation of Infrastructure as code (IaC) artifacts. It has inbuilt support for creating IaC artifacts for replatforming to Kubernetes/OpenShift. Currently we have rudimentary support for resources such as ArgoCD, Tekton, etc. We need to enhance this to make it useful. Example: https://github.com/konveyor/move2kube/issues/930
- Expected Outcome:
  - More comprehensive support for advanced K8s resources so as to support real world use cases.
- Recommended Skills:
  - Golang
  - K8s
  - ArgoCD
  - Tekton
- Mentor(s):
  - Akash Nayak (@Akash-Nayak, akash.nayak1@ibm.com)
  - Harikrishnan Balagopal (@HarikrishnanBalagopal, harikrishnan.balagopal@ibm.com)
- Upstream Issue: https://github.com/konveyor/move2kube/issues/1063
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/b9aad4e2-d9c7-405e-8482-5aced0a4ecdb

### KubeArmor

#### Implement DNS visibility with KubeArmor II

- Description: The project aims to provide better visibility into the domains accessed from pods, with a focus on identifying and containing attacks that use techniques like Domain Generation Algorithms (DGA) to connect to remote command and control (C&C) servers. By gathering information on which domains are being accessed and applying network rules to allow only specific domains, the project aims to empower security operations (secops) teams to better prevent and respond to such attacks.
- Expected Outcome:  
  - KubeArmor to emit telemetry events for any DNS lookups from any pods.
  - Ability to see egress DNS lookups done from any pods using karmor summary.
  - Documentation
- Recommended Skills: Go, K8s, eBPF. familiarity with network security and a basic understanding of KubeArmor is a plus.
- Mentors:
  - Anurag Kumar (@kranurag7, contact.anurag7@gmail.com)
  - Barun Acharya (@daemon1024, barun1024@gmail.com)
  - Ankur Kothiwal (@Ankurk99, ankur.kothiwal99@gmail.com)
  - Rudraksh Pareek (@DelusionalOptimist, rudrakshpareek3601@gmail.com)
- Upstream Issue: https://github.com/kubearmor/KubeArmor/issues/1219
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/53d7c0da-f066-486a-a9cb-c2da55e42375

#### Extend Support Matrix and Document Usecases

- Description: The project aims to extend KubeArmor support and document how KubeArmor is relevant for securing Kubernetes on Edge in addition to generic Kubernetes based Application deployments
- Expected Outcome:  
  - Try KubeArmor on Different Kubernetes Platforms
      - Microshift, k0s
      - Make fixes to deployments to make them work if needed
  - Document Usecases on these platforms
  - Document Usecases at a broader level for EDGE and Container Security
  - Produce Blogs about extended support and additional usecases
- Recommended Skills: K8s, Basic understanding of KubeArmor, Content Writing is a plus.
- Mentors:
  - Anurag Kumar (@kranurag7, contact.anurag7@gmail.com)
  - Barun Acharya (@daemon1024, barun1024@gmail.com)
  - Ankur Kothiwal (@Ankurk99, ankur.kothiwal99@gmail.com)
  - Rudraksh Pareek (@DelusionalOptimist, rudrakshpareek3601@gmail.com)
- Upstream Issue: https://github.com/kubearmor/KubeArmor/issues/1334
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/eba8fbf7-848b-4d69-8b0e-b6852acc7755

### KubeEdge

#### Add case study center in website

- Description: Now we have had many user cases in the community. However, the KubeEdge website does not have a page to display user cases. Many users lack ways to understand and learn KubeEdge implementation cases., we hope to build a case center to display them, so that more users can consult and learn. 
- Expected Outcome: Add user case study center to display all KubeEdge user cases. Users can upload their own cases. Also users and learners can also manage and view cases by industry tag.
- Recommended Skills: JS , HTML, KubeEdge
- Mentor(s): 
  - Shelley Bao (@Shelley-BaoYue, baoyue2@huawei.com)
  - Fisher Xu (@fisherxu, fisherxu1@gmail.com)
- Upstream Issue: https://github.com/kubeedge/website/issues/347
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/12dda5ae-a123-4e2a-985c-13d33f8a25f0

#### Support latest version in keink and run demo on keink

- Description: keink (KubeEdge IN kind) is a project for running local KubeEdge clusters using Docker container "nodes", so developers can install a multi-node
  edge cluster in one node. Now we need to support the latest version installation in keink. 
- Expected Outcome: keink can install the latest version of KubeEdge and developers can quickly use keink to run kubeedge, and then develop applications on KubeEdge.
- Recommended Skills: Kubernetes, KubeEdge, Golang
- Mentor(s):
  - Fisher Xu (@fisherxu, fisherxu1@gmail.com)
- Upstream Issue: https://github.com/kubeedge/keink/issues/8
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/8c7c6769-edea-4ecd-8fb4-53aa1dacb070

#### Support latest version installation demo in killercoda

- Description: We have created a tutorial in the interactive learning platform killercoda for KubeEdge deployment. This can give a hands-on experience of KubeEdge deployment. Now we need to support the latest version of KubeEdge and integrate example for developers.
- Expected Outcome: It can install the latest version of KubeEdge example, developers can experience these cloud native edge-computing demos online.
- Recommended Skills: Kubernetes, KubeEdge, Golang
- Mentor(s):
  - Fisher Xu (@fisherxu, fisherxu1@gmail.com)
- Upstream Issue: https://github.com/kubeedge/killercoda-scenarios/issues/8
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/36bfe273-9059-47e0-88f7-afb38b2d9ebb

### Kubernetes

#### Build a Go library and CLI for interacting with OpenBuildService

- Description: Kubernetes is set to start using [OpenBuildService](http://openbuildservice.org) as a platform for building, publishing, and hosting Kubernetes system (Debian and RPM) packages. The current integration with the OpenBuildService platform assumes a lot of manual tasks and depending on `osc` command-line tool written in Python. At SIG Release, we're striving to automate as many tasks as possible. We want to build a library and CLI written in Go for interacting with the OpenBuildService APIs and platform that can be integrated with our existing [release tooling (`krel`)](http://github.com/kubernetes/release).
- Expected Outcome: Library and CLI tool for interacting with OpenBuildService platform via their publicly available APIs. Both library and CLI tool should be properly tested via unit, integration, and end-to-end tests, and properly documented.
- Recommended Skills: Golang, working with APIs
- Mentor(s):
  - Carlos Panato (@cpanato, ctadeu@gmail.com)
  - Marko Mudrinić (@xmudrii, mudrinic.mare@gmail.com)
- Upstream Issue: https://github.com/kubernetes/sig-release/issues/2295
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/47f53d22-ff5c-4479-b701-3ca3dbc7df0a

### Kubescape

#### Build an admission controller for Kubescape

- Description: [Kubescape](http://kubescape.io/) is a utility that can scan a Kubernetes cluster and report on its security posture. It can also scan individual workloads (e.g. YAML files) before they are applied. By creating a Kubescape admission controller, we will be able to combine the two, denying workloads into a cluster where it would reduce the security posture.
- Expected Outcome: The Kubescape application will be extended and packaged to operate as an admission controller inside a cluster. The controller will be well documented, safe to install, and instrumented with logging and telemetry data to be able to diagnose problems.
- Recommended Skills:
  - Go
  - Experience using Kubernetes and understanding of its concepts
- Mentors:
  - Craig Box (@craigbox, craigb AT armosec.io)
  - Ben Hirschberg (@slashben, ben AT armosec.io)
- Upstream Issue: https://github.com/kubescape/kubescape/issues/1301
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/271852c6-3348-4ec7-bf09-035913b1c86e

#### Upgrade the documentation publishing pipeline for Kubescape controls

- Description: [Kubescape's control library](https://github.com/kubescape/regolibrary) includes more than 200 controls, tests that codify Kubernetes best practices derived from the most prevalent security frameworks in the industry. Metadata in the controls is used to generate documentation pages in the ARMO website. This project will update this automation to make this control documentation available on kubescape.io.
- Expected Outcome: A full set of documentation for Kubescape controls on kubescape.io. Stretch goals include better README-style documentation inside the repository, and documentation pages on how the controls, frameworks and tests relate.
- Recommended Skills: 
  - Python
  - Technical writing
  - Rego
- Mentors:
  - Ben Hirschberg (@slashben, ben AT armosec.io)
  - Craig Box (@craigbox, craigb AT armosec.io)
- Upstream Issue: https://github.com/kubescape/kubescape/issues/1302
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ccd3fc5f-a0a9-441f-bd4c-5caae8ab6509

### KubeVela

#### Support auto generation of multiple languages SDK from CUE II

- Description: In KubeVela, we use [CUElang](https://cuelang.org/) to code the X-Definition. We want to support auto generation of multiple languages SDK from CUE, so that users can buidling KubeVela Application in their own language. This helps to adoptors to build platform based on KubeVela.
- Expected Outcome: Support auto generation of multiple languages SDK from CUE, including Java, Typescript ,Python. This capability should be part of vela CLI command.
- Recommended Skills: Java, Typescript ,Python, Kubernetes, CUE
- Mentor(s): 
    - Qiao Zhongpei (@chivalryq, chivalry.pp@gmail.com) 
    - Wang YiKe (@wangyikewxgm, wangyike.wyk@gmail.com)
- Upstream Issue: [kubevela/kubevela#5365](https://github.com/kubevela/kubevela/issues/5365)
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e8c0d16a-c263-4a6c-bce7-0b896c925a52

### Kyverno

#### Pod Security Admission Integrations II

- Description: Integrate Kubernetes Pod Security with Kyverno - Part Ⅲ
- Expected Outcome: Kyverno's podSecurity "subrule" has the ability to exclude based on specific field paths and not just the control level.
- Recommended Skills: Golang, Kubernetes, Pod Security
- Mentor(s):
  - Shuting Zhao (@realshuting, shuting@nirmata.com)
- Upstream Issue: https://github.com/kyverno/kyverno/issues/6144
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a7f754b4-5c8c-48a3-8f5f-b3ff6307b0f4

#### Policy Exceptions 2.0

- Description: Enhancements for Kyverno Policy Exceptions including support for images and conditions.
- Expected Outcome: A future version of Kyverno has enhanced support for its Policy Exception resource.
- Recommended Skills: Golang, Kubernetes
- Mentor(s):
  - Jim Bugwadia (@jimbugwadia, jim@nirmata.com)
  - Mariam Fahmy (@MariamFahmy98, mariam.fahmy@nirmata.com)
- Upstream Issue: https://github.com/kyverno/kyverno/issues/7907
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/7ffb0f63-e1e4-477b-ab0c-a69cb681f112

#### Kyverno Kuttl Enhancements

- Description: Add new features to the kuttl application used by the Kyverno project to aid in its end-to-end testing process.
- Expected Outcome: Kyverno's fork of kuttl has these enhancements allowing more and better test cases to be written.
- Recommended Skills: Golang
- Mentor(s):
  - Charles-Edouard Brétéché (@eddycharly, charles.edouard@nirmata.com)
- Upstream Issue: https://github.com/kyverno/kuttl/issues/18
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/919e8b57-8fc1-4f61-8bc8-3c8b06dd5e7a

### LitmusChaos

#### Improve litmusctl UX and codebase and add new functionalities to litmusctl
- Description: [LitmusChaos](https://litmuschaos.io) is an open-source chaos engineering platform for Kubernetes, enabling users to test and improve the resilience of their cloud-native applications. The project focuses on improving litmusctl by enhancing its interactive mode with promptui, and refactoring code to Go interfaces for better unit testing and code quality. Additionally, it aims to replace kubectl with client-go for more efficient Kubernetes operations, resulting in a more user-friendly and reliable command-line tool for chaos engineering and workload management.
- Expected outcome: The expected outcome of the project includes an improved litmusctl tool with a user-friendly promptui-based interactive mode, enhanced code quality through Go interfaces, and a robust test suite. The migration to client-go for Kubernetes operations will ensure better performance and reduced external dependencies, providing users with a reliable and efficient command-line utility for chaos engineering and Kubernetes management tasks.
- Recommended Skills:
  - Golang
  - Kubernetes (Basic understanding of interaction with Kubernetes via kubectl)
- Mentor(s):
  - Saranya Jena (@Saranya-jena, saranya.jena@harness.io)
  - Sayan Mondal (@S-ayanide, sayan.mondal@harness.io)
- Upstream Issue (URL): https://github.com/litmuschaos/litmus/issues/4101
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/fde90e7f-0410-4b84-ad9c-99f7139267ed

#### Improve Chaoscenter Web and Authentication Server: Add Unit Test Cases, Enhance GQL APIs, Update API Documentation

- Description: [LitmusChaos](https://litmuschaos.io) is an open-source chaos engineering platform for Kubernetes, enabling users to test and improve the resilience of their cloud-native applications. The task is add unit tests for Chaoscenter Web and test cases for the Authentication Server. The GraphQL API documentation will be updated with the latest APIs, while the GraphQL server's APIs and handler functions will be optimized to reduce code duplicacy. Additionally, comprehensive documentation and video tutorials will be created for local development setup, promoting easier onboarding and collaboration.
- Expected outcome: The expected outcome of this issue is an improved Chaoscenter Web and Authentication Server with added unit tests, updated GraphQL API documentation, and optimized APIs and handler functions. The enhancements will result in a more reliable, efficient, and user-friendly chaos engineering platform, promoting better collaboration within the community.
- Recommended Skills:
  - Golang
  - TypeScript
- Mentor(s):
  - Sarthak Jain (@SarthakJain26, sarthak.jain@harness.io)
  - Neelanjan Manna (@neelanjan00, neelanjan.manna@harness.io)
- Upstream Issue (URL): https://github.com/litmuschaos/litmus/issues/4102
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/237b7300-d749-4f14-bd4c-9375e5ec39b6

### Meshery

#### Overhaul UX Design System

- Description: [Meshery](https://meshery.io) is a self-service engineering platform, Meshery enables collaborative design and operation of cloud native infrastructure. The Meshery Design System is a flexible, scalable design system built on the foundations of accessibility, beautiful design, and consistent user experience.
- Expected outcome: Rebuild the Meshery Design System so that it provides the open source building blocks to design and implement consistent, accessible, and delightful product experiences.
- Recommended Skills:
  - Figma
  - User-centered Design
  - Visual Design
- Mentor(s):
  - Lee Calcote (@leecalcote, leecalcote@gmail.com)
  - Ritik Saxena (@ritiksaxena124, ritiksaxena124@gmail.com)
- Upstream Issue (URL): https://github.com/meshery/meshery/issues/8347
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a61f6cdb-98b4-43c9-8ca2-ea9bb5d5c470

#### Package Meshery Catalog Artifacts as OCI Images

- Description: [Meshery](https://meshery.io) is a self-service engineering platform, Meshery enables collaborative design and operation of cloud native infrastructure. [Meshery Catalog](https://meshery.io/catalog) content represents a schema-based description of cloud native infrastructure. Catalog content need to be portable between Meshery deployments as well as easily version-able in external repositories.
- Expected outcome: Rebuild the Meshery Design System so that it provides the open source building blocks to design and implement consistent, accessible, and delightful product experiences.
- Recommended Skills:
  - Golang, GraphQL, Reactjs
  - OCI Registries
- Mentor(s):
  - Lee Calcote (@leecalcote, leecalcote@gmail.com)
  - Uzair Shaikh (@MUzairS15, muzair.shaikh810@gmail.com)
- Upstream Issue (URL): https://github.com/meshery/meshery/issues/8348
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/aff716df-c257-4ead-8b48-39a3f9272b7f

#### WASM-based OPA policy evaluation with Rego

- Description: Meshery's highly dynamic infrastructure configuration capabilities require real-time evaluation of complex policies. Policies of various types and with a high number of parameters need to be evaluted client-side. With policies expressed in Rego, the goal of this project is to incorporate use of the https://github.com/open-policy-agent/golang-opa-wasm project into Meshery UI.
- Expected outcome: a powerful real-time multi-user collaboration experience.
- Recommended Skills:
  - Golang
  - Open Policy Agent, Rego
  - WASM
- Mentor(s):
  - Lee Calcote (@leecalcote, leecalcote@gmail.com)
  - Abhishek Kumar (@Abhishek-kumar09, abhimait1909@gmail.com)
- Upstream Issue (URL): https://github.com/meshery/meshery/issues/7019
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9faff011-1027-49c0-aa37-8d5be7208d6f

### Thanos

#### Implement fan-out query observability in Thanos

- Description:
  In the previous mentorship sessions we added the foundation required for query observability in Thanos's new [promql-engine](https://github.com/thanos-io/promql-engine) and hooked it up in the UI. We now have the foundation to record telemetry from our query engine as well such as time consumed per operator.
  This project aims to expand on this and add more metadata to the query execution, both on the promql-engine operator tree level and Thanos Query `Select()` calls for fan-out query observability.
  Once we have this metadata, we would like to visualize it in the Query UI.
- Expected Outcome:
  The end goal is to have a query execution tree decorated with the metadata, collected during execution (ideally even visualized in the Thanos UI). This will help users to understand the performance implications of their PromQL queries and the bottlenecks in their Thanos Query setups.
- Recommended Skills:
  - Golang
  - React.js with TypeScript
  - Git + GitHub
  - Any Prometheus/PromQL/Thanos understanding is a plus
- Mentor(s):
  - Giedrius Statkevičius (@GiedriusS, giedriuswork@gmail.com)
  - Saswata Mukherjee (@saswatamcode, saswataminsta@yahoo.com)
- Upstream Issue: https://github.com/thanos-io/thanos/issues/6517, https://github.com/thanos-community/promql-engine/issues/106
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/5a96f43c-d858-40c2-b556-2770ba6b03d4

#### Release the distributed query engine in Thanos

- Description:
  The Thanos engine is capable of executing queries in a distributed manner, by pushing down aggregations to other querier nodes. This querying mode is not yet integrated well in the UI and is not exposed to users.
  The goal of this project is to add the needed integrations to the Thanos UI and officially release the feature to end users.
- Expected Outcome:
  The expected outcome of the project is to have a fully integrated distributed querying capability through the Thanos UI.
- Recommended Skills:
  - Golang
  - React.js with TypeScript
  - Git + GitHub
  - Any Prometheus/PromQL/Thanos understanding is a plus
- Mentor(s):
  - Filip Petkovski (@fpetkovski, filip.petkovsky@gmail.com)
- Upstream Issue: https://github.com/thanos-io/thanos/issues/6124
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/3d6d3534-24e9-4261-9b91-7de3d78554f7

### Vitess

#### Continue the migration to React and enhance existing frontend UI

- Description: Vitess uses arewefastyet to automatically benchmark its codebase and ensure no performance regression is introduced. The mentee will have the responsibility of continuing the UI that was previously created using React/Vite.
- Expected Outcome: The expected outcome is to continue working on the Frontend UI that was developed during the 2023-summer term, that includes adding an admin UI, adding a feature to ensure the consistency of the results, improving the overall UX of the website, and add new pages to improve the scope of arewefastyet. The full list of expected work can be found in the issue linked below.
- Recommended Skills: React +++, Docker ++, Vite +, REST API +++, Golang ++

- Mentor(s):
  - Florent Poinsard @fouioui florent@planetscale.com
- Upstream Issue (URL): https://github.com/vitessio/arewefastyet/issues/415
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/10d70edd-60ec-409b-8801-0fb752501b12


### OpenKruise

#### Integrate Openkruise workload with ArgoCD and Helm

- Description: ArgoCD and Helm are popular tools to delivery k8s workload, yet currently only the k8s built-in workload are supported out-of-box for ArgoCD and Helm. OpenKruise provide advanced worklood that resemble with the built-in workload,  users can use OpenKruise workload with ArgoCD and Helm, yet they cannot tell ArgoCD and Helm whether Openkruise workload is ready or not. 
- Expected Outcome:
  - Improve ArgoCD integration by writing custom lua script to tell whether OpenKruise workload is healthy. The lua script can be submited to the Argo-CD repository.
  - Improve Helm intergration by building a job container that can check whether OpenKruise workload is healthy during helm install/upgrade process. 
- Recommended Skills: Lua ,Docker, Kubernetes
- Mentor(s):
    - Zhang zhen (@furykerry, furykerry@gmail.com)
    - Zhao Mingshan (@zmberg, berg.zms@gmail.com)
- Upstream Issue: https://github.com/openkruise/kruise/issues/1345
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/f603a2e7-9af2-40b2-a74f-109cad843de1

### Volcano

#### Support NPU accelerator scheduling in Volcano

- Description: design and implement NPU accelerator scheduling in Volcano including the vitrualized NPU resource scheduling, job controller enhancement for NPU distributed training, NPU topology scheduling and so on.
- Expected Outcome:  
  - design doc and feature user guide
  - implement NPU topology scheduling
  - implement job controller enhancement
  - vitrualized NPU resource scheduling
- Recommend Skills: Go, Kubernetes, Volcano
- Mentor(s):
  william wang(@william-wang, wang.platform@gmail.com)
  wang yang(@wangyang0616, wangyang8126@gmail.com)
- Upstream Issue (URL): https://github.com/volcano-sh/volcano/issues/3019
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/2d07fac8-9206-4299-a9fe-a55f366a38f3

#### Build a new elastic resource quota mechinism in Volcano 

- Description: design and implement a new hierarchical elastic resource quota mechinism to support resource lending and borrowing to improve the cluster utilization for multi-tenants environment. 
- Expected Outcome:  
  - design doc and how to use
  - implement a elastic resource quota mechinism to support min, max and resource sharing
  - implement the hierarchical resource quota
  - produce Blogs about these new cases.
- Recommend Skills: Go, Kubernetes, Volcano
- Mentor(s):
  william wang(@william-wang, wang.platform@gmail.com)
  wang yang(@wangyang0616, wangyang8126@gmail.com)
- Upstream Issue (URL): https://github.com/volcano-sh/volcano/issues/3018
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ffbb6bb3-b9d1-4e96-9f72-4a0566f6b0c3

#### Add user guidance for jobflow

- Description: Since jobflow is an important built-in orchestration engine for Volcano, it is still lack of user guidance. Please add more docs to demonstrate its installation, usage, tips and so on. 
- Expected Outcome: Add docs into volcano-sh/volcano/docs/user-guide and describe the usage of jobflow.
- Recommended Skills: Volcano, jobflow
- Mentor(s): Thor Wu (@Thor-wl, 13164644535@163.com)
- Upstream Issue: https://github.com/volcano-sh/volcano/issues/3013
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/757e329b-0083-4720-bd96-8bbbd6a7aeb3

#### Fix bugs for jobflow to enhance its stability

- Description: As a built-in orchestration engine for Volcano, jobflow acts as an improtant role for users and it's still new-born. Many issues related to its stability are reported recently. Please help make full test for job-flow on the classical scenarios and reslove bugs reported in issues.
- Expected Outcome: Make full test for jobflow and output the test report, fix bugs reported in recent issues.
- Recommended Skills: Volcano, jobflow, Golang, UT, E2E
- Mentor(s): Thor Wu (@Thor-wl, 13164644535@163.com)
- Upstream Issue: https://github.com/volcano-sh/volcano/issues/3014
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/2fa8d7b8-01fa-4375-b3a8-1b626348fedd

### WasmEdge

#### Add matrix operations for OpenCVMini-Wasm-Plugin

- Description: [WasmEdge](https://github.com/WasmEdge/WasmEdge) is a WebAssembly runtime that supports both interpreter and ahead-of-time modes. To expand its capabilities, WasmEdge provides a plugin system that helps people attach more existing software. OpenCVMini is one of them, intended to help users get a limited OpenCV interface. With this feature, AI inference will have more flexible helper functions for pre-processing and post-processing. In this mentorship, we aim to add more OpenCV capabilities to the WasmEdge environment.
- Expected Outcome:
  - Define the new interfaces for the OpenCVMini plugin, which supports those functions listed in the upstream issue.
  - Use the above interface and generate related APIs.
  - Implement the functions of the plugin with OpenCV 4.x.
  - Design unit tests and examples for verifying the above functions.
  - Enable the building, testing, and packaging on the upstream CI.
  - Write documents about how to build and use this plugin.
- Recommended Skills:
  - C++
  - Basic understanding of the Wasm spec
  - Basic understanding of using OpenCV
  - Basic understanding of writing Rust programs
- Mentor(s):
  - Lîm Tsú-thuàn (@dannypsnl, dannypsnl@secondstate.io)
  - Hung-Ying Tai (@hydai, hydai@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2680
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/f21bec94-085e-4e2d-94ac-3b61b4471818

#### Support AOT mode in proxy-wasm

- Description: [WasmEdge](https://github.com/WasmEdge/WasmEdge) is a WebAssembly runtime that supports both interpreter and ahead-of-time modes. For proxy-wasm support, WasmEdge only provides the interpreter mode currently. Such as the other runtimes, WasmEdge should be able to support the AOT mode for better performance. In this mentorship, the mentees will help the WasmEdge project to complete the AOT mode in proxy-wasm proposal and write the docs for examples of running with proxy-wasm.
- Expected Outcome:
  - Modify the Bazel file to include the LLVM dependency.
  - Modify the code to support running WASM in AOT mode.
  - Add the documentation of proxy-wasm in the WasmEdge docs repo.
- Recommended Skills:
  - C++
  - Basic understanding of bazel
- Mentor(s):
  - Yi-Ying He (@q82419, yiying@secondstate.io)
  - Hung-Ying Tai (@hydai, hydai@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2686
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/3ee046ab-29d9-4e5c-bb7a-4564bd4e2765

#### Create a Rust crate for YOLO model

- Description:
  With [WASI-NN plugins](https://wasmedge.org/docs/category/neural-networks-for-wasi), WasmEdge is well-suited for running AI applications. However, AI applications are more than just the model. The application must pre-process data (such as images, audio and video) into TFLite / PyTorch formats, and convert the inference results back into application data in post-processing. Here are some examples:

  * The [mediapipe-rs](https://github.com/WasmEdge/mediapipe-rs) project provides a Rust SDK to build applications for the mediapipe AI models.
  * The [llama2.c](https://github.com/karpathy/llama2.c) application is [compiled to Wasm and runs in WasmEdge](https://medium.com/@michaelyuan_88928/running-llama2-c-in-wasmedge-15291795c470) to generate text using the [llama2](https://ai.meta.com/llama/) models.

  In this project, we would like to build a Rust SDK to support applications on the [YOLO models](https://pjreddie.com/darknet/yolo/).
- Expected Outcome:
  - A Rust SDK that implements the pre-processing and post-processing functions required for the YOLO models. Those functions are implemented in OpenCV and Python in the official YOLO release.
  - Both image and video inputs should be supported.
  - Examples and documentation should be provided.
- Recommended Skills:
  - OpenCV
  - Rust
  - Tensorflow / Pytorch
  - WebAssembly
- Mentor(s):
  - Michael Yuan (@juntao, michael@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2690
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/63adcf97-cd3e-4c96-a5fc-6076b5a5d511

#### Create a ffmpeg plugin

- Description:
  The [mediapipe-rs](https://github.com/WasmEdge/mediapipe-rs) project provides a Rust SDK to support mediapipe AI models. The SDK provides utility functions to pre-process application data (such as images, audio and video) into TFLite / PyTorch formats, and convert the inference results back into application data. In order to accomplish this, the [mediapipe-rs](https://github.com/WasmEdge/mediapipe-rs) project has made extensive use of the [ffmpeg](https://www.ffmpeg.org/) library. It [compiles ffmpeg to Wasm](https://github.com/WasmEdge/mediapipe-rs/blob/main/src/build.rs) and then builds it together with the application binary.

  However, the issue with this approach is that those Wasm-compiled ffmpeg functions are slow. We believe a better approach is to create a ffmpeg plugin for WasmEdge, and allow Wasm applications to call native ffmpeg functions as host functions.
- Expected Outcome:
  - The deliverables will be
    - A WasmEdge plugin for ffmpeg that is similar to the [WasmEdge OpenCV-mini plugin](https://github.com/WasmEdge/WasmEdge/tree/master/plugins/wasmedge_opencvmini). That is to re-export ffmpeg functions in C style as plugin functions as covered in the [plugin developer guide](https://wasmedge.org/docs/category/wasmedge-plugin-system).
    - A Rust SDK for Wasm programs to access ffmpeg functions in the plugin. Similar to the [WasmEdge OpenCV-mini SDK](https://github.com/second-state/opencvmini)
    - Refactor the mediapipe-rs project to use the ffmpeg plugin instead of compiling ffmpeg to Wasm.
  - We expect the deliverable will cover at least 80% of all ffmpeg functions, and have complete unit test and documentation coverage.
- Recommended Skills:
  - C/C++
  - ffmpeg
  - Rust
  - WebAssembly
- Mentor(s):
  - Michael Yuan (@juntao, michael@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2689
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/41a8bf79-a903-4c03-afb7-256fd373c0b0

---------------
# Term 02 - 2023 June - August

Status: Complete

Mentorship duration - three months (12 weeks - full-time schedule)

### Timeline

| activity | date |
| --- | --- |   
| project proposals due | Tue, May 9, 5:00 PM PDT |
| mentee applications open | Wed May 10 - Tue May 23, 5:00 PM PDT |
| application review/admission decisions | Wed May 24 - Mon May 29, 5:00 PM PDT |
| Mentorship program begins with the initial work assignments |  Thur June 1 (Week 1) | 
| Midterm mentee evaluations and first stipend payments | Wed July 12 (Week 6) |
| Final mentee evaluations and mentee feedback/blog submission due, second and final stipend payment approvals | Wed Aug 23, 5:00 PM PST (Week 12) |
| Last day of term | Thur Aug 31 |

### Project Instructions

Project maintainers and potential mentors are welcome to propose their mentoring project ideas via submitting a PR to GitHub here https://github.com/cncf/mentoring/blob/main/programs/lfx-mentorship/2023/02-Jun-Aug/project_ideas.md, by Tuesday, May 9, 2023.

### Application instructions

Mentee application instructions can be found on the [Program Guidelines](https://github.com/cncf/mentoring/blob/main/programs/lfx-mentorship/README.md#program-guidelines) page.

---

Table of Contents

- [Armada](#armada)
  - [Build interfaces around Postgres for Armada](#build-interfaces-around-postgres-for-armada)
- [Cilium/Tetragon](#ciliumtetragon)
  - [Implement a Kubernetes operator to maintain pod IP to pod metadata mapping](#implement-a-kubernetes-operator-to-maintain-pod-ip-to-pod-metadata-mapping)
- [CNCF Landscape ](#cncf-landscape)
  - [UX / UI Improvements II](#ux--ui-improvements-ii)
- [CoreDNS](#coredns)
  - [Add DNS-over-QUIC (DoQ) and/or DNS-over-HTTP/3 (DoH3) support](#add-dns-over-quic-doq-andor-dns-over-http3-doh3-support)
- [Jaeger](#jaeger)
  - [Upgrade Jaeger's internal telemetry to OpenTelemetry](#upgrade-jaegers-internal-telemetry-to-opentelemetry)
  - [Implement Critical Path analysis](#implement-critical-path-analysis)
- [Knative](#knative)
  - [Self-Balancing Knative Kafka Broker partitions](#self-balancing-knative-kafka-broker-partitions)
  - [Porting Knative Serving to Microshift](#porting-knative-serving-to-microshift)
- [Konveyor](#konveyor)
  - [Add Integration test suite and components testing to Konveyor](#add-integration-test-suite-and-components-testing-to-konveyor)
- [KubeArmor](#kubearmor)
  - [Implement DNS visibility with KubeArmor](#implement-dns-visibility-with-kubearmor)
  - [Manage KubeArmor policies using OCI registry and use OCI hooks for container events](#manage-kubearmor-policies-using-oci-registry-and-use-oci-hooks-for-container-events)
- [Kubescape](#kubescape)
  - [Store Kubescape configuration scan results as CRs](#store-kubescape-configuration-scan-results-as-crs)
  - [Prometheus exporter for image vulnerabilities](#prometheus-exporter-for-image-vulnerabilities)
  - [Vulnerability-based Dockerfile generator](#vulnerability-based-dockerfile-generator)
- [KubeVela](#kubevela)
  - [Expand multiple database drivers for the API server](#expand-multiple-database-drivers-for-the-api-server)
  - [Auto-generate the TypeScript and Java languages API SDK](#auto-generate-the-typescript-and-java-languages-api-sdk)
- [Kyverno](#kyverno)
  - [Kuttl tests for the Kyverno policy library](#kuttl-tests-for-the-kyverno-policy-library)
  - [Sigstore Cosign Updates](#sigstore-cosign-updates)
  - [ValidatingAdmissionPolicy support, Phase 2](#validatingadmissionpolicy-support-phase-2)
  - [Cleanup Policies, Phase 2](#cleanup-policies-phase-2)
- [LitmusChaos](#litmuschaos)
  - [Migrate chaos workflow api from graphql to rest and improve chaos center code base](#migrate-chaos-workflow-api-from-graphql-to-rest-and-improve-chaos-center-code-base)
  - [Enhance/Upgrade chaos operator and chaos exporter module](#enhanceupgrade-chaos-operator-and-chaos-exporter-module)
- [Meshery](#meshery)
  - [Meshery UI Permissions Framework](#meshery-ui-permissions-framework)
  - [OPA policy evaluation in-browser using WebAssembly and Rego](#opa-policy-evaluation-in-browser-using-webassembly-and-rego)
  - [Adopt OCI as the packaging and distribution format for Meshery MeshModels](#adopt-oci-as-the-packaging-and-distribution-format-for-meshery-meshmodels)
  - [OCI compatible Kubernetes ontology](#oci-compatible-kubernetes-ontology)
- [Notary](#notary)
  - [Design and implement the new Notary website](#design-and-implement-the-new-notary-website)
  - [Develop content for Notary documentation and blogs](#develop-content-for-notary-documentation-and-blogs)
- [ORAS](#oras)
  - [Design and implement Artifact Explore web portal](#design-and-implement-artifact-explore-web-portal)
  - [Refactor the ORAS documentation structure and write new user guides](#refactor-the-oras-documentation-structure-and-write-new-user-guides)
- [Service Mesh Performance](#service-mesh-performance)
  - [Service Mesh Performance IDE Plugin](#service-mesh-performance-ide-plugin)
- [Strimzi](#strimzi)
  - [Proof of Concept of an MQTT to Apache Kafka bridge for producing messages](#proof-of-concept-of-an-mqtt-to-apache-kafka-bridge-for-producing-messages)
- [Thanos](#thanos)
  - [Continuation of add query observability for the new engine](#continuation-of-add-query-observability-for-the-new-engine)
- [Vitess](#vitess)
  - [Rework the frontend UI of Vitess’ benchmarking tools](#rework-the-frontend-ui-of-vitess-benchmarking-tools)
- [WasmEdge](#wasmedge)
  - [Serialization Completion](#serialization-completion)
  - [zlib Plugin Support](#zlib-plugin-support)
  - [Support Tensorflow and PyTorch in WasmEdge’s Python runtime](#support-tensorflow-and-pytorch-in-wasmedges-python-runtime)
  - [A stream log processing framework for WasmEdge](#a-stream-log-processing-framework-for-wasmedge)

---

## Accepted projects

### Armada

#### Build interfaces around Postgres for Armada

- Description: Open source projects should not be hard coded to a particular Database. Armada currently only allows users to use Postgres. This project is to build interfaces around our connections to Postgres so we can allow other databases.
- Expected outcomes:
  - A interface is created that allows Armada to interact with any SQL database without exposing implementation details of postgres
  - increase Test coverage
- Recommend Skills: Go, SQL
- Mentor(s):
  - Geoffrey Wilson, @suprjinx, geoff@gr-oss.io
  - Kevin Hannon, @kannon92, kevin@gr-oss.io
- Upstream Issue (URL): https://github.com/armadaproject/armada/issues/2121
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/73d90321-62b3-498e-bf37-d899ec99df9e

### Cilium/Tetragon

#### Implement a Kubernetes operator to maintain pod IP to pod metadata mapping

- Description:

  Tetragon currently depends on Cilium to look up pod information by their IP
  addresses. The goal of this project is to remove this Cilium dependency by
  implementing a Kubernetes operator that provides this information. The idea
  is for this operator to maintain a new custom resource that provide a mapping
  from IPs to the small subset of pod information that Tetragon needs.

- Expected Outcome:
  - A Kubernetes operator that maintains IP to pod info mapping used by Tetragon.
  - The operator should be installable via Helm as a Kubernetes deployment.
  - Replace Cilium dependency in the code base with this new custom resource.
  - Some performance benchmarks in a high pod churn environment.
- Recommended Skills:
  - Goassign
  - Kubernetes
- Mentor(s):
  - Kornilios Kourtis (@kkourt, kornilios@isovalent.com)
  - Michi Mutsuzaki (@michi-covalent, michi@isovalent.com)
- Upstream Issue:
  - https://github.com/cilium/tetragon/issues/794
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/659fe584-68e6-46bf-bd13-12653ef60268

### CNCF Landscape 

#### UX / UI Improvements II

- Description: With your collaboration, we aim to analyze findings and meaningful information (quantitative and qualitative data) and run a series of ideation rounds. We will create user personas, empathy maps, and other UX deliverables that will be the foundation to lay out a set of solutions to improve the current way to search, navigate and find relevant information on the Landscape.
- Expected Outcome: Creation user personas, empathy maps, and other UX deliverables.
- Recommended Skills: UX reaserach, desighn thinking, Figma and prototyping. 
- Mentors: Andrea Velázquez @andreuxxxx andrea@buoyant.io, Nate W. @nate-double-u natew@cncf.io, Chris Aniszczyk @caniszczyk caniszczyk@linuxfoundation.org
- Upstream Issue: https://github.com/cncf/landscape/issues/2467
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/c45cc842-278f-4663-9ff4-deecc3fc040d

### CoreDNS

#### Add DNS-over-QUIC (DoQ) and/or DNS-over-HTTP/3 (DoH3) support

- Description: DNS-over-QUIC (DoQ) and DNS-over-HTTP/3 (DoH3) are relatively new protocols for transmitting DNS queries with security and privacy. Additionally, DoQ and DoH3 also offers other benefits such as improved latency and better error detection. The goal of this proposal is to add DoQ and/or DoH3 support to CoreDNS.
- Expected Outcome: An implementation of DoQ or DoH3 for CoreDNS. A stretch goal of adding both DoQ and DoH3 is also within scope.
- Recommended Skills: Golang, DNS.
- Mentor(s): Yong Tang @yongtang (yong.tang.github@outlook.com); Chris O'Haver @chrisohaver (cohaver@infoblox.com)
- Upstream Issue (URL): https://github.com/coredns/coredns/issues/5583, https://github.com/coredns/coredns/issues/5539
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/dd10bf62-53d1-4a96-bea2-65bbb78bd10e

### Jaeger

#### Upgrade Jaeger's internal telemetry to OpenTelemetry

- Description: historically, the Jaeger backend used the OpenTracing API, with Jaeger's own Go SDK `jaeger-client-go`, for instrumenting its own internals for distributed tracing. Since Jaeger's SDKs have been deprecated, we want to upgrade the Jaeger backend to use the OpenTelemetry tracing API and SDK directly.
- Expected Outcome:
  - Replace the use of OpenTracing API with OpenTelemetry
  - Remove `jaeger-client-go` and `jaeger-lib` as dependencies
  - Remove `opentracing-go` and `opentracing-contrib/*` as dependencies
  - Switch to standard instrumentation libraries where available (e.g. for HTTP, gRPC)
  - Rethink/rework `crossdock` integration tests to test end-to-end flow with OpenTelemetry data
  - Publish a blog post on medium.com/jaegertracing documenting the experience
- Recommended Skills: Go
- Mentor(s): Yuri Shkuro (@yurishkuro, github@ysh.us); Albert Teoh (@albertteoh, see.kwang.teoh@gmail.com)
- Upstream Issue: https://github.com/jaegertracing/jaeger/issues/3381
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/b8009398-1252-4f63-82fe-363846ccc11d

#### Implement Critical Path analysis

- Description: Jaeger (https://jaegertracing.io) is a popular platform for distributed tracing. Critical path analysis is an important tool in the latency investigations. This project aims to add support for critical path analysis to Jaeger UI.
- Expected outcomes:
  - Implement critical path determination algorithm (maybe in the backend)
  - Enhance Trace Timeline view to overlay critical path on top of the trace.
  - Add relevant documentation to the Jaeger website
  - Author a blog post on Jaeger blog explaining the new feature
- Stretch goals:
  - Add critical path visualization to other trace views (graph, table, flamechart)
- Recommended Skills: Javascript, Typescript, Go
- Mentor(s): Yuri Shkuro (@yurishkuro, github@ysh.us), Yash Sharma (yashrsharma44@meta.com)
- Upstream Issue (URL): https://github.com/jaegertracing/jaeger-ui/issues/1288
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0fc6c44b-5ddf-467f-8016-72cc35b4e3ff

### Knative

#### Self-Balancing Knative Kafka Broker partitions

- Description: Creating a Knative Kafka Broker requires developers to specify the number of partitions the backing Kafka topic should have, however, this is not an easy decision to make and it requires planning based on the expected load the Knative Broker could receive. This project aims to remove this configuration setting by having an autoscaler that is responsible to add or remove partitions based on the effective load the Knative Kafka Broker receives while preserving [ordered and unordered delivery features](https://knative.dev/docs/eventing/brokers/broker-types/kafka-broker/#configuring-the-order-of-delivered-events) for Triggers.
- Expected outcome: A Knative Kafka Broker can be created without setting the number of partitions and the number of partitions for a topic backing the Knative Kafka Broker increases or decreases based on the observed load received.
- Recommended Skills: Kubernetes, Apache Kafka, Go, Java
- Mentor(s): Pierangelo Di Pilato @pierDipi (pierdipi AT redhat DOT com), Ali Ok @aliok (aliok AT redhat DOT com)
- Upstream Issue (URL): https://github.com/knative-sandbox/eventing-kafka-broker/issues/2917
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ac483209-2b08-4f74-aaa5-4ab3203b0677

#### Porting Knative Serving to Microshift

- Description: More and more workload is moving towards running on the edge. We saw experiments running Kubernetes on vehicles, fighter jets, 5G antenna and various far edge, near edge and fat edge environments. We would like to see what the challenges are when Knative is run in a resource limited environment. While there are multiple edge-friendly Kubernetes distributions, we would like to see [Microshift](https://github.com/openshift/microshift) used as the base platform. Knative consists of Serving and Eventing modules but focusing on Knative Serving as a first step should be more approachable. The project consists of 2 stages. First one is to run Knative on Microshift with minimal resources. This requires finding out problems here, solving them. A stretch goal is to find out what happens with architectures other than x86_64.
- Expected outcome:  Having Knative Serving with an ingress layer running on top of Microshift. Having a Hello-World Knative Service running on top. Finding issues blocking the edge setup, and possibly fixing them.
- Recommended Skills: Golang, Kubernetes, Knative, good understanding of networking, good understanding of CI/CD
- Mentor(s): Reto Lehmann @ReToCode (rlehmann AT redhat DOT com),  Stavros Kontopoulos @skonto (skontopo AT redhat DOT com)
- Upstream Issue (URL): https://github.com/knative/serving/issues/12718
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/830eb064-cf8a-4a8e-bba3-97d429a6ca79

### Konveyor

#### Add Integration test suite and components testing to Konveyor

- Description:
The Konveyor project helps modernize applications by providing open source tools to rehost, replatform, and refactor applications to Kubernetes and cloud-native technologies.We’re looking for help on building integration tests on application level as well as work on missing parts of Konveyor component tests.There is open testing work to better applications analysis, tasks coverage, more detailed Hub API tests and Hub integration with addons. All of those use the Hub API that is covered with basic tests already. Based on existing Hub API tests, it is expected to continue work to cover more Konveyor functionality with tests.
The development environment is based on golang and Kubernetes. A minikube instance will work well for local development on Linux or Mac systems.
- Expected Outcome:
  - Integration test suite and components testing added to existing Konveyor upstream automated test suite
- Recommended Skills:
  - Go
  - Basic software development skills (command line, git)
- Mentor(s):
  - Marek Aufart (@aufi, maufart@redhat.com)
  - David Zager (@djzager, dzager@redhat.com)
- Upstream Issue:
  - https://github.com/konveyor/tackle2-operator/issues/220
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/78852896-9785-4156-bb9b-bc3c5cb6ed17

### KubeArmor

#### Implement DNS visibility with KubeArmor

* Description: The project aims to provide better visibility into the domains accessed from pods, with a focus on identifying and containing attacks that use techniques like Domain Generation Algorithms (DGA) to connect to remote command and control (C&C) servers. By gathering information on which domains are being accessed and applying network rules to allow only specific domains, the project aims to empower security operations (secops) teams to better prevent and respond to such attacks.
* Expected Outcome:  
  * KubeArmor to emit telemetry events for any DNS lookups from any pods.
  * Ability to see egress DNS lookups done from any pods using karmor summary.
  * Documentation
* Recommended Skills: Go, K8s, familiarity with network security and a basic understanding of KubeArmor is a plus.
* Mentors:
  * Anurag Kumar (@kranurag7, contact.anurag7@gmail.com)
  * Barun Acharya (@daemon1024, barun1024@gmail.com)
  * Ankur Kothiwal (@Ankurk99, ankur.kothiwal99@gmail.com)
* Upstream Issue: [Issue #1219](https://github.com/kubearmor/KubeArmor/issues/1219)
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/cfa22331-36f3-4d20-abf0-667a31fd2ba8

#### Manage KubeArmor policies using OCI registry and use OCI hooks for container events

* Description: The feature aims to manage KubeArmor policies using OCI registry and use OCI hooks to get container events. Currently, KubeArmor uses a UNIX domain socket file to watch for container events, but the proposed feature aims to use OCI hooks instead.
* Expected Outcome: To provide a more secure and efficient way of managing KubeArmor policies by leveraging OCI registry. Storing policies in OCI registries will make it easier to distribute policies across multiple clusters and environments. Using OCI hooks will also reduce the overhead of monitoring container events and make it easier to integrate KubeArmor with other container runtimes.
* Recommended Skills: Go, K8s, understanding of the Open Container Initiative (OCI) and container runtimes.
* Mentors:
  * Anurag Kumar (@kranurag7, contact.anurag7@gmail.com)
  * Barun Acharya (@daemon1024, barun1024@gmail.com)
  * Ankur Kothiwal (@Ankurk99, ankur.kothiwal99@gmail.com)
* Upstream Issue: [Issue #1130](https://github.com/kubearmor/KubeArmor/issues/1130)
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/08d245cb-001f-4292-90eb-e8895189c77a

### Kubescape

#### Store Kubescape configuration scan results as CRs

- Description: [Kubescape](http://kubescape.io/) is a utility that can scan a Kubernetes cluster and report on its security posture. There is an "operator" which can be installed in the cluster to perform scheduled scans scan, but this is largely used to send the data to an external service. In this project, you will implement a mechanism in the Kubescape operator to save scan results locally in a custom resource (CR), as well as a watch so that scans can be performed on cluster state changes.
- Expected Outcome: Having the ability to scan a cluster when it changes, and have the results saved inside the cluster. This will allow users and automations to judge the security posture of changes that are made to the cluster (for example, deployments or rollouts.)
- Recommended Skills: Go
- Mentors:
  - Ben Hirschberg (@slashben, ben AT armosec.io)
  - Craig Box (@craigbox, craigb AT armosec.io)
  - David Wertenteil (@dwertent, dwertent AT armosec.io)
 - Upstream Issue: https://github.com/kubescape/kubescape/issues/1225
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1a6a7aaf-7436-431b-9131-9422e4b2fb71

#### Prometheus exporter for image vulnerabilities

- Description: Kubescape has a component that runs in-cluster which performs image scanning on all the container images deployed to a cluster. This function is largely used to send the data to an external service.  In this projet, you will develop a Prometheus exporter for the image vulnerability information produced by Kubescape.  This will allow users to access the data from within the cluster, as well as use it for alerting.
- Expected Outcome: Access to cluster vulnerability data through Prometheus.  For example, you should have the ability to alert on number or percentage of "Critical" level vulnerabilities in containers running in the cluster.
- Recommended Skills: Go, Prometheus
- Mentors:
  - Ben Hirschberg (@slashben, ben AT armosec.io)
  - Craig Box (@craigbox, craigb AT armosec.io)
  - David Wertenteil (@dwertent, dwertent AT armosec.io)
- Upstream Issue: https://github.com/kubescape/kubescape/issues/1226
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/8c701687-7cde-42fc-8195-08d35fdb5ee8

#### Vulnerability-based Dockerfile generator

- Description: Kubescape can detect vulnerabilities in a container image. Some can automatically be remediated by changing the base image version (or other package information) inside the Dockerfile which created the image. This project is to automate this remediation.
- Expected Outcome: An enhancement to Kubescape to generate a Dockerfile that proposes fixes for vulnerabilities found in a container image. This may be by integration with existing open source tools or developing something new.
- Recommended Skills: Go
- Mentors:
  - Ben Hirschberg (@slashben, ben AT armosec.io)
  - Craig Box (@craigbox, craigb AT armosec.io)
  - David Wertenteil (@dwertent, dwertent AT armosec.io)
- Upstream Issue: https://github.com/kubescape/kubescape/issues/1227
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/fbaf3d52-77ee-469c-8eb4-3e0378896159


### KubeVela

#### Expand multiple database drivers for the API server
- Description: Now KubeVela's VelaUX uses two kinds of Database to store metadata: Kubernetes ConfigMap and MongoDB. As more users are expecting using different kinds of database. We proposing to expanding multiple database drivers for the VelaUX API server. 
- Expected Outcome: The outcome of this project will be expand two more database driver for KubeVela VelaUX API server:
  - Mysql
  - PostgreSQL
- Recommended Skills:
  - Golang
  - Kubernetes
  - Backend APIs Development
- Mentor(s):
  - Qiao Zhongpei (@chivalryq, chivalry.pp@gmail.com)
  - Zeng Qingguo (@barnettZQG, barnett.zqg@gmail.com)
- Upstream Issue (URL): https://github.com/kubevela/kubevela/issues/5426
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/21c95d53-dd75-4a2f-a8fd-92374c54940d

#### Auto-generate the TypeScript and Java languages API SDK
- Description: The VelaUX API server follows the Open API schema. It could auto-generate the swagger configs via CLI. When VelaUX frontend or other projects need to call these API, they must write the model code and request the API code. We can provide SDK for them to start faster. [OpenAPI generator](https://openapi-generator.tech/) could help to generate most codes. But there are still some special cases like:
  - Dynamic component/trait/policy/workflowsteps properties need to be generated according to CUE.
  - Automatically handles the user authentication process, including automatically refreshing tokens.
  - The API definition may be incomplete accuracy, we should check it to generate high-quality code.
- Expected Outcome: The outcome of this project will be expand two more database driver for KubeVela VelaUX API server:
  - VelaUX APIServer TypeScript SDK
  - VelaUX APIServer Java SDK
- Recommended Skills:
  - Golang
  - Kubernetes
  - Backend APIs Development
  - OpenAPI schema
  - CUE
- Mentor(s):
  - Qiao Zhongpei (@chivalryq, chivalry.pp@gmail.com)
  - Yin Da (@somefive, Somefive@foxmail.com)
- Upstream Issue (URL): https://github.com/kubevela/kubevela/issues/5428
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/b97b2f2d-4dbd-45f5-9121-0e865aa6dfd9

### Kyverno

#### Kuttl tests for the Kyverno policy library

- Description: Kyverno has the largest policy library of any policy tool for Kubernetes. Ensuring that policies work effectively across releases of both Kyverno and Kubernetes is important for users. Additionally, these tests can be leveraged in the CI processes ensuring that changes to the Kyverno codebase do not cause regressions which impact areas relevant to these policies. In this mentorship, you will learn how the `kuttl` tool works and write test cases using `kuttl` to cover all policies in the official Kyverno policy library.
- Expected outcome: All policies have corresponding tests using the `kuttl` tool.
- Recommended Skills: Kubernetes, Kyverno
- Mentor(s): Chip Zoller @chipzoller (chipzoller AT gmail DOT com)
- Upstream Issue (URL): https://github.com/kyverno/policies/issues/546
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/85ebe560-e9ee-42fe-9dff-f8dc6a11ef27

#### Sigstore Cosign Updates

- Description: Kyverno supports image signature and attestation verification using the Sigstore Cosign tooling. Re-implement the Kyverno Sigstore Cosign module to use OCI artifacts and references and remove dependencies to the Cosign CLI packages.
- Expected outcome: Kyverno can use OCI artifacts to verify container images that are in Cosign format.
- Recommended Skills: Golang, Kubernetes, Kyverno
- Mentor(s):
  - Shuting Zhao @realshuting (shuting AT nirmata DOT com)
  - Vishal Choudhary @Vishal-Chdhry (contactvishaltech AT gmail DOT com)
- Upstream Issue (URL): https://github.com/kyverno/kyverno/issues/7087
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/cabb007c-5669-4b16-8778-36d995a71591

#### ValidatingAdmissionPolicy support, Phase 2

- Description: Kyverno is working towards support of ValidatingAdmissionPolicy (CEL admission). Extend this support for other items such as CLI, reporting, and auto-generating ValidatingAdmissionPolicies from Kyverno policies.
- Expected outcome: Extended support and integration with ValidatingAdmissionPolicies
- Recommended Skills: Golang, Kubernetes, Kyverno
- Mentor(s):
  - Jim Bugwadia @jimbugwadia (jim AT nirmata DOT com)
  - Mariam Fahmy @MariamFahmy98 (mariamfahmy66 AT gmail DOT com)
- Upstream Issue (URL): https://github.com/kyverno/kyverno/issues/7088
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e4be265d-fa05-46b7-8fad-2585b6a76082

#### Cleanup Policies, Phase 2

- Description: Kyverno has a policy type called Cleanup Policies which allow removal of resources defined in a policy. In this second phase, we would like to extend this ability to cleanup resources based upon defining a label for even more fine-grained control.
- Expected outcome: Extend Cleanup Policies feature by allowing per-resource removal based upon label assignment
- Recommended Skills: Golang, Kubernetes, Kyverno
- Mentor(s): Charles-Edouard Brétéché @eddycharly (charled.breteche AT gmail DOT com)
- Upstream Issue (URL):
  - https://github.com/kyverno/kyverno/issues/5748
  - https://github.com/kyverno/KDP/blob/main/proposals/cleanup.md#proposal
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/4689c5fa-165e-4015-ad21-951d9babcb7e

### LitmusChaos

#### Enhance/improve chaos center code base and redesign chaos workflow apis
- Description: This project focuses on enhancing and improving the Chaos Center code base, specifically redesigning the Chaos Workflow APIs to provide an enhanced user experience. The main objectives include refining the functionality of the Chaos Workflow and Workflow Run APIs, modularizing the chaos-workflow package into separate packages, and addressing security vulnerabilities and golangci-lint issues in the Chaos Center backend components. The project aims to deliver a more robust and secure Chaos Center platform, offering improved usability and performance for users.
- Expected outcome: The outcome of this project will be improved functionality, security, and usability of the chaos workflow APIs and chaos-center backend components through the implementation of new features, refactoring of existing code, and addressing of security vulnerabilities.
- Recommended Skills:
  - Golang
  - Kubernetes
  - Backend APIs Development
- Mentor(s):
  - Amit Kumar Das (@amityt, amit.das@harness.io)
  - Arkajyoti Mukherjee (@arkajyotiMukherjee, arkajyoti.mukherjee@harness.io)
- Upstream Issue (URL): https://github.com/litmuschaos/litmus/issues/3970
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/983193ea-9cca-405f-baa5-e6ade4df1ba2

#### Enhance/Upgrade chaos operator and chaos exporter module

- Description: LitmusChaos is an open source Chaos Engineering platform that enables teams to identify weaknesses & potential outages in infrastructures by inducing chaos tests in a controlled way. This project idea involves upgrading the Chaos Operator and Chaos Exporter repositories by updating their dependencies, addressing security vulnerabilities, and adding new functionality. Specifically, the project aims to upgrade the operator-sdk and Prometheus exporter versions, add new Prometheus metrics to the Chaos Exporter, and fix security vulnerabilities pointed out by trivy and golangci-lint. Furthermore, the project seeks to add unit test cases to both repositories to ensure that their functionality is robust and reliable. Overall, this project aims to improve the stability, security, and functionality of the Chaos Operator and Chaos Exporter repositories, making them better suited for use in production environments.
- Expected outcome: The outcome of this project will be improved stability, security, and functionality of the Chaos Operator and Chaos Exporter modules through the upgrade of dependencies, addition of new metrics, and implementation of unit tests.
- Recommended Skills:
  - Golang
  - Kubernetes and k8s golang client
  - Prometheus
- Mentor(s):
  - Shubham Chaudhary (@ispeakc0de, shubham.chaudhary@harness.io)
  - Vansh Bhatia (@vanshBhatia-A4k9, vansh.bhatia@harness.io)
- Upstream Issue (URL): https://github.com/litmuschaos/litmus/issues/3969
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/bd6e875a-a64c-4405-af1c-677d8c45014b

### Meshery

#### Meshery UI Permissions Framework

- Description: Meshery UI lacks a permissions framework. The existing internal implementation is simple, fragile and must be completely rewritten. The approach to implemention a permmissions framework includes using React.js and CASL.js. Meshery UI's approach needs to be extensible given that this framework will be an extension point for Remote Providers to supply their own permissions.
- Expected outcome: Definition of permissions and their enforcement in Meshery with an aim for deep granularity and extensibility with each user interface input component carrying a unique permission key id. Each key is then put into a group of keys in a keychain, keychains assigned to user roles, in turn, roles assigned to users. With users having the ability to create own custom roles, the framework will be dynamic based on the associated server-side permissions for the currently auth’ed user.
- Recommended Skills: React.js, CASL.js
- Mentor(s): Lee Calcote @leecalcote (leecalcote@gmail.com), Abhishek Kumar @Abhishek-kumar09 (abhimait1909@gmail.com)
- Upstream Issue (URL): https://github.com/meshery/meshery/issues/7436, https://github.com/meshery/meshery/issues/7382
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/f4a9804f-2e46-42a4-b2ae-ad3ea7b29734

#### OPA policy evaluation in-browser using WebAssembly and Rego

- Description: Meshery's highly dynamic infrastructure configuration capabilities require real-time evaluation of complex policies. Policies of various types and with a high number of parameters need to be evaluted client-side. With policies expressed in Rego, the goal of this project is to incorporate use of the https://github.com/open-policy-agent/golang-opa-wasm project into Meshery UI.
- Expected outcome: a powerful real-time multi-user collaboration experience.
- Recommended Skills: Golang, Open Policy Agent, WASM
- Mentor(s): Lee Calcote @leecalcote (leecalcote@gmail.com), Abhishek Kumar @Abhishek-kumar09 (abhimait1909@gmail.com)
- Upstream Issue (URL): https://github.com/meshery/meshery/issues/7019
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/005db8db-7efe-4433-9605-91d14174c72c

#### Adopt OCI as the packaging and distribution format for Meshery MeshModels

- Description: Meshery MeshModels represent a schema-based description of cloud native infratructure. MeshModels need to be portable between Meshery deployments as well as easily versionable in external repositories.
- Expected outcome:
  - Meshery clients (mesheryctl and Meshery UI) should be able to import/export MeshModels as OCI images.
  - Meshery clients (mesheryctl and Meshery UI) should be able to push/pull from OCI-compatible registries.
  - Stretch Goal: OCI image signing; Verify the authenticity of MeshModels using [cosign](https://github.com/sigstore/cosign).
  - Target registries: Meshery Catalog (https://meshery.io/catalog), Artifact Hub.
- Recommended Skills: Reactjs, Golang, GraphQL
- Mentor(s): Lee Calcote @leecalcote (leecalcote@gmail.com)
- Upstream Issue (URL): https://github.com/meshery/meshery/issues/6447
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/26377c30-9ffd-41e3-bfea-839bf126f8f6

#### OCI compatible Kubernetes ontology

- Description: Network topologies and graph databases go hand-in-hand. The OpenAPI specifications for Kubernetes provides taxonomy, but augmenting a graph data model with formalized ontologies enables any number of capabilities, one of the more straightforward is the inferencing requisite for natural language processing, and consequently, a human-centric query / response interaction becomes becomes possible. More importantly, more advanced systems can be built when a graph data model of connected systems is upgraded to be a knowledge semantic graph. Deliverables (among other items):

- MeshModel capabilities browser
- Import/export of MeshModel models and components as OCI images
- augmentation of cuelang-based component generator

- Recommended Skills: cuelang, golang, OCI
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com)
- Issue: https://github.com/cncf/tag-network/issues/24
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/bb8ddf84-31d7-4a89-9e4b-e6aa9601c0db

### Notary

#### Design and implement the new Notary website

- Description: Design the new Notary website using the Figma tool and develop it based on the design layout. We redesigned the Notary website and finished the first phase development work with CNCF employee @thisisobate in [#PR 139](https://github.com/notaryproject/notaryproject.dev/pull/139). This project is to continue to design and implement the new Notary website and ensure deliver a developer-friendly experience.
- Expected Outcome: 
   - Design and implement the Adopters page
   - Redesign a Community page
   - Improve the landing page design; add an installation section with a terminal effect design
   - Support mobile responsive design
   - Add a pop-up window on the landing page to tell users how to join the community
   - Add Algolia search for the website
   - Design and implement a video page to list Youtube videos
   - Refine the content on the website
   - Add Broken link check to Netlify CI
- Recommended Skills: Figma design, HTML, CSS, JavaScript, Hugo
- Mentor(s):  Feynman Zhou (@FeynmanZhou , feynmanzhou@microsoft.com)
- Upstream Issue (URL): https://github.com/notaryproject/notaryproject.dev/issues/194
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/06774504-da91-469e-89f9-14fb18b6e0d8

#### Develop content for Notary documentation and blogs

- Description: Develop content for Notary documentation and write blog posts to educate users about the Notary use cases. Write user guides, contributing guides, and developer guides for every new Notary release and keep those content up-to-date.
- Expected Outcome: 
   - Write user guides with end-to-end scenarios based on given doc structure and requirement
   - Write contributing guides and developer guides, ensure new developers can easily build and start contributing to Notary subprojects 
   - Write blog posts to educate users to use Notation with cloud-native ecosystem tools
- Recommended Skills: OCI, Docker, Kubernetes, Notary, Git, Markdown, Technical writing experience
- Mentor(s): Mentor(s):  Yi Zha, @yizha1 (yizha1@microsoft.com)
- Upstream Issue (URL): https://github.com/notaryproject/notaryproject.dev/issues/195
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/007ca3e9-c121-4428-8e63-57bc0418e98a

### ORAS

#### Design and implement Artifact Explore web portal

- Description: This project goal is to improve the efficiency of the image developers and users through the artifact explorer tool with ORAS under the hood. This tool helps users to explore and search the content of an artifact or a registry. This doc is to gather ideas for early brainstorming purposes. For users, this tool reduces CLI learning cost and improve efficiency for developers. They don’t need to memorize and type the CLI commands to explore the content of an OCI artifact and registry.

- Expected Outcome:
   - Provides a web portal to view the content of OCI artifacts from any public registries
   - Users can drill down into the detailed content of an image manifest or a layer
   - Users can view the artifact reference graph from the web portal
   - Users can view and download the supply chain artifacts like the signature, SBOM, attestation 
   - Provides search capabilities to allow users to search container images or OCI artifacts on a central web portal. We can combine it with Artifact [Search API capabilities](https://docs.google.com/document/d/1rcQROZP31q7BOjoZ977Ok7pt28z_UXfW0vAK3xC0wdI/edit#heading=h.rx512bvufn5q).
   - Explore the image’s file system of layer (tentative)
   
- Recommended Skills: Figma design, HTML, CSS, JavaScript, Hugo, Docker
- Mentor(s):  Feynman Zhou (@FeynmanZhou , feynmanzhou@microsoft.com), Billy Zha (@qweeah , jinzha1@microsoft.com), Asmit Malakannawar (@asmitbm , asmitbm2952002@gmail.com) 
- Upstream issue: https://github.com/oras-project/oras-www/issues/158
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9749bc0a-04c9-498d-a16c-e66c0930e819

#### Refactor the ORAS documentation structure and write new user guides

- Description: Refactor the ORAS documentation structure and write new user guides based on the latest version of ORAS. The detailed ORAS documentation structure and content should be refactored according to the proposal in the [upstream issue](https://github.com/oras-project/oras-www/issues/65). 
- Expected Outcome: Deliver a developer-friendly documentation structure for ORAS and write new user guides according to the proposed documentation structure. Publish all content at https://oras.land/
- Recommended Skills: OCI, Docker, ORAS, Markdown
- Mentor(s): Terry Howe (@TerryHowe , terrylhowe@gmail.com), Asmit Malakannawar (@asmitbm , asmitbm2952002@gmail.com), Feynman Zhou (@FeynmanZhou , feynmanzhou@microsoft.com)
- Upstream issue: https://github.com/oras-project/oras-www/issues/65
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/2314fcc1-f09b-4dab-90fb-d0ef092b6c0e

### Service Mesh Performance

#### Service Mesh Performance IDE Plugin

- Description: The objective of this project is to develop IDE plugins that can enhance the developer experience while working with Service Mesh Performance Performance Profiles. The proposed plugins will leverage technologies such as golang and cuelang to provide features such as syntax highlighting, auto-completion, validation, and rendering previews for Service Mesh Performance profile and model definitions.
- Expected outcome:
- 1. Release VS Code Extension
- 2. Syntax Highlighting and Auto-completion: The plugin can fetch SMP Model definitions such as cloud-native components and their relationships. This information can be used to provide syntax highlighting and auto-completion for these definitions in the JSON files, making it easier for developers to write error-free code.
- 3. Validation and Reference: For Meshery MeshModel definitions such as cloud-native components and their relationships, the plugin can use the CUE language to provide validation for the CUE input and preview the rendering result. The plugin can also fetch the SMP Model schemas and display them in the IDE for reference.
- Recommended Skills: Cuelang
- Mentor(s): Lee Calcote @leecalcote (leecalcote@gmail.com), Xin Huang @gyohuangxin (xin1.huang@intel.com)
- Upstream Issue (URL): https://github.com/service-mesh-performance/service-mesh-performance/issues/379
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/4735d0fa-229f-43e7-9415-dff9220bf687

### Strimzi

#### Proof of Concept of an MQTT to Apache Kafka bridge for producing messages

- Description: A really common use case we have been seeing is about enabling an IoT scenario with MQTT based devices and using an Apache Kafka cluster as the events and storage platform running on Kubernetes via Strimzi. In order to do that, there is the need to map the MQTT protocol to the custom Apache Kafka one and bridge from one to the other. This project idea is about designing such a mapping and developing a pure [Netty](https://github.com/netty/netty/tree/4.1/codec-mqtt/src/main/java/io/netty/handler/codec/mqtt) based MQTT server component (not a full MQTT broker) able to accept MQTT client connections and handling the corresponding communication based on the [MQTT 3.1.1 specification](http://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.html). Finally, developing the Kafka producer part to get messages from MQTT clients and sending them to an Apache Kafka cluster.
- Expected outcome: POC source code for an MQTT to Apache Kafka bridge
- Recommended Skills:
  - Java
  - Apache Kafka (not mandatory but to be learned)
  - MQTT protocol (not mandatory but to be learned)
- Mentor(s):
  - Paolo Patierno (@ppatierno, ppatiern@redhat.com)
  - Kyle Liberti (@kyguy, kliberti@redhat.com)
- Upstream Issue (URL): https://github.com/strimzi/strimzi-kafka-operator/issues/8030
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/8d301adf-94d8-4e5d-821d-f904ed15c3f9

### Thanos

#### Continuation of add query observability for the new engine

- Description: We have added solid foundation for query observability in the new engine during the previous LFX mentorship term. Let's continue the awesome work by Pradyumna by implementing other features.
- Expected outcome: other query observability visualizations are implemented; extra observability data has been added
- Recommended skills: Golang, React
- Mentor(s): @saswatamcode, Saswata Mukherjee saswataminsta@yahoo.com, @GiedriusS Giedrius Statkevičius giedriuswork@gmail.com
- Difficulty: Medium
- Upstream issue (URL): https://github.com/thanos-community/promql-engine/issues/106
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1953e512-fa8c-4f0e-9b24-0e6c81a7cd39

### Vitess

#### Rework the frontend UI of Vitess’ benchmarking tools

- Description: Vitess uses a couple of tools to benchmark its codebase and to make sure that new code doesn’t introduce performance regressions. These tools are: arewefastyet and the VReplication Benchmarking Framework. We currently have an old frontend UI that serves arewefastyet. However, this UI is slow, not optimized and not easily extensible. It uses the built-in Golang template system to serve pages. We would like to create a common frontend UI that will be used by both benchmarking tools and that will replace the current arewefastyet’s UI. The mentee will have the responsibility of creating the UI using (most likely) React/Vite on Vercel. The frontend component will connect to our already-existing backend components: a MySQL database and arewefastyet’s REST API.
- Expected Outcome: The expected outcome is to have a working frontend UI that integrates well with our different backends (databases and benchmarking tools’ APIs).
- Recommended Skills: React, Vercel, Vite, REST API, (Optional writing APIs in Golang)

- Mentor(s):
  - @fouioui Florent Poinsard frouioui@planetscale.com
  - Rohit Nayak @rohit-nayak-ps rohit@planetscale.com
- Upstream Issue (URL): https://github.com/vitessio/arewefastyet/issues/328 
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/8299d27a-9e36-4de6-abbc-c9282634ee03

### WasmEdge

#### Serialization Completion

- Description: WasmEdge is a WebAssembly runtime in both interpreter and ahead-of-time mode. However, WasmEdge only supports the binary format for the input WebAssembly file. To help the text format WebAssembly loader feature in the future, the implementation of serializing a WebAssembly module is necessary. In this mentorship, we hope the mentee should complete the serialization functions already in [the `dev/serialize` branch](https://github.com/WasmEdge/WasmEdge/tree/dev/serialize) of the `WasmEdge` repo.
- Expected outcome: Complete the serialization functions of WebAssembly modules, such as the element segment and data segment encoding. Complete the WebAssembly instructions encoding. Generate the unit test data and pass the unit tests. >80% of code coverage for serialization.
- Recommended Skills: C/C++, WebAssembly
- Mentor(s): Yi-Ying He @q82419 (yiying at secondstate dot io), Hung-Ying Tai @hydai (hydai at secondstate dot io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2262
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/4a8a4f26-0ca9-4517-8cce-582c92092e33

#### zlib Plugin Support

- Description: The zlib is required for compiling and running many existing C / C++ / Rust apps in Wasm. Most noticeably, it is [needed in the Python port to Wasm](https://github.com/python/cpython/issues/93819). The VMWare Wasm Labs team is using a zlib port from [Singlestore](https://github.com/singlestore-labs/python-wasi) in [their Python Wasm runtime](https://wasmlabs.dev/articles/python-wasm32-wasi/). In WasmEdge, we could support the zlib host functions through our [plugin system](https://wasmedge.org/book/en/plugin.html). This way, any existing zlib apps can be compiled to Wasm and runs inside WasmEdge.
- Expected outcome: Create a new [WasmEdge plugin](https://wasmedge.org/book/en/plugin.html) that exports all public functions in `zlib`. Implement SDK (in C/Rust) that uses the C ABI to generate corresponding headers for the above plugin. Generate the unit tests and pass the unit tests. >80% of code coverage for verification.
- Recommended Skills: C/C++, Rust, WebAssembly
- Mentor(s): Yi-Ying He @q82419 (yiying at secondstate dot io), Hung-Ying Tai @hydai (hydai at secondstate dot io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2244
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/74cecdf7-e886-4830-8bb0-7814f0d1aa2d

#### Support Tensorflow and PyTorch in WasmEdge’s Python runtime

- Description: In this project, you will incorporate WasmEdge’s NN (Neural Network) extensions into the Python interpreter. WasmEdge provides C and Rust APIs for guest applications to access host functions in the underlying Tensorflow and PyTorch libraries. You will make those functions accessible from the CPython-based interpreter as Python wrappers. This way, Python applications can do lightweight AI inference on the WasmEdge container.
- Expected outcome:
  * Investigate and list all C-based host function APIs for Tensorflow and PyTorch inference in WasmEdge NN.
  * Create CPython wrappers for those host functions.
  * Create high-level Python wrapper functions that are ergonomic for Python developers.
  * Create CI and demo apps to validate the Python wrapper API.
  * Create detailed documentation and tutorials.
- Recommended Skills: Proficient in C programming including creating dynamic libraries; Proficient in Python and machine learning programming. Basic understanding of WebAssembly and WasmEdge.
- Mentor(s): Michael Yuan @juntao (michael at secondstate dot io), Asen Alexandrov @adalexandrov (alexandrov at vmware dot com)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2471
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/884ff3f2-3ea3-4010-8928-ca27bbae219a

#### A stream log processing framework for WasmEdge

- Description: In this project, we aim to build a Rust-based log processing framework. Applications built on this framework will be compiled into WebAssembly and run in WasmEdge containers side by side with Linux containers and apps. The WasmEdge app collects logs from other containerized apps and then sends them to a streaming database or processing pipeline.
- Expected outcome:
  * Create a Rust framework with 3 traits similar to the [`Transformer`](https://github.com/second-state/MEGA/blob/main/mega_etl/src/lib.rs#L99) trait in the [MEGA framework](https://github.com/second-state/MEGA).
    * The `Collector` trait abstracts operations needed for a log collector.
    * The `Transformer` trait abstracts the transformation algorithms that can be applied to the logs.
    * The `Destination` trait abstracts operations needed to send transformed to a streaming data pipeline or database.
  * Implement at least two `Collector`s. One for MySQL database binlog and the other for a generic log file in a Linux container in the same Kubernetes pod.
  * Implement at least two `Transformer` algorithms supported by [FileBeat](https://www.elastic.co/guide/en/beats/filebeat/current/filebeat-overview.html).
  * Implement at least three `Destination`s. One for a Kafka queue, one for a Redis database, and the other for ElasticSearch.
  * Provide CI and demo test cases.
  * Provide documentation and tutorials.
- Recommended Skills: Proficient in the Rust programming language; Familiarity with MySQL, Kafka, ElasticSearch, and FileBeat; Familiarity with Kubernetes and related container management tools; Basic understanding of WebAssembly and WasmEdge
- Mentor(s): Michael Yuan @juntao (michael at secondstate dot io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2470
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/55c226fe-d119-4b2c-aba0-e7415867f6e5

-----------------------
# Term 01 - 2023 March - May

Status: Complete

Mentorship duration - three months (12 weeks - full-time schedule)

| activity | date |
| --- | --- |   
| project proposals | January 16 - 31, 5:00 PM PDT |
| mentee applications open | February 1 - 21, 5:00 PM PDT |
| application review/admission decisions/HR paperwork | February 22 - March 7, 5:00 PM PDT |
| Mentorship program begins with the initial work assignments | March 8 (Week 1) | 
| Midterm mentee evaluations and first stipend payments | April 12 (Week 6) |
| Final mentee evaluations and mentee feedback/blog submission due, second and final stipend payment approvals | May 24, 5:00 PM PST (Week 12) |
| Last day of term | May 31 |


### Project Instructions

Project proposals open Jan 16th, 2023.

Once opened, Project maintainers and potential mentors are welcome to propose their mentoring project ideas via submitting a PR to GitHub here https://github.com/cncf/mentoring/blob/main/lfx-mentorship/2023/01-Mar-May/project_ideas.md, by January 31, 2023.

### Application instructions

Mentee application instructions can be found on the [Program Guidelines](https://github.com/cncf/mentoring/blob/main/lfx-mentorship/README.md#program-guidelines) page.

---

- [Accepted Projects](#accepted-projects)
  - [Cilium](#cilium)
    - [Website Use Cases pages](#website-use-cases-pages)
  - [Cloud Native Buildpacks](#cloud-native-buildpacks)
    - [Pack Performance enhancements](#pack-performance-enhancements)
    - [Multi-Architecture Builds Support](#multi-architecture-builds-support)
  - [CNCF Landscape](#cncf-landscape)
    - [UX UI improvement](#ux-ui-improvement)
  - [CNCF Tag Contributor Strategy](#cncf-tag-contributor-strategy---ii)
    - [Mentoring Workspaces - GITHUBUSER.PROJECT.cncf.io (w/ VSCode)](#mentoring-workspaces---githubuserprojectcncfio-w-vscode)
  - [CNCF TAG Network](#cncf-tag-network)
    - [Representing Kubernetes ontology in MeshModel](#representing-kubernetes-ontology-in-meshmodel)
  - [Cortex](#cortex)
    - [Experimental Auth Gateway](#experimental-auth-gateway)
    - [API to import Prometheus \& Thanos blocks](#api-to-import-prometheus--thanos-blocks)
    - [Switch Cortex Ruler to query Query Frontend](#switch-cortex-ruler-to-query-query-frontend)
    - [Automated nightly benchmarks](#automated-nightly-benchmarks)
  - [Harbor](#harbor)
    - [Regex replication rules](#regex-replication-rules)
    - [An official Golang API client and CLI for Harbor](#an-official-golang-api-client-and-cli-for-harbor)
    - [Implement per project and/or for the whole instance vulnerability overview](#implement-per-project-andor-for-the-whole-instance-vulnerability-overview)
    - [Harbor Robot accounts with full Harbor API access](#harbor-robot-accounts-with-full-harbor-api-access)
  - [Kubernetes](#kubernetes)
    - [Cluster API Provider GCP (CAPG)](#cluster-api-provider-gcp-capg)
      - [Add telemetry and profiling support](#add-telemetry-and-profiling-support)
    - [Cluster API Provider AWS (CAPA)](#cluster-api-provider-aws-capa)
      - [Reimagining how we handle AWS account preparation](#reimagining-how-we-handle-aws-account-preparation)
  - [Kubescape](#kubescape)
    - [Implement security controls based on penetration testing best practices](#implement-security-controls-based-on-penetration-testing-best-practices)
    - [Build debugging capabilities for Helm](#build-debugging-capabilities-for-helm)
    - [Release engineering: add Kubescape to commonly-requested package managers](#release-engineering-add-kubescape-to-commonly-requested-package-managers)
  - [KubeVela](#kubevela)
    - [Extend the capability of KubeVela by making several useful addons](#extend-the-capability-of-kubevela-by-making-several-useful-addons)
    - [Support auto generation of CUE schema and docs from Go struct](#support-auto-generation-of-cue-schema-and-docs-from-go-struct)
    - [Support auto generation of multiple languages SDK from CUE](#support-auto-generation-of-multiple-languages-sdk-from-cue)
  - [Kyverno](#kyverno)
    - [Pod Security Admission Integrations](#pod-security-admission-integrations)
    - [Kubernetes Validating Admission Policy Support](#kubernetes-validating-admission-policy-support)
    - [OCI references support](#oci-references-support)
    - [Artifact Hub listing of Kyverno Policy Library](#artifact-hub-listing-of-kyverno-policy-library)
  - [Karmada](#karmada)
    - [Provide interactive environments for Karmada users](#provide-interactive-environments-for-karmada-users)
    - [Enhance Karmada testing coverage](#enhance-karmada-testing-coverage)
    - [Bundle third-party resources into the Resource Interpreter framework](#bundle-third-party-resources-into-the-resource-interpreter-framework)
  - [Konveyor](#konveyor)
    - [Move2Kube: Allow customizations be added as remote git repo path](#move2kube-allow-customizations-be-added-as-remote-git-repo-path)
    - [Move2Kube: Implement a test suite](#move2kube-implement-a-test-suite)
    - [Move2Kube: Consume Move2Kube through a plugin on Eclipse](#move2kube-consume-move2kube-through-a-plugin-on-eclipse)
    - [Move2Kube: Consume Move2Kube through a plugin on VSCode](#move2kube-consume-move2kube-through-a-plugin-on-vscode)
  - [KubeArmor](#kubearmor)
    - [KubeArmor Telemetry Monitoring and Dashboards](#kubearmor-telemetry-monitoring-and-dashboards)
    - [Adding OpenTelemetry Support](#adding-opentelemetry-support)
    - [Rancher Plugin Integration](#rancher-plugin-integration)
  - [Kubewarden](#kubewarden)
    - [Kubewarden SDKs feature parity](#kubewarden-sdks-feature-parity)
    - [Kubewarden policies enhancements](#kubewarden-policies-enhancements)
  - [KubeEdge](#kubeedge)
    - [Design and implement the KubeEdge Dashboard](#design-and-implement-the-kubeedge-dashboard)
    - [Re-design and implement the KubeEdge website](#re-design-and-implement-the-kubeedge-website)
    - [Cloud-Robotic AI Benchmarking for Edge-cloud Collaborative Lifelong Learning](#cloud-robotic-ai-benchmarking-for-edge-cloud-collaborative-lifelong-learning)
  - [Meshery](#meshery)
    - [Distributed workflow engine](#distributed-workflow-engine)
    - [Multi-user cloud native playground](#multi-user-cloud-native-playground)
    - [Distributed client-side policy evaluation in WASM and Rego](#distributed-client-side-policy-evaluation-in-wasm-and-rego)
  - [Linkerd](#linkerd)
    - [Linkerd Dashboard Improvements](#linkerd-dashboard-improvements)
    - [Add dynamic profiling to Linkerd Rust controllers](#add-dynamic-profiling-to-linkerd-rust-controllers)
    - [Prototype multi-cluster service discovery and operations](#prototype-multi-cluster-service-discovery-and-operations)
  - [LitmusChaos](#litmuschaos)
    - [Improve code quality and add unit tests of litmus chaos components](#improve-code-quality-and-add-unit-tests-of-litmus-chaos-components)
  - [NATS](#nats)
    - [End-to-end example of a multiplayer game using NATS in Unity](#end-to-end-example-of-a-multiplayer-game-using-nats-in-unity)
  - [Notary](#notary)
    - [HashiCorp Vault plugin for Notary](#hashicorp-vault-plugin-for-notary)
  - [OpenKruise](#openkruise)
    - [Bring progressive delivery to daemon workload](#bring-progressive-delivery-to-daemon-workload)
    - [Support customize arbitary fields of workload subset in UnitedDeployment](#support-customize-arbitary-fields-of-workload-subset-in-uniteddeployment)
  - [ORAS](#oras)
    - [Develop .NET SDK for ORAS](#develop-net-sdk-for-oras)
    - [Develop ORAS Website](#develop-oras-website)
  - [Service Mesh Performance](#service-mesh-performance)
    - [Adaptive Load Controller](#adaptive-load-controller)
  - [TestGrid](#testgrid)
    - [Frontend development inside Lit Component Framework](#frontend-development-inside-lit-component-framework)
  - [Thanos](#thanos)
    - [Add query observability for new promql engine](#add-query-observability-for-new-promql-engine)
    - [Series Cardinality API](#series-cardinality-api)
    - [Querying Apache Parquet files with PromQL](#querying-apache-parquet-files-with-promql)
  - [Vitess](#vitess)
    - [Implement a benchmarking and load testing framework for the VReplication module in Vitess](#implement-a-benchmarking-and-load-testing-framework-for-the-vreplication-module-in-vitess)
    - [Add complete parsing support for Spatial MySQL functions](#add-complete-parsing-support-for-spatial-mysql-functions)
  - [WasmEdge](#wasmedge)
    - [Streaming data processing with WasmEdge](#streaming-data-processing-with-wasmedge)
    - [A Rust library crate for mediapipe models for WasmEdge NN](#a-rust-library-crate-for-mediapipe-models-for-wasmedge-nn)
    - [Unified WasmEdge tools](#unified-wasmedge-tools)
    - [WasmEdge C++ SDK](#wasmedge-c-sdk)

---

## Accepted Projects

### Cilium

#### Website Use Cases pages

- Description: Cilium would like to have use case pages built out on its website to make it easy for people to find the information and relevant content to the problems they are trying to solve with Cilium.
- Expected Outcome: The mentee will read through relevant docs, blogs, case studies, user stories, and labs to understand the use cases which will drive the content for each of the pages being built. The finished product will be a new use cases section on the Cilium website.
- Recommended Skills: Content Writing, Javascript, CSS
- Mentor(s): Bill Mulligan (@xmulligan, bill@isovalent.com) 
- Upstream Issue: https://github.com/cilium/cilium.io/issues/226
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/81a0e506-1c05-45fa-90c4-6bde8bdc0e61

### Cloud Native Buildpacks

#### Pack Performance enhancements

- Description: Pack is the reference implementation of a Cloud Native Buildpacks platform used to build application images in multiple organizations. Because all developers want their code to build and deploy as quickly as possible, small speedups in pack can have significant benefits, and slow-downs in pack are undesirable. Today, pack has no benchmark suite that would safe-guard against regressions in execution speed.
- Expected Outcome: The mentee will create a benchmark suite around some critical path sections identified with help from maintainers. The mentee will be supported in applying profiling tools to identify possible speedups, hopefully leading to at least one user-facing performance improvement.
- Recommended Skills: Golang, git, software development.  (Mentee does not need prior experience in profiling or performance tuning)
- Mentor(s): Natalie Arellano (@natalieparellano, narellano@vmware.com); Joe Kimmel (@joe-kimmel-vmw, jkimmel@vmware.com) 
- Upstream Issue: https://github.com/buildpacks/pack/issues/1610
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/33e0747c-4ab8-4074-aa90-3b908b3a588e

#### Multi-Architecture Builds Support

- Description: The rise of ARM processors has created new binary targets for pre-compiled executables. Additionally, there are tales of widespread use of operating systems that aren't linux? In the ideal case a `pack` user could create a build for an abritrary architecture and operating system, regardless of the host system they used to run the command.
- Expected outcome: Improved multi-architecture (including ARM) and multi-os "cross-compilation" support in [pack](https://github.com/buildpacks/pack/)
- Recommended Skills: Golang, software development literacy. Familiarity with buildpacks will be helpful.
- Mentor(s): Aidan Delaney (@AidanDelaney); Jerico Pena (@jpena-r7); Juan Bustamante (jbustamante@vmware.com, @jjbustamante)
- Expected project size: 350 Hours
- Difficulty: Medium
- Upstream Issue (URL): https://github.com/buildpacks/pack/issues/1459 and https://github.com/buildpacks/pack/issues/1460
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ee387e1b-de4e-4c1e-9bef-0239a2e9ca40

### CNCF Landscape

#### UX UI improvement
- Description: In an effort to better the user experience, the CNCF Landscape is actively seeking ways to improve and enhance its features.
- The aim is for the mentee to carry out a User Research to validate existing user personas, gain a deeper understanding of user needs, and conduct a thorough heuristic evaluation to gain insights into user experiences. Using the results, the mentee will establish a solid foundation to start an iterative process of ideation, prototyping, and testing possible solutions. The ultimate goal is to initiate a continuous cycle of improvement and further development of features that enhance the user experience of the CNCF Landscape.
- Recommended skills: Design Thinking, UX research methodology. 
In this stage of the project, we are seeking candidates with a background and/or training in user research. Supporting materials, such as the following recommended deliverables, that demonstrate your understanding and experience in this area are ideal:

1. Proto-Personas
2. Validated Personas with Supporting Findings
3. Brief Explanation of the Difference between Proto-Personas and Validated Personas
4. List of UX Research Techniques for Kickstarting the Discovery of Landscape Users
5. Figma and Visual Design are a plus.

- Mentors: Andrea Velázquez andrea@buoyant.io, Nate W. @nate-double-u natew@cncf.io, Chris Aniszczyk @caniszczyk caniszczyk@linuxfoundation.org 
- Upstream issue: https://github.com/cncf/landscape/issues/2467
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/df011bb8-8ce1-4092-bfc6-1e92ce40a17d

### CNCF Tag Contributor Strategy - ii

#### Mentoring Workspaces - GITHUBUSER.PROJECT.cncf.io (w/ VSCode)

- Description: pair.sharing.io is a mentoring / pair environment used by ii.nz that brings up clusters to co-learn and co-author via tmate+emacs and a live cluster with many features useful to cloud native development. However, while many folks find the ideas useful, it would be good to reach a wider audience by bringing up workspaces w/ VSCode as an alternative to emacs. The request is for a PoC deploying coder.com to CNCF Infrastructure (likely Packet) and bringing over some of the methods of collaboration learned by ii on pair to a wider audience.
  "If you want to go fast, go by yourself. If you want to go far, go together." African Proverb – Martha Goedert
- Recommended Skills: shell, terminals, VSCode, k8s, System Administration
- Mentor: Hippie Hacker (@hh, hh@cncf.io)
- Issue: https://github.com/sharingio/pair/issues/173
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/632ab03f-a970-44ce-b451-fac0a7349f71

### CNCF TAG Network

#### Representing Kubernetes ontology in MeshModel

- Description: Network topologies and graph databases go hand-in-hand. The OpenAPI specifications for Kubernetes provides taxonomy, but augmenting a graph data model with formalized ontologies enables any number of capabilities, one of the more straightforward is the inferencing requisite for natural language processing, and consequently, a human-centric query / response interaction becomes becomes possible. More importantly, more advanced systems can be built when a graph data model of connected systems is upgraded to be a knowledge semantic graph. Deliverables (among other items):

- MeshModel capabilities browser
- Import/export of MeshModel models and components as OCI images
- augmentation of cuelang-based component generator

- Recommended Skills: cuelang, golang, OCI
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com)
- Issue: https://github.com/cncf/tag-network/issues/24
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/96080e3d-83e2-46ed-928c-b6e7f3154bf3

### Cortex

#### Experimental Auth Gateway
- Description: Cortex server has a simple authentication mechanism (X-Scope-OrgId) but users can’t use the multi tenancy features out of the box without complicated proxy configuration. It’s hard to support all the different authentication mechanisms used by different companies but plan to have a simple but opinionated auth-gateway that provides value out of the box.
- Expected Outcome: A new experimental cortex component called auth-gateway that validates tenants requests and proxies valid requests to distributors and query-frontend.
- Recommended Skills: Golang, HTTP proxies
- Mentor: Friedrich Gonzalez (@friedrichg, friedrichg@gmail.com)
- Upstream Issue: https://github.com/cortexproject/cortex/issues/5106
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/820f9269-ddef-44e9-bf77-95a8d2444c1e

#### API to import Prometheus & Thanos blocks
- Description: For users who want to migrate from Prometheus to Cortex, currently it is supported via a tool called [Thanosconvert](https://cortexmetrics.io/docs/blocks-storage/migrate-storage-from-thanos-and-prometheus/#when-migrating-from-prometheus). However, having this feature as part of the tool is limited in some usecase like SaaS because users usually don’t have permissions to access their storage layer directly. It would be nice to extend this feature into an API so that users can import their Prometheus TSDB compatible blocks for easier migration.
- Expected Outcome: An API that imports Prometheus blocks into Cortex.
- Recommended Skills: Golang, Prometheus, Thanos
- Mentor: Alan Protasio (@alanprot, alanprot@gmail.com), Daniel Blando (@danielblando, daniel@blando.com.br)
- Upstream Issue: https://github.com/cortexproject/cortex/issues/4956
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/184ccb3e-6abe-4bf9-9659-b42b5c07c5a5

#### Switch Cortex Ruler to query Query Frontend
- Description: Cortex Ruler queries ingester directly for rule evaluation. This is okay but if Cortex Ruler could query Query Frontend instead for rule evaluation, it can benefit from more features in the Query Frontend like vertical sharding. This also simplifies the Cortex ruler to not embed a querier and uses less resources. For this project, we would like to switch Cortex Ruler to query Query Frontend. You are expected to work with a microservice architecture and write unit tests and end to end tests to make sure the feature works correctly.
- Expected Outcome: Cortex Ruler talks to Query Frontend for rules evaluation.
- Recommended Skills: Golang, distributed systems
- Mentor: Alvin Lin (@alvinlin123, alvinlin123@gmail.com), Yijie Qin (@qinxx108, qinyijie1994@gmail.com)
- Upstream Issue: https://github.com/cortexproject/cortex/issues/5105
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/fe5c060e-420b-4c0f-90ae-389d893c50b6

#### Automated nightly benchmarks
- Description: In order to make sure Cortex doesn’t introduce performance regressions across releases and major changes, we would like to introduce an automated way to run some nightly macro/micro benchmarks for Cortex clusters. This project could potentially involve setting up Kubernetes clusters, Cortex components, and load generators. We’d love to keep track of performance metrics for each test run and visualize them through a UI.
- Expected Outcome: An automated workflow that runs performance macro/micro benchmarks everyday or on demand and performance metrics can be visualized through a UI.
- Recommended Skills: Golang, Kubernetes
- Mentor: Ben Ye (@yeya24, yb532204897@gmail.com)
- Upstream Issue: https://github.com/cortexproject/cortex/issues/5107
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0071e2ff-f538-4817-978b-07b267cfcd6a

### Harbor

#### Regex replication rules

- Description: Add more versatile replication filters
- Expected Outcome: Implement regex capability when defining relication rules, update documentation and present the functionality
- Recommended Skills: Angular, JavaScript, Golang
- Mentor(s): vb@container-registry.com@Vad1mo @wy65701436 @OrlinVasilev
- Mentor(s): @Vad1mo - Vadim Bauer, vb@container-registry.com); @wy65701436 - Yan Wang(wangyan@vmware.com); @OrlinVasilev Orlin Vasilev (ovasilev@vmware.com)
- Upstream Issue (URL): https://github.com/goharbor/harbor/issues/8614 
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/49749be9-5a67-4b2b-9312-7def13ae98b8

#### An official Golang API client and CLI for Harbor

- Description: Design, plan and implement an Golang API client for Harbor
- Expected Outcome: Working golang harbor API client which can be used in the CI/CD implementations which compliments the Web UI, well documented and with the coresponding architectural diagrams under the Harbor org(not necessary to be complete functionality)
- Recommended Skills: Golang, spf13/cobra
- Mentor(s): Vadim Bauer, vb@container-registry.com); @wy65701436 - Yan Wang(wangyan@vmware.com);
- Upstream Issue (URL): https://github.com/search?q=Harbor%20CLI&type=repositories
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/7e8cb88a-5b37-471c-8db8-e11907b5a661

#### Implement per project and/or for the whole instance vulnerability overview
  
- Description: Design, plan and implement an and UI and backend to be able to visualize per project and/or for the registry vulnerability overview which will allow better security audits and vulenrability mitigation 
- Expected Outcome: Addition to the Web UI which can be used to represent in full for the whole Harbor instance or per project the vulnerability status of the images, which will allow Harbor admin or project admin to get an overview of the existing vulnerabilities on in the images, also to provide capability to export the data via the CVE exporter so it can be consumed in 3rd party tools(not necessary to be complete functionality)
- Recommended Skills: Angular, JavaScript, Golang, UI/UX, Clarity 
- Mentor(s): Vadim Bauer, vb@container-registry.com); @wy65701436 - Yan Wang(wangyan@vmware.com);
- Upstream Issue (URL): https://github.com/goharbor/harbor/issues/16680 https://github.com/goharbor/harbor/issues/10496 https://dso.docker.com/explore?search=pkgs
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/7ea4c506-c830-4a15-be4a-600d2dfe3f44

#### Harbor Robot accounts with full Harbor API access

- Description: Robot accounts should be allowed to access the full Harbor API (more of a UI thing)
- Expected Outcome: Implement a way to configure and fully documented with examples usecase how to setup Harbor Robot accounts with full or managed access to Harbor
- Recommended Skills: Angular, JavaScript, Golang, UI/UX, Clarity 
- Mentor(s): @wy65701436 - Yan Wang(wangyan@vmware.com); Vadim Bauer, vb@container-registry.com);
- Upstream Issue (URL): https://github.com/goharbor/harbor/issues/8723
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/4a96c735-6480-4464-8b33-4f9c58ba1005

### Kubernetes

#### Cluster API Provider GCP (CAPG)

##### Add telemetry and profiling support

- Description: Cluster API Provider GCP (CAPG) enables the creation of Kubernetes clusters in GCP with Cluster API. With increasing adoption of Cluster API (CAPI) in general and of CAPG we want to improve the supportability of CAPG, especially for production environments. The first part of this is to add telemetry/tracing using OpenTelemetry so that we can understand and visualize the flow of reconciliation within the provider. The next part is to add a **pprof** endpoint that can be optionally enabled to enable operations/support users to collect profiling information from a running instances of CAPG.
- Expected Outcome: This work will enable tracing and profiling of a running instance of CAPG (along with supporting docs) to supports operations/support engineers.
- Recommend Skills: Golang, Kubernetes
- Mentors(s): Carlos Panato (@cpanato ctadeu@gmail.com), Richard Case (@richardcase richmcase@gmail.com)
- Upstream Issue: https://github.com/kubernetes-sigs/cluster-api-provider-gcp/issues/810
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/55469b74-0c98-44f1-b8e1-4244a736bf82

#### Cluster API Provider AWS (CAPA)

##### Reimagining how we handle AWS account preparation

- Description: Cluster API Provider AWS (CAPA) can create and manage the lifecycle of Kubernetes clusters in AWS (with the help of Cluster API in general). For each target AWS account where a user wants to create clusters it must be prepared for usage first. This is currently done using [clusterawsadm](https://cluster-api-aws.sigs.k8s.io/topics/using-clusterawsadm-to-fulfill-prerequisites.html) which creates/updates a CloudFormation stack that in turn creates/updates IAM resources. This approach has caused issues as CloudFormation is region specific but IAM is global and users often run the tool in different regions which results in failed stacks that cannot easily be deleted. As a project we want to move away from using CloudFormation and instead use API calls (like the rest of CAPA). We also want to make the process idempotent so it doesn't matter if you run it against different regions. This account preparation is key to CAPA and with out it CAPA cannot run.
- Expected Outcome: A new approach to handling the prerequisites required for CAPA. We need to continue to support the cli based approach (so clusterawsadm will be updated) but we can also explore a declarative approach with an operator.
- Recommend Skills: Golang, Kubernetes
- Mentors(s): Richard Case (@richardcase richmcase@gmail.com)
- Upstream Issue: https://github.com/kubernetes-sigs/cluster-api-provider-aws/issues/3715
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/2d76dbe6-43eb-465e-a852-64b2e48f2c68

### Kubescape

#### Implement security controls based on penetration testing best practices

- Description: Kubescape covers different hardening guidelines around Kubernetes: NSA-CISA, MITRE and CIS. Detection capabilities of potential security issues could be even more enriched by researching pen-testing tools and practices regarding Kubernetes and implementing these as controls. An example pen-test writeup is https://hacktricks.boitatech.com.br/pentesting/pentesting-kubernetes. This and others could help define a set of “offensive” controls to complement the “defensive” controls we have today.
- Expected Outcome: ~10 controls for detecting challenges that would commonly be found in a cluster penetration test. Documentation on how they were selected and how to use them.
- Recommended Skills: Cybersecurity, Rego 
- Mentor(s): Ben Hirschberg (@slashben, ben@armosec.io)
- Upstream Issue: https://github.com/kubescape/kubescape/issues/1072
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/db63c23a-2b41-40e0-a833-cf0e2c33c739

#### Build debugging capabilities for Helm

- Description: The Go standard templating package (`text/template`) is the base on which Helm templates are built. We wish to be able to backtrack lines and fields in objects after rendering Helm charts. This would help users of Helm to be able to understand quickly where different security issues in the final object are coming from in the source. To do this, the `text/template` package should be extended to include debug markers that point from the output lines to the input lines. 
- Expected Outcome: Propose and implement an extension to the Go package which solves this.
- Recommended Skills: Go
- Mentor(s): Ben Hirschberg (@slashben, ben@armosec.io)
- Upstream Issue: https://github.com/helm/helm/issues/11552
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/570b1bba-206d-47ac-9667-22268ff7a6d9

#### Release engineering: add Kubescape to commonly-requested package managers

- Description: The Kubescape client binary is built from GitHub using standard patterns. Support for homebrew and krew exists, but users have requested RPM and DEB packages. In this project you will stabilize the delivery of new builds to existing package managers, and implement support for RPM and DEB packages using GitHub Actions.
- Expected Outcome: When a new Kubescape version is released, it is available in homebrew, krew, RPM and DEB repositories.
- Recommended Skills: Release management, scripting
- Mentor(s): Craig Box (@craigbox, craigb@armosec.io)
- Upstream Issue: https://github.com/kubescape/kubescape/issues/400
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/138e9cac-ec86-43cb-a04f-c2980e3c2865


### KubeVela

#### Extend the capability of KubeVela by making several useful addons

- Description: KubeVela currently have a variety of addons , including experimental options, that address scenarios such as Continual Delivery and observability. To further enhance the out-of-box functionality for users of KubeVela, we can offer additional useful addons.
- Expected Outcome: 10+ eperimetal addons, clear documentation should be provided for enabling and using these addons, including examples of useful use-cases.
- Recommended Skills: golang, kubernetes, cueLang
- Mentor(s): Jianbo Sun (@wonderflow, wonderflow.sun@gmail.com), Wong Yike (@wangyikewxgm, wangyike_wyk@163.com) 
- Upstream Issue: https://github.com/kubevela/kubevela/issues/5358
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/51398c19-87c2-4b50-9dd3-760fbd820688

#### Support auto generation of CUE schema and docs from Go struct

- Description: In KubeVela's provider system, we can use our defined Go functions in CUE schema. The Go providers usually have a parameter and return. Fields in Go providers are the same as fields in CUE schema, so it is possible and important to support automatic generation of CUE schemas and documents from Go structs.
- Expected Outcome: Auto-generators of CUE schemas and docs from Go structs, the capabilities should be wrapped in vela cli command.
- Recommended Skills: Go, CUE
- Mentor(s): Fog Dong (@FogDong, wuwuglu19@gmail.com), Da Yin(@Somefive, yd219913@alibaba-inc.com)
- Upstream Issue: https://github.com/kubevela/kubevela/issues/5364
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/85f61cae-02d7-4931-8d87-d3da3128060e

#### Support auto generation of multiple languages SDK from CUE

- Description: In KubeVela, we use CUElang to code the definition. We want to support auto generation of multiple languages SDK from CUE, so that users can use KubeVela in their own language.
- Expected Outcome: Support auto generation of multiple languages SDK from CUE, including Golang, Java, Python, etc. The capabilities should be wrapped in vela cli command.
- Recommended Skills: Go, Kubernetes, CUE
- Mentor(s): Qiao Zhongpei (@chivalryq, chivalry.pp@gmail.com) Zeng Qingguo (@barnettZQG, barnett.zqg@gmail.com)
- Upstream Issue: https://github.com/kubevela/kubevela/issues/5365
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/2981c1de-49af-4bd8-b87d-02e455a96ee1

### Kyverno

#### Pod Security Admission Integrations

- Description: Integrate Kubernetes Pod Security with Kyverno - Part II
- Expected Outcome: PR sent to kubernetes/kubernetes containing necessary changes to implement the behavior on the Kyverno side.
- Recommended Skills: Golang, Kubernetes, Pod Security
- Mentor(s): Shuting Zhao (@realshuting, shuting@nirmata.com)
- Upstream Issue: https://github.com/kyverno/kyverno/issues/6144
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/59afc794-c33e-4930-a5b8-eb3abd8d9896

#### Kubernetes Validating Admission Policy Support

- Description: Kubernetes Validating Admission Policy Support
- Expected Outcome: Kyverno support for ValidatingAdmissionPolicy in one of the identified proposals.
- Recommended Skills: Golang, Kubernetes, Admission Controls
- Mentor(s): Jim Bugwadia (@jimbugwadia, jim@nirmata.com)
- Upstream Issue: https://github.com/kyverno/kyverno/issues/5441
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a00294be-06a0-4e66-a2a5-6e2dfb3a097c

#### OCI references support

- Description: Use OCI References in image verification
- Expected Outcome: PR sent to kyverno/kyverno implementing support for OCI references in verifyImages rules
- Recommended Skills: Golang, Kubernetes, OCI images
- Mentor(s): Jim Bugwadia (@jimbugwadia, jim@nirmata.com)
- Upstream Issue: https://github.com/kyverno/kyverno/issues/6142
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e5da551f-8a3d-42ec-8c00-e9ae10a86aa2

#### Artifact Hub listing of Kyverno Policy Library

- Description: Develop a system to reflect all Kyverno Policies in the community library on Artifact Hub
- Expected Outcome: All Kyverno policies searchable on Artifact Hub with an extensible system for future use
- Recommended Skills: Golang, Artifact Hub, DevOps Automation, GitHub Actions
- Mentor(s): Chip Zoller (@chipzoller, chipzoller@gmail.com)
- Upstream Issue: https://github.com/kyverno/policies/issues/491
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/f502b839-a804-4a6c-8da5-3985ce25883e


### Karmada

#### Provide interactive environments for Karmada users
- Description: Using interactive environments(like killercoda) for users to get started quickly.
- Expected Outcome: Implement 2 Karmada examples in killercoda, including a CLI installation example and script installation example, both contains installation and deploying workload to multi-clusters steps.
- Recommended Skills: Kubernetes, Karmada
- Mentor(s): Wei Jiang (@jwcesign, jiangwei115@huawei.com), Hongcai Ren(@RainbowMango, qdurenhongcai@gmail.com)
- Upstream Issue: https://github.com/karmada-io/karmada/issues/3085
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/6a6e8093-660a-4b6e-8d29-24b8ef70e4f0

#### Enhance Karmada testing coverage

- Description: Karmada would like to improve the UT coverage of the code to better maintain the quality of the code and reduce the introduction of defects.
- Expected Outcome: Increase the UT coverage rate to 65% (currently, the UT coverage rate is [43%](https://app.codecov.io/gh/karmada-io/karmada) ), increase the code coverage rate by about 20%.
- Recommended Skills: Golang, Git
- Mentor(s): Zhen Chang (@XiShanYongYe-Chang, changzhen5@huawei.com), Hongcai Ren(@RainbowMango, qdurenhongcai@gmail.com)
- Upstream Issue: https://github.com/karmada-io/karmada/issues/3086
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1b2c5ff4-d6ea-4ca5-b138-75fce03407b4

#### Bundle third-party resources into the Resource Interpreter framework

- Description: Karmada's Resource Interpreter Framework is designed for interpreting resource structure. It consists of built-in and customized interpreters. Karmada could bundle some popular and open-sourced resources so that users can save the effort to customize them.
- Expected Outcome: The resources from projects, including Argo Workflow/Flux CD/Kyverno/OpenKurise, could be bundled in Karmada, and the corresponding documentation should also be supplemented.
- Recommended Skills: Go, Cloud Native
- Mentor(s): Tiecheng Shen (@Poor12, shentiecheng@huawei.com), Hongcai Ren(@RainbowMango, qdurenhongcai@gmail.com)
- Upstream Issue: https://github.com/karmada-io/karmada/issues/3087
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/891b4b92-0a78-409e-8b90-dcd58d126225

### Konveyor

#### Move2Kube: Allow customizations be added as remote git repo path

- Description: Move2Kube is a command-line tool for automating creation of Infrastructure as code (IaC) artifacts. It has inbuilt support for creating IaC artifacts for replatforming to Kubernetes/OpenShift. Currently, in the CLI we can use the -c flag to point to the folder containing customizations and in UI we could upload a zip file containing the customizatoins. It would be better to consume customizations when specified as a git repo path. The use case can also be extended to take source code input taken directory from a remote git repository.
- Expected Outcome: Move2Kube should be able to consume git repo path as input.
- Recommended Skills: Golang
- Mentor(s): Mehant Kammakomati (@kmehant, mehant.kammakomati2@ibm.com), Harikrishnan Balagopal (@HarikrishnanBalagopal, harikrishnan.balagopal@ibm.com)
- Upstream Issue: https://github.com/konveyor/move2kube/issues/604
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/fc06da19-fadd-499f-ae71-3da2caba5aea

#### Move2Kube: Implement a test suite

- Description: Move2Kube is a command-line tool for automating creation of Infrastructure as code (IaC) artifacts. It has inbuilt support for creating IaC artifacts for replatforming to Kubernetes/OpenShift. The project is actively developed with new features and bug fixes being added and it is being actively used by many users. There is a need for a concrete test suite to test various components of Move2Kube and integrate it to the existing CI/CD pipeline.
- Expected Outcome: A test suite for Move2Kube
- Recommended Skills: Golang, testing package, jest and/ react testing library.
- Mentor(s): Harikrishnan Balagopal (@HarikrishnanBalagopal, harikrishnan.balagopal@ibm.com), Mehant Kammakomati (@kmehant, mehant.kammakomati2@ibm.com)
- Upstream Issue: https://github.com/konveyor/move2kube/issues/957
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/6d457c37-68cb-4d52-b9d6-798b09350255

#### Move2Kube: Consume Move2Kube through a plugin on Eclipse

- Description: Move2Kube is a command-line tool for automating creation of Infrastructure as code (IaC) artifacts. It has inbuilt support for creating IaC artifacts for replatforming to Kubernetes/OpenShift. Users currently have to use move2kube command line tool or UI to access move2kube and use it in their replatforming workflows. Allow Move2Kube to be accessible from Eclipse as a plugin. It can start with simple functionality like right clicking on a docker-compose file, and generating all Kubernetes artifacts. An eclipse plugin for Move2kube will promote fast integration in replatforming workflows.
- Expected Outcome: An end to end working eclipse plugin with a demo video showcasing the functionality.
- Recommended Skills: Eclipse, Java, Golang.
- Mentor(s): Harikrishnan Balagopal (@HarikrishnanBalagopal, harikrishnan.balagopal@ibm.com), Mehant Kammakomati (@kmehant, mehant.kammakomati2@ibm.com)
- Upstream Issue: https://github.com/konveyor/move2kube/issues/396
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9976a49b-0aa4-49db-ae71-6180f85218ef

#### Move2Kube: Consume Move2Kube through a plugin on VSCode

- Description: Move2Kube is a command-line tool for automating creation of Infrastructure as code (IaC) artifacts. It has inbuilt support for creating IaC artifacts for replatforming to Kubernetes/OpenShift. Users currently have to use move2kube command line tool or UI to access move2kube. Allow Move2Kube to be accessible from VSCode as a plugin. It can start with simple functionality like right clicking on a docker-compose file, and generating all Kubernetes artifacts. A VSCode plugin for Move2kube will promote fast integration in replatforming workflows.
- Expected Outcome: An end to end working VSCode plugin with a demo video showcasing the functionality.
- Recommended Skills: VSCode plugins, TypeScript, Golang.
- Mentor(s): Harikrishnan Balagopal (@HarikrishnanBalagopal, harikrishnan.balagopal@ibm.com), Mehant Kammakomati (@kmehant, mehant.kammakomati2@ibm.com)
- Upstream Issue: https://github.com/konveyor/move2kube/issues/395
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/d8a7022f-8c62-4776-9e7c-4cc12f306177

### KubeArmor

#### KubeArmor Telemetry Monitoring and Dashboards

- Description: KubeArmor generates a large amount of data through logs and alerts, but interpreting this data can be difficult. To make it easier to understand, it is necessary to parse the telemetry, create meaningful metrics, enable data filtering, and create visualizations such as graphs to display on a dashboard.
- Expected Outcome: Create a telemetry dashboard, write setup documentation and usage guide.
- Recommended Skills: ELK stack (Elasticsearch, Logstash & Kibana), Fluentd, Loki and Grafana
- Mentors: Anurag Kumar (@kranurag7, contact.anurag7@gmail.com), Ankur Kothiwal (@Ankurk99, ankur.kothiwal99@gmail.com), Barun Acharya (@daemon1024, barun1024@gmail.com), Rahul Jadhav (@nyrahul, nyrahul@gmail.com)
- Upstream Issue: https://github.com/kubearmor/KubeArmor/issues/836
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a0696db8-509e-44ff-ae61-82a3442853c1

#### Adding OpenTelemetry Support

- Description: To integrate KubeArmor with OpenTelemetry, an adapter needs to be created. OpenTelemetry is a standard for telemetry data, including distributed tracing, metrics, and logs, and has an SDK and a collector component that can run on Kubernetes. Applications can directly expose OpenTelemetry data through in-app instrumentation using the OpenTelemetry SDK. The collector can then gather data from multiple applications in a cluster and send it to various backends for storage and visualization, such as Jaeger.
- Expected Outcome: The mentee's task is to develop an OpenTelemetry adapter for KubeArmor that can receive logs, alerts, and telemetry from the kubearmor-relay-service and convert it into the OpenTelemetry format. They are also expected to create documentation and usage guides that describe how to set up and use the adapter, as well as demonstrate the integration with a backend that supports OpenTelemetry.
- Recommended Skills: OpenTelemetry, Go
- Mentor(s): Anurag Kumar (@kranurag7, contact.anurag7@gmail.com), Ankur Kothiwal (@Ankurk99, ankur.kothiwal99@gmail.com), Barun Acharya (@daemon1024, barun1024@gmail.com), Rahul Jadhav (@nyrahul, nyrahul@gmail.com)
- Upstream Issue: https://github.com/kubearmor/KubeArmor/issues/894
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/369f081d-398e-4ce8-b645-e9605b62326a

#### Rancher Plugin Integration

- Description: The goal is to create an extension for Rancher, a Kubernetes management platform, which will enable interaction with KubeArmor. The extension will have the capability to install KubeArmor, allow for the management of security policies, and provide monitoring of workload behavior through alerts and telemetry.
- Expected Outcome: Rancher plugin address the following points: Install KubeArmor within Rancher, document and demonstrate the usage.
Note: This item is a work in progress. The selected mentee is expected to continue the same work.
- Recommended Skills: Rancher, Grafana stack, Javascript
- Mentor(s): Anurag Kumar (@kranurag7, contact.anurag7@gmail.com), Ankur Kothiwal (@Ankurk99, ankur.kothiwal99@gmail.com), Barun Acharya (@daemon1024, barun1024@gmail.com), Rahul Jadhav (@nyrahul, nyrahul@gmail.com)
- Upstream Issue: https://github.com/kubearmor/KubeArmor/issues/992
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/b7accea9-22bc-44e7-bac0-2f7b986fa626


### Kubewarden

#### Kubewarden SDKs feature parity

- Description:  Kubewarden currently allow policy writers to use 4 different programming languages. Therefore, there are 4 SDKs to be maintained. However, they lack feature parity. In other words, some SDK have feature that have features not available in other SDKs. It's necessary to map what are the features missing between the Go and Rust SDKs and implement some of them. For that, it is necessary to read and understand what is done in the Rust SDK and implement the equivalent in the Go SDK.
- Expected Outcome: Map all the features missing between the Go and Rust SKDs and implement some of the missing features
- Recommended Skills: Rust, Go, Kubernetes
- Mentor(s): José Guilherme Vanz (@jvanz), Victor Cuadrado Juan (@viccuad)
- Upstream Issue: https://github.com/kubewarden/kubewarden-controller/issues/392
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ddc368b7-1e24-42ed-9e30-02abdf6fcd33

#### Kubewarden policies enhancements

- Description:  Kubewarden has many policies to validate and mutate Kubernetes resources. Therefore, there are many enhancements to be made on them. However, these improvements are still to be made. Thus, it's necessary to fix the open issues in the policies repositories and implement new policies to add more value to the Kubewarden users. 
- Expected Outcome: Fix as many open issues in the Kubewarden policies as possible and create new policies requested by the community
- Recommended Skills: Rust, Go, Kubernetes
- Mentor(s): José Guilherme Vanz (@jvanz), Victor Cuadrado Juan (@viccuad)
- Upstream Issue: https://github.com/kubewarden/kubewarden-controller/issues/393
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9b8a3840-1355-4301-894b-7271c597f0cf

### KubeEdge

#### Design and implement the KubeEdge Dashboard

- Description: Users now can use K8s API or Kubectl to talk to KubeEdge, in this project we will design and implement the KubeEdge dashboard, so users can talk to KubeEdge cluster through UI.
- Expected Outcome: Create the KubeEdge dashboard, users can view and operate the resource through UI.
- Recommended Skills: JS, Kubernetes, KubeEdge, Html
- Mentors: Vincent Lin (@vincentgoat, linguohui1@huawei.com), Fisher Xu (@fisherxu, fisherxu1@gmail.com)
- Upstream Issue: https://github.com/kubeedge/dashboard/issues/1
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/4d9d8e17-8484-4c3e-9210-bb911633f57c


#### Re-design and implement the KubeEdge website

- Description: KubeEdge's website has been running for a few years, and now we have more customer cases and more developer courses, so this project will update KubeEdge's website, with more readable documents on the homepage, covering user cases, developer courses, etc.
- Expected Outcome: The website has more readable documentation, covering user cases, developer courses, etc.
- Recommended Skills: JS, KubeEdge, Html
- Mentor(s):  Shelley Bao (@Shelley-BaoYue, baoyue2@huawei.com), Fisher Xu (@fisherxu, fisherxu1@gmail.com)
- Upstream Issue: https://github.com/kubeedge/website/issues/292
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a50fec46-7bc6-4fa0-ba84-848f0c136b5c

#### Cloud-Robotic AI Benchmarking for Edge-cloud Collaborative Lifelong Learning

- Description: Based on real-world datasets provided by industry members of KubeEdge SIG AI, the issue aims to build a lifelong learning benchmarking on KubeEdge-Ianvs. Namely, it aims to help all Edge AI application developers to validate and select the best-matched algorithm of lifelong learning.
- Expected Outcome: The benchmark includes: 1) Work together to release a new dataset to the public! 2) Implement critical algorithm or system metrics, e.g., BWT, FWT and thoughput; 3) (Optional) Develop a baseline algorithm for this benchmark.
- Recommended Skills: TensorFlow/Pytorch, Python, Kubernetes
- Mentor(s): Siqi Luo (@luosiqi, luosiqi2@huawei.com), Fisher Xu (@fisherxu, fisherxu1@gmail.com)
- Upstream Issue: https://github.com/kubeedge/ianvs/issues/48
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/50cdbd65-e0cd-4c0f-8c63-6bd5c603ba89

#### Meshery

##### Distributed workflow engine

- Description: Integrate a new architectural component into Meshery: a workflow engine. This project involves shifting Meshery off of bitcask and off of sqlite over to postgres using gorm (golang). Interns will familiarize with concepts of orchestration engines, including chaining workflows, and content lifecycle management.
- Recommended Skills: Golang, Temporal, ReactJS
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Ashish Tiwari (ashishjaitiwari15112000@gmail.com)
- Issue: https://github.com/meshery/meshery/issues/3934
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/73202d21-d4ca-4435-9a73-f326c9b3e796
  
##### Multi-user cloud native playground

- Description: Advance the cloud native playground in which any CNCF project can be explored. Meshery’s genesis is that of helping teach people about cloud native technology and enabling to operate various types of cloud native infrastructure confidently. The proposed project is aimed at furthering this mission by infusing multi-user collaboration as a pervasisve feature so that users can learn together in a running instance of Meshery.
- Recommended Skills: ReactJS, CSS, Golang (nice-to-have)
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Abhishek Kumar (@abhishek-kumar09, abhimait1909@gmail.com)
- Issue: https://github.com/meshery/meshery/issues/7020
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/2ee7a912-e26e-4602-9dfc-4febe3842df3

#### Distributed client-side policy evaluation in WASM and Rego

- Description: Meshery's highly dynamic infrastructure configuration capabilities require real-time evaluation of complex policies. Policies of various types and with a high number of parameters need to be evaluted client-side. With policies expressed in Rego, the goal of this project is to incorporate use of the https://github.com/open-policy-agent/golang-opa-wasm project into Meshery UI, so that a powerful, real-time user experience is possible.
- Recommended Skills: Golang, Open Policy Agent, WebAssembly
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Ashish Tiwari (ashishjaitiwari15112000@gmail.com)
- Issue: https://github.com/meshery/meshery/issues/7019
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/7e3382be-5d82-443e-b0bc-4dcd2194705d

### Linkerd

#### Linkerd Dashboard Improvements

- Description: Improve the Linkerd web dashboard with improved topology visualization, support for Linkerd conformance to the Gateway API project, and improved multi-cluster support.
- Expected Outcome: A period of focused investment in the Linkerd viz dashboard experience will greatly improve the experience for Linkerd users. 
- Recommended Skills: React/JavaScript, Kubernetes
- Mentor(s): Oliver Gould (@olixOr, ver@buoyant.io), Alex Leong (@adleong, alex@buoyant.io) 
- Upstream Issue: https://github.com/linkerd/linkerd2/issues/7865, https://github.com/linkerd/linkerd2/issues/9243, https://github.com/linkerd/linkerd2/issues/9554
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/0dd36ed5-4c92-4fb3-b809-bb614261a199

#### Add dynamic profiling to Linkerd Rust controllers
- Description: The Linkerd control plane includes controllers that are written in Rust. Enable users to dynamically profile the running application can aid significantly in debugging and diagnostics. 
- Expected Outcome: In an upcoming release of Linkerd the policy controller would expose endpoints (leveraging [pprof](https://github.com/tikv/pprof-rs/blob/master/README.md) or another tool) for profiling controller resource consumption.
- Recommended Skills: Rust, Kubernetes
- Mentor(s): Oliver Gould (@olixOr, ver@buoyant.io), Alex Leong (@adleong, alex@buoyant.io) 
- Upstream Issue: https://github.com/linkerd/linkerd2/issues/10227
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e1ff5120-32e4-44a8-a1be-4e0717ef9ad6

#### Prototype multi-cluster service discovery and operations
- Description: When deploying a multi-cluster resource one has to perform certain contortions such as providing a list of other clusters to each cluster. This places a dependency ordering on spinning up new clusters and a requirement for application operators to coordinate with cluster operators.
- Expected Outcome: Develop a prototype where each cluster only needs to reference a common service definition to discover peers without knowledge of the names or even number of other clusters.
- Recommended Skills: Go, Rust, Kubernetes
- Mentor(s): Oliver Gould (@olixOr, ver@buoyant.io), Matei David (@mateiidavid, matei@buoyant.io) 
- Upstream Issue: https://github.com/linkerd/linkerd2/issues/7566
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ce8883ce-9e32-4337-8fe0-5c51fed758e4


### LitmusChaos

#### Improve code quality and add unit tests of litmus chaos components
- Description:  [LitmusChaos](https://litmuschaos.io) is an open-source Chaos Engineering platform that enables teams to identify weaknesses & potential outages in infrastructures by inducing chaos tests in a controlled way. This project aims to improve the code quality of the golang components of litmus chaos and refactor the codebase for adding the unit test cases.
- Expected Outcome: This will help the project to improve code quality, enhance the unit test suite, and identification of weaknesses
- Recommended Skills: Golang, Kubernetes
- Mentor: Amit Kumar Das (@amityt, amit.das@harness.io)  Sayan Mondal (@S-ayanide, sayan.mondal@harness.io)
- Upstream Issue: https://github.com/litmuschaos/litmus/issues/3892
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a222f58a-08ee-4727-80c8-41c4d6f5a2a9

### NATS

#### End-to-end example of a multiplayer game using NATS in Unity

- Description: This project consists of developing an example Unity setup of a multiplayer game using the latest version of the NATS Server.
- Expected Outcome: A well documented repository under the `nats-io` GitHub organization that contains the artifacts and sample code of the setup using the .NET NATS Client (https://github.com/nats-io/nats.net)
- Recommended Skills: .NET, C#, Unity, NATS
- Mentor(s): Waldemar Quevedo (@wallyqs)
- Upstream Issue: https://github.com/nats-io/dot-net-nats-examples/issues/1
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/127da817-037b-4225-83a6-3a3eeea8b421


### Notary

#### HashiCorp Vault plugin for Notary

- Description: Notary is a CNCF incubating project that aims to provide signing and verification capabilities to ensure delivery integrity and security. It supports creating and storing signatures for container images, SBOM, vulnerability scanning results, etc. to ensure the artifacts someone produced have not been tampered by others. Notary only has an Azure Key Vault plugin for storing keys in Azure Key Vault, which is used to sign and verify artifacts in the OCI registry. [HashiCorp Vault](https://github.com/hashicorp/vault) is a popular KMS and we see more and more users rely on it in the on-premise environment.
- Expected Outcome: Develop a Key Management System (KMS) plugin with [HashiCorp Vault](https://github.com/hashicorp/vault) for Notary CLI (Notation), which can be used to store the keys for Notation signing and verification.
- Recommended Skills: Golang programming language, Notary knowledge.
- Mentor(s): Patrick Zheng (@patrickzheng200, patrickzheng@microsoft.com), Shiwei Zhang (@shizhMSFT, shiwei.zhang@microsoft.com)
- Upstream Issue: https://github.com/notaryproject/notation/issues/521
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9710c834-913d-487d-9ebf-8205cdf48ab4

### OpenKruise

#### Bring progressive delivery to daemon workload

- Description: Kruise Rollout enable progressive delivery of various workload ranging from stateless workload such as Deployment to stateful workload such as StatefulSet or customized operators. This project aims to bring progress delivery capability to daemon workload, which is run on each node of a k8s cluster. The project involves implementing common API of progressive delivery for OpenKruise Advance DaemonSet, and integrate with the Kruise Rollout framework. 
- Expected Outcome: Support progressive delivery for OpenKruise Advance DaemonSet(along with supporting test cases and docs) , that is, update new version of daemon pods in batches with user defined pause strategy. Traffic scheduling is not required for this project. 
- Recommended Skills: Go, Kubernetes
- Mentor(s):  Zhang Zhen (@furykerry, furykerry@gmail.com), Zhang Lei(@resouer, resouer@gmail.com)
- Upstream Issue: https://github.com/openkruise/rollouts/issues/69
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/d3a1507a-b132-4c7c-aead-dfe78fd34eb8

#### Support customize arbitary fields of workload subset in UnitedDeployment

- Description: UnitedDeployment in OpenKruise enable users to manage a set of k8s workloads in whole while be able to customize the topology and replicas of each workload. This project extends the customization capability to arbitary workload fields by adding common patch fields, so that 
each subset of UnitedDeployment can have different metadata, container configuration etc. 
- Expected Outcome: Support generate patches for new creating pods of each subset workload while the users can rollout and scale the UnitedDeployment in whole. 
- Recommended Skills: Go, Kubernetes
- Mentor(s): Zhang Zhen (@furykerry, furykerry@gmail.com), Zhang Lei(@resouer, resouer@gmail.com)
- Upstream Issue: https://github.com/openkruise/kruise/issues/811
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/9e0f01ab-615f-44ed-b65b-0f1296037a48


### ORAS

#### Develop .NET SDK for ORAS

- Description: [ORAS](https://oras.land/) is a tool for working with OCI artifacts and OCI registries. It allows users to distribute OCI artifacts across OCI Registries. Users seeking a generic registry client can benefit from the ORAS CLI, while developers can build their own clients on top of one of the ORAS client libraries. ORAS has Python and Golang SDK that allow developers to build their own clients on top of one of the library. Similarly, developing a .NET SDK will enable .Net developers to use ORAS API and enhance the ORAS ecosystem. 
- Expected Outcome: Develop a .NET SDK in a new repository and write the examples and API document on GoDoc. Write unit test for this SDK and make sure the testing coverage is qualified.
- Recommended Skills: C#/.NET, ORAS conceptual knowledge.
- Mentor(s): Sylvia Lei (@Wwwsylvia, lixia.lei@microsoft.com), Shiwei Zhang (@shizhMSFT, shiwei.zhang@microsoft.com)
- Upstream Issue: https://github.com/oras-project/oras/issues/774
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/5d331c88-fc2d-4635-a92c-5d25fb42f47d

#### Develop ORAS Website

- Description: [ORAS](https://oras.land/) is a tool for working with OCI artifacts and OCI registries. It allows users to distribute OCI artifacts across OCI Registries. ORAS only has a documentation site so far, the project goal is to develop a new website using Hugo framework based on the Figma layout design.
- Expected Outcome: Develop a new website using the [Hugo framework](https://gohugo.io/) based on the Figma layout design. It will replace the existing [ORAS documentation website](https://oras.land/) and provide a better user experience with interactive design.
- Recommended Skills: HTML, Javascript, CSS, Hugo.
- Mentor(s): Feynman Zhou (@FeynmanZhou, feynmanzhou@microsoft.com), 
- Upstream Issue: https://github.com/oras-project/oras-www/issues/82
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/7f633ade-64f5-477c-bcbe-7b6693329c63

### Service Mesh Performance

#### Adaptive Load Controller II

- Description: The adaptive load controller is to execute optimization routines recursivley to determine the maximum load a system can sustain. The maximum load is usually defined by the maximum requests per second (rps) the system can handle. The metrics (CPU usage, latency etc) collected from the system under test are the constraints we provide to judge whether a system under test (SUT) is sustaining the load.

A use-case that fits very well is be the ability to use it to run performance tests on a schedule and track the maximum load a system can handle over time. This could give insights to performance improvements or degradations.

- Recommended Skills: golang, grpc, docker, kubernetes
- Mentor(s): Lee Calcote (@leecalcote, leecalcote@gmail.com), Xin Huang (@gyohuangxin, xin1.huang@intel.com)
- Upstream Issue (URL): https://github.com/service-mesh-performance/service-mesh-performance/issues/350
LFX URL: https://mentorship.lfx.linuxfoundation.org/project/2597fc3d-eb2c-411f-b02d-940c8347328d

### TestGrid

#### Frontend development inside Lit Component Framework

- Description: [TestGrid](http://testgrid.k8s.io) is the test visualization tool attached to Prow to
  collate and display historical test results for the k8s and k8s-adjacent
  communities. The UI is in the process of being rewritten.
- Expected Outcome: Create Lit-based view components for TestGrid (summary, index, etc.) that display data from the API. Implement Jasmine and Storybook testing for these components.
- Recommended Skills: TypeScript, CSS, Golang
- Mentor(s): Sean Chase (@chases2, slchase@google.com)
- Upstream Issue: https://github.com/GoogleCloudPlatform/testgrid/issues/1005
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/ca622980-cc8c-4f18-8a74-b9a7b4b49e3a

### Thanos

#### Add query observability for new promql engine
- Description: The new [Thanos Promql Engine](https://github.com/thanos-community/promql-engine) lacks observability down to operator level and we don't have a way to track each operator's performance. This project aims to extend the `Explain` method of each operator, and return an operator tree with time taken recorded. Then Thanos Query UI could then visualize the operator trace.
- Expected Outcome: Add a button in Query UI that when enabled will show query tree + how much time has been spent in each operator
- Recommended Skills: Golang, React
- Mentor: Giedrius Statkevičius (@GiedriusS, giedriuswork@gmail.com), Saswata Mukherjee (@saswatamcode, saswataminsta@yahoo.com)
- Upstream Issue: https://github.com/thanos-community/promql-engine/issues/106
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a0958ddf-1fd6-4c8e-887f-adb28639a9f4

#### Series Cardinality API
- Description: Prometheus has a TSDB stats API https://prometheus.io/docs/prometheus/latest/querying/api/#tsdb-stats which contains information about series cardinality and the API is supported by Thanos. However, it can only return 10 results per stats, which is not flexible to track the arbitrary metrics. This project aims to design and implement APIs that expose cardinalities. Stretch goal can be to add cardinality explorer page to Thanos UI.
- Expected Outcome: New Thanos APIs to expose series cardinality.
- Recommended Skills: Golang, React
- Mentor: Ben Ye (@yeya24, yb532204897@gmail.com)
- Upstream Issue: https://github.com/thanos-io/thanos/issues/6007
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/dbce5279-d029-46f3-b117-9e9dd7f84bd6

#### Querying Apache Parquet files with PromQL
- Description: The new [Thanos PromQL Engine](https://github.com/thanos-community/promql-engine) has a sufficient separation between the syntax tree and the execution plan to allow us to query arbitrary data sources. In this project we would like to explore ways to query data stored in Apache Parquet files.
- Expected Outcome: The Thanos PromQL engine can query timeseries data from Apache Parquet files.
- Recommended Skills: Golang
- Mentor: Filip Petkovski (@fpetkovski, filip.petkovsky@gmail.com), Prem Saraswat (@onprem, prmsrswt@gmail.com)
- Upstream Issue: https://github.com/thanos-community/promql-engine/issues/167
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/a04cfbe4-4dde-4c7e-8b70-9570639b48a7

### Vitess

#### Implement a benchmarking and load testing framework for the VReplication module in Vitess
- Description: Vitess is a distributed database system built around MySQL. VReplication is core technology built into Vitess that is used to enable many features like vertical and horizontal sharding, change data capture and materialized views. The project involves designing and implementing a customizable framework that enables us to test different VReplication workflows at scale and to obtain benchmarks that can be used to monitor performance improvements and regression from code changes. The framework will consist of a custom DSL (Domain Specific Language) which will be used to define each test case and a driver which will read the DSLs and execute the tests. The DSL will be based on the Hashicorp Configuration Language (https://github.com/hashicorp/hcl). The driver will be written in Golang and target AWS using Terraform for provisioning and Ansible for automation. The results and benchmarks will be stored in PlanetScale (https://planetscale.com/) in the existing vitess benchmark database.
- Expected Outcome: The test framework with at least one working test and stored benchmark metrics for a MoveTables workflow.
- Recommended Skills: golang
- Mentor: Rohit Nayak (@rohit-nayak-ps, rohit@planetscale.com) 
- Upstream Issue: https://github.com/vitessio/vitess/issues/12136
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/b903d812-c3ff-47bf-8626-0b9274fec742

#### Add complete parsing support for Spatial MySQL functions
- Description: Vitess is a database clustering system for horizontal scaling of MySQL. One of the key goals of Vitess is to emulate MySQL behavior even while running multiple MySQL instances so that ORMs and frameworks work seamlessly. Vitess has its own in-built SQL-parser which it uses to understand the query and represent as structs for further processing. As of now, a lot of spatial MySQL functions are not parsed correctly and result in syntax errors. The task of the mentee would be to add parsing support for such functions and features which can be found at https://dev.mysql.com/doc/refman/8.0/en/spatial-analysis-functions.html
- Recommended Skills: go, SQL, yacc, compilers and lexers
- Mentor(s): [Manan Gupta](https://github.com/GuptaManan100) (manan@planetscale.com)
- Upstraeam Issue: https://github.com/vitessio/vitess/issues/8604
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/d338ee93-e767-4f44-a0ea-02dbf803a55a

### WasmEdge

#### Streaming data processing with WasmEdge

- Description: WasmEdge would like to integrate WasmEdge as an alternative runtime for Fluvio. We would like to create a compile-time feature for the [fluvio-smartengine](https://github.com/infinyon/fluvio/tree/master/crates/fluvio-smartengine) crate. Once this feature is turned on, the compiler will choose to embed WasmEdge into the binary build using the [WasmEdge Rust SDK](https://wasmedge.org/book/en/sdk/rust.html).
- Expected Outcome: A complete PR and a demo app that uses WasmEdge to process streaming data using a Tensorflow or Pytorch model
- Recommended Skills: working knowledge of the Rust language and WebAssembly Rust SDK
- Mentor(s): Michael Yuan (@juntao, michael@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2231
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/484542b0-84d6-43e3-b3fe-16fb2624f1b2

#### A Rust library crate for mediapipe models for WasmEdge NN

- Description: WasmEdge would like to build a Rust library crate that enables easy integration of Mediapipe models in WasmEdge applications. Each Mediapipe model has [a description page](https://google.github.io/mediapipe/solutions/face_detection.html) that describes its input and output tensors. The [models](https://google.github.io/mediapipe/solutions/models.html) are available in Tensorflow Lite format, which is supported by the WasmEdge Tensorflow Lite plugin.
- Expected Outcome: We need at least one set of library functions for each model in Mediapipe. Each library function takes in a media object and returns the inference result.
- Recommended Skills: basic knowledge of Rust and experience in working with AI models and image processing.
- Mentor(s): Michael Yuan (@juntao, michael@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2229
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/e4e6d486-e6df-475d-8074-a363d0361076

#### Unified WasmEdge tools

- Description: WasmEdge provides two tools in the release assets: `wasmedgec` and `wasmedge`. However, providing multiple tools will make it too complicated to use. That's why we want a simple entry point, `wasmedge`. As its subcommands, all the tools above should be collected into this new tool.
- Expected Outcome: A document to explain the new WasmEdge tools, a test suite covers the implementation details, and implement `wasmedge run` and `wasmedge compile` featues.
- Recommended Skills: C++ programming language, WebAssembly knowledge.
- Mentor(s): Hung-ying Tai (@hydai, hydai@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2226
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/2ebb39fd-3497-44f3-90d7-e95b444b2bc8


#### WasmEdge C++ SDK

- Description: WasmEdge provides C SDK as the based library and uses this to implement other languages SDK such as Golang, Rust, Java, and Python(developing). We would like to provide C++ SDK in this task.
- Expected Outcome: A document to explain the C++ SDK, a test suite cover the implementation details, and the implementation of WasmEdge Basics and VM sections in the C SDK.
- Recommended Skills: C++ programming language, WebAssembly knowledge.
- Mentor(s): Yiying He (@q82419, yiying@secondstate.io)
- Upstream Issue: https://github.com/WasmEdge/WasmEdge/issues/2241
- LFX URL: https://mentorship.lfx.linuxfoundation.org/project/1d5d1fcd-b671-4367-b6db-13ef263aece1

