# DB Zugbausatz — Create 1.20.1

Original-3D-Modelle, in 1 m³-Blöcke geschnitten (KubeJS + Create, Forge 1.20.1).

Grok kann in der Vorschau **keine Dateien auf den PC speichern**. Links in einem normalen Tab öffnen.

## Fertige Züge (nicht Block für Block)

**[litter.catbox.moe/k3re1m.zip](https://litter.catbox.moe/k3re1m.zip)** · 295 KB · 72 Stunden  
Kopie: **[gofile.io/d/Rn7VmsQf](https://gofile.io/d/Rn7VmsQf)**  
Umbenennen zu `db-zug-schematics.zip`.

Block-Pack muss schon installiert sein. ZIP in den Instanzordner mergen (`kubejs/` neben `mods/`). Spiel neu starten. An die Stelle der Nase stellen, nach Norden schauen:

```
/zug ice3
/zug ice1
/zug flirt
/zug kiss
/zug dosto
/zug ic
/zug br101
/zug br146
```

| Befehl | Zug | Blöcke | Raster |
| --- | --- | --- | --- |
| `/zug ice3` | ICE 3 (5 Wagen) | 1453 | 3×6×134 |
| `/zug ice1` | ICE 1 (5 Wagen) | 1335 | 4×6×127 |
| `/zug flirt` | FLIRT 3 | 692 | 4×5×69 |
| `/zug kiss` | KISS | 1097 | 4×6×80 |
| `/zug dosto` | Dosto Steuerwagen+Wagen | 780 | 4×5×59 |
| `/zug ic` | IC Steuerwagen+Wagen | 502 | 4×4×49 |
| `/zug br101` | BR 101 + IC + Steuerwagen | 957 | 4×6×94 |
| `/zug br146` | BR 146 + Dosto + Steuerwagen | 982 | 4×6×79 |

Cheats/OP nötig. Heck-Köpfe sind schon um 180° gedreht. 1 Block Kupplungsabstand.

Alternativen in derselben ZIP:

- Vanilla: `/place template kubejs:ice3_zug ~ ~ ~` oder `/function kubejs:ice3_zug`
- Create: Ordner `schematics/` in den Instanz-Ordner `schematics/` (Schematic Table)
- WorldEdit: `worldedit/` nach `config/worldedit/schematics/`, dann `//schem load ice3_zug` und `//paste -a`

## Block-Packs

**[gofile.io/d/IoinsdvF](https://gofile.io/d/IoinsdvF)** — dort die ZIP anklicken (`db-ice3.zip` usw.).

| Pack | Größe | Direkt | Umbenennen zu |
| --- | --- | --- | --- |
| ICE 3 | 4,2 MB | https://litter.catbox.moe/siddmu.zip | `db-ice3.zip` |
| BR 101 | 6,7 MB | https://litter.catbox.moe/rx8we9.zip | `db-br101.zip` |
| BR 146 | 7,2 MB | https://litter.catbox.moe/pef6m8.zip | `db-br146.zip` |
| ICE 1 | 12,5 MB | https://litter.catbox.moe/93nn9i.zip | `db-ice1.zip` |
| FLIRT 3 | 13,8 MB | https://litter.catbox.moe/eqlbhy.zip | `db-flirt.zip` |
| KISS | 18,2 MB | https://litter.catbox.moe/xloth0.zip | `db-kiss.zip` |
| IC Steuerwagen | 20,6 MB | https://litter.catbox.moe/tc0ke5.zip | `db-ic.zip` |
| Dosto / DABpzfa | 25,8 MB | https://litter.catbox.moe/ywfgr7.zip | `db-dosto.zip` |
| Komplett-Pack | 109 MB | https://litter.catbox.moe/6lsmci.zip | `db-zugbausatz-create-1.20.1.zip` |

## Installation Blöcke

1. Forge 1.20.1 + Create 0.5.1 + KubeJS 2001.6
2. ZIP **in den Instanzordner** entpacken (neben `mods/`) — Ordner `kubejs/` muss dort landen
3. Spiel komplett neu starten
4. Kreativ-Tabs: DB ICE 3, DB BR 101, DB FLIRT 3, …

Einzel-ZIPs in denselben Ordner entpacken. **Nicht** Einzelpacks und Komplett-Pack gleichzeitig.

Falls `kubejs.log` `Cannot find function flat` zeigt: Datei `kubejs/startup_scripts/zug_blocks.js` löschen (die `zug_blocks_ice3.js` usw. behalten), Spiel neu starten.
