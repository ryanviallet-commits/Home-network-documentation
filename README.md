
# Home Network Documentation

## Network Configuration

### Internet Service Provider (ISP)
- **ISP:** Bell Fibre

### Router Configuration

| Setting | Value |
|---------|-------|
| Router Model | Bell Home Hub 3000 |
| Default Gateway (IP Address) | 192.168.100.254 |
| Subnet Mask | 255.255.255.0 |

### Connected Devices

| Device | IP Address | Subnet Mask | MAC Address |
|---------|------------|-------------|-------------|
| Laptop 1 | 192.168.100.124 | 255.255.255.0 | A8-E2-91-BA-FF-A6 |
| Laptop 2 | 192.168.100.133 | 255.255.255.0 | 38-B1-DB-FF-1C-81 |
| Desktop | 192.168.100.255* | 255.255.255.0 | 34-C9-3D-2C-4E-12 |

> **Note:** Verify the desktop IP address. `192.168.100.255` is the broadcast address for a `255.255.255.0` subnet and should not be assigned to a device.

---

## Network Device Inventory

| Device Type | Model |
|-------------|-------|
| Internet Service Provider | Bell Fibre |
| Wi-Fi Router | Bell Home Hub 3000 |
| Desktop Computer | Lenovo Legion T5 Gaming PC (10th Generation) |
| Laptop 1 | HP ProBook 445 14-inch G11 Notebook PC |
| Laptop 2 | HP Pavilion 17-g148dx |

---

## Secure Login Credential Storage

### Password Manager

The method I use for securely storing my login credentials is **Bitwarden**, a free and open-source password manager. Bitwarden securely stores usernames, passwords, and other sensitive information using strong encryption.

Bitwarden is available as:
- A web browser extension
- A desktop application
- A mobile application

### Security Features

Bitwarden uses **end-to-end, zero-knowledge encryption**, which means all passwords are encrypted on the user's device before they are uploaded to the cloud. Only the user has the encryption key, so even Bitwarden cannot access or view the stored passwords. This helps protect sensitive information even if the service were compromised.

---

## References

1. Bitwarden. (n.d.). *Bitwarden Overview*. https://bitwarden.com/resources/bitwarden-overview/
