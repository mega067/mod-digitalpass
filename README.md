# 🎬 Módulo DigitalPass (Streaming, IA & Licencias) (mod-digitalpass)

<p align="center">
  <img src="https://megaunlockphone-panel.alwaysdata.net/digitalpass-logo.png" width="160" alt="DigitalPass Logo">
</p>

<p align="center">
  <strong>Portal y Catálogo Especializado para Comercialización de Cuentas Premium, Herramientas de IA y Software</strong>
</p>

<p align="center">
  <a href="https://github.com/mega067/MegaUnlockPhone"><img src="https://img.shields.io/github/stars/mega067/MegaUnlockPhone?style=for-the-badge&color=f59e0b&logo=github" alt="Stars"></a>
  <a href="https://github.com/mega067/MegaUnlockPhone/releases"><img src="https://img.shields.io/github/downloads/mega067/MegaUnlockPhone/total?style=for-the-badge&color=10b981&logo=github" alt="Downloads"></a>
  <a href="https://megaunlockphone-panel.alwaysdata.net/digital-pass"><img src="https://img.shields.io/badge/DigitalPass-Online-emerald?style=for-the-badge" alt="Status"></a>
  <img src="https://img.shields.io/badge/Module-Plug%26Play-purple?style=for-the-badge" alt="Module">
</p>

---

## 📌 1. ¿Qué es `mod-digitalpass`?

**`mod-digitalpass`** es el portal de productos digitales del ecosistema **[MegaUnlockPhone](https://github.com/mega067/MegaUnlockPhone)**. Permite a los clientes adquirir de forma instantánea:

- 📺 **Plataformas de Streaming:** Netflix, Max (HBO), Disney+, Prime Video, Spotify, YouTube Premium.
- 🤖 **Herramientas de Inteligencia Artificial:** Cuentas ChatGPT Plus, Claude Pro, Midjourney, Canva Pro.
- 💻 **Licencias & Software:** Windows 11 Pro, Office 365, Antivirus y créditos para activaciones de dongles/boxes GSM.

---

## 🏛️ Integración en el Ecosistema Modular

Este módulo es un componente desacoplado del proyecto principal **[MegaUnlockPhone](https://github.com/mega067/MegaUnlockPhone)**:

- **Frontend Dedicado:** Accesible en `/digital-pass`.
- **Conexión al Core:** Consume la billetera secundaria (`credits_3`) y el catálogo del Servidor 3 de [mup-core](file:///home/angel/Projects/REPOS/dhru-client-web/packages/mup-core/README.md).
- **Notificaciones:** Si el cliente adquiere una cuenta, [mod-whatsapp-bot](file:///home/angel/Projects/REPOS/dhru-client-web/packages/mod-whatsapp-bot/README.md) despacha las credenciales directamente a su WhatsApp.

---

## 🚀 Instalación y Uso

Dentro del entorno de MegaUnlockPhone:
```bash
# Se activa o desactiva con un simple interruptor desde el Panel de Administración
# O en modules.config.json:
{
  "modules": {
    "digitalPass": { "enabled": true, "route": "/digital-pass" }
  }
}
```

---

<p align="center">
  <sub>DigitalPass &copy; 2026. Módulo Oficial de MegaUnlockPhone.</sub>
</p>
