# Open Rust: Essential Rust for Substrate Developers

![-OpenRust-2-29-2024](https://github.com/openguild-labs/open-rust/assets/56880684/36780f74-079c-45ab-986a-f69e414a3a30)

## Curriculum
### Getting started
| Module Index      | Module Name | Assignments |
| ----------- | ----------- | ---------- |
| **Module 0**       | **Overview of Rust and Polkadot SDK** | 2 in total |
| Module 0.1      | [Introduction to Rust](/syllabus/module/0.1-slides.md) |
| Module 0.2      | [Introduction to Polkadot SDK](/syllabus/module/0.2-slides.md) | 1 multiple select question |
| **Module 1**      | **Rust Basic Concepts** | 2 in total |
| Module 1.1       | [Common programming concepts](/syllabus/module/1.1-slides.md) |
| Module 1.2       | [Program life cycle](/syllabus/module/1.2-slides.md) | 1 exercise-based assignment |
| Module 1.3       | [Ownership & Borrow checker](/syllabus/module/1.3-slides.md) |
| Module 1.4       | [Common Data Structures](/syllabus/module/1.4-slides.md) | 1 project-based assignment |
| **Module 2**       | **Advanced Rust Concepts** | 2 in total |
| Module 2.1       | [Generic types, trait extension and advanced types](/syllabus/module/2.1-slides.md) | |
| Module 2.2       | [Lifetimes](/syllabus/module/2.2-slides.md) | 1 exercise-based assignment | 
| Module 2.3       | [Smart pointers & Macros](/syllabus/module/2.3-slides.md) | |
| Module 2.4       | [Common design patterns in Rust](/syllabus/module/2.4-slides.md) | |
| Module 2.5       | [Package Management & How to structure your Rust project](/syllabus/module/2.5-slides.md) | 1 project-based assignment |
| Module 2.6 | [Overview of the Rust ecosystem: Libraries & Resources](/syllabus/module/2.6-slides.md) | |
| **Module 3**       | **Rust in Substrate** | 2 in total |
| Module 3.1       | [Common blockchain data structures: Header, Block, Extrinsic, etc.](/syllabus/module/3.1-slides.md) | |
| Module 3.2       | [Substrate State Machine in Rust](https://github.com/shawntabrizi/rust-state-machine) | 1 exercise-based assignment | 
| Module 3.3       | [Common Rust libraries used in Substrate Node](/syllabus/module/3.3-slides.md) | |
| Module 3.4       | [Modular architecture of Substrate FRAME system. Defining shared behaviour of traits](/syllabus/module/3.4-slides.md) | |
| Module 3.5       | [WebAssembly in Rust & WASM executor](/syllabus/module/3.5-slides.md) | 1 project-based assignment |
| Module 3.6 | [Advanced macros used in Substrate](/syllabus/module/3.6-slides.md) | |

--------------------------------------------------------
## Self-taught Resources
### General Resources
- [`Rust` | Rust Language Cheat Sheet](https://cheats.rs/)
- [`Rust` | A bunch of links to blog posts, articles, videos, etc for learning Rust](https://github.com/ctjhoa/rust-learning)
### Learn by Practice
- [`Exercise` | `Rust` | Polkadot Blockchain Academy - Qualification Exam](https://github.com/Polkadot-Blockchain-Academy/pba-qualifier-exam/): This exam is maintained by the Polkadot Blockchain Academy, for the benefit of the entire Rust community. The Academy accepts individuals modestly skilled in Rust, and maintains this exam to help everyone asses their proficiency being of a level we would consider for the program.
- [`Exercise` | `Rust` | Rust by Practice](https://practice.course.rs/why-exercise.html): Practice Rust with challenging examples, exercises and projects 
### Courses, Videos & Tutorials
- [`Couuse` | `Rust` | Design Patterns in Rust](https://rust-unofficial.github.io/patterns/): Learn common design patterns & anti-pattern in Rust
- [`Course` | `Rust` | Comprehensive Rust (by Google Android Team)](https://github.com/google/comprehensive-rust): This is a free Rust course developed by the Android team at Google. The course covers the full spectrum of Rust, from basic syntax to advanced topics like generics and error handling.
- [`Tutorial` | `WASM` | WebAssembly Fizzbuzz](https://github.com/diekmann/wasm-fizzbuzz): WebAssembly crash course
- [`Tutorial` | `WASM` | Port 1997 DOOM to Web Assembly](https://github.com/diekmann/wasm-fizzbuzz/tree/main/doom): This course is in a [WebAssembly Fizzbuzz course collection](https://github.com/diekmann/wasm-fizzbuzz/)
- [`Video` | What and How about Futures and async/await in Rust - Jon Gjengset](https://www.youtube.com/watch?v=9_3krAQtD2k)
### Programming Concepts
- [`Rust` | Advanced Concepts | Typelevel Recursion](https://beachape.com/blog/2017/03/12/gentle-intro-to-type-level-recursion-in-Rust-from-zero-to-frunk-hlist-sculpting/)
- [`Rust` | "Move, copies and clones in Rust" by HashRust](https://hashrust.com/blog/moves-copies-and-clones-in-rust/)
#### Asynchronous Programming
- [`Rust` | Advanced Concepts | Actor Model by Actix](https://actix.rs/docs/actix/actor/): Actor basically has their own execution context, communicates with each other through messaging channel
- [`Rust` | Rust Forum - Pin use in `Future::poll()`](https://users.rust-lang.org/t/pin-use-in-futures-poll/80264/7): Discussion thread about `Future::pollPint(<&mut self>, _)` on Rust Forum, the discussion explains the `Pin` trait in a very deep level of low-level knowledge.
- [`Rust` | "Pin, Unpin and why Rust needs them" by Cloudflare](https://blog.cloudflare.com/pin-and-unpin-in-rust/)
- [`Rust` | "Understanding pinning in Rust futures" on Hackernoon](https://hackernoon.com/pin-safety-understanding-pinning-in-rust-futures): This resource is very easy to understand, it gives a clear cut about `Future` and `Pinning`
#### Asynchronous Runtime - Scheduler
- [`Rust` | `std::pin::Pin`: Pin Projection](https://doc.rust-lang.org/std/pin/index.html#projections-and-structural-pinning): Learn more about [pin_project](https://docs.rs/pin-project/latest/pin_project/) crate for safe pin projection
- [`Rust` | "How Tokio schedule tasks?" on Rust Magazine](https://rustmagazine.org/issue-4/how-tokio-schedule-tasks/)
- [`Rust` | Advanced Concepts | Scheduling Internals](https://tontinton.com/posts/scheduling-internals/)
- [`Rust` | About Tokio scheduler internal](https://tokio.rs/blog/2019-10-scheduler): Understanding how Tokio scheduler works under the hood

