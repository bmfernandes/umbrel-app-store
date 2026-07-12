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
  inference-broker OpenAI-compatible do homelab. Imagem publicada num **registry Docker privado
  rodando no próprio Beelink** (não mais GHCR — TASK_V26), referenciada por `127.0.0.1` (loopback,
  já que o pull acontece no mesmo host que roda o registry) — sem autenticação necessária para
  instalar/atualizar.
