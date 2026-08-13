# is-test-repo-changelog-v5

## Descripcion y proposito

Repositorio de prueba funcional con **80 archivos** (subset de mf-apex) para validar changelog multi-archivo, dedup de sync, fallback 406 y olas LLM en Confluence DEMO.

Apunta a la pagina Confluence **Documentacion de Sistemas DEMO** (ID `732659714`).

## Repositorio

https://github.com/IOscco/is-test-repo-changelog-v5

## Estructura

```
is-test-repo-changelog-v5/
├── README.md
├── docs/                 # Sync a Confluence
├── src/                  # Codigo representativo (sin data/_raw ni poc JSON masivos)
├── .github/workflows/
└── vite.config.ts
```

## Jira

Prueba funcional: **JIRA-AI-1009**.

- **PR #1:** carga inicial 80 archivos (validacion multi-archivo).
- **PR #2:** cambio minimo para validar dedup QueryRunner + resumen LLM post-fix AI-970.
