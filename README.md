### Joaquín Escrivá de Romaní

Computer Science & Engineering student at **Universidad Carlos III de Madrid**, and former
**Cybersecurity R&D intern at cyan Digital Security** (Vienna, 2026).

I build complete software by directing AI coding agents (Claude Code, Codex, Kimi CLI, Cursor).
I write the spec, split the work into phases, review the code, and demand tests that prove it
works. AI co-authorship is recorded in the commits.

[LinkedIn](https://linkedin.com/in/joaquin-escriva) · Madrid, Spain · Spanish (native), English (C1 Advanced)

---

#### Selected projects

| Project | What it is | Evidence |
|---|---|---|
| [**AISight**](https://github.com/VortexJer/AISight) | Five CLIs that let an AI agent *measure* what a human would *look at*: 3D CAD, PCB layouts, animation, UVs/textures and materials. Deterministic reports with a location and a fix for every finding. | 6 packages on PyPI, published via OIDC (no stored tokens) · CI matrix Ubuntu/Windows/macOS · 272 tests |
| [**NovaChat**](https://github.com/VortexJer/NovaChat-AI) | Self-built AI chat client with no agent framework: own streaming tool loop, hand-written MCP client, `.docx`/`.pptx`/`.xlsx` generation. | Found and fixed an SSRF (IP validated before the request *and* at the socket, closing DNS rebinding) · scrypt + AES-256-GCM · Docker → GHCR → Render |
| [**Orquestador**](https://github.com/VortexJer/orquestador) | CLI version of NovaChat: FastAPI gateway that routes each task to one of 21 domains and fails over across 23 LLM providers. | 1,097 tests · router accuracy measured on an eval set and enforced as a CI gate |
| [**MotorForge**](https://github.com/VortexJer/MotorForge) | Desktop app that simulates internal-combustion engines and explains each failure with its causal chain. 0D Otto cycle, voxel FEA, hardware-in-the-loop digital twin. *(in development)* | 178 Vitest tests · Windows NSIS installer |
| [**goldentokens**](https://github.com/VortexJer/Goldentoken) | Token-saving CLIs and Claude Code hooks, based on an audit of real agent sessions (~88 % of tokens went to reading images). | Risk-tiered installer |
| [**ShieldX**](https://github.com/VortexJer/ShieldX) | Manifest V3 ad, tracker and cookie-banner blocker for Chrome. | 360+ `declarativeNetRequest` rules |

#### Toolbox

**Security:** VirusTotal, urlscan.io, OSINT, code review, input validation<br>
**Languages:** Python, SQL, C, R, assembly · TypeScript (reading)<br>
**Stack:** FastAPI, Next.js, React, Electron, PostgreSQL, Qdrant, Docker, GitHub Actions, pytest, Vitest<br>
**Systems:** Linux, macOS, Windows, Cisco networking

#### Certifications

Cambridge C1 Advanced · Cisco Networking Basics · Cisco Linux Unhatched · Google Technical Support Fundamentals · C Programming (Alison)
