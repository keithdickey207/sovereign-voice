# Sovereign Voice

Local voice / Mycroft-style assistant runtime for the Sovereign stack.

| | |
|---|---|
| **Status** | SUPPORT |
| **License** | [MIT](LICENSE) |
| **Operator** | Keith Alan Dickey — WSDS / 04901 Studio |

## Layout

```
sovereign_voice/
  config/mycroft.conf     # Mycroft config
  docker-compose.yml      # Containerized voice stack
  *.log                   # Runtime logs (gitignored)
```

## Quick start

```bash
cd ~/sovereign_voice
docker compose up -d
# Command Hub: http://localhost:5090
```

## License

MIT — Copyright (c) 2026 Keith Alan Dickey, Waterville Software Development Services.
