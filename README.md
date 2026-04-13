```
╔═══════════════════════════════════════════════════════════╗
║   node --experimental-vm-modules ./me.mjs                 ║
╚═══════════════════════════════════════════════════════════╝
```

[![wakatime](https://wakatime.com/badge/user/b1595087-a571-4f81-947d-01faae33c67b.svg)](https://wakatime.com/@b1595087-a571-4f81-947d-01faae33c67b)

---

## $ whoami

Full stack dev — je vis entre le **process principal** et le **renderer**, entre le DOM et le système de fichiers.  
Stack quotidienne : **Electron · Svelte · Node.js**. Quand quelque chose peut tourner en natif, il tourne en natif.

Pas de framework pour le plaisir. Pas de dépendance sans raison. Du code qui fait exactement ce qu'il dit faire.

---

## $ ls -la ./stack

| Couche | Outils |
|---|---|
| Desktop | Electron, contextBridge, IPC, auto-updater |
| UI | Svelte, SvelteKit, transitions natives |
| Back / scripts | Node.js, ESM, worker_threads, streams |
| Data | SQLite (better-sqlite3), JSON, fichiers plats |
| Tooling | Vite, esbuild, pnpm, GitHub Actions |
| Logger | ANSI custom · zéro dépendance · ES2020+ |

---

## $ cat ./approach.md

- L'architecture d'abord. Le code suit.  
- Un module fait une chose. Un fichier dit ce qu'il contient.  
- Les outils CLI, les loggers, les utilitaires — tout s'écrit à la main quand c'est plus propre.  
- Les dépendances se justifient. `node_modules` n'est pas un fourre-tout.

---

## $ git log --oneline ./interests

```
feat: desktop apps avec UX web, perf native
feat: IPC typé, stores Svelte réactifs bout en bout  
feat: tooling Node.js sans overhead inutile
feat: ES modules, import.meta, top-level await
feat: scripts CLI utilitaires avec zéro friction
```

---

## $ ping

> Toujours partant pour parler architecture Electron, patterns Svelte, ou outillage Node.  
> Les issues et discussions sont ouvertes.

---

*`process.exit(0)`*
