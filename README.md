# Nikonov Maxim

**Compiler Engineer | Systems Architect | Research Engineer**

Creator of programming languages, runtimes, and production frameworks. Specializing in compiler design, systems programming, and cross-platform architecture.

## 🔧 Flagship Projects

### [TSClang](https://github.com/tsclang/tsclang) — TypeScript to C Compiler
TypeScript-like language with Rust-inspired ownership semantics compiling to clean C.

**Key features:**
- **Borrow checker**: `Ref<T>`, `Mut<T>`, `Arc<T>` for memory safety
- **Async/await → C state machine** (no runtime, no heap for embedded)
- **10+ target platforms**: desktop, AVR, ARM, NES, PS1, PS2, DOS, ZX Spectrum, WASM
- **1764+ tests**, pnpm monorepo, custom package manager, LSP support
- **Embedded optimizations**: cooperative scheduler, `Volatile<T>`, `@embedded.pool`

### [mclang](https://github.com/tsclang/mclang) — Mathematical Formula Compiler
Domain-specific language for mathematical formulas compiling to pure C with zero runtime.

**Key features:**
- **LaTeX-like syntax**: `\arcsin`, `\frac`, implicit multiplication (`2πr`)
- **`where` blocks** for intermediate calculations
- **5 compilation targets**: C, shared library, WASM, Node.js addon, Rust FFI
- **Zero dependencies** — pure C output, works on Arduino, STM32, WASM, browsers
- **Real-world examples**: orbital mechanics, Kalman filters, DSP, geodesy, Black-Scholes

### [workspace](https://github.com/fwmakc/workspace) — Cross-Platform Overlay Runtime
Host-agnostic runtime providing unified workspace across Windows, macOS, Linux, Android, iOS.

**Architecture:**
- **Rust system layer**: wgpu (WebGPU), winit (windowing), CPAL (audio), storage with BLAKE3
- **Bun/TypeScript micro-kernel**: IPC, SQLite, CRDT sync, capability security
- **V8 Isolates**: sandboxed apps with `@workspace/*` API
- **Local AI**: ONNX/Ollama for intent-based UI, voice control, scheduling
- **P2P mesh**: offline-first sync without central cloud
- **37 implementation phases**, Phase 0 (playable demo) complete

### [api-server-toolkit](https://github.com/fwmakc/api-server-toolkit) — NestJS Microservices Framework
Production-ready framework for REST APIs with comprehensive access control.

**Key features:**
- **6-level access control**: public/account/tenant/owner/superuser/closed
- **Deny-by-default security**: 4 layers (operations, relations, nested filtering, fields)
- **Multi-tenancy** with flexible tenant scoping
- **125+ unit tests**, TypeORM optimizations (N+1 → 2 queries)
- Used in production microservices architecture (7+ services)

## 🎯 Expertise

**Compiler Engineering:**
- Language design (type systems, ownership semantics, DSLs)
- Code generation (C, Assembly for multiple architectures)
- Lexer/parser implementation
- Async/await → state machine compilation
- Cross-compilation toolchains (AVR, ARM, MIPS, Z80, x86)
- Mathematical formula compilation (LaTeX → C)

**Systems Programming:**
- Embedded development (AVR, ARM, ESP32, retro consoles)
- Memory management (borrow checking, no-heap environments)
- Runtime architecture (micro-kernels, isolates, capability security)
- Graphics programming (WebGPU, wgpu, WGSL shaders)
- Audio subsystems (CPAL, ring buffers, lock-free SPSC queues)
- Storage with atomic writes and BLAKE3 hashing
- P2P networking with CRDTs

**Backend Architecture:**
- Microservices design patterns
- REST API design with security best practices
- Multi-tenancy implementations
- Row-level security, RBAC
- Database optimization (PostgreSQL, TypeORM)

## 📊 Tech Stack

**Languages:** TypeScript (expert), Rust (advanced), C (advanced), Python (advanced)

**Compilers:** GCC, Clang, avr-gcc, arm-none-eabi-gcc, cc65, m68k-elf-gcc, mipsel-elf-gcc, emscripten

**Embedded:** AVR (ATmega), ARM Cortex-M, ESP32, NES (6502), ZX Spectrum (Z80), PS1/PS2 (MIPS)

**Graphics:** WebGPU, wgpu, WGSL, Vulkan, Metal

**Backend:** NestJS, Node.js, Bun, PostgreSQL, TypeORM, Docker, PM2, Nginx

**Systems:** Rust (winit, wgpu, CPAL, notify, zeroize), SQLite, CRDTs, ONNX, Ollama

**Tools:** Git, pnpm, Jest, Vitest, LSP, CMake

## 📚 Project Philosophy

I build tools that transform high-level abstractions into efficient, safe low-level code:

- **TSClang**: TypeScript ergonomics → C performance with memory safety
- **mclang**: Mathematical notationation → optimized C functions
- **workspace**: Unified experience → platform-specific optimizations
- **api-server-toolkit**: Declarative access control → secure REST APIs

Each project follows the same principles:
- Zero or minimal runtime overhead
- Strong safety guarantees (borrow checking, capability security)
- Cross-platform portability
- Production-ready quality (comprehensive tests, documentation)

## 💼 Open to Work

Seeking **Compiler Engineer**, **Systems Architect**, or **Research Engineer** roles:
- Compiler/language development (language design, code generation, DSLs)
- Systems programming (embedded, runtime, toolchains, graphics)
- Runtime architecture (micro-kernels, isolates, cross-platform)
- Backend architecture (microservices, security, multi-tenancy)

**Remote-first** | Available for international opportunities

## 📫 Contact

- **Email:** fwmakc@google.com, fwmakc@mail.ru
- **Telegram:** [@fwmakc](https://t.me/fwmakc)

---

*"I build compilers and runtimes that turn high-level abstractions into efficient, safe low-level code."*
