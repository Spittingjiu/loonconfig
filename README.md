# loonconfig

Loon configuration template for:
- CN direct
- Non-CN proxy
- DNS leak mitigation baseline

## Files
- `loon.conf` — import into Loon

## Notes
- Node lines are intentionally not included; import your nodes/subscription separately.
- If you still see DNS leak on iOS, check device-level settings:
  - iOS Settings -> Wi-Fi -> current network -> Configure DNS (avoid manual ISP DNS)
  - iOS Settings -> General -> VPN & Device Management -> ensure only Loon VPN active
  - Disable other DNS/VPN apps simultaneously
