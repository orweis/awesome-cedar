# Awesome Cedar [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for [Cedar](https://www.cedarpolicy.com/), AWS's open-source policy language and authorization engine: tools, frameworks, bindings, articles and guides.

Contributions are welcome, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Official](#official)
- [Deploy and Run Cedar](#deploy-and-run-cedar)
- [Policy Administration](#policy-administration)
- [Cedar Core and Bindings](#cedar-core-and-bindings)
- [Articles](#articles)
- [Videos](#videos)
- [Contributing](#contributing)

## Official

- [Cedar Project](https://www.cedarpolicy.com/en) - Home page of the Cedar language.
- [Cedar Docs](https://docs.cedarpolicy.com/) - Language reference and guides.
- [Cedar Playground](https://www.cedarpolicy.com/en/playground) - Try Cedar policies in the browser.
- [cedar-policy on GitHub](https://github.com/cedar-policy) - Official organization: the Rust core, formal spec, examples and more.
- [Cedar Community](https://io.permit.io/07ATaP) - Community link (a short link, maintained by Permit.io).

## Deploy and Run Cedar

- [Amazon Verified Permissions](https://aws.amazon.com/verified-permissions/) - Managed AWS service for Cedar-based authorization.
- [Cedar Agent](https://github.com/permitio/cedar-agent) - HTTP server that stores Cedar policies and data and answers authorization requests. *(Permit.io project.)*
- [Permit.io](https://www.permit.io/) - Authorization platform with Cedar support. *(Vendor.)*

## Policy Administration

- [OPAL](https://github.com/permitio/opal) - Open Policy Administration Layer: keeps policy engines in sync in real time. *(Permit.io project.)*
- [OPAL docs for Cedar](https://docs.opal.ac/tutorials/cedar) - Tutorial for running OPAL with Cedar.

## Cedar Core and Bindings

- [cedar-policy/cedar](https://github.com/cedar-policy/cedar) - Official Rust implementation: parser, evaluator and validator.
- [cedar-policy/cedar-go](https://github.com/cedar-policy/cedar-go) - Official Go implementation.
- [cedar-policy/cedar-spec](https://github.com/cedar-policy/cedar-spec) - Formal specification and verification of Cedar.
- [cedar-policy/cedar-examples](https://github.com/cedar-policy/cedar-examples) - Example applications and policies.
- [Joffref/cedar](https://github.com/Joffref/cedar) - Go bindings (WASM based).
- [iann0036/cedargo](https://github.com/iann0036/cedargo) - Go bindings (CGO based).

## Articles

- [Cedar vs Rego (OPA)](https://www.permit.io/blog/opa-vs-cedar) - Comparison of the two policy languages. *(Permit.io blog.)*
- [How we built Cedar with automated reasoning and differential testing](https://www.amazon.science/blog/how-we-built-cedar-with-automated-reasoning-and-differential-testing) - Verification-guided development of Cedar.
- [Cedar: A new policy language](https://onecloudplease.com/blog/cedar-a-new-policy-language) - Introductory overview.

## Videos

- [Use policies to manage permissions with Amazon Verified Permissions (AWS re:Invent 2022)](https://www.youtube.com/watch?v=k6pPcnLuOXY) - Conference session.

## Contributing

Got a Cedar-related project to add? Please read [CONTRIBUTING.md](CONTRIBUTING.md) and open a pull request.

Disclosure: the maintainer works at Permit.io, so some entries are Permit.io projects. They are marked as such and held to the same criteria as everything else.
