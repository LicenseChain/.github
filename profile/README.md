# LicenseChain

<div align="center">

![LicenseChain](https://img.shields.io/badge/LicenseChain-License%20Management-00D9FF?style=for-the-badge&logo=github)

**Production-grade license management with multi-language SDK support**

[![Website](https://img.shields.io/badge/Website-licensechain.app-00D9FF?style=flat-square)](https://www.licensechain.app)
[![Documentation](https://img.shields.io/badge/Docs-docs.licensechain.app-00D9FF?style=flat-square)](https://docs.licensechain.app)
[![API](https://img.shields.io/badge/API-api.licensechain.app-00D9FF?style=flat-square)](https://api.licensechain.app)
[![Dashboard](https://img.shields.io/badge/Dashboard-dashboard.licensechain.app-00D9FF?style=flat-square)](https://dashboard.licensechain.app)
[![License](https://img.shields.io/badge/License-Elastic--2.0-yellow?style=flat-square)](https://www.elastic.co/licensing/elastic-license)

</div>

---

## What is LicenseChain?

LicenseChain helps developers and businesses manage, validate, and track software licenses across platforms and programming languages.

- Secure API-key authentication
- Create, verify, update, and revoke licenses
- Hardware ID binding
- Webhooks for license lifecycle events
- Multi-language SDKs

---

## Public SDKs

### JavaScript / TypeScript

- [Node.js SDK](https://github.com/LicenseChain/LicenseChain-NodeJS-SDK)
- [JavaScript SDK](https://github.com/LicenseChain/LicenseChain-JavaScript-SDK)

### Backend languages

- [Python SDK](https://github.com/LicenseChain/LicenseChain-Python-SDK)
- [Go SDK](https://github.com/LicenseChain/LicenseChain-Go-SDK)
- [Rust SDK](https://github.com/LicenseChain/LicenseChain-Rust-SDK)
- [Ruby SDK](https://github.com/LicenseChain/LicenseChain-Ruby-SDK)
- [PHP SDK](https://github.com/LicenseChain/LicenseChain-PHP-SDK)
- [Java SDK](https://github.com/LicenseChain/LicenseChain-Java-SDK)
- [C# SDK](https://github.com/LicenseChain/LicenseChain-CSharp-SDK)
- [VB.NET SDK](https://github.com/LicenseChain/LicenseChain-VB-SDK)
- [Perl SDK](https://github.com/LicenseChain/LicenseChain-Perl-SDK)
- [C++ SDK](https://github.com/LicenseChain/LicenseChain-CPP-SDK)

### Mobile, desktop & game

- [Android SDK](https://github.com/LicenseChain/LicenseChain-Android-SDK)
- [iOS SDK](https://github.com/LicenseChain/LicenseChain-iOS-SDK)
- [macOS SDK](https://github.com/LicenseChain/LicenseChain-macOS-SDK)
- [Unity SDK](https://github.com/LicenseChain/LicenseChain-Unity-SDK)
- [Luau SDK](https://github.com/LicenseChain/LicenseChain-Luau-SDK)

### Tools

- [Mirror SDK](https://github.com/LicenseChain/LicenseChain-Mirror-SDK)

---

## Quick start

```bash
# Node.js
npm install licensechain-node-sdk

# Python
pip install licensechain-python-sdk

# Go
go get github.com/LicenseChain/LicenseChain-Go-SDK

# Ruby
gem install licensechain_ruby_sdk

# Rust
cargo add licensechain
```

```javascript
import LicenseChain from 'licensechain-node-sdk';

const client = new LicenseChain({
  apiKey: process.env.LICENSECHAIN_API_KEY,
  baseUrl: 'https://api.licensechain.app'
});

const license = await client.licenses.verify('LICENSE-KEY-HERE');
console.log('License status:', license.status);
```

Full guides: [docs.licensechain.app](https://docs.licensechain.app)

---

## Documentation

- [Getting started](https://docs.licensechain.app/getting-started)
- [API reference](https://docs.licensechain.app/api-reference)
- [SDK documentation](https://docs.licensechain.app/sdk)
- [Integration guides](https://docs.licensechain.app/guides)

---

## Contributing

- Open issues on the relevant **public** SDK repository
- Follow that repository’s contribution guidelines and code style
- Include tests and docs updates with pull requests

---

## License

Public LicenseChain SDK repositories use the **Elastic License 2.0**. See each repository’s `LICENSE` file.

---

## Links

- Website: [licensechain.app](https://www.licensechain.app)
- API: [api.licensechain.app](https://api.licensechain.app)
- Dashboard: [dashboard.licensechain.app](https://dashboard.licensechain.app)
- Docs: [docs.licensechain.app](https://docs.licensechain.app)
- Support: [support@licensechain.app](mailto:support@licensechain.app)

<div align="center">

**[LicenseChain LLC](https://www.licensechain.app)**

</div>
