# Hi, I'm Zhang
[![GitHub Roast 评分徽章](https://githubroast.icu/api/badge/Zhang-986)](https://githubroast.icu/u/Zhang-986)
<a href="https://githubroast.icu/u/Zhang-986"><img src="https://githubroast.icu/api/badge/Zhang-986" alt="GitHub Roast 评分徽章" /></a>


Software engineer based in Hangzhou, China.

I work on backend systems, developer tooling, and Go SDK/CLI reliability.

My recent open-source work is focused on Lark/Feishu developer infrastructure: auth correctness, token cache safety, WebSocket lifecycle bugs, streaming downloads, cross-platform CLI behavior, and automation-friendly error handling.

## Focus

- Go backend engineering and platform tooling
- Lark/Feishu SDK and CLI reliability
- Auth, token lifecycle, cache isolation, and transport edge cases
- WebSocket concurrency, graceful shutdown, and streaming I/O
- Structured errors and test coverage from both RD and QA perspectives

## Open Source

I prefer practical fixes to tools that developers actually run: reproduce the issue, isolate the root cause, add regression coverage, and keep the change small enough to review.

Merged Lark/Feishu contributions:

- [larksuite/cli#1454](https://github.com/larksuite/cli/pull/1454) - clarified remote event bus recovery when local `status` / `stop` cannot fix a remote blocker. Merged.
- [larksuite/cli#740](https://github.com/larksuite/cli/pull/740) - migrated task shortcut failures from bare errors to structured CLI errors for machine-readable recovery. Merged.

Active Lark/Feishu work under review:

- [larksuite/oapi-sdk-go#218](https://github.com/larksuite/oapi-sdk-go/pull/218) - isolates app and tenant token cache entries by app secret fingerprint to avoid credential cross-use.
- [larksuite/oapi-sdk-go#217](https://github.com/larksuite/oapi-sdk-go/pull/217) - adds streaming Drive download APIs to avoid buffering large files into memory.
- [larksuite/oapi-sdk-go#215](https://github.com/larksuite/oapi-sdk-go/pull/215) - guards WebSocket client config updates to remove a data race.
- [larksuite/oapi-sdk-go#216](https://github.com/larksuite/oapi-sdk-go/pull/216) - adds graceful shutdown support for WebSocket clients.
- [larksuite/cli#1525](https://github.com/larksuite/cli/pull/1525) - fixes Windows exec provider security audit false positives caused by synthetic Unix mode bits.
- [larksuite/cli#1524](https://github.com/larksuite/cli/pull/1524) - translates rich text segment styles in Sheets cell writes.



## Tech Stack

**Languages:** Go, Python, Java

**Backend:** APIs, CLIs, SDKs, Spring Boot, MySQL, Redis, PostgreSQL, MongoDB

**Tools:** Git, Docker, Linux, Kubernetes, Jenkins

## Contact

- Email: 3225483474@qq.com
