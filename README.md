# OpenKore Configuration for rAthena Server

Private OpenKore configuration files for connecting to my personal rAthena server.

## Files

- `config.txt` - OpenKore bot configuration
  - Server: Localhost (128.168.135.92:6900)
  - Account: gmadmin
  - Character: Athena (slot 2)
  - Mode: Stationary bot (no auto-attack, no movement)

- `servers.txt` - Server connection settings
  - Packet version: kRO_RagexeRE_2020_04_01b
  - Character block size: 155
  - Custom table folders for packet parsing

## Usage

### On macOS/Linux:
```bash
cp config.txt /path/to/openkore/control/
cp servers.txt /path/to/openkore/tables/
```

### On Windows:
```
Copy config.txt to:   C:\OpenKore\control\config.txt
Copy servers.txt to:  C:\OpenKore\tables\servers.txt
```

## Server Details

- **IP**: 128.168.135.92
- **Port**: 6900 (Login), 6121 (Char), 5121 (Map)
- **Type**: rAthena Pre-Renewal
- **Packet Version**: 20200401

## Notes

- PIN Code: Configured in config.txt
- Bot is configured to remain stationary
- Compatible with OpenKore latest version
- Requires packet tables for kRO_RagexeRE_2020_04_01b

---
**Created**: November 7, 2025
**Platform**: Cross-platform (macOS/Windows/Linux)
