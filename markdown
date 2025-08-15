# 🚀 Crypto Trading Bot - Web Interface

Un bot de trading automatisé avec interface moderne, connecté à *Binance (Testnet), utilisant **Streamlit*.

## 🔧 Fonctionnalités
- Analyse technique (SMA, RSI)
- Signaux d'achat/vente
- Interface web fluide
- Déploiement facile sur Railway ou Streamlit

## 🛠 Installation locale

```bash
git clone https://github.com/ton-pseudo/crypto-trading-bot-web.git
cd crypto-trading-bot-web

# Créer .env à partir de .env.example
cp .env.example .env
# ➕ Remplis tes clés Binance dans .env

# Installer
pip install -r requirements.txt

# Lancer
streamlit run main.py 
