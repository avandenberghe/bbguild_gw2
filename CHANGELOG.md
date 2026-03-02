# Changelog

## 2.0.0-a1 02/03/2026
  - [NEW] Initial release as standalone phpBB extension
  - [NEW] Extracted from bbGuild core as part of the game plugin architecture
  - [NEW] Implements `game_provider_interface` — registers GW2 with bbGuild via tagged services
  - [NEW] `gw2_installer` extends `abstract_game_install` with clean array-based table names
  - [NEW] `gw2_provider` supplies game metadata (factions, regions)
  - [NEW] Custom Damage/Support/Control roles (overrides standard holy trinity)
  - [NEW] Game images served from plugin directory including GW2 API emblem assets
  - [CHG] Installer uses `$this->table()` helper instead of direct property access
