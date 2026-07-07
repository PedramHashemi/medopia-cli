# meditopia-cli

Official CLI for [MedOpia](https://meditopia.io) — upload and manage clinical AI models and datasets from your terminal.

## Installation

```bash
pip install meditopia-cli
```

## Quick start

```bash
medi login --token <your-api-token>
medi upload model ./my-model --name "chest-xray-classifier"
medi upload dataset ./my-dataset --name "mimic-cxr-subset"
```

## Commands

```
medi --help
```

## Getting an API token

1. Log in to [meditopia.io](https://meditopia.io)
2. Go to **Settings → API Tokens**
3. Create a new token and copy it
4. Run `medi login --token <token>`
