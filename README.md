<p align="center">
  <img src="./assets/profile-banner.svg" alt="Finnley, software developer" width="100%" />
</p>

<p align="center">
  I turn repetitive, awkward, or interesting problems into focused software.
  <br />
  Desktop tools, web apps, native mobile projects, automation, and C# game mods.
</p>

<p align="center">
  <a href="https://git.finnley.co.uk/"><strong>Portfolio</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/KeyErrorFinn?tab=repositories"><strong>Repositories</strong></a>
</p>

## Currently building

These projects are still in development and are not publicly released yet.

| Project | What I am building | Engineering focus |
| --- | --- | --- |
| **WoL Plus** | An Alexa Smart Home skill and Windows companion for securely waking, monitoring, and shutting down registered computers. | AWS Lambda, DynamoDB, API Gateway WebSockets, SST, Python, React, TypeScript, Rust, Tauri |
| **RepQuest** | An Android-first, offline workout tracker that turns training into a lightweight role-playing game with routines, quests, XP, cosmetics, achievements, and a weekly boss. | React, TypeScript, Tauri, Rust, SQLite, Android, offline-first architecture |

<details>
<summary><strong>What makes those projects interesting?</strong></summary>

<br />

**WoL Plus** combines cloud infrastructure with a native Windows agent. It uses authenticated short-lived connection tickets, durable shutdown commands, event-driven device presence, reconnect recovery, transactional writes, and shared operational monitoring.

**RepQuest** keeps workout data on the device while separating the React interface from native persistence. Important workout completion, reward, personal-record, and progression updates are handled transactionally so retries cannot duplicate XP or coins.

</details>

## Pick a project

| If you want to see... | Start here |
| --- | --- |
| Browser-side archive processing and a detailed editor interface | [Online Stream Deck Editor](https://github.com/KeyErrorFinn/online-elgato-streamdeck-editor), [live demo](https://git.finnley.co.uk/online-elgato-streamdeck-editor/) |
| Electron process boundaries, image processing, and desktop performance work | [RPUK Screenshot Cropper](https://github.com/KeyErrorFinn/rpuk-screenshot-cropper) |
| C# game integration and careful item-safety rules | [How to QuickSell](https://github.com/KeyErrorFinn/how-to-fish-quicksell-mod) |
| React data parsing for a real community workflow | [Park Ranger Bills Helper](https://github.com/KeyErrorFinn/rpuk-park-ranger-bills), [live demo](https://git.finnley.co.uk/rpuk-park-ranger-bills/) |
| Unity asset replacement, skins, configuration, and custom controls | [How to Karambit](https://github.com/KeyErrorFinn/how-to-fish-karambit-mod) |
| A collaborative Python learning project | [Order Book Project](https://github.com/KeyErrorFinn/mthree-order-book-project) |

## The toolbox

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB" />
  <img alt="Electron" src="https://img.shields.io/badge/Electron-47848F?logo=electron&logoColor=fff" />
  <img alt="Tauri" src="https://img.shields.io/badge/Tauri-FFC131?logo=tauri&logoColor=111827" />
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=fff" />
  <img alt="C Sharp" src="https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=fff" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff" />
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=fff" />
</p>

I care about clear interfaces, sensible boundaries, failure recovery, local-first behaviour where it fits, and documentation that tells the truth about what is tested.

<details>
<summary><strong>A quick look behind the code</strong></summary>

<br />

Recent work has included:

* Designing authenticated WebSocket recovery and idempotent command handling
* Keeping Electron filesystem access behind a context-isolated preload bridge
* Improving cold-start performance for large screenshot libraries
* Building retry-safe workout rewards with Rust and SQLite transactions
* Working with Unity internals through BepInEx and Harmony
* Adding build checks that caught real cross-platform failures

</details>

## Say hello

I am open to junior software development opportunities where I can keep learning and ship useful work.

The easiest way to explore what I build is through [my portfolio](https://git.finnley.co.uk/) or the project links above.
