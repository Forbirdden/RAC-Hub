[<img src="https://github.com/user-attachments/assets/f2be5caa-6246-4a6a-9bee-2b53086f9afb" height="50">]() [<img src="https://github.com/user-attachments/assets/4d35191d-1dbc-4391-a761-6ae7f76ba7af" height="50">]() 

Here you can find RAC clients, servers and more 

You can help RAC Hub by [adding more information](https://github.com/Forbirdden/rachub/pulls)

# Clients

| Title        | Description | Author        | Download     | Status     | Lang | RAC   |   WRAC |
|    :----:    |    :----:   |    :----:     |  :----:  |  :----:    |  :----:    | :----:    | :----: |
| clRAC | The official RAC client | Mr. Sugoma | [WDfiles](https://wdfiles.ru/Ofx7) | Active | C | v2 | ❌ |
| [CRAB](https://gitea.bedohswe.eu.org/pixtaded/crab) | Bundle with both client and server | pixtaded | [Bʰedoh₂ swé's Gitea](https://gitea.bedohswe.eu.org/pixtaded/crab/releases) | Frozen | Java | v1.99.2 | ❌ |
| [bRAC](https://github.com/MeexReay/bRAC)[^1] | better RAC client (GUI) | MeexReay | [GitHub](https://github.com/MeexReay/bRAC/releases) | Active | Rust | v2 | v2 |
| [Mefedroniy](https://github.com/OctoBanon-Main/mefedroniy-client) | TUI client for RAC | OctoBanon | [GitHub](https://github.com/OctoBanon-Main/mefedroniy-client/releases) | Active | Rust | v1.99.2 | ❌ |
| Snowdrop | WRAC GUI client | Forbirdden | Soon... | In development | JavaScript | ❌ | v2 |
| [сRACk](https://github.com/pansangg/cRACk) | client for RAC kettles (TUI) | pansangg | [GitHub](https://github.com/pansangg/cRACk/releases) | Active | Python | v2 | ❌ |
| [Tower](https://github.com/kostya-zero/tower) | GUI client for RAC developed using the Tauri framework | Kostya Zero | ❌ | Active | Rust | v2 | ❌ |
| [RAC.rs](https://github.com/kostya-zero/rac-rs) | A Rust client library for RAC protocol | Kostya Zero | ❌ | Active | Rust | v2 | v2 |
| [Dobroho Vechora](https://gitea.bedohswe.eu.org/bedohswe/dobroho_vechora) | The first open-source client | Bʰedoh₂ swé | [Bʰedoh₂ swé's Gitea](https://gitea.bedohswe.eu.org/bedohswe/dobroho_vechora/src/branch/main/dobroho_vechora.bash) | Abandoned | Bash | v1[^2] | ❌ |
| WebbyCRAB | Fork of CRAB that runs online using TeaVM | Forbirdden | ❌ | Abandoned | Java | v1, v1.99.2 | ❌ |
| WinRAC | GUI client for RAC developed using WinForms | cat8753 | ❌ | Abandoned | C# | v1.99.2 | ❌ |
| lRAC[^3] | The first original RAC client developed using the tkinter library | Mr. Sugoma | [GitHub](https://github.com/The-Stratosphere-Solutions/RAC-Hub/tree/main/Archive/lRAC) | Abandoned | Python | v1 | ❌ |

[^1]: [bRAC-0.1.3+2.0 requires GTK4 to be installed on Windows](https://github.com/MeexReay/bRAC/releases/tag/0.1.3%2B2.0#user-content-window-gui-install)
[^2]: "_Я раньше хотел допилить его до v2, но мой bash код было трудно обновить_" - chunbyonga


# Server software

| Title        | Description | Author        | Download     | Status     | Lang     | RAC   | WRAC |
|    :----:    |    :----:   |    :----:     |  :----:  |  :----:    |  :----:    | :----:    | :----: |
| lRACd | The official RAC server | Mr. Sugoma | [WDfiles](https://wdfiles.ru/Obvt) | Active | C | v2 | ❌ |
| [CRAB](https://gitea.bedohswe.eu.org/pixtaded/crab) | Bundle with both client and server | pixtaded | [Bʰedoh₂ swé's Gitea](https://gitea.bedohswe.eu.org/pixtaded/crab/releases) | Abandoned | Java | v1.99.2 | ❌ |
| [sRAC](https://github.com/MeexReay/sRAC) | simple RAC server | MeexReay | [GitHub](https://github.com/MeexReay/sRAC/releases) | Active | Rust | v2 | v2 | 
| Gashishnik | WRAC server | OctoBanon | Soon... | In development | Rust | ❌ | v2 | ❌ |
| [AlmatyD](https://gitea.bedohswe.eu.org/bedohswe/almatyd) | Open source server | Bʰedoh₂ swé | [Bʰedoh₂ swé's Gitea](https://gitea.bedohswe.eu.org/bedohswe/almatyd) | Abandoned[^3] | TypeScript | v1 | ❌ |
| WebbyCRAB | Fork of CRAB that runs online using TeaVM | Forbirdden | ❌ | Abandoned | Java | v1, v1.99.2 | ❌ |
| Butter | Simple Node.js RAC server | Forbirdden | ❌ | Abandoned | JavaScript | v1.99, v2 | ❌ |

[^3]: "_Мне лень его допиливать. Если тебе зачем-то очень нужен RAC сервер, то ставь CRAB._" - chunbyonga

# Known servers

| IP        | Port | Description | Software     | Status     | Protocol | Auth |
|    :----:    |    :----:   |    :----:     |  :----:  |  :----:    |  :----:    | :----: |
| 91.192.22.20 | 42666 | Official server by Mr. Sugoma | lRACd | Active | RACv2 | Optional |
| meex.lol | 11234 | WRACS tor proxy of 91.192.22.20:42666 | [sRAC](https://github.com/MeexReay/sRAC) | Active | WRACSv2 | Optional |
| meex.lol | 42666 | RAC proxy of meex.lol:52667 | [sRAC](https://github.com/MeexReay/sRAC) | Active | RACv2 | Required |
| meex.lol | 52667 | Official WRACS server | [sRAC](https://github.com/MeexReay/sRAC) | Active | WRACSv2 | Required |

# Protocol documentation

- [RACv1.0](https://github.com/Forbirdden/RAC-Hub/blob/main/RACv1.md)[^4] 
- [RACv1.99.x](https://github.com/Forbirdden/RAC-Hub/blob/main/RACv1.99.md)
- [RACv2.0](https://github.com/Forbirdden/RAC-Hub/blob/main/RACv2.md)
- [WRACv2.0](https://github.com/Forbirdden/RAC-Hub/blob/main/WRAC.md)

[^4]: "_Про RAC 1 вообще забудь, это днище, его юзать нельзя._" - Mr. Sugoma

# See also

- [User agents](USER_AGENTS.md)
- [Original RAC-Hub](https://github.com/The-Stratosphere-Solutions/RAC-Hub)