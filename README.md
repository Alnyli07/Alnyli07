# Hi, I'm Ali Tuğrul Pınar

Senior Platform & DevOps Engineer at **Keymate**. I build and run identity and access platforms on Kubernetes, and I ship the same stack to both cloud and air-gapped environments.

### What I work on

- **Kubernetes platforms**: AKS and on-prem clusters, Helm charts, Argo CD and GitOps delivery
- **Identity and access**: Keycloak extensions, database migrations and zero-downtime upgrades, fine-grained authorization
- **API gateways**: Apache APISIX, including a DPoP (RFC 9449) plugin
- **Delivery**: GitLab CI pipelines, release automation, mirrored deployments into air-gapped environments
- **Data and operations**: PostgreSQL operations, observability

Most of my day-to-day work is private on GitLab, so this profile shows only the open source part.

### Open source

**Projects I published at Keymate**
- [keycloak-ambient-authz](https://github.com/Keymate-io/keycloak-ambient-authz): zero-code service authorization on Kubernetes, Keycloak decisions enforced at the Istio Ambient waypoint
- [keycloak-ambient-authz-uma](https://github.com/Keymate-io/keycloak-ambient-authz-uma): Keycloak UMA ticket token exchange as a Proxy-Wasm PEP for Istio Ambient
- [keymate-apisix-dpop-plugin](https://github.com/Keymate-io/keymate-apisix-dpop-plugin): RFC 9449 DPoP validation plugin for Apache APISIX
- [keycloak-runtime-protobuf-schemas-demo](https://github.com/Keymate-io/keycloak-runtime-protobuf-schemas-demo): runtime-mounted Protobuf schemas in Keycloak's embedded Infinispan

**Keycloak**
- Merged: [#49061](https://github.com/keycloak/keycloak/pull/49061) export custom provider changesets in the manual migration strategy
- Merged: [#46387](https://github.com/keycloak/keycloak/pull/46387) fix resource selection display in scope-based permission creation
- Open: [#51730](https://github.com/keycloak/keycloak/pull/51730) and [#51933](https://github.com/keycloak/keycloak/pull/51933), manual migration fixes for empty databases

**Apache APISIX**
- Open: [#13165](https://github.com/apache/apisix/pull/13165) DPoP plugin for RFC 9449 proof-of-possession tokens

**Appcircle CLI**
- Organization commands, build listing and artifact download, and a few fixes ([merged PRs](https://github.com/appcircleio/appcircle-cli/pulls?q=is%3Apr+author%3AAlnyli07+is%3Amerged))

Before platform work I spent several years at Smartface building mobile and IDE tooling in TypeScript and Node.js.
