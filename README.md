# 🚀 Bot de Trading Automatisé - Binance (avec Interface Web)

![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?style=for-the-badge&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![Binance](https://img.shields.io/badge/Binance-F0B90B?style=for-the-badge&logo=binance&logoColor=black)

Un *bot de trading algorithmique* moderne avec interface web, connecté à *l'API Binance*, capable d'analyser les graphiques, de détecter des signaux d'achat/vente (via SMA, RSI), et de fonctionner 24h/24 sur un serveur. Idéal pour les débutants comme les traders expérimentés.

> 🔐 Fonctionne par défaut sur *Binance Testnet* – aucun risque financier.

---

## 📋 Fonctionnalités

✅ Interface web moderne avec *Streamlit*  
✅ Analyse technique en temps réel (moyennes mobiles, RSI)  
✅ Détection automatique de signaux *ACHAT / VENTE*  
✅ Trading automatique ou manuel  
✅ Journal des actions en temps réel  
✅ Compatible *Binance Testnet & Mainnet*  
✅ Déploiement facile sur *Railway, **Streamlit*, ou VPS  
✅ Gestion sécurisée des clés API via .env  

---

## 🛠 Prérequis

- Compte Binance (ou [Binance Testnet](https://testnet.binance.vision))
- Clé API et Secret API
- Compte GitHub
- (Optionnel) Compte sur [Railway](https://railway.app) ou [Streamlit](https://streamlit.io)

---

## 🔐 Étape 1 : Configurer les clés API

1. Va sur [Binance Testnet](https://testnet.binance.vision) et connecte-toi (ou crée un compte)
2. Génère une *clé API* et un *secret* dans "API Management"
3. Crée un fichier .env à la racine du projet :

```env
API_KEY=tu_cle_api_ici
API_SECRET=ton_secret_api_ici
