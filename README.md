# Hi, I'm Zhang

Software engineer based in Hangzhou, China.

I work on backend systems, developer tooling, and Go SDK/CLI reliability. I care about small, reviewable fixes with clear tests: auth and config boundaries, transport behavior, structured errors, streaming, and developer workflows that fail in predictable ways.

## Focus

- Go backend engineering and platform tooling
- SDK, CLI, and OpenAPI integration reliability
- Auth, config, transport, and protocol edge cases
- Test coverage from both RD and QA perspectives

## Open Source

I prefer practical fixes to tools that developers actually run: reproduce the issue, isolate the root cause, add regression coverage, and keep the change easy to review.

Selected recent work:

- [larksuite/cli#1454](https://github.com/larksuite/cli/pull/1454) - clarified remote event bus recovery when local `status` / `stop` cannot fix a remote blocker. Merged.
- [larksuite/cli#740](https://github.com/larksuite/cli/pull/740) - migrated task shortcut failures from bare errors to structured CLI errors for machine-readable recovery. Merged.
- [anthropics/anthropic-sdk-go#374](https://github.com/anthropics/anthropic-sdk-go/pull/374) - skips environment auth autoload when explicit credentials are configured. Open PR.
- [anthropics/anthropic-sdk-go#375](https://github.com/anthropics/anthropic-sdk-go/pull/375) - makes Bedrock requests respect the configured AWS HTTP client. Open PR.
- [google/adk-go#1022](https://github.com/google/adk-go/pull/1022) - runs callbacks for aggregated A2A events emitted from partial artifact streams. Open PR.
- [google/adk-go#1023](https://github.com/google/adk-go/pull/1023) - aligns skill tool instructions with the actual `load_skill` schema. Open PR.

## Tech Stack

**Languages:** Go, Python, Java

**Backend:** APIs, CLIs, SDKs, Spring Boot, MySQL, Redis, PostgreSQL, MongoDB

**Tools:** Git, Docker, Linux, Kubernetes, Jenkins

## Contact

- Email: 3225483474@qq.com
