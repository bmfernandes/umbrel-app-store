# BMFERNANDES — Umbrel Community App Store

Repositório de **metadados** (manifesto + docker-compose) para instalar apps pessoais no umbrelOS
via *Community App Store*. Não hospeda código-fonte nem imagens — código e imagens permanecem
privados nos seus respectivos repositórios/registries.

## Adicionar esta store no seu Umbrel

Settings → Community App Stores → colar:

```
https://github.com/bmfernandes/umbrel-app-store
```

## Apps

- **`bmfernandes-llm-gateway`** — [LLM Gateway](https://github.com/bmfernandes/llm-gateway):
  inference-broker OpenAI-compatible do homelab. Imagem **privada** (GHCR) — o Umbrel precisa
  estar autenticado no registry para instalar/atualizar (`docker login ghcr.io`, token
  `read:packages`).
