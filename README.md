# webware-models-lynx-ag2

Pacote completo LynX's Custom Models (AG2) para o changer do WebWare.

## O que tem no pacote

Total: **67.556 arquivos, 16,4 GB**.

| Pasta | Conteúdo | Tamanho |
|---|---|---:|
| `agents/` | `hmn_ag2`, `oylsister`, `s2ze` | 1,4 GB |
| `characters/` | `93x`, `b_cansin`, `exg`, `flux`, `kianya`, `kuristaja`, `maoling`, `materials`, `models`, `security`, `tongyong` | 11,4 GB |
| `materials/` | | 3,2 GB |
| `models/` | | 218 MB |
| `particles/` | | 152 MB |
| `phase2/` | | 98 MB |

## Onde ficam os arquivos

Os modelos **não ficam no git**. Eles são publicados como arquivos `.zip` na página de [Releases](../../releases) deste repositório.
O `.gitignore` bloqueia arquivos compilados do Source 2 (`*.vmdl_c`, `*.vmat_c`, `*.vtex_c`, `*.vanim_c`, `*.vmesh_c`, `*.vpcf_c`, `*.vsnd_c`), além de `*.zip` e `*.vpk`, para evitar commits de modelo por engano.

O git guarda apenas:

- `README.md` — este arquivo
- `.gitignore`
- `manifest.json` — lista dos modelos do pacote (id, nome, tipo, caminho do `.vmdl`, nome do zip, tamanho e SHA-256)

## Estrutura dentro de cada zip

A estrutura de pastas dentro de cada `.zip` espelha `game/csgo/` do CS2:

```
game/csgo/
├── agents/
├── characters/
├── materials/
├── models/
├── particles/
├── phase2/
└── weapons/
```

Para instalar, extraia o zip diretamente em `game/csgo/` (ou na pasta que o changer do WebWare usar como raiz).
