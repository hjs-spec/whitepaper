# AI Judgment Layer Standard

<p align="center">
    <a href="https://github.com/hjs-spec/whitepaper">
        <img src="https://img.shields.io/badge/Status-White%20Paper%20%7C%20v1.0-blue" alt="Status">
    </a>
    <a href="https://creativecommons.org/publicdomain/zero/1.0/">
        <img src="https://img.shields.io/badge/License-CC0_1.0-lightgrey" alt="License">
    </a>
    <a href="https://github.com/hjs-spec/whitepaper/issues">
        <img src="https://img.shields.io/badge/Issues-Welcome-brightgreen" alt="Issues">
    </a>
</p>

---

# AI Judgment Layer Standard (2026)

This repository contains the official white paper for the **AI Judgment Layer**, a foundational infrastructure layer independent of model layer, system layer, and application layer in AI systems.

## Document

| File | Description |
|------|-------------|
| [`AI Judgment Layer.md`](https://github.com/hjs-spec/whitepaper/blob/main/AI%20Judgment%20Layer.md) | Full white paper (English) |

## Current implementation entry points

The white paper is the original architectural document; its body is preserved
as published. For the current wire format, validation scopes and runnable code,
use [JEP-Core-0.6](https://github.com/hjs-spec/jep-v06), the
[reference validator](https://github.com/hjs-spec/jep-v06/tree/main/reference-validator)
and the [API implementation](https://github.com/hjs-spec/jep-api).
Repository code availability does not imply a live deployment.

## Relationship to JEP Protocol

The AI Judgment Layer Standard describes the **conceptual architecture** and **motivation** for a dedicated judgment layer in AI systems. The [JEP Protocol](https://github.com/hjs-spec/jep-v06) is a concrete implementation of this layer, providing the core primitives defined in this white paper.

| Concept | Implementation |
|---------|----------------|
| Judgment Layer Architecture | [JEP Protocol Specification](https://github.com/hjs-spec/jep-v06) |
| Core Primitives | [JEP Core reference validator (Python)](https://github.com/hjs-spec/jep-v06/tree/main/reference-validator) |
| API Service | [JEP API](https://github.com/hjs-spec/jep-api) |

## License

This white paper is released into the **public domain** under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.

## Related Repositories

- [JEP Protocol Specification](https://github.com/hjs-spec/jep-v06)
- [JEP Core Implementation](https://github.com/hjs-spec/jep-v06/tree/main/reference-validator)
- [JEP API Service](https://github.com/hjs-spec/jep-api)

## Contact

- **Email**: [signal@humanjudgment.org](mailto:signal@humanjudgment.org)

---

**© 2026 HJS Foundation Ltd.**  
This document is dedicated under [CC0 1.0 Universal](LICENSE).
