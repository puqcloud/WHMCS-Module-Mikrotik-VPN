# WHMCS Installation and Update

### Mikrotik VPN module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-mikrotik-vpn.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Mikrotik-VPN/) | [Community](https://community.puqcloud.com/)

## System requirements

| Requirement | Minimum |
|-------------|---------|
| **WHMCS** | 8.x+, 9.x+ |
| **PHP** | 7.4, 8.1, 8.2, 8.3, 8.4 |
| **Mikrotik RouterOS** | 7.x or higher |
| **ionCube Loader** | v15+ |

> **Note:** The module uses ionCube encoding. Make sure ionCube Loader is installed and active on your server.

## Installation

> **Note:** The module now uses **ionCube 15**, which provides universal out-of-the-box support for all encodings.
>
> All versions can be found at this link:
> `https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Mikrotik-VPN/`
>
> Older module versions for WHMCS 8 are available in the archive directory:
> `https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Mikrotik-VPN/archive/`

1. Download the latest version from the PUQ download page:
   ```bash
   wget https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Mikrotik-VPN/PUQ_WHMCS-Mikrotik-VPN-latest.zip
   ```

2. Unzip the archive:
   ```bash
   unzip PUQ_WHMCS-Mikrotik-VPN-latest.zip -d PUQ_WHMCS-Mikrotik-VPN-latest
   ```

3. Upload the module files to your WHMCS installation:
   - For **Server modules:** copy the `puqMikrotikVPN` directory from the unzipped folder to `whmcs/modules/servers/`
   ```bash
   cp -r PUQ_WHMCS-Mikrotik-VPN-latest/puqMikrotikVPN /path/to/whmcs/modules/servers/
   ```

4. The module files are now in place. Proceed to the configuration chapter to set up your Mikrotik router and WHMCS product.

## Update

The update procedure is the same as installation — replace the existing files with the new version:

1. Download the latest version as described in the Installation section.
2. Unzip the archive.
3. For server modules: simply overwrite the files in `whmcs/modules/servers/puqMikrotikVPN/`. No deactivation is needed.
4. Verify the version number in the module interface matches the new release.
