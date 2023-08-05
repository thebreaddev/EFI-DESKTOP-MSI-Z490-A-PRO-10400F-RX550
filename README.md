# EFI-DESKTOP-MSI-Z490-A-PRO-10400F-RX550
 Hackintosh EFI (OpenCore 0.9.3) for macOS Ventura MSI Z490-A PRO and i5-10400F and Sapphire AMD Radeon RX 550 PULSE OC

# Hardware
- CPU: Intel Core i5-10400F
- GPU: Sapphire AMD Radeon RX 550 PULSE OC 4 GB (Lexa)
- Motherboard: MSI Z490-A PRO
- Memory: Kingston FURY Beast RGB 16 GB [DDR4, 8 GB x 2, 3200 MHz, 16-18-18]
- SSD: Kingston A400 240 GB 2.5" (macOS Ventura)
- NVME: Samsung 970 Evo Plus 500 GB (Windows 11)
- Case: Cougar MX410 MESH-G RGB

# Notes
- macOS 10.15.x, 11.x, 12.x 13.4 and lower is untested but should be fine, read note about SSDT-PLUG.aml.
- Works with macOS 13.5 and 13.4.1 (c)
- Sleep works with Intel XMP (Profle 1 - 3200 MHz)
- SSDT-PLUG.aml is not required on macOS 12.3 and up. But i still use it for 12.2 and below compatibility, you can remove it if you don't want to use Monterey.
- Use iMacPro or MacPro SMBIOS (Discrete Graphics only) or iMac20,x SMBIOS (only if have CPU with Integrated Graphics) for hardware decoding/encoding to work.
- and yeah i got Lexa core GPU why not if it works