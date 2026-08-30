# DeepSeek Harness

English | [中文](README.zh.md)

DeepSeek Harness (`dsh`) is an open-source agent harness developed by [DeepSeek AI](https://deepseek.com).

It uses an architecture where **everything is a plugin**, and is powered by [Cordis](https://github.com/cordiverse/cordis), whose design is described in [_A Programming Paradigm for Spatiotemporal Composability_](https://github.com/cordiverse/paper).

## Developer preview

DeepSeek Harness is currently in _developer preview_ and is iterating rapidly. **THERE WILL BE COMPATIBILITY-BREAKING CHANGES.**

## Run

### Run from `npm`

Install `Node.js`, then run:

```sh
npx @deepseek-ai/dsh web
```

The command starts the Web UI, served at `http://127.0.0.1:3080` by default. See [Web UI guide](docs/user/guide/index.md).

### Run from source

To run from a repository checkout:

```sh
git clone https://github.com/deepseek-ai/deepseek-harness.git
cd deepseek-harness
pnpm install
pnpm run build
pnpm dsh web
```

## Community and support

- Feel free to submit feedback or bug reports through [GitHub Discussions](https://github.com/deepseek-ai/deepseek-harness/discussions).
- Add the [`dsh-plugin`](https://github.com/topics/dsh-plugin) topic to your plugin repository for discoverability.
- Join <a href="https://discord.gg/Ycq5dCaS4">DeepSeek Harness Discord community</a>.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Development

Start with the [development guide](docs/development.md) and [architecture documentation](docs/architecture.md).

For agents, follow [AGENTS.md](AGENTS.md).

## License

[MIT](LICENSE)

Third-party dependencies and their licenses are disclosed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

---

## ⚠️ Scoras Digital DevOps Agent — Verificação

[![DevOps Score](https://img.shields.io/badge/DevOps%20Score-56%2F100%20(C)-yellow?style=for-the-badge&logo=github)](./andersonamaral2_deepseek-harness_2026-08-30.md)
[![Scoras DevOps Agent](https://img.shields.io/badge/Scoras_DevOps_Agent-Verificado-blue?style=for-the-badge&logo=githubactions)](https://github.com/andersonamaral2/deepseek-harness)

| Campo | Valor |
|-------|-------|
| 🤖 Avaliado por | Scoras Digital DevOps Agent |
| 📅 Data da Avaliação | `30/08/2026` |
| 📊 Score DevOps & Segurança | `56/100` |
| 🎯 Nota | C — Regular |
| 📄 Relatório Completo | [andersonamaral2_deepseek-harness_2026-08-30.md](./andersonamaral2_deepseek-harness_2026-08-30.md) |

> *Este repositório foi auditado automaticamente pelo **Scoras Digital DevOps Agent**,*  
> *verificando métricas DORA, CI/CD, segurança (CVEs, secrets, SAST) e boas práticas.*  
> *Última avaliação: **30/08/2026***

---

