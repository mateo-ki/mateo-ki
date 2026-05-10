# Hi there, I'm Mateo-ki 👋

### 💻 Systems Programmer | Compiler & Database Kernel Enthusiast

我是一名专注于底层架构的软件开发者，热衷于拆解计算机世界的“黑盒”。我深信 **"Understand the machine to command the machine"**，并致力于通过从零构建核心组件（编译器、数据库、内核）来掌握计算的本质。

---

## 🛠 技术栈 (Tech Stack)

| 类别 | 工具与语言 |
| :--- | :--- |
| **编程语言** | `C` / `C++` (Expert), `Rust`, `Java`, `Assembly (x86/x64)` |
| **核心领域** | 编译器架构 (Compiler Construction), 数据库内核, 逆向工程 |
| **二进制处理** | COFF/ELF 格式, 链接器机制, 内存管理 (Memory Management) |
| **开发工具** | WinDbg, GDB, IDA Pro, CMake, LLVM/Clang, Claude Code |

---

## 🚀 核心项目 (Key Projects)

### 🏗️ [minic](https://github.com/mateo-ki/minic) — *Self-hosted C Compiler*
一个从零构建的 C 语言编译器，旨在打通从源代码到多平台可执行二进制文件的全链路。
* **前端:** 独立实现词法/语法/语义分析及自研 IR 中间表示。
* **优化:** 包含常量折叠、死代码消除等基础优化器模块。
* **后端:** 深度定制的 **COFF/ELF 链接器**，手动处理 `REL32`、`ADDR64` 等底层重定位逻辑。
* **跨平台:** 支持 Windows PE 与 Linux ELF 格式，实现多环境兼容。

### 🗄️ [minipg](https://github.com/mateo-ki/minipg) — *High-Performance Storage Engine*
受 PostgreSQL 启发的高性能数据库原型，专注于事务可靠性与查询效率。
* **核心机制:** 实现了 `VACUUM` 垃圾回收机制与多级索引系统。
* **SQL 解析:** 支持 `NATURAL JOIN`、`USING` 等标准 SQL 语法。
* **并发控制:** 深入解决多线程环境下的**死锁预防**与**事务隔离**问题。

---

## 📚 工程路线图 (Engineering Roadmap)

* **当前重心:** 深度探索**逆向工程** (Reverse Engineering) 与系统漏洞分析。
* **AI + 编程:** 探索 LLM 在复杂系统代码生成与静态分析中的边界。
* **未来愿景:**
    * [ ] 构建一个高性能的**自定义解释器**。
    * [ ] 开发一个基于底层硬解码的**视频播放器**。

---

## 📬 联系我 (Contact Me)

* **GitHub:** [@mateo-ki](https://github.com/mateo-ki)
* **兴趣领域:** 底层技术、二进制协议、高性能计算、AI 辅助编程。

---

> "Understand the machine to command the machine."
