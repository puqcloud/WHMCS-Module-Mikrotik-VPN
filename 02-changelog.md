# Changelog

### Mikrotik VPN module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://panel.puqcloud.com/index.php?rp=/store/whmcs-module-mikrotik-vpn) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Mikrotik-VPN/) | [FAQ](https://faq.puqcloud.com/)

---

## v3.1 (20-04-2026)

- **Improved stability across the WHMCS admin area.** Rare page-loading errors that could appear on some admin screens (for example when opening a support ticket on installations with non-standard file layouts, symlinks or custom hosting paths) have been eliminated. The admin panel now loads smoothly in every environment.
- **Greater compatibility with complex hosting setups.** The module is now fully resilient to WHMCS installations using symlinked directories, multi-domain hosting and custom include paths.
- **Smoother day-to-day operation for administrators.** Fewer interruptions, no unexpected "Oops!" pages, and a more predictable experience when working with tickets, clients and services — so your team can focus on customers, not on troubleshooting.

---

## v3.0 (01-02-2026)

- Support for WHMCS 9+
- Redesigned product module settings
- Updated client area interface design
- Remote ability to have traffic-based packages has been removed; instead, a post-paid traffic billing model has been implemented using standard WHMCS metrics

> **Note:** Product reconfiguration is required after update.

---

## v2.2 (23-01-2025)

- The product configuration method has been redesigned
- Added a configuration option in the product settings to display custom HTML in the client panel based on the VPN protocol

> **Important:** After the update, all products using this module must be completely reconfigured.

---

## v2.0 (23-09-2024)

- Module coded with ionCube v13
- Supported PHP versions: 7.4, 8.1, 8.2
- Compatible with WHMCS 8.11.0+
- Client area more adapted for mobile
- Copy-to-clipboard buttons added for login and password

---

## v1.3.5 (11-10-2023)

- Support for WHMCS v8.8.0
- Translations added/updated: Arabic, Azerbaijani, Catalan, Chinese, Croatian, Czech, Danish, Dutch, English, Estonian, Farsi, French, German, Hebrew, Hungarian, Italian, Macedonian, Norwegian, Polish, Romanian, Russian, Spanish, Swedish, Turkish, Ukrainian

---

## v1.3 (04-02-2023)

- Redesigned client side with intuitive icons
- Improved PHP 8.1 compatibility
- Bug fix: "Attempt to assign property bytes_upload on string" in puqMikrotikVPN.php

---

## v1.2 (04-01-2023)

- Support for WHMCS v8.6
- Support for IonCube PHP Loader v12
- PHP 8.1 support
- Template improvements
- Added configurable frequency for traffic statistics collection (daily cron and per cron)
- Traffic counters on Mikrotik are reset to zero after each statistics collection
- Email template selection changed from text input to dropdown menu

---

## v1.1 (28-10-2022)

- Client area design improvements
- Ukrainian and Persian translations added
- PPP secret profile selection in product settings changed from text input to dropdown

---

## v1.0 (01-08-2022)

- First release
