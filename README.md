<div align="center">
  <img src="https://usebound.app/usebound_logo.svg" alt="UseBound Logo" width="200"/>

  <h1>UseBound</h1>
  <h3>Privacy-Focused Document Watermarking Tool</h3>
  <p><strong>Share safely. Trace clearly.</strong></p>

  <p>
    <a href="https://usebound.app"><img src="https://img.shields.io/badge/Website-usebound.app-blue" alt="Website"></a>
    <a href="https://usebound.app"><img src="https://img.shields.io/badge/Privacy-100%25%20Client--Side-green" alt="Privacy"></a>
  </p>

  <p><strong>⚠️ This is the issue tracker and information page for UseBound</strong></p>
  <p>Use this repository to report bugs and request features.</p>

  <p><a href="https://usebound.app">🌐 Visit the app at usebound.app</a></p>
</div>

---

## What is UseBound?

UseBound is a **100% client-side document watermarking tool** that helps you protect sensitive documents before sharing them. Add visible, purpose-bound watermarks to PDFs and images directly in your browser—no uploads, no tracking, complete privacy.

## The Problem It Solves

When you share sensitive documents (IDs, passports, contracts, financial records), you lose control once they're uploaded. If they leak in a data breach, there's no way to prove misuse or track the source. Documents can be used for identity theft, fraud, or unauthorized purposes without consequence.

## The Solution

UseBound adds visible watermarks that state:
- **WHO** the document is for (recipient/organization)
- **WHAT** it's for (purpose: job application, account opening, etc.)
- **WHEN** it expires (time-limited validity)

This creates built-in accountability. If the document appears in a hacked database:
- ✅ The watermark makes it useless for identity theft (clearly marked as bound to specific use)
- ✅ You know exactly which organization leaked it (accountability)
- ✅ You have proof of the intended purpose (legal protection)

## 🚀 Key Features

### Privacy First
- **100% client-side processing** - Documents never leave your browser
- **No uploads, no servers** - Everything happens locally
- **No tracking or analytics** - Your privacy is respected
- **Offline capable** - Works without internet after initial load
- **Open for verification** - Check Network tab in DevTools (zero requests)

### Powerful & Easy to Use
- **PDF & Image Support** - PNG, JPG, and multi-page PDFs
- **Customizable Watermarks** - Text, position, size, rotation, opacity, color
- **Template System** - Save and reuse common watermark configurations
- **Batch Processing** - Apply watermarks to multiple pages
- **Live Preview** - See exactly how your watermark will look
- **Touch-Friendly** - Optimized for mobile devices with larger handles

### Professional Features
- **Multi-page PDF** - Watermark all pages or specific pages
- **Metadata Stripping** - Optionally remove EXIF data on export
- **High Quality Output** - Maintains document quality
- **Keyboard Shortcuts** - Fast workflow with hotkeys
- **Responsive Design** - Works on desktop, tablet, and mobile

## Primary Use Cases

### 1. ID Verification
Watermark passports/driver's licenses before sending to companies:
```
For: Acme Corp HR (Job Application)
Valid until: Feb 2025
```
Protects against identity theft if company is breached.

### 2. Contract Sharing
Mark contracts before sending to third parties:
```
For: Legal Review - Smith & Associates
Confidential
```
Prevents unauthorized distribution.

### 3. Financial Documents
Watermark bank statements, tax returns before sharing:
```
For: Mortgage Application - Bank XYZ
Valid until: March 2025
```
Limits misuse if leaked.

### 4. Legal Documents
Add accountability to NDAs, agreements, sensitive communications. Clear audit trail of legitimate access.

### 5. Medical Records
Watermark medical documents before sharing with providers. HIPAA compliance support with accountability layer.

## How It Works

1. **Load Your Document** - Drag & drop or select PDF/image files
2. **Customize Watermark** - Set text, position, style, rotation
3. **Preview Live** - See changes in real-time on canvas
4. **Download Protected** - Export watermarked document

## 💖 Support This Project

UseBound is **100% free** with no ads or premium features. If you find it useful, please consider supporting its development:

- ☕ [Ko-fi](https://ko-fi.com/bened1kt)
- 💳 [PayPal](https://paypal.me/btroe)

## 🔐 Privacy Architecture

UseBound is built with a **zero-trust architecture**:
- ✅ All processing in JavaScript in the browser
- ✅ No backend servers
- ✅ No analytics or telemetry
- ✅ No cookies (except saved templates in localStorage)
- ✅ Content Security Policy enforced
- ✅ Verifiable via browser DevTools Network tab

## Technology Stack

- **Frontend**: Vanilla JavaScript (ES6+)
- **PDF Processing**: PDF-lib
- **Build Tool**: Vite
- **Styling**: CSS Variables with light/dark theme support
- **Canvas API**: For image watermarking

## Target Audience

- Privacy-conscious individuals sharing sensitive documents
- Job seekers (ID verification)
- Freelancers/contractors sharing agreements
- Anyone uploading documents to websites
- Security professionals
- Legal professionals
- Healthcare providers/patients

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature idea? Please [open an issue](https://github.com/reijin90/usebound.app/issues)!

**Before submitting**:
- Search existing issues to avoid duplicates
- Provide clear reproduction steps for bugs
- Explain the use case for feature requests

## License

**UseBound is free to use, but not open source.** The source code is proprietary and not publicly available.

This means:
- ✅ You can **use the app for free** at [usebound.app](https://usebound.app)
- ✅ You can **report bugs and request features** in this repository
- ❌ You **cannot access, copy, or modify** the source code
- ❌ You **cannot redistribute or sell** this software

The project runs entirely on donations. If UseBound helps you protect your sensitive documents, please consider [supporting its development](#-support-this-project) to keep it free and ad-free for everyone!

---

<div align="center">
  <p><strong>Built with ❤️ in Switzerland 🇨🇭</strong></p>
  <p><a href="https://usebound.app">🌐 usebound.app</a></p>
</div>

## Keywords

document watermarking, privacy, security, ID verification, contract watermarking, browser-only, offline, no upload, accountability, data breach protection, identity theft prevention, sensitive documents, passport watermark, financial documents, legal documents, HIPAA, GDPR, privacy-first, zero-trust, client-side processing, PDF watermark, image watermark, document security, leak tracing, purpose-bound documents
