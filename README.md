<p align="center">
  <img src="https://usebound.app/usebound_logo.svg" alt="UseBound Logo" width="120">
</p>

# UseBound

**Free, browser-based purpose-bound watermarking for identity documents. Label who it's for, why, and until when. If it leaks, you know who's responsible.**

[![Website](https://img.shields.io/badge/Website-usebound.app-blue)](https://usebound.app)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Client--Side-green)](https://usebound.app)

[🌐 Visit the app at usebound.app](https://usebound.app)

> **⚠️ This is the issue tracker and information page for UseBound.** The source code is proprietary and not publicly available. Use this repository to report bugs and request features.

---

## What is UseBound?

UseBound is a **free, privacy-first tool for purpose-bound document watermarking**. It adds visible watermarks to your passport, ID, contract, or financial document that state who the document is for, why it's being shared, and when the authorization expires — all processed 100% in your browser with no uploads.

## The Problem

When you share sensitive documents (IDs, passports, contracts, financial records), you lose control once they're handed over. If the receiving organization suffers a data breach, your documents can be used for identity theft, fraud, or unauthorized purposes — and there's no way to prove which organization leaked them.

## The Solution

UseBound adds visible, purpose-bound watermarks that state:

* **WHO** the document is for (recipient/organization)
* **WHAT** it's for (purpose: job application, account opening, etc.)
* **WHEN** it expires (time-limited validity)

This creates built-in accountability. If the document appears in a hacked database:

* ✅ The watermark makes it harder to misuse for identity theft (clearly bound to a specific recipient and purpose)
* ✅ You know exactly which organization leaked it (accountability)
* ✅ You have proof of the intended purpose and time limitation (legal protection)

## Why Purpose-Bound?

Generic watermarks like "COPY" or "CONFIDENTIAL" don't help after a breach — they don't tell you who leaked the document or restrict its use. A purpose-bound watermark is specific: it names the recipient, states the purpose, and sets an expiration. This means every copy of your document is unique to the organization you shared it with, creating an automatic audit trail without requiring any infrastructure on the recipient's end.

The term "purpose-bound" comes from data protection principles in regulations like the GDPR, which requires that personal data be collected for specified, explicit, and legitimate purposes. Purpose-bound watermarking makes this principle physically visible on the document itself.

## How It Works

1. **Open UseBound** at [usebound.app](https://usebound.app) — no account or install needed
2. **Load your document** — drag & drop or select a PDF or image. The file stays on your device.
3. **Write your purpose-bound watermark** — include the recipient, purpose, and expiration date (e.g., "For: Deutsche Bank — KYC Verification — Valid until: Sept 2026")
4. **Position and style** — adjust placement, opacity, rotation, and size with a live preview
5. **Export** — download your watermarked document, ready to share

All processing happens in your browser. Your documents are never uploaded to any server. You can verify this by checking the Network tab in your browser's DevTools — you'll see zero document uploads.

## Primary Use Cases

### ID Verification (KYC)

Watermark passports or driver's licenses before sending to banks, employers, or service providers:

```
For: Acme Corp HR (Job Application)
Valid until: Feb 2025
```

Protects against identity theft if the company is breached.

### Rental Applications

Watermark documents before sharing with landlords or property managers:

```
For: Greenfield Property Management — Rental Application 42 Oak Lane
Valid until: March 2026
```

Landlords often store documents in unsecured email accounts or shared drives.

### Contract Sharing

Mark contracts before sending to third parties for review:

```
For: Legal Review - Smith & Associates
Confidential
```

Prevents unauthorized distribution.

### Financial Documents

Watermark bank statements or tax returns before sharing:

```
For: Mortgage Application - Bank XYZ
Valid until: March 2025
```

Limits misuse if leaked.

### Legal Documents

Add accountability to NDAs, agreements, and sensitive communications. Creates a clear audit trail of legitimate access.

### Medical Records

Watermark medical documents before sharing with providers. Adds an accountability layer for sensitive health information.

## 🚀 Key Features

### Privacy First

* **100% client-side processing** — documents never leave your browser
* **No uploads, no servers** — everything happens locally
* **No tracking or analytics** — your privacy is respected
* **Offline capable** — works without internet after initial load
* **Verifiable** — check the Network tab in DevTools (zero requests)

### Powerful & Easy to Use

* **PDF & image support** — PNG, JPG, and multi-page PDFs
* **Customizable watermarks** — text, position, size, rotation, opacity, color
* **Template system** — save and reuse common watermark configurations
* **Batch processing** — apply watermarks to multiple pages
* **Live preview** — see exactly how your watermark will look
* **Touch-friendly** — optimized for mobile devices with larger handles

### Professional Features

* **Multi-page PDF** — watermark all pages or specific pages
* **Metadata stripping** — optionally remove EXIF data on export
* **High quality output** — maintains document quality
* **Keyboard shortcuts** — fast workflow with hotkeys
* **Responsive design** — works on desktop, tablet, and mobile

## 🔐 Privacy Architecture

UseBound is built with a **zero-trust architecture**:

* ✅ All processing in JavaScript in the browser
* ✅ No backend servers
* ✅ No analytics or telemetry
* ✅ No cookies (except saved templates in localStorage)
* ✅ Content Security Policy enforced
* ✅ Verifiable via browser DevTools Network tab

## Technology Stack

* **Frontend**: Vanilla JavaScript (ES6+)
* **PDF Processing**: PDF-lib
* **Build Tool**: Vite
* **Styling**: CSS Variables with light/dark theme support
* **Canvas API**: For image watermarking

## Target Audience

* Privacy-conscious individuals sharing sensitive documents
* Job seekers submitting ID verification
* Freelancers and contractors sharing agreements
* Anyone uploading identity documents to organizations
* Security professionals
* Legal professionals
* Healthcare providers and patients

## 💖 Support This Project

UseBound is **100% free** with no ads or premium features. If you find it useful, please consider supporting its development:

* ☕ [Ko-fi](https://ko-fi.com/bened1kt)
* 💳 [PayPal](https://paypal.me/btroe)

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature idea? Please [open an issue](https://github.com/benedikt90/usebound.app/issues)!

**Before submitting**:

* Search existing issues to avoid duplicates
* Provide clear reproduction steps for bugs
* Explain the use case for feature requests

## License

**UseBound is free to use, but not open source.** The source code is proprietary and not publicly available.

* ✅ You can **use the app for free** at [usebound.app](https://usebound.app)
* ✅ You can **report bugs and request features** in this repository
* ❌ You **cannot access, copy, or modify** the source code
* ❌ You **cannot redistribute or sell** this software

The project runs entirely on donations. If UseBound helps you protect your sensitive documents, please consider [supporting its development](#-support-this-project) to keep it free and ad-free for everyone!

---

**Built with ❤️ in Switzerland 🇨🇭**

[🌐 usebound.app](https://usebound.app)

## Keywords

purpose-bound watermarking, purpose-bound watermark, document watermarking, watermark passport before sharing, watermark ID for KYC, document watermark accountability, privacy, security, ID verification, contract watermarking, browser-only, offline, no upload, accountability, data breach protection, identity theft prevention, sensitive documents, passport watermark, financial documents, legal documents, privacy-first, zero-trust, client-side processing, PDF watermark, image watermark, document security, leak tracing
