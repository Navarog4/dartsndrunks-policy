# Privacy Policy

**Last updated: 2026-09-15**
**Version: 2.0**

---

## 1. Data Controller

**Individual:**  
**Trade name:** DartsNDrunks  
**Legal representative:** Faustin LEGRAND  
**Status:** Private individual  
**Address:** 9 rue du Pressoir, 80800 Villers-Bretonneux, France  
**Email / GDPR Contact:** faustinlegrand4@gmail.com

---

## 2. Covered Application

This Privacy Policy applies to the mobile application **"DartsNDrunks"** (hereinafter "the Application"), published on the **Google Play Store** (Android, package ID `com.dartsndrunks.game`).

The Application is a drinking game involving darts (adult use, related to alcohol consumption) that manages rounds, scores, penalties (forfeits/dares), and both free and premium game modes.

---

## 3. Key Principles

- **Local storage only:** Game data (profiles, scores, history, preferences) is stored **exclusively on your device** in an embedded SQLite database. None of this data is transmitted to the Publisher (who operates no servers).
- **Minimization:** We only process data strictly necessary for game functionality and ad delivery.
- **Transparency:** We exhaustively declare below all collected data, its purpose, legal basis, and retention period.
- **Ad consent:** Personalized advertisements are only displayed with your explicit consent, collected via the Google UMP (User Messaging Platform) consent banner in compliance with the GDPR.
- **User control:** You delete your game data directly within the Application.

---

## 4. Data Collected and Purposes

### 4.1 Data stored locally on your device (never transmitted)

| Category | Data | Purpose | Legal basis (GDPR) | Retention |
|----------|------|---------|---------------------|-----------|
| **Player profiles** | Entered names, avatars (emojis), statistics (wins, losses, forfeits, points) | Gameplay, score display, personal history | Art. 6.1.b (contract performance) | Until manual deletion |
| **Game history** | Dates, played modes, scores, forfeits received, participants | Personal statistics, reviewing past games | Art. 6.1.b (contract performance) | Until manual deletion |
| **Preferences** | Language, theme (light/dark), volumes (music/SFX), vibrations, forfeit frequency, mode mixing, player order, default mode, default players, ad toggle | User experience personalization | Art. 6.1.f (legitimate interest) | Until reset or uninstallation |
| **Premium purchase rights** | Purchased product IDs, premium mode "purchased" status | Local premium access verification, purchase restoration | Art. 6.1.b (contract performance) | Until deletion or uninstallation |

**This data never leaves your device.** It is not accessible to, read by, or transmitted to the Publisher or any third parties.

### 4.2 Data transmitted to Google LLC (AdMob — integrated advertising)

The Application contains interstitial advertisements served by **Google AdMob** (provider: Google LLC / Google Ireland Ltd). The AdMob SDK, integrated into the Application, may collect and transmit the following data to Google when advertisements are displayed:

| Data | Description | Purpose | Legal basis | Retention |
|------|-------------|---------|-------------|-----------|
| **Advertising ID** | Advertising ID (GAID on Android, IDFA on iOS) | Audience measurement, delivery frequency, ad personalization | **Consent** (Art. 6.1.a) for personalized ads; legitimate interest for non-personalized ads | Per Google policy (see section 8) |
| **IP address** | Connection IP address | Approximate geolocation (region/country), contextual ad selection | Consent / legitimate interest | Per Google policy |
| **Device technical data** | Model, manufacturer, OS version, screen resolution/size, language, time zone | Compatibility, ad performance measurement | Legitimate interest / consent | Per Google policy |
| **Application usage data** | Application name, ad interactions (impressions, clicks), session | Ad performance analysis | Consent / legitimate interest | Per Google policy |
| **Diagnostic data (crash)** | Anonymized technical error reports from AdMob modules | Technical stability | Legitimate interest (Art. 6.1.f) | Per Google policy |

**Consent (UMP banner):** Where applicable (users in the European Union, European Economic Area, United Kingdom, and countries subject to similar regulations), a **Google UMP (User Messaging Platform)** consent banner is displayed at launch. It allows you to:
- **Accept** personalized advertisements (recommended for full functionality);
- **Refuse** personalized advertisements: only **non-personalized** advertisements will be served, with no advertising ID collection or profiling.

You may change your choice at any time via your Google Ads account settings (https://adssettings.google.com), by resetting your device's advertising ID, or by disabling personalization in Android/iOS settings. Google, as an independent controller of this processing, will update the consent status at the next launch.

### 4.3 Data transmitted to stores (in-app purchases)

| Data | Recipient | Purpose | Legal basis | Retention |
|------|-----------|---------|-------------|-----------|
| **Purchase tokens and receipts** | Google (Play Store) | In-app purchase authentication and validation, purchase restoration, fraud prevention | Art. 6.1.b + 6.1.c (store accounting and tax obligations) | Per Google policy; statutory accounting period (10 years) managed by Google |
| **Associated Google account** | Google (Play Store) | Receipt issuance, transaction history | Art. 6.1.b + 6.1.c | Managed by Google |

The Publisher receives and stores **no financial data** (card numbers, payment information) — these are handled exclusively by Google.

### 4.4 Build and distribution technical data (Expo / EAS)

| Data | Recipient | Purpose | Legal basis | Retention |
|------|-----------|---------|-------------|-----------|
| Build logs, project ID, anonymized usage metrics | Expo Inc. (EAS Build, EAS Update) | Building, signing, and distributing Application versions | Art. 6.1.f (legitimate interest) | Per Expo policy (see section 8) |

---

## 5. Data NOT Collected

- **No precise geolocation** (GPS) is used.
- **No access** to contacts, photos, microphone, or camera.
- **No financial data** processed by the Publisher.
- **No centralized user account** — no account identifiers are created by the Publisher.
- **No medical, biometric, racial, religious, or sexual orientation data** is collected.
- The forfeits in "Couple" and "Crazy" modes may reference sensuality between consenting adults, but **no data related to these contents is recorded or transmitted**.

---

## 6. Advertising — Detailed Functionality

### 6.1 Ad types
- **Interstitials:** Displayed at specific moments in the Application (on startup and/or between games), based on default configuration and user preferences.

### 6.2 Personalized vs non-personalized ads
- **Personalized:** Based on the advertising ID, interests, and browsing behavior. Require your consent (UMP banner).
- **Non-personalized:** Based exclusively on context (content type, time, language, approximate IP location). Do not require consent.

### 6.3 No consent
If you decline personalization, the Application remains **fully functional**: only non-personalized advertisements are served. Game modes, scores, and in-app purchases are not affected.

### 6.4 Google policy
Ad delivery is subject to Google's **EU User Consent Policy** and Google's **Privacy Policy**: https://policies.google.com/privacy.

---

## 7. Data Sharing

### 7.1 No commercial sharing with third parties
Your game data is **never sold, rented, or exchanged** for marketing purposes by the Publisher.

### 7.2 Sub-processors and joint controllers

| Partner | Role | Data involved | Relationship type | Location |
|---------|------|---------------|-------------------|----------|
| **Google AdMob** (Google LLC / Google Ireland Ltd) | Ad delivery, audience measurement | Advertising ID, IP, technical data, ad usage data | Independent controller (for ads) | USA / EU |
| **Google Play** (Google LLC) | In-app payments, distribution | Purchase receipts, Google account | Independent controller | USA / EU |
| **Expo Inc. (EAS)** | Build, signing, technical distribution | Build logs, technical metrics | Sub-processor (DPA) | USA |
| **SQLite (on device)** | Local game database storage | Profiles, scores, preferences | No transmission | User's device |

### 7.3 Legal obligations
Data disclosure may only occur pursuant to a **court order, regulatory mandate, or imperative legal obligation** (Art. 6.1.c GDPR).

---

## 8. Transfers Outside the EU

Google and Expo are companies based in the **United States**. Resulting data transfers rely on:
- **Standard Contractual Clauses (SCC)** approved by the European Commission;
- The **EU-US Data Privacy Framework** adequacy decision (since 10 July 2023) for certified entities (Google is certified).

Applicable policies:
- **Google AdMob / Google Play:** https://policies.google.com/privacy
- **Expo / EAS:** https://expo.dev/privacy

---

## 9. Retention Periods

| Data | Period |
|------|--------|
| Profiles, history, preferences (local) | Until manual deletion in the Application or uninstallation |
| AdMob advertising data (ID, impression/click logs) | Per Google policy (generally retained up to 14 months for ad browsing logs and less for reports) |
| Purchase receipts and tokens | Google account lifetime + statutory accounting obligations (10 years) — managed by Google |
| Build logs / metrics (Expo/EAS) | Per Expo policy (30–90 days for execution logs) |

**Immediate local data deletion available:** Options menu → "Reset options" / profile deletion / history clearing. Uninstalling the Application permanently deletes all local data.

---

## 10. Security

- **Local data:** Stored in the Application's secure sandbox (Android app sandbox), with access encryption via Android Keystore for any sensitive keys.
- **Network:** Only connections to Google servers (advertising, purchases) and Expo (updates) are established, encrypted via **TLS**.
- **Purchase authentication:** Validated server-side by the Play Store (Google), with fraud prevention.
- **Code:** The distributed version uses Hermes bytecode; updates are signed (EAS).

---

## 11. Your Rights (Art. 15–22 GDPR)

| Right | How to exercise it |
|-------|---------------------|
| **Access** | View your game data within the Application (profiles, history, options). |
| **Rectification** | Edit names, avatars, preferences directly within the Application. |
| **Erasure** | Delete profiles, clear history, reset options within the Application. |
| **Portability** | Simple local data, JSON export available upon written request. |
| **Restriction** | Not applicable for local data; for advertising data, decline personalization in the UMP banner or Google Ads settings. |
| **Objection** | Uninstall the Application = complete cessation of local data processing; Google Ads settings for advertising. |
| **Withdraw consent** | At any time via the UMP banner, Google Ads settings, or resetting the advertising ID. |
| **Complaint** | You may lodge a complaint with your local data protection authority (e.g., CNIL in France: https://www.cnil.fr/en/complain) |

**Contact to exercise your rights:** faustinlegrand4@gmail.com — response within 30 days.

---

## 12. Minors and Advertising

- The Application is rated **PEGI 16** (not recommended for children under 16) due to references to alcohol consumption and adult themes.
- The Application displays an **age gate** requiring users to confirm legal age before any use.
- In compliance with Google policy: no personalized ads are served to users identified as below the age of consent in their region; family-friendly ads remain available.
- **Google Play Families** users or accounts identified as minors will automatically receive non-personalized or family-appropriate ads.

---

## 13. Cookies / Trackers

- **No cookies** are stored by the Application.
- The Application integrates a **third-party advertising SDK** (AdMob/Google) that uses **advertising identifiers** (Advertising ID) and ad tracking mechanisms in compliance with the GDPR and Google policy.
- **No other trackers** (Firebase Analytics, Google Analytics, Facebook, Adjust, AppsFlyer, etc.) are present.

---

## 14. Changes

Any updates to this Policy will be reflected by a change in version and update date. Users are encouraged to review this page regularly. In the event of a material change, a notification will be displayed within the Application.

---

## 15. Contact

**Email:** faustinlegrand4@gmail.com  
**Postal address:** 9 rue du Pressoir, 80800 Villers-Bretonneux, France  
**Response time:** Maximum 30 days.

For questions related to advertising and your ad choices: https://support.google.com/adsense or your Google Ads account.

---

*Document reviewed as version 2.0 on 2026-09-15 — to be supplemented with your legal information before publication. Recommendation: have this document reviewed by a legal professional if your business scales.*