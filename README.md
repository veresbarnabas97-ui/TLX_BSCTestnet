# TLX_BSCTestnet
# 🌟 TetraLux (TLX) & Telegram Bot

A TetraLux egy innovatív blokklánc-alapú projekt, amely a BSC (Binance Smart Chain) hálózatán működik. Ez a repository tartalmazza a projekt DApp felületét és a tartalomvédett Telegram bot forráskódját.

## 🚀 Projekt Áttekintés

A projekt főbb elemei:
- **DApp:** Interaktív Web3 felület tárcacsatlakozással és Staking lehetőséggel.
- **Token Gating:** Automatizált Telegram bot, amely ellenőrzi a felhasználók egyenlegét a blokkláncon.

## 🤖 TetraLux Bot (Python)

A bot feladata a prémium tartalmak (PDF kiskönyvek, oktató anyagok) védelme. Csak azon felhasználók számára engedélyezi a letöltést, akik rendelkeznek a meghatározott mennyiségű TLX tokennel.

### Főbb funkciók:
- **Valós idejű egyenlegellenőrzés:** BSC Testnet hálózaton keresztül.
- **Tartalomfeloldás:** - `1,000 TLX` -> TetraLux Kiskönyv (PDF)
  - `10,000 TLX` -> TetraLux 7. Epizód (PPTX)
- **Biztonság:** A fájlok nem a GitHubon, hanem védett szerverkörnyezetben (PythonAnywhere) tárolódnak.

## 🛠 Technikai háttér

| Technológia | Használat |
| :--- | :--- |
| **Python 3.x** | Bot logika és backend |
| **Web3.py** | BSC Blokklánc kommunikáció |
| **Telegraf / python-telegram-bot** | Telegram API kezelés |
| **Ethers.js / HTML / CSS** | DApp (Frontend) fejlesztés |
| **BSC Testnet** | Hálózati infrastruktúra |
