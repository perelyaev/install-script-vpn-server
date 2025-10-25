# Устанавливаем 3x-ui панель для VLESS и сертификаты на 10 лет

## 📚 Описание

Этот скрипт автоматически устанавливает:
1. Панель **3X-UI** для управления VPN-протоколами.
2. Самоподписной **SSL-сертификат** сроком на **10 лет**.

## 🛠️ Что будет установлено?
- **OpenSSL**
- **3X-UI**

## 🚀 Как использовать?

### 1. Клонирование репозитория
```bash
sudo apt update && sudo apt install -y git curl openssl systemd && rm -rf ~/install-script-vpn-server && git clone https://github.com/perelyaev/install-script-vpn-server.git && cd install-script-vpn-server && chmod +x install-script-vpn-server.sh && sudo ./install-script-vpn-server.sh
