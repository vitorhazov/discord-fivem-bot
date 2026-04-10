# Discord FiveM Bot

Bot avançado para Discord com integração completa com servidor FiveM.

### ⚡ Funcionalidades principais
- `!playerinfo <id>` — Mostra informações detalhadas do jogador
- `!staffonline` — Lista todos os staffs online no servidor
- `!whitelist <discord>` — Gerenciamento de whitelist
- Sistema de tickets para suporte
- Logs automáticos de banimentos, kicks e warns
- Status do servidor em tempo real
- Comando de anunciar (announce)

### 🛠️ Tecnologias utilizadas
- **Python** (discord.py 2.0)
- **Lua** (lado do servidor FiveM)
- **SQLite / MySQL**
- Integração via HTTP (FiveM → Discord)

### Como instalar

**Bot (Python):**
```bash
git clone https://github.com/vitorhazov/discord-fivem-bot.git
cd discord-fivem-bot
pip install -r requirements.txt
