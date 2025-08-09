# 🛩️ Layover

Layover is a Twine-based text adventure game adopted from a flash fiction I wrote not too long ago. While the premise is based on true story, the events and characters are completely fictional.

Normally, modern text adventure games are published online. This project aims to experiment with creating an offline version using Tauri. It's something I always wanted to try.

## 🗓️ Update Cycle

| Type         | Frequency            | Notes                                    |
| ------------ | -------------------- | ---------------------------------------- |
| Minor Update | Every 3–6 months     | Small enhancements, non-breaking changes |
| Patch Update | Monthly or as needed | Bug fixes, security updates              |
| Major Update | As needed            | Framework upgrades, major refactors      |

## 🛡️ Support

- [x] Active Support
- [ ] Limited Support (Security patches only)
- [ ] Maintenance Mode (Dependency-only updates)
- [ ] Archived (No active work planned)

## 🧰 Recommended IDE Setup

Before you begin, ensure you have the latest versions of the following installed:

- [VS Code](https://code.visualstudio.com/) (or [VSCodium](https://vscodium.com/))
- [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode)
- [Rust](https://www.rust-lang.org/tools/install)
  - [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
- [Bun](https://bun.com/)
- [Twine](https://twinery.org/)

## 🛠️ Getting Started

1. Install dependencies with `bun install`
2. Simply type `bun tauri dev` to run the application
3. Finally, you can compile your own copy with `bun tauri build`.

### 📖 Twine

You will need to import the `.twee` source code into Twine in order to test or build. **DO NOT** open the `index.html`.

## 📄 License

Entries is licensed under the GPL-3.0 license. For more information, please refer to the [LICENSE](LICENSE) file in the project repository.
