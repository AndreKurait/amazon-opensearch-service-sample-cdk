# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.1.0 - 2026-03-04

### Added
- `StackComposer` for orchestrating multi-stack CDK deployments
- `NetworkStack` for VPC infrastructure with configurable AZ count and CIDR
- `OpenSearchDomainStack` for managed OpenSearch Service domains
- Cluster configuration via `cdk.context.json` with typed parsing
- Fine-grained access control support (SAML, basic auth, IAM)
- EBS volume configuration including throughput for gp3
- Encryption at rest and node-to-node encryption
- VPC-based and public domain deployments
- ESLint with typescript-eslint strict + stylistic rules
- Jest test suite with coverage
- GitHub Actions CI (lint, test, link checker)
- Release workflow with automated GitHub Releases
- Version bump workflow for one-click releases
- npm package tarball as release artifact
