# Product Information

### Mikrotik VPN module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://panel.puqcloud.com/index.php?rp=/store/whmcs-module-mikrotik-vpn) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Mikrotik-VPN/) | [FAQ](https://faq.puqcloud.com/)

## Admin area product information

The administrator can view detailed service information in the WHMCS admin panel on the product/service page. The module adds a custom panel in the **Module Data** section with the following information:

### License verification status

Displays the current license status with a colored indicator:
- **Green** — license is valid and active
- **Red** — license is invalid, expired, or missing

### API connection status

Shows the result of a real-time connection test to the Mikrotik router API-SSL, confirming that the credentials entered for the server are working correctly.

### VPN account information

| Field | Description |
|-------|-------------|
| **Username** | The VPN account username (PPP secret name) on the Mikrotik router |
| **Enabled** | Whether the VPN account is currently enabled or disabled on the router |
| **Profile** | The PPP profile assigned to the account |
| **Service** | The VPN service / protocol (e.g. `any`, `pptp`, `l2tp`, `pppoe`) |
| **IP address** | The IP address assigned to the account from the server's IP pool |
| **Comment** | Includes the configured Comment PREFIX and WHMCS service identifier |

### Traffic information

- **Bandwidth limits** — configured download / upload speed limits
- **Traffic balance** — current remaining traffic balance for the customer
- **Traffic that will be added** on the next billing cycle
- **Connection status** — shows whether the client is currently online

### Available management actions

The standard WHMCS module command buttons are available:
- **Create** — provision a new VPN account on the Mikrotik router
- **Suspend** — disable the VPN account
- **Unsuspend** — re-enable the VPN account
- **Terminate** — permanently delete the VPN account from the router
- **Change Password** — reset the account's password
- **Change Package** — update profile, service, bandwidth limits and traffic configuration (used during upgrades/downgrades)
- **Reset Connection** — force-disconnect the current VPN session (useful when the customer needs to re-establish the tunnel)

---

## Screenshot

![Admin area product information](../img/15-product-information.png)
*15-product-information.png*
