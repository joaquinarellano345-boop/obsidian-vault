# 🧠 Cerebro Autónomo HJAZZI

> Knowledge graph + Obsidian vault + Git sync = cerebro vivo del ecosistema

## Arquitectura

```
┌──────────────────────────────────────────────────────┐
│                   GRAPHIFY ENGINE                      │
│  Tree-sitter AST → Knowledge Graph → Obsidian Export  │
└──────────┬──────────────────────────┬────────────────┘
           │                          │
           ▼                          ▼
   ┌──────────────┐         ┌──────────────────┐
   │ graphify-out │         │  Obsidian Vault  │
   │  graph.json  │ ──────▶ │  📝 notas .md    │
   │  report.md   │         │  🔗 wikilinks    │
   └──────────────┘         │  🗺️ graph.canvas │
                            └────────┬─────────┘
                                     │
                                     ▼
                            ┌──────────────────┐
                            │   GitHub Sync    │
                            │  auto commit +   │
                            │  auto push       │
                            └──────────────────┘
```

## Subgrafos activos

| Proyecto | Nodos | Aristas | Comunidades | Vault |
|----------|-------|---------|-------------|-------|
| graphify | 9,395 | 19,324 | 567 | `graphify-brain/` |
| Documentos | 338 | 538 | 29 | `documentos-brain/` |

## Comandos manuales

```bash
# Rebuild + export todo
cd /root/repos/graphify && graphify extract . --code-only && graphify export obsidian && cp -r graphify-out/obsidian/* ~/obsidian-vault/graphify-brain/

# Push a GitHub
cd ~/obsidian-vault && git add -A && git commit -m "🧠 cerebro: update $(date +%Y-%m-%d)" && git push
```

## Automatización

- **Git hooks**: `graphify hook install` → auto-rebuild en cada commit del repo graphify
- **Cron job**: rebuild semanal + export Obsidian + git push (ver `cerebro-autonomo` skill)
- **Graphify Hermes skill**: `/graphify` disponible en Hermes Agent
