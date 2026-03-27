# OpenClaw Telegram Assistant

Self-hosted AI personal assistant integrated with Telegram.

## Installation

```bash
chmod +x scripts/install.sh
./scripts/install.sh
openclaw config set channels.telegram.botToken "YOUR_TOKEN"
openclaw config set channels.telegram.dmPolicy "owner_only"
chmod +x scripts/start.sh
./scripts/start.sh
