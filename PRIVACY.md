# Privacy Policy - WandR

**Effective Date:** February 17, 2026
**Last Updated:** February 17, 2026

WandR ("the App") is committed to protecting your privacy. This Privacy Policy explains how the App handles your data.

---

## Who We Are

**Developer:** Adotob LLC
**Contact:** support@adotob.com
**Location:** Maryland, United States
**Website:** https://adotob.com

---

## The Short Version

WandR sends your trip queries and location to our backend to plan routes. We use OpenAI to understand your requests and find locations. Your subscription is managed by Apple and RevenueCat. We don't sell your data or show you ads.

---

## What Data We Collect and Why

### Trip Queries (Required for core functionality)

When you plan a trip, the natural language text you enter (e.g., "Find breweries, 2 hours, motorcycle, from Baltimore") is sent to our backend server hosted on Microsoft Azure.

**What happens to it:**
- Our backend parses your query using OpenAI's API
- OpenAI uses this text to identify activity type, duration, transport, and location
- Your query is used to search for relevant locations and plan a route
- We do not store your queries beyond the duration of the request

### Location Data (Optional — used when you share it)

If you grant location permission, WandR uses your GPS coordinates to automatically set your starting point.

**What happens to it:**
- Your coordinates are sent to our backend as part of the trip planning request
- They are used solely to determine a starting point for your route
- We do not track your location continuously
- We do not store your location beyond the duration of the request
- You can deny location permission and enter a starting location manually

### Subscription and Billing Data

WandR uses **RevenueCat** to manage subscription state and **Apple** to process payments.

**What happens:**
- RevenueCat receives a device identifier and subscription status
- Apple processes all payment information (we never see your payment details)
- RevenueCat stores subscription state to determine your access level (free vs. WandR Pro)

### Usage Data

We track how many trips you've planned (stored locally on your device via UserDefaults) to manage the free tier limit. This data never leaves your device.

---

## What We Do NOT Collect

- ❌ Your name, email, or personal identity
- ❌ Your contacts or address book
- ❌ Your photos or camera
- ❌ Continuous location tracking
- ❌ Browsing history or cross-app tracking
- ❌ Advertising identifiers (IDFA)
- ❌ Crash reports (no Crashlytics or Sentry)

---

## Third-Party Services

### OpenAI
Your trip query text and location name are processed by OpenAI's API to parse intent and find locations. OpenAI's privacy policy applies: https://openai.com/privacy

### Microsoft Azure
Our backend is hosted on Microsoft Azure Container Apps in the East US 2 region. Microsoft's privacy policy applies: https://privacy.microsoft.com

### RevenueCat
RevenueCat manages subscription entitlements. They receive device identifiers and subscription events. RevenueCat's privacy policy applies: https://www.revenuecat.com/privacy

### Apple
Apple processes all in-app purchases and subscription billing. Apple's privacy policy applies: https://www.apple.com/privacy

---

## Data Storage and Retention

| Data | Where Stored | Retention |
|------|-------------|-----------|
| Trip queries | Azure backend (in-memory only) | Deleted after request completes |
| Location coordinates | Azure backend (in-memory only) | Deleted after request completes |
| Usage count (free tier) | Your device (UserDefaults) | Until app is deleted |
| Subscription status | RevenueCat servers | Per RevenueCat's retention policy |

We do not maintain a database of user trips or queries.

---

## Permissions

### Location (Optional)
Used to auto-detect your starting point. You can deny this and type a location manually. Revoke anytime: iOS Settings → Privacy & Security → Location Services → WandR.

### No Other Permissions Required
WandR does not request access to Contacts, Camera, Photos, Microphone, or Calendar.

---

## Your Privacy Rights

### Access
Contact support@adotob.com to request any data we hold associated with your device.

### Deletion
Since we don't store trip data beyond each request, there is minimal data to delete. For subscription data, contact RevenueCat at privacy@revenuecat.com.

### GDPR (EU Users)
Our legal basis for processing your trip query and location is the performance of the service you requested. You may request data deletion by contacting support@adotob.com.

### CCPA (California Users)
We do not sell personal information. We do not share personal information for cross-context behavioral advertising.

### COPPA
WandR is not directed at children under 13. We do not knowingly collect data from children.

---

## Data Security

- All data in transit is encrypted via HTTPS/TLS
- Our Azure backend uses managed identity and Azure Key Vault for secrets
- Payment data is handled entirely by Apple — we never see it
- Trip data is processed in-memory and not persisted to any database

---

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted at this URL with an updated "Last Updated" date. Continued use of the App after changes constitutes acceptance.

---

## Contact Us

Questions about this Privacy Policy?

**Email:** support@adotob.com
**GitHub:** [WandR Community Issues](https://github.com/fabianwilliams/wandr-community/issues)
**Response Time:** Within 48 hours

---

*Last Updated: February 17, 2026*
*Governed by the laws of Maryland, United States*
