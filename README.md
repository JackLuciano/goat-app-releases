# GOAT Árajánlat Készítő – kiadások

Ez a repó kizárólag az alkalmazás **telepítőit** és az automatikus frissítéshez szükséges
`latest.json` fájlt tartalmazza. A forráskód nem nyilvános.

## Letöltés

A legfrissebb verzió a [Releases](../../releases/latest) oldalon érhető el:

| Rendszer | Fájl |
| --- | --- |
| Windows | `GOAT_<verzió>_x64-setup.exe` |
| macOS (Apple Silicon és Intel) | `GOAT_<verzió>_universal.dmg` |
| Linux | `GOAT_<verzió>_amd64.deb` / `.AppImage`, `GOAT-<verzió>-1.x86_64.rpm` |

Csak az első telepítéshez kell letölteni. A `.sig`, `.app.tar.gz` és `latest.json` fájlokat az
alkalmazás beépített frissítője használja.

A telepítés után az alkalmazás a háttérben automatikusan letölti az új verziókat, és a következő
újraindításkor telepíti őket. Frissítés után egy ablak mutatja meg, mi változott.

A telepítők nincsenek kódaláírással ellátva, ezért első indításkor a Windows SmartScreen, illetve
macOS-en a Gatekeeper figyelmeztethet („További információ → Futtatás mindenképp”, illetve macOS-en
jobb klikk → Megnyitás).
