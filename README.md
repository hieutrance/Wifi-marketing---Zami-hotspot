# WiFi Marketing Captive Portal

This project contains the **initial code for a captive portal** used in WiFi marketing systems. It is designed to authenticate users, display advertisements, and manage user sessions in public or guest WiFi networks.

## 📁 Folder Structure


## 🚀 Features

- **Captive Portal** login flow with support for:
  - Login page (with or without password)
  - Redirect page after login
  - Advertisements before redirecting to internet
- **Client-side password hashing** using `md5.js`
- **Custom UI support** with separate folders for CSS, fonts, and images
- **Guest session status** via `status.html`
- **Support for multi-language (lv/)** and flexible configuration via XML

## 🔧 Usage

1. Deploy this portal on a compatible device (e.g., MikroTik Hotspot, OpenWRT with coovachilli, etc.)
2. Point the device's captive portal redirect to `login.html`
3. Customize UI, logos, and redirect logic if needed
4. Use `status.html` to show users their session usage and time

## 📌 Notes

- This is a **frontend-only** implementation. Backend handling (authentication, session control) is expected to be handled by the router or external RADIUS system.
- `md5.js` helps to hash credentials before sending, for minimal security on open networks.

## 📄 License

MIT License. Feel free to customize and deploy for your own business or client needs.

---

**Author:** HIUCHAN\trung  
**Initial Commit:** f7af1ca  
