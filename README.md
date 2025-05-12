# Bac Bo Telegram Bot

Este é um bot de sinais para o jogo Bac Bo. Ele lê os resultados do [casinoscores.com](https://casinoscores.com/pt-br/bac-bo/) e envia sinais para o Telegram com base em padrões predefinidos.

## Padrões:

- **Padrão A**: 🔴🔴🔵🔵🔴🔴 = 🔵
- **Padrão B**: 🔵🔵🔴🔴🔵🔵 = 🔴
- **Padrão C**: 🔴🔵🔵🔴🔵🔵 = 🔴
- **Padrão D**: 🔵🔴🔴🔵🔴🔴 = 🔵

## Como usar:

1. Suba o código para o **Render** ou **Heroku**.
2. Adicione as variáveis de ambiente:
   - **TELEGRAM_TOKEN**: O token do seu bot do Telegram.
   - **TELEGRAM_CHAT_ID**: O ID do chat do Telegram onde o bot enviará os sinais.
3. O bot começará a rodar e enviar sinais para o seu Telegram!

## Licença

Este projeto é de código aberto e pode ser utilizado livremente.
