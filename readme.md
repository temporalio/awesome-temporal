# Awesome Temporal [![Awesome list badge](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="temporal.png" align="right" width="200">](https://temporal.io/)

> A curated list of awesome Temporal libraries and resources.

Temporal is a [durable execution system](https://youtu.be/W0Ygep6iCJY?t=609). It makes code fault-tolerant and simple.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [Related awesome lists](#related-awesome-lists)
- [Communities](#communities)
- [DSL & Abstractions](#dsl--abstractions)
- [Cluster Management](#cluster-management)
- [Videos](#videos)
  - [Why Temporal](#why-temporal)
  - [Using Temporal](#using-temporal)
- [Podcasts](#podcasts)
- [Blog posts](#blog-posts)
  - [Why Temporal](#why-temporal-1)
  - [Using Temporal](#using-temporal-1)
- [Go](#go)
  - [Samples](#samples)
  - [Libraries](#libraries-1)
  - [Tutorials](#tutorials)
  - [Blog posts](#blog-posts-1)
  - [Videos](#videos-1)
- [TypeScript](#typescript)
  - [Samples](#samples-1)
  - [Libraries](#libraries-2)
  - [Tutorials](#tutorials-1)
  - [Blog posts](#blog-posts-2)
  - [Videos](#videos-2)
- [Java](#java)
  - [Samples](#samples-2)
  - [Libraries](#libraries-3)
  - [Tutorials](#tutorials-2)
  - [Blog posts](#blog-posts-3)
  - [Videos](#videos-3)
- [Python](#python)
  - [Samples](#samples-3)
  - [Libraries](#libraries-4)
  - [Tutorials](#tutorials-3)
  - [Blog posts](#blog-posts-4)
  - [Videos](#videos-4)
- [.NET](#net)
  - [Samples](#samples-4)
  - [Libraries](#libraries-5)
  - [Tutorials](#tutorials-4)
  - [Blog posts](#blog-posts-5)
  - [Videos](#videos-5)
- [PHP](#php)
  - [Samples](#samples-5)
  - [Libraries](#libraries-6)
  - [Tutorials](#tutorials-5)
  - [Blog posts](#blog-posts-6)
  - [Videos](#videos-6)
- [Ruby](#ruby)
  - [Samples](#samples-6)
  - [Libraries](#libraries-7)
  - [Tutorials](#tutorials-6)
  - [Blog posts](#blog-posts-7)
- [Clojure](#clojure)
- [Credits](#credits)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Related awesome lists

- [All lists](https://github.com/sindresorhus/awesome)
- [Software architecture](https://github.com/simskij/awesome-software-architecture#readme)
- [Microservices](https://github.com/mfornos/awesome-microservices#readme)
- [Queues](https://github.com/tonyhb/awesome-queues-jobs-and-tasks/)
- Languages we have SDKs in:
  - [Go](https://github.com/avelino/awesome-go#readme)
  - [Java](https://github.com/akullpp/awesome-java#readme)
  - [JavaScript](https://github.com/sorrycc/awesome-javascript#readme)
  - [Node](https://github.com/sindresorhus/awesome-nodejs#readme)
  - [Python](https://github.com/vinta/awesome-python#readme)
  - [PHP](https://github.com/ziadoz/awesome-php#readme)
  - [.NET](https://github.com/quozd/awesome-dotnet#readme)
  - [Ruby](https://github.com/markets/awesome-ruby#readme)
  - [Rust](https://github.com/rust-unofficial/awesome-rust#readme)
- Databases we support:
  - [Cassandra](https://github.com/Anant/awesome-cassandra#readme)
  - [Postgres](https://github.com/dhamaniasad/awesome-postgres#readme)
  - [MySQL](https://github.com/shlomi-noach/awesome-mysql#readme)

## Communities

- [Slack](https://t.mp/slack)
- [Forum](https://community.temporal.io/)
- [r/Temporal](https://www.reddit.com/r/Temporal/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/temporal-workflow+or+temporal-typescript)

## DSL & Abstractions
- [iWF](https://github.com/indeedeng/iwf) - DSL workflow framework on Temporal

## Cluster Management
- [`alexandrevilain/temporal-operator`](https://github.com/alexandrevilain/temporal-operator) - The Kubernetes operator to deploy and manage Temporal Clusters.

## Videos

### Why Temporal

- [Replay Keynote](https://www.youtube.com/watch?v=W0Ygep6iCJY) - Durable execution, Nexus, and Cloud.
- [Glovo: Fault tolerant distributed microservices with Temporal](https://youtu.be/6lSuDRRFgyY)
- [TheDevConf: Fault Tolerant, Distributed Microservices Orchestration with Temporal](https://www.youtube.com/watch?v=6T6zVZHU7_Q) - The problem Temporal solves and how it works ([slides](https://temporal-intro-and-demo.netlify.app/)).
- [State of Affairs or Affairs of State](https://www.youtube.com/watch?v=2P_aXee2qh4) - Stateless vs stateful architecture and why Temporal.
- [Designing a Workflow Engine from First Principles](https://temporal.io/blog/workflow-engine-principles/) - The internal system design of Temporal Server and how it solves consistency and scaling issues with workflow engines.
- [Sidekiq, Outbox, SAGAs and Best Practices for Distributed Transactions!](https://www.youtube.com/watch?v=Rr4DnHmy6eE)

### Using Temporal

- [A Guided Tour of Temporal’s New Web UI](https://www.youtube.com/watch?v=iCT4mml8mdM)
- [Time Travel Tests! Testing Async Workflows, Signals, and Queries with Temporal](https://www.youtube.com/watch?v=-GKxFDQSlEU)
- [Temporal Service and Application Architecture](https://youtu.be/r5bnp5bQHI4)
- [How to get workflow failure info using Temporal SDKs](https://www.youtube.com/watch?v=0QuWgqwmr-s)
- [Keeping Workflow Developers Afloat](https://www.youtube.com/watch?v=yeoawVIn060)
- [Temporal @ Datadog](https://www.youtube.com/watch?v=LxgkAoTSI8Q)
- [Workflow versioning](https://www.youtube.com/watch?v=kkP899WxgzY)
- [Polyglot Microservices Orchestration](https://www.youtube.com/watch?v=LSXP_o6sTic)

## Podcasts

- [Flagsmith](https://flagsmith.com/podcast/temporal-w-co-founder-and-ceo-maxim-fateev-and-head-of-product-ryland-goldstein/) - Maxim & Ryland explain Temporal and answer questions (50 min, Jun 19, 2022).
- [Stack Overflow Podcast: Run your microservices in no-fail mode](https://twitter.com/StackOverflow/status/1536740460789739520) - Maxim & Dominik explain Temporal (22 min, Jun 14, 2022).
- [Serverless Chats Podcast: Self-Provisioning Runtimes](https://www.serverlesschats.com/124/) - swyx presents Temporal as a self-provisioning runtime (1h, Feb 14, 2022).
- [Break Things on Purpose (Gremlin): Origin story, Choreography vs Orchestration, and Tips](https://temporal.io/blog/gremlin-podcast) - Maxim & Samar share the Temporal origin story (21 min, Oct 5, 2021).
- [JS Party: Temporal is like React for the backend](https://changelog.com/jsparty/208)

## Blog posts

### Why Temporal

- [Temporal - the iPhone of System Design](https://www.swyx.io/why-temporal)
- [Stack Overflow Blog: The macro problem with microservices](https://stackoverflow.blog/2020/11/23/the-macro-problem-with-microservices/)
- [Snap Engineering: Build a Reliable System in a Microservices World](https://eng.snap.com/build_a_reliable_system_in_a_microservices_world_at_snap)
- [Dealing with failure](https://temporal.io/blog/dealing-with-failure) - RPCs vs queues vs workflows.
- [Inversion of Execution](https://temporal.io/blog/sergey-inversion-of-execution)

### Using Temporal

- [A Practical Approach to Temporal Architecture](https://mikhail.io/2020/10/practical-approach-to-temporal-architecture/)
- [Introduction to Temporal Workflows](https://temporal.io/blog/dominik-workflow-part-1)
- [Failure Handling in Practice](https://temporal.io/blog/failure-handling-in-practice)
- [The 4 Types of Activity Timeouts](https://temporal.io/blog/activity-timeouts)
- [What does "Long Running" really mean?](https://temporal.io/blog/long-running)
- [Productionizing Workers](https://temporal.io/blog/workers-in-production)
- [Defining Workflows](https://temporal.io/blog/defining-workflows) - Using DSLs vs code to define workflows.
- [Tips and Tricks for Temporal Developer Productivity](https://temporal.io/blog/temporal-tips-tricks-1)
- [Easily Manage Workflows at Scale with Temporal.io and Astra DB](https://www.datastax.com/blog/easily-manage-workflows-at-scale-with-temporal-io-and-astra-db)
- [Why Rust powers Temporal's new Core SDK](https://temporal.io/blog/why-rust-powers-core-sdk)

## Go

- [Go SDK](https://github.com/temporalio/sdk-go)
- [Go SDK docs](https://t.mp/go)
- [Go SDK API reference](https://t.mp/go-api)

### Samples

- [`temporalio/samples-go`](https://github.com/temporalio/samples-go)
- [Benthos PoC](https://github.com/disintegrator/benthos-temporal-poc) - Start a workflow from a Benthos message.

### Libraries

- [`Courtsite/temporal-go-helpers`](https://github.com/Courtsite/temporal-go-helpers) - Collection of helpers: saga, receive Signal with timeout, drain channel.

### Tutorials

- [Getting started](https://learn.temporal.io/getting_started/go/dev_environment/)
- [Temporal 101](https://learn.temporal.io/courses/temporal_101)
- [eCommerce app](https://learn.temporal.io/tutorials/go/ecommerce/)
- [Background Check app](https://learn.temporal.io/examples/go/background-checks/)

### Blog posts

- [Media processing workflows](https://temporal.io/blog/media-processing-workflows)
- [Writing a Workflow, Simulating Failures, Retries, and Testing](https://www.jcheng.org/post/workflow-orchestration-1.2/)
- [Passing Context with Temporal​](https://spiralscout.com/blog/passing-context-with-temporal)

### Videos

- [Intro to Temporal with Go SDK](https://www.youtube.com/watch?v=-KWutSkFda8)
- [Intro Workshop with Go](https://www.youtube.com/watch?v=UwdGmdTO3Ts)

## TypeScript

- [TypeScript SDK](https://github.com/temporalio/sdk-typescript)
- [TypeScript SDK docs](https://t.mp/ts)
- [TypeScript SDK API reference](https://t.mp/ts-api)

### Samples

- [`temporalio/samples-typescript`](https://github.com/temporalio/samples-typescript)

### Libraries

- [`lorensr/temporal-time-utils`](https://github.com/lorensr/temporal-time-utils) - `sleepUntil` and `UpdatableTimer`.
- [Cognosis AI Platform](https://github.com/cognosisai/platform) - Template for large language model applications.

### Tutorials

- [Getting started](https://learn.temporal.io/getting_started/typescript/dev_environment/)
- [Next.js](https://learn.temporal.io/tutorials/typescript/nextjs/)
- [Subscriptions](https://learn.temporal.io/tutorials/typescript/subscriptions/) - Write a Workflow that models a user's subscription, periodically charging them for your service.
- [Create a Slack bot](https://learn.temporal.io/tutorials/typescript/chatbot/)

### Blog posts

- [Building Reliable Distributed Systems in Node](https://temporal.io/blog/building-reliable-distributed-systems-in-node)
- [How to Use Node.js Temporal Workflows to Batch Process Operations](https://www.bitovi.com/blog/how-to-use-node.js-temporal-workflows-for-batch-processing)
- [Using Temporal as a Node.js Task Queue](https://temporal.io/blog/using-temporal-as-a-node-task-queue)
- [Caching API Requests with Long-Lived Workflows](https://temporal.io/blog/caching-api-requests-with-long-lived-workflows)
- [Express middleware that creates a REST API for your Workflows](https://temporal.io/blog/temporal-rest)
- [1.0.0 release of the Temporal TypeScript SDK](https://temporal.io/blog/typescript-1-0-0)
- [How we use V8 isolates to enforce Workflow determinism](https://temporal.io/blog/intro-to-isolated-vm)

### Videos

- [Glovo: Fault tolerant distributed microservices with Temporal](https://youtu.be/6lSuDRRFgyY)
- [Building Reliable Distributed Systems](https://www.youtube.com/watch?v=fZHL1k5iEmA) ([slides](https://docs.google.com/presentation/d/1x0ETmVVJcbluTSnJGo8F2sNL1GKJPwOh-2s53x_UKLg/))
- [Complete Intro to Temporal Workshop](https://www.youtube.com/watch?v=CeHSmv8oF_4)
- [Slack Bot Tutorial](https://youtu.be/hGIhc6m2keQ)

## Java

- [Java SDK](https://github.com/temporalio/sdk-java)
- [Java SDK](https://t.mp/java)
- [Java SDK API reference](https://t.mp/java-api)

### Samples

- [`temporalio/samples-java`](https://github.com/temporalio/samples-java)

### Libraries

### Tutorials

- [Getting started](https://learn.temporal.io/getting_started/java/dev_environment/)

### Blog posts

### Videos

- [Intro to Temporal with Java SDK](https://youtu.be/1RY2lWSuJaA)
- [Java SDK Workshop](https://youtu.be/VoSiIwkvuX0)

## Python

- [Python SDK](https://github.com/temporalio/sdk-python)
- [Python SDK docs](https://t.mp/py)
- [Python SDK API reference](https://t.mp/py-api)

### Samples

- [`temporalio/samples-python`](https://github.com/temporalio/samples-python)

### Libraries

### Tutorials

### Blog posts

### Videos

- [Python SDK First Look](https://www.youtube.com/watch?v=jZgtiGgEK6A)

## .NET

- [.NET SDK](https://github.com/temporalio/sdk-dotnet)
- [.NET SDK docs](https://dotnet.temporal.io/)

### Samples

### Libraries

### Tutorials

### Blog posts

### Videos

## PHP

- [PHP SDK](https://github.com/temporalio/sdk-php)
- [PHP SDK docs](https://t.mp/php)

### Samples

- [`temporalio/samples-php`](https://github.com/temporalio/samples-php)

### Libraries

- [RoadRunner](https://github.com/roadrunner-server/roadrunner) - PHP application server and process manager.

### Tutorials

- [Getting started](https://learn.temporal.io/getting_started/php/dev_environment/)
- [Saga](https://learn.temporal.io/tutorials/php/booking_saga/) - Write a saga Workflow.
- [Subscriptions](https://learn.temporal.io/tutorials/php/subscriptions/) - Write a Workflow that models a user's subscription, periodically charging them for your service.

### Blog posts

### Videos

- [Create Your First Workflow](https://youtu.be/goulj2CRNOY)
- [PHPKonf 2021: Fault tolerant workflow orchestration on PHP](https://www.youtube.com/watch?v=pdxHkIqX62A)

## Ruby

- [Ruby SDK](https://github.com/temporalio/sdk-ruby)

### Samples

### Libraries

### Tutorials

### Blog posts

## Clojure

- [Clojure SDK](https://github.com/manetu/temporal-clojure-sdk)

## Credits

We welcome contributions! See [`contributing.md`](contributing.md).

🙏 Thank you to: 

- [All those who have contributed](https://github.com/temporalio/awesome-temporal/graphs/contributors)
- [`firdaus`](https://github.com/firdaus) for [`firdaus/awesome-cadence-temporal-workflow`](https://github.com/firdaus/awesome-cadence-temporal-workflow)
