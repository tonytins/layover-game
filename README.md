# 🛩️ Layover

Layover is a Twine-based text adventure game adopted from a flash fiction I wrote not too long ago. While the premise is based on true story, the events and characters are completely fictional.

## 🗓️ Update Cycle

| Type         | Frequency            | Notes                                    |
| ------------ | -------------------- | ---------------------------------------- |
| Minor Update | Every 3–6 months     | Small enhancements, non-breaking changes |
| Patch Update | Monthly or as needed | Bug fixes, security updates              |
| Major Update | As needed            | Framework upgrades, major refactors      |

## 🖥️ Platform Support

| Target  | Windows | macOS  | Linux |
| ------- | ------- | ------ | ----- |
| x86_64  | ✅      | ⚠️[^1] | ✅    |
| aarch64 | ✅      | ✅     | ✅    |

[^1]: Rust 1.89 downgrades AMD64 support after Apple and GitHub CI did the same.

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

You will need to import the `.twee` source code into Twine in order to test or build. **DO NOT** edit `index.html`.

## 🔍 Background

Normally, modern text adventure games are published online. This project aims to experiment with a standalone offline version powered by Tauri. It's just something I always wanted to try.

## 📄 License

This project is licensed under the [GPL-3.0](LICENSE-GPL) and[CC0](LICENSE-CC0).
