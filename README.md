# Albab Hasan

High school student, systems programmer, and open-source contributor from Bangladesh. I contribute to developer tools used by thousands of engineers and build compilers and shells from scratch.

**12+ merged PRs** to [rust-analyzer](https://github.com/rust-lang/rust-analyzer), [Zed](https://github.com/zed-industries/zed), [Linux kernel](https://lore.kernel.org/linux-staging/DGROXGWX17G4.1782487P7HLCT@gmail.com/T/#t), and [ACE-Step](https://github.com/ace-step/ACE-Step-1.5) -- fixing compiler bugs, memory safety issues, and security vulnerabilities in production codebases.

## Open Source Contributions

### rust-analyzer -- Rust compiler frontend for IDEs

| PR | Description | Status |
|----|-------------|--------|
| [#21838](https://github.com/rust-lang/rust-analyzer/pull/21838) | fix: skip usages inside macro expansions in destructure struct/tuple binding | Merged |
| [#21779](https://github.com/rust-lang/rust-analyzer/pull/21779) | Replace TODO placeholders in next-solver IrPrint with proper formatting | Merged |
| [#21726](https://github.com/rust-lang/rust-analyzer/pull/21726) | Align `is_rust()` with rustc by correcting constructor ABI in next solver | Merged |
| [#21699](https://github.com/rust-lang/rust-analyzer/pull/21699) | Detect E0804 when casting raw ptr-to-dyn adds auto traits | Merged |
| [#21654](https://github.com/rust-lang/rust-analyzer/pull/21654) | Use `ExprIsRead::Yes` for rhs of binary operators | Merged |
| [#21649](https://github.com/rust-lang/rust-analyzer/pull/21649) | Use `ExprIsRead::Yes` for rhs of ordinary assignments | Merged |
| [#21647](https://github.com/rust-lang/rust-analyzer/pull/21647) | Handle `ref mut` bindings in `contains_explicit_ref_binding` | Merged |

### Zed -- high-performance code editor

| PR | Description | Status |
|----|-------------|--------|
| [#50173](https://github.com/zed-industries/zed/pull/50173) | Fix `send_file_drop_event` holding mutex during event callback | Merged |
| [#49906](https://github.com/zed-industries/zed/pull/49906) | Call `ack_configure` on throttled Wayland resize events | Merged |
| [#48850](https://github.com/zed-industries/zed/pull/48850) | Fix double-close of fd in `read_fd` on Linux | Merged |
| [#48727](https://github.com/zed-industries/zed/pull/48727) | Reset `external_files_dragged` after drag-drop on macOS | Merged |
| [#48317](https://github.com/zed-industries/zed/pull/48317) | Remove duplicate `line_hint` assignment in `StreamingFuzzyMatcher::push` | Merged |

### Linux kernel

- [staging: vme_user: remove unimplemented `#if 0` code blocks](https://lore.kernel.org/linux-staging/DGROXGWX17G4.1782487P7HLCT@gmail.com/T/#t) -- in staging tree
- [rust: transmute: use `split_at_checked()` and `split_at_mut_checked()`](https://lore.kernel.org/all/20260310095710.1166-1-albabhasan276@gmail.com/) -- pending MSRV bump
- [rust: print: add SAFETY comments to unsafe blocks](https://lore.kernel.org/all/20260321143406.67066-1-albabhasan276@gmail.com/) -- waiting for possible collab/closure. reason: duplicate
- [rust: workqueue: add SAFETY comments for Pin<KBox<T>> impl blocks](https://lore.kernel.org/all/20260322044340.129985-1-albabhasan276@gmail.com/) -- Cc'd to workqueue owners.

### ACE-Step-1.5 -- security fixes

| PR | Description | Status |
|----|-------------|--------|
| [#343](https://github.com/ace-step/ACE-Step-1.5/pull/343) | Fix path traversal vulnerability in audio file path handling | Merged |
| [#319](https://github.com/ace-step/ACE-Step-1.5/pull/319) | Prevent arbitrary code execution via unsafe `torch.load()` | Merged |
| [#226](https://github.com/ace-step/ACE-Step-1.5/pull/226) | Use per-socket timeout instead of global `setdefaulttimeout` | Merged |
| [#161](https://github.com/ace-step/ACE-Step-1.5/pull/161) | Fix path traversal vulnerability in audio endpoint | Merged |

## Projects

**[Hydrogen Orbital Visualizer](https://github.com/Albab-Hasan/Hydrogen-Orbital-Visualizer)** -- Real-time 3D quantum mechanics visualizer in C++. Solves the Schrödinger equation and renders electron orbital probability densities as 500k-particle point clouds with GPU shaders.

**[redix](https://github.com/Albab-Hasan/redix)** -- C compiler written in C. Lexer, parser, and code generator built from scratch.

**[Ash](https://github.com/Albab-Hasan/Ash)** -- Unix shell written in Rust with async I/O, syntax highlighting, tab completion, piping, and I/O redirection.

**[Bangladesh Weather & Pollution Dataset](https://github.com/Albab-Hasan/Bangladesh-Weather-Pollution-Dataset)** -- 14,208 daily observations of weather and air quality across all 64 districts of Bangladesh. 7 months of cleaned data, no missing values.

## Research

**Automated Semantic Testing of IDE Code Assists via Differential Compilation**

## Competitive Programming & ML

| Platform | Rating | Rank |
|----------|--------|------|
| Codeforces | **Expert** (1627) | -- |
| CodeChef | **4-star** (1947) | #88 in Bangladesh |
| Kaggle Notebooks | **Expert** | #838 / 58,000 |

Kaggle: 1 silver medal, 9 bronze medals, 353 upvotes, 238 forks across notebooks.

## Links

[![Codeforces](https://img.shields.io/badge/Codeforces-1627-blue?logo=codeforces)](https://codeforces.com/profile/albab_hasan-)
[![CodeChef](https://img.shields.io/badge/CodeChef-1947-brown?logo=codechef)](https://www.codechef.com/users/albab_hasan)
[![Kaggle](https://img.shields.io/badge/Kaggle-Expert-20beff?logo=kaggle)](https://www.kaggle.com/albab12)
[![LeetCode](https://img.shields.io/badge/LeetCode-albab__hasan-orange?logo=leetcode)](https://leetcode.com/albab_hasan)
[![YouTube](https://img.shields.io/badge/YouTube-Channel-red?logo=youtube)](https://www.youtube.com/@albabhasan0)
