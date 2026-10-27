# GOAT Árajánlat Készítő – kiadások

Ez a repó kizárólag az alkalmazás **telepítőit** és az automatikus frissítéshez szükséges
`latest.json` fájlt tartalmazza. A forráskód nem nyilvános.

## Letöltés

A legfrissebb verzió a [Releases](../../releases/latest) oldalon érhető el:

| Rendszer | Fájl |
| --- | --- |
| Windows | `GOAT-Setup-<verzió>-x64.exe` |
| macOS (Apple Silicon és Intel) | `GOAT-<verzió>-macos-universal.dmg` |
| Linux | `GOAT-<verzió>-linux-<arch>.deb` / `.rpm` / `.AppImage` |

A telepítés után az alkalmazás a háttérben automatikusan letölti az új verziókat, és a következő
újraindításkor telepíti őket. Frissítés után egy ablak mutatja meg, mi változott.

A telepítők nincsenek kódaláírással ellátva, ezért első indításkor a Windows SmartScreen, illetve
macOS-en a Gatekeeper figyelmeztethet („További információ → Futtatás mindenképp”, illetve macOS-en
jobb klikk → Megnyitás).
