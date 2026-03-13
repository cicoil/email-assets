# Email Assets

Publicly hosted images for email signatures used by CicoilSuite.

## Source Files

The original PNGs come from the CicoilCore repo:

```
CicoilCore/CicoilSuite.Core/Assets/
├── Logos/    → uploaded to logos/ here
└── Social/  → uploaded to social/ here
```

If you add a new logo or icon to `CicoilSuite.Core/Assets/`, upload a copy here too so the hosted URL is available for mobile signatures.

## How It's Used

- **In-app preview**: Uses embedded `data:` URIs (from `EmbeddedAssets.cs`)
- **Clipboard copy**: Uses hosted URLs from this repo (via `EmbeddedAssets.GetLogo/Social/ContactIconHostedUrl()`)
- **Why**: Mobile Outlook blocks `data:` URIs — hosted `https://` URLs work everywhere

## Base URL

```
https://raw.githubusercontent.com/cicoil/email-assets/main/
```

## Logos

Company logos used as the main signature logo.

| File | URL |
|------|-----|
| CEPA.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/CEPA.png` |
| Cicoil.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/Cicoil.png` |
| ConexSmart.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/ConexSmart.png` |
| CRE.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/CRE.png` |
| EZForm.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/EZForm.png` |
| FEC.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/FEC.png` |
| HydroGroup.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/HydroGroup.png` |
| ICS.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/ICS.png` |
| IntelliConnect.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/IntelliConnect.png` |
| PCI.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/PCI.png` |
| Trexon.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/logos/Trexon.png` |

## Social & Contact Icons

Small icons used for social media links and contact info in signatures.

| File | URL |
|------|-----|
| discord.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/discord.png` |
| facebook.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/facebook.png` |
| github.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/github.png` |
| globe.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/globe.png` |
| instagram.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/instagram.png` |
| linkedin.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/linkedin.png` |
| mail.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/mail.png` |
| map-pin.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/map-pin.png` |
| mastodon.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/mastodon.png` |
| medium.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/medium.png` |
| phone.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/phone.png` |
| pinterest.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/pinterest.png` |
| reddit.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/reddit.png` |
| snapchat.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/snapchat.png` |
| spotify.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/spotify.png` |
| telegram.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/telegram.png` |
| threads.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/threads.png` |
| tiktok.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/tiktok.png` |
| twitch.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/twitch.png` |
| whatsapp.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/whatsapp.png` |
| x.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/x.png` |
| youtube.png | `https://raw.githubusercontent.com/cicoil/email-assets/main/social/youtube.png` |
