# Super Sound Machine — Support

## App Description

Super Sound Machine is a high-fidelity sound and sleep app designed to help you relax, focus, and rest more deeply. It combines layered ambient audio, precise mixing and EQ, timers, Apple Health–powered sleep insights, and optional Lamp Mode for a calm night-time setup. Perfect for building personalized sleep environments, steady background sound for work, or winding down at the end of the day.

## Key Features

- **High-fidelity audio** — Lossless sounds with seamless looping  
- **Multi-channel mixing** — Blend multiple sounds into custom environments  
- **Sound profiles** — Save, load, import/export, and share personalized mixes  
- **Built-in equalizer** — Fine-tune the tonal balance of your mix  
- **Lullabies and sleep-focused content** — Curated material for rest  
- **Timers and timer chains** — Simple timers and more advanced chained sessions  
- **Custom sounds** — Import your own audio to use alongside built-in sounds  
- **Sleep tracking & insights** — Trends and analysis using **Apple Health** sleep data (with your permission)  
- **Lamp Mode** — Customizable nightlight-style colors  
- **Dark Mode** — In-app appearance toggle  
- **Shop** — Subscriptions and purchases for full access (handled by Apple)  

## How to Use (Overview)

1. **Choose sounds** — Open the main sound list / mixer, pick channels, and adjust volumes.  
2. **Optional EQ** — Open the equalizer to shape highs, lows, and mids for your mix.  
3. **Save a profile** — Save your mix as a named profile for quick recall.  
4. **Timers** — Set a timer or chain so playback can stop or transition automatically.  
5. **Sleep (optional)** — Grant **Health** read access when prompted if you want sleep charts and insights; you can change this anytime in **Settings → Privacy & Security → Health**.  
6. **Share a profile (optional)** — Use share from profiles to send a link or file; recipients can import if they have the app.  
7. **Custom audio (optional)** — Import supported audio (e.g. **WAV** where applicable) from **Files** or related pickers, depending on feature entry points in your build.  
8. **Lamp Mode** — Switch to Lamp Mode for a dim, color-tunable companion to your audio.  
9. **More** — Tutorials, Shop, **About**, **Terms**, **Privacy Policy**, and **App Version** live under **More**.  

## Troubleshooting

### App Crashes or Freezes

- Ensure you have enough free storage on your device.  
- Force-quit the app and reopen it.  
- Restart your iPhone or iPad.  
- If you use **beta iOS**, try on a stable release if possible.  

### No Sound or Audio Drops Out

- Check the **Ring/Silent** switch and system **volume**; use in-app volume and **mute** states.  
- Confirm no other app has taken exclusive audio (phone calls, some video apps).  
- If interruption persists, stop and restart playback or reload the profile.  

### iCloud / Data Not Syncing

- Confirm you’re signed into **iCloud** on all devices (**Settings → [your name] → iCloud**).  
- Check **iCloud Drive** and network connectivity.  
- Allow time for **NSUbiquitousKeyValueStore** / document sync after large changes.  

### Health / Sleep Data or Charts

- Grant **read** access to **Sleep** (and related) categories when the app asks.  
- Open **Settings → Privacy & Security → Health → Super Sound Machine** and enable categories you want.  
- Apple **Watch** or other sources must actually write sleep data to **Health** for charts to populate.  
- Remember: in-app sleep analysis is **informational only**, not medical advice (see **Terms of Service** in the app).  

### Purchases or Subscriptions

- Use **Restore Purchases** in the **Shop** when you reinstall or change devices.  
- Manage or cancel subscriptions in **Settings → [your name] → Subscriptions** (Apple), or use **Manage Subscriptions** links in the Shop when shown.  
- Billing issues are handled by **Apple**; the app does not store your card number.  

### Sharing Profiles / Links

- Sharing creates a **link** or file others can open; links require network access.  
- If a link expired or fails, share again from a saved profile.  
- Avoid putting **personal information** in profile names (they may appear in shared data).  

### Custom Sounds Won’t Play or Import

- Prefer supported formats (commonly **WAV** for custom files in this app).  
- Ensure the file isn’t corrupted and is fully downloaded if it came from **iCloud Drive**.  

### Lamp Mode or Display Issues

- Try toggling **Dark Mode** under **More** if the UI is hard to see.  
- Toggle Lamp Mode off and on if colors or brightness look stuck.  

## Privacy & Data

- **Health data** — Read from **HealthKit** only with your permission; the app is designed **not** to write Health data back and **not** to upload your Health samples to developer-controlled servers for storage (see in-app **Privacy Policy**).  
- **iCloud** — Profiles, timers, settings, and related app data may sync via **your** iCloud account when enabled.  
- **Profile sharing** — If you share a profile, configuration data is sent to **Super Sound Machine** infrastructure (e.g. short links) so others can import it; see **Privacy Policy** for details.  
- **Payments** — Handled by **Apple**; the app does not receive your card details.  
- **Advertising** — This app does not use third-party ad SDKs like AdMob for banners (no ad network section analogous to the Pixel Swap example).  
- **Full policy** — See **Privacy Policy** in the app or your published policy URL / `PRIVACY_POLICY.md` in this repo if you mirror it on GitHub.  

## In-App Purchases

- **Unlock / subscribe** — Products shown in the **Shop** (e.g. monthly subscription, lifetime, or as configured in App Store Connect).  
- **Restore** — Always try **Restore Purchases** after reinstalling or switching devices before contacting support.  

## System Requirements

- **iPhone** or **iPad** supported by your current App Store **minimum iOS version** (the Xcode project may target a specific version; the App Store listing is definitive).  
- Sufficient storage for the app, custom audio, and iCloud data.  
- **Internet** useful for **Shop**, **profile sharing URLs**, and some support flows—but core **offline playback** may still work for downloaded/bundled content depending on feature flags and entitlements.  

## Contact Support

If your issue isn’t covered here, contact us:

- **Email:** somdrummer@gmail.com  
- **Subject:** Super Sound Machine Support  

**Please include:**

- Device model and **iOS version**  
- Brief description of the problem  
- Steps to reproduce (if any)  
- Screenshots or screen recordings (if helpful)  
- Whether **Health**, **iCloud**, or **Shop / purchases** are involved  

## Frequently Asked Questions

**Q: Does the app work in the background?**  
**A:** The app supports **audio** background modes where enabled so mixes can continue while the screen is off or you use other apps (subject to iOS behavior and settings).

**Q: Is my sleep data uploaded to your servers?**  
**A:** Per the in-app **Privacy Policy**, Health / sleep samples are used to power on-device analysis and are **not** described as being stored on separate external Health databases by the developer; profile **sharing** is separate and optional.

**Q: Can I use my own audio files?**  
**A:** Yes, where the **custom sounds** feature is available—typically **WAV** and workflows described in-app or in tutorials.

**Q: How do I turn off Health access?**  
**A:** Use **Settings → Privacy & Security → Health → Super Sound Machine** and revoke categories.

**Q: I paid before and lost entitlements.**  
**A:** Open **Shop** and tap **Restore Purchases**; stay signed into the same **Apple ID** used for the purchase.

**Q: What age is the app intended for?**  
**A:** See **Terms of Service** in the app for current eligibility language (e.g. intended minimum age and children’s privacy).

---

## Version History

_Add release notes here as you ship, or point readers to the App Store “What’s New” section for authoritative version history._
