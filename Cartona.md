# Privacy Policy

_Last updated: 24 September 2025_

> IMPORTANT: This template is provided for convenience only and does **not** constitute legal advice. Please have qualified counsel review and adapt it to your specific circumstances, especially if you operate in regions with specific privacy laws (e.g. GDPR, CCPA, LGPD, POPIA, COPPA).

## 1. Introduction
This Privacy Policy describes how **Cartona** ("the App", "we", "us", or "our") collects, uses, discloses, and safeguards information when you use our mobile and/or web application.

By using the App, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree, please discontinue use.

## 2. Summary (Quick Read)
| Category | Do we collect? | Purpose | Shared with third parties? |
|----------|----------------|---------|-----------------------------|
| Personal Identifiers (e.g., email if you provide it) | Possibly / Optional | Account features, support | Service providers only |
| Device & App Info | Yes | Performance, compatibility, analytics | Firebase services |
| Usage & Interaction Data | Yes | Improve features & stability | Firebase Analytics / Performance |
| Crash Data | Yes | Diagnose & fix issues | Firebase Crashlytics |
| Push Notification Tokens | Yes | Deliver notifications | Firebase Cloud Messaging |
| Payment Data | N/A (Not collected) | — | — |
| Location Data | No (unless stated otherwise) | — | — |

(Adjust the table above to reflect actual behavior.)

## 3. Information We Collect
We collect the following categories of data. Some data is collected automatically; some only if you voluntarily provide it.

### 3.1 Information You Provide Voluntarily
- Contact details (e.g., email) when you contact support or register (if such a feature exists).
- Feedback, inquiries, or other communication content.

### 3.2 Information Collected Automatically
- Device information: model, OS version, device identifiers (non‑persistent or pseudonymous where possible), preferred language.
- App metadata: version, build number.
- Usage data: screens viewed, feature interactions, session timestamps, approximate engagement patterns.
- Performance metrics: app startup time, network latency (aggregated), ANRs.
- Crash diagnostics & stack traces.

### 3.3 Push Notifications
We (via Firebase Cloud Messaging) receive a device token used solely to deliver notifications. You can disable notifications at any time in system settings.

### 3.4 Aggregated / De‑Identified Data
We may aggregate or anonymize data so it can no longer reasonably identify an individual. We may use and retain such data for analytics and product improvement.

## 4. How We Use Information
We use collected data to:
- Provide, operate, and maintain the App.
- Improve performance, reliability, and user experience.
- Monitor usage patterns and plan new features.
- Diagnose crashes, errors, and security incidents.
- Send push notifications (if enabled) related to updates or relevant content.
- Respond to user support requests.
- Comply with legal obligations and enforce terms.

## 5. Legal Bases for Processing (EEA/UK Only)
If you are in the European Economic Area or UK, we rely on these bases (as applicable):
- Legitimate Interests (analytics, crash diagnostics, app security, improvement).
- Consent (push notifications if legally required; adjust if you implement explicit consent flows).
- Legal Obligation (where processing is required by law).

## 6. Third-Party Services
We use trusted third-party services to support core functionality:

| Service | Purpose | Data Involved | Policy |
|---------|---------|---------------|-------|
| Firebase Analytics | Usage analytics | Events, device/app metadata | https://firebase.google.com/support/privacy |
| Firebase Crashlytics | Crash diagnostics | Crash traces, device state at crash | https://firebase.google.com/support/privacy |
| Firebase Performance Monitoring | Performance metrics | Network timing, app performance | https://firebase.google.com/support/privacy |
| Firebase Cloud Messaging | Push delivery | Device token | https://firebase.google.com/support/privacy |

(Replace / add services as needed.)

## 7. Data Retention
We retain personal and diagnostic data only as long as necessary for the purposes described or as required by law. Aggregated or anonymized data may be retained longer.

## 8. Data Sharing & Disclosure
We do **not** sell your personal information. We may share data with:
- Service providers (e.g., Firebase) under contractual safeguards.
- Authorities when required by law, regulation, or legal process.
- Successors in a merger, acquisition, or asset transfer (subject to continuity of protections).

## 9. International Data Transfers
Data may be processed in countries different from your residence. We implement reasonable safeguards (e.g., standard contractual clauses where applicable) to protect transferred data.

## 10. Security
We employ reasonable technical and organizational measures to protect data (secure connections, least‑privilege access, dependency maintenance). However, no method of transmission or storage is 100% secure.

## 11. Your Rights
Your local privacy rights may include (depending on jurisdiction):
- Access / obtain a copy of your data.
- Rectify inaccurate data.
- Delete data (subject to exemptions).
- Restrict or object to processing.
- Data portability.
- Withdraw consent (where processing is based on consent).

To exercise rights, see Contact section below. We may need to verify identity before responding.

### 11.1 California (CCPA/CPRA) Notice (If Applicable)
We do not sell or share personal information for cross‑context behavioral advertising as defined by California law. You may request disclosure or deletion of personal data subject to legal exceptions.

### 11.2 Children’s Privacy
The App is not directed to children under 13 (or the age defined by your jurisdiction). We do not knowingly collect data from children. If you believe a child provided data, contact us to remove it.

## 12. Push Notification & Analytics Choices
- Disable push notifications: via device OS settings.
- Limit ad tracking (if later introduced): via platform privacy settings.
- Analytics opt-out: (If you implement a toggle, describe here.) Currently no in‑app opt-out—contact us to discuss removal if required by your jurisdiction.

## 13. Changes to This Policy
We may update this Privacy Policy periodically. The “Last updated” date reflects the latest revision. Material changes will (where required) be communicated via in‑app notice or other means.

## 14. Contact Us
If you have questions, requests, or complaints about this Privacy Policy or data handling, contact us:

- Email: [REPLACE_WITH_CONTACT_EMAIL]
- Company / Developer: [YOUR_NAME_OR_ENTITY]
- Address (if required by law): [POSTAL_ADDRESS]

If you are in the EEA/UK and require a Data Protection Officer (DPO) or EU/UK representative, list details here once appointed.

## 15. Glossary (Optional)
- "Personal Data": Information relating to an identified or identifiable individual.
- "Processing": Any operation performed on data (collection, storage, analysis, deletion, etc.).
- "Service Providers": Third parties that process data on our behalf.

---
**Action Items for You Before Publishing:**
1. Replace all bracketed placeholders (email, entity, address).
2. Confirm actual data flows & remove sections not applicable.
3. Add any additional third-party SDKs you integrate (ads, payments, maps, etc.).
4. Ensure in‑app disclosures match this document.
5. If subject to GDPR/CCPA, confirm rights handling workflow.

After customizing, link this file from `README.md` or your app store listing.
