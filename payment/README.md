# Payment & License Activation Instructions

**Nandini VK** — Developer Tools & Security Software

---

## Products & Pricing

| Product | Personal | Commercial |
|---------|----------|------------|
| Twenty MCP Server | Free (MIT) | $49 USD |
| Sentinel-RS EDR | Free (MIT) | $29 USD/server |
| DevSecOps Bundle (Both) | — | $69 USD |

All commercial prices are **one-time** purchases. No subscriptions, no recurring fees.

---

## Payment Methods

### 🇮🇳 UPI (India — Preferred)

**UPI ID:** `7852034945@paytm`

Scan the QR code or send payment to the UPI ID above. Available on any UPI app (Google Pay, PhonePe, Paytm, BHIM).

### 🏦 Bank Transfer (India)

| Field | Value |
|-------|-------|
| Account Name | Nandini VK |
| Account Number | `7626002100006961` |
| IFSC Code | `PUNB0762600` |
| Bank | Punjab National Bank |
| Branch | Jodhpur, Pal Road |

### 💳 International Customers

For international bank transfers (SWIFT/ACH), please email [licenses@nandini-vk.dev](mailto:licenses@nandini-vk.dev) for wire transfer instructions. SWIFT/IBAN details will be provided on request.

---

## Bank Transfer Template

Use this template when making a bank transfer:

```
────────────────────────────────────
NEFT/RTGS Transfer Form
────────────────────────────────────
Beneficiary Name : Nandini VK
Account Number   : 7626002100006961
IFSC Code        : PUNB0762600
Bank Name        : Punjab National Bank
Branch           : Jodhpur, Pal Road

Amount           : ₹_______
Product          : [Twenty MCP / Sentinel-RS / Bundle]
────────────────────────────────────
```

---

## After Payment: Getting Your License Key

1. **Make the payment** using any method above.
2. **Email** your payment confirmation/receipt to:
   **`licenses@nandini-vk.dev`**
3. **Include** in the email:
   - Product name you purchased
   - Your GitHub username (for repository access)
   - Any notes (e.g., number of servers for Sentinel-RS)

4. **License delivery:** Keys are sent to your email within **24 hours** (usually same day).

---

## License Activation

### For Twenty MCP Server

```bash
# After downloading the binary:
twenty-mcp-server --license NVK-XXXXX-XXXXX-XXXXX-XXXXX-XXXXXC

# Or set via environment variable:
export TWENTY_MCP_LICENSE=NVK-XXXXX-XXXXX-XXXXX-XXXXX-XXXXXC
twenty-mcp-server
```

### For Sentinel-RS EDR

```bash
# During installation:
sentinel-rs --activate NVK-XXXXX-XXXXX-XXXXX-XXXXX-XXXXXC

# Or via config file:
echo 'license_key = "NVK-XXXXX-XXXXX-XXXXX-XXXXX-XXXXXC"' >> /etc/sentinel-rs/config.toml
sentinel-rs --start
```

---

## License Policy

- **Personal licenses:** Free. No activation required. Use under MIT terms.
- **Commercial licenses:** One key per purchase. Key can be transferred between machines but may only be active on one at a time (unless bundle/multi-seat purchased).
- **Bundle:** Includes both products under one license key.
- **Refunds:** 14-day money-back guarantee. Email [licenses@nandini-vk.dev](mailto:licenses@nandini-vk.dev) for a refund if the software doesn't meet your needs.

---

## Need Help?

- **License issues:** licenses@nandini-vk.dev
- **Technical support:** GitHub Issues on the respective repository
- **Feature requests:** Open an issue or discussion on GitHub

---

*Last updated: May 2026*
