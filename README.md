<div align="center">

# Saif Messaoudi

**Staff Mobile Engineer · [MaaarPay](https://maaarpay.com)**

Building a regulated digital wallet for the GCC and MENA, from the first commit to production

[![LinkedIn](https://img.shields.io/badge/LinkedIn-saif--messaoudi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/saif-messaoudi)
[![Email](https://img.shields.io/badge/Email-Contact-1E3A8A?style=flat-square&logo=maildotru&logoColor=white)](mailto:saif.messaoudi@esprit.tn)
[![MaaarPay](https://img.shields.io/badge/MaaarPay-Live_on_iOS_%26_Android-102A71?style=flat-square)](https://maaarpay.com)

</div>

---

### About

I lead mobile engineering at **MaaarPay**, a fintech super-app for the GCC and MENA. It covers digital wallets, virtual Visa cards, crypto, transfers, and rewards in one product.

I joined on day one. I wrote the app's first commit in June 2025, and I now own its mobile architecture, platform, and engineering standards. My work is to let a small team ship financial features quickly and safely in an app where a missed edge case can affect someone's balance.

### MaaarPay in numbers

<div align="center">

| **7** | **22** | **9** | **1,000+** | **31** | **100+** |
|:---:|:---:|:---:|:---:|:---:|:---:|
| markets | feature modules | platform packages | test suites | CI quality gates | tagged store releases |

</div>

<sub>UAE · Saudi Arabia · Bahrain · Kuwait · Qatar · Oman · Tunisia · in English, Arabic (RTL), French and German</sub>

### Growth timeline

| When | Milestone |
|---|---|
| **Jun 2025** | Day one: I set up the app's foundation, architecture, and delivery pipeline from an empty repository |
| **Q4 2025** | Core wallet: identity verification (KYC), crypto deposits, virtual cards, and asset swap |
| **H1 2026** | Production launch on the App Store and Google Play, followed by a steady release train |
| **Jun – Aug 2026** | Re-platformed the monolith into a modular super-app (22 isolated feature modules on 9 shared kernel packages) and migrated the state and navigation layers without stopping releases |
| **Jul – Aug 2026** | New business lines: in-app marketplace and the MaaarPoints rewards program |
| **Sep – Oct 2026** | Passkeys with step-up authentication, bank payouts, and faster secure sign-in |

### Impact

- **Built the product end to end.** I took MaaarPay from an empty repository to a multi-market wallet with cards, crypto, transfers, KYC, a marketplace, and rewards, shipping on iOS and Android with Flutter plus native Swift and Kotlin.
- **Turned one app into a platform.** I designed a modular "mini-app" architecture in which every feature is an isolated module with explicit contracts. The boundaries are enforced in CI rather than left to convention, so the team can grow without the codebase decaying.
- **Made money safety structural.** Every payment path gets idempotent requests, remote kill switches for each flow, and double-submit protection by design. Automated checks fail the build when a money path ships without these protections.
- **Raised the security baseline.** Certificate pinning with remote rotation, passkeys and step-up authentication, device attestation, secure on-device storage, and static checks that block PII from reaching logs.
- **Made quality measurable.** More than 1,000 test suites, 31 custom static-analysis gates, blocking visual-regression tests, and on-device end-to-end tests for money flows.
- **Closed the loop in production.** Every crash is attributed to the feature that owns it, performance budgets are measured on mid-range devices, and every incident becomes a regression test or a CI gate.

### How I work

- **Architecture is a liability budget.** Boundaries exist to contain change.
- **Unverified means unfinished.** If a rule matters, a machine enforces it.
- **Root cause over symptom.** I prefer small, correct changes to heroic rewrites.
- **Production is the real test environment.** Green CI is necessary but never sufficient.

### Toolbox

<p>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
<img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" />
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" />
<img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=black" />
</p>

**Focus areas:** mobile architecture · modular / super-app platforms · payments and money movement · mobile security · release engineering · performance

---

<div align="center">
<sub>Open to conversations about mobile platforms, fintech, and engineering at scale.</sub>
</div>
