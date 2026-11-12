<img src="https://github.com/redpanda-data/community/blob/main/icon-redpanda.png" alt="Redpanda logo" width="200">

# Redpanda Community
## **QUICK LINKS**
**[Docs](https://docs.redpanda.com/)** | **[Quickstart](https://docs.redpanda.com/streaming/current/get-started/quick-start/)**


The online community for Redpanda Community Edition, Redpanda Operator, and rpk.

- **Redpanda Community Edition** is the community-available version of Redpanda Streaming, the event-driven streaming data platform for developers. Kafka API compatible yet 10x faster. Raft is built in to every broker; there’s no separate controller quorum to manage. Written in highly-performant C++, so no JVM stop-the-world pauses or heap tuning. Designed from the ground up to run blazingly fast on Linux.
- **Redpanda Operator** is our Kubernetes Operator for automated deployment and easy orchestration of clusters, providing full lifecycle management and facilitating “day 2” operations.
- **rpk (Redpanda Keeper)** is the Command Line Interface (CLI) for managing everything from configuring brokers to high-level general Redpanda tasks. It spans many capabilities from cluster management, to Docker or Podman deployments for testing, to introspecting topics, consumer groups, and messages, to establishing security and access controls, to YAML configuration profiles. Runs on Linux, macOS and Windows.

## Check the Docs!

If you have basic questions about Redpanda, we encourage you to first check out the documentation (**[docs.redpanda.com](http://docs.redpanda.com)**). If you don’t find what you wanted at first, make sure to ask the integrated Redpanda AI assistant! It is like a friendly neighborhood Reference Librarian and can help get you to the answers you need.

## Discussions vs. Issues

If you still can’t find what you are looking for, or if you suspect you have a bug and want to report it, use this repo to open an issue or a discussion.

Discussions are for when you want to state your opinions, or to obtain feedback that may come from your peers as well as from Redpanda employees. These are not necessarily bugs. They may just be observations or questions you couldn’t find answers to in the documentation.

Issues are for when you truly suspect you are facing a problem in using the software as designed. They could be for technical support, or they could be for a feature request.

- **Security issues** — Don’t do it publicly! If you have a security-related issue you wish to report, please follow the policy found in **[SECURITY.md](https://github.com/redpanda-data/community/blob/main/SECURITY.md)** for reporting and responsible disclosure.
- Best-effort: Community support is best-effort, with no guaranteed response time or SLA.
- IMPORTANT! Redpanda Enterprise and Cloud customers. If you have a support contract you should use the support portal for faster, SLA-backed help.

## Opening an Issue

Please provide the following details:
- Specific product you are using (Redpanda Community Edition, Redpanda Operator or rpk)
- The specific version(s) you are using
- Your deployment type (bare metal, Docker, Kubernetes/Operator)
- The OS you are deploying on and its version
- How the problem manifests (how you noted the problem; when it occurred)
- Any steps you undertook to reproduce
- Any command or error logs

## Licensing

- Redpanda Community Edition, staring with release 26.3.1, is community-available, provided as binaries, under the Redpanda Community Edition License, which limits use to 50 cores per organization. Users who wish to have access to source code for older versions (pre-26.3.1) can find them under the repository at github.com/redpanda-data/redpanda.
- Redpanda Operator and rpk are also community-available, provided as binaries, under the Redpanda Community Edition License.
