## Aixo impulse GmbH

Willkommen bei der Aixo impulse GmbH.

Diese Organisation wurde gegründet, um allen Mitarbeitern und Partnern der Aixo einen Ort zu bieten an dem man gemeinsam lernen und Werte schaffen kann.

## Infrastructure

### Runner

Die Aixo impulse GmbH stellt die drei internen (self hosted) Runner, concierge, aragorn und bosmang, für Builds zur Verfügung.

| Runner    | Labels                                                    |
| --------- | --------------------------------------------------------- |
| Concierge | `self-hosted`, `Linux`, `x64`, `aixo`, `CI`, `dependabot` |
| Aragorn   | `self-hosted`, `Linux`, `x64`, `aixo`, `CI`, `dependabot` |
| Bosmang   | `self-hosted`, `Linux`, `x64`, `aixo`, `CI`, `dependabot` |

Sie sind über das Label `dependabot` so konfiguriert, dass der GitHub Security Service `dependabot` auf den Runnern arbeiten und automatisiert Updates der Dependencies eines Projekts per Pull Request einspielen kann.
