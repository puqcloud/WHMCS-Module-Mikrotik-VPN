# Email Template (puqMikrotikVPN Suspension Notification traffic limit)

### Mikrotik VPN module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://panel.puqcloud.com/index.php?rp=/store/whmcs-module-mikrotik-vpn) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Mikrotik-VPN/) | [FAQ](https://faq.puqcloud.com/)

## Creating the email template

Navigate to **System Settings** → **Email Templates** → **Create New Email Template**

This template is used to notify the customer that the VPN account has been **suspended on the Mikrotik router** because the traffic balance reached zero or below. The traffic limit will be restored on the next billing cycle.

---

## Template configuration

| Parameter | Value |
|-----------|-------|
| **Email Type** | Product/service |
| **Unique Name** | puqMikrotikVPN Suspension Notification traffic limit |

---

## Email subject

```
Suspension Information - {$username}
```

---

## Email body

```
Dear {$client_name},

This letter informs you that the VPN account has been suspended due to traffic exhaustion.
The traffic limit will be restored from the next service cycle.
It is also possible to switch to a package with a large amount of traffic.

Product/Service: {$service_product_name}
Due Date: {$service_next_due_date}


Username: {$username}
Left traffic: {$traffic_balance_gb} GB
After renewing the service, {$traffic_billingcycle_gb} GB will be automatically added.


{$signature}
```

---

## Available template variables

The same custom variables as in the traffic-limit notification template are available:

| Variable | Description |
|----------|-------------|
| `{$username}` | VPN account username |
| `{$traffic_balance_gb}` | Remaining traffic balance (GB) — normally zero or below when this template is sent |
| `{$traffic_billingcycle_gb}` | Traffic that will be added on the next billing cycle (GB) |

Plus all standard WHMCS product/service merge fields (`{$client_name}`, `{$service_product_name}`, `{$service_next_due_date}`, `{$signature}`).

> **Note:** This email is sent automatically by the module when the VPN account is auto-suspended on the Mikrotik router because the customer's traffic balance has been exhausted.
