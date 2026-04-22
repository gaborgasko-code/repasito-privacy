# Privacy Policy — Repasito

**Last updated:** 22 April 2026

This Privacy Policy explains how the Repasito mobile application ("**Repasito**", "**we**", "**us**") collects, uses, stores and shares personal data when you use the app. Repasito is a homework-checking app intended to be used by a **parent, guardian or teacher** on behalf of a child.

We comply with the EU General Data Protection Regulation (**GDPR**) and, where applicable, the U.S. Children's Online Privacy Protection Act (**COPPA**).

---

## 1. Who is the data controller

The data controller responsible for your data is:

- **Name:** Gabor Gasko
- **Contact email:** gaborgasko@gmail.com

> Replace the placeholders above before publishing. If you operate as an individual, put your full legal name and a contact address you are willing to make public. This is a GDPR requirement — the privacy policy must name a controller.

---

## 2. Who should use Repasito

Repasito is designed to be operated by an **adult** (parent, guardian or teacher). By using the app you confirm that you are at least 18 years old and that you have parental responsibility for, or teaching responsibility over, any child whose homework you scan.

The app is **not directed to children under 13** for independent use. Children may appear in scanned homework content because the app is designed to check their work, but the account and the app controls are operated by the adult.

---

## 3. What data we process

### 3.1 Data stored on your device only

The following data never leaves your phone:

- Photos of your child that you attach to their profile (stored locally in app storage).
- Your preferred app language, onboarding status, preferred teaching method.
- Local cache of your recent scan summaries (last 100 scans) and weekly scan counter.

This data is stored via the device's encrypted local storage and is deleted when you uninstall the app or use the "Clear data" option in Android settings.

### 3.2 Data processed on our servers (Supabase)

When you use the app, the following data is processed on our backend (Supabase, see §5):

- **Account data:** your email address and authentication session (if you sign in).
- **Child profile:** the **name** you enter for a child profile, the active flag and the creation date. We do **not** store the child's photo on our servers — photos stay on your device.
- **Scan history:** the subject, score, number of correct answers and total questions for each scan. We do not store the full homework image on our servers after analysis.
- **Subscription / usage:** your weekly scan counter, plan type, and any promo codes you redeem.

### 3.3 Data sent for AI analysis (Google Gemini)

When you scan homework, the image (as a base64-encoded JPEG) is sent from the app to our Supabase Edge Function, which forwards it to **Google's Gemini API** for analysis. Gemini returns a structured JSON result (transcription, corrections, score, encouragement message) which we then return to the app. We do **not** retain the image after the request; only the structured result and its metadata are stored.

Google processes the image under its own terms — see https://ai.google.dev/gemini-api/terms and https://policies.google.com/privacy.

> ⚠️ **Important for parents:** if the homework image contains the child's handwritten name, school name, or other identifying marks, that information is temporarily transmitted to Google for processing. Consider cropping or covering such details before scanning if you prefer to minimise this.

---

## 4. Why we process your data (legal bases)

| Purpose | Legal basis (GDPR) |
| --- | --- |
| Running the app and analysing homework you submit | Performance of a contract with you (Art. 6(1)(b)) |
| Enforcing weekly scan limits and subscription tiers | Legitimate interest in preventing abuse (Art. 6(1)(f)) |
| Storing your child's profile and scan history | Your consent, given by creating the profile (Art. 6(1)(a)) |
| Complying with legal obligations (tax, accounting, etc.) | Legal obligation (Art. 6(1)(c)) |

We do **not** use your data for advertising, profiling, or training AI models, and we do **not** sell your data to anyone.

---

## 5. Who we share data with (processors)

We share personal data only with the following third-party processors, each under a data-processing agreement:

- **Supabase, Inc.** — hosts the database, authentication and edge functions. https://supabase.com/privacy
- **Google LLC (Gemini API)** — processes homework images to return an analysis. https://policies.google.com/privacy
- **Expo / EAS (Expo Application Services)** — builds and distributes the app. Expo does not receive your personal data during runtime. https://expo.dev/privacy
- **Google Play Store** — distributes the app and processes subscription payments if and when enabled. https://policies.google.com/privacy

We do not share your data with advertisers or analytics providers.

---

## 6. Where your data is processed

Supabase and Google may process your data in the European Union, the United Kingdom, the United States or other countries where they or their sub-processors operate. Transfers outside the EEA are protected by the European Commission's Standard Contractual Clauses.

---

## 7. How long we keep your data

- **Account and child profiles:** until you delete them or delete your account.
- **Scan history:** until you delete it or your account.
- **Backups:** up to 30 days after deletion, after which they are overwritten.
- **Locally cached data:** until you clear the app storage or uninstall the app.

---

## 8. Your rights

Under GDPR you have the right to:

- **Access** the personal data we hold about you.
- **Rectify** inaccurate data.
- **Erase** your data ("right to be forgotten").
- **Restrict** or **object** to our processing.
- **Portability** — receive your data in a machine-readable format.
- **Withdraw consent** at any time.
- **Complain** to the Spanish data protection authority, the AEPD (https://www.aepd.es), or your local supervisory authority.

To exercise any of these rights, contact us at **[YOUR CONTACT EMAIL]**. We will respond within 30 days.

You can also delete your account and all associated data directly from the app: **Profile → Delete account**.

---

## 9. Children's data (COPPA)

Repasito is intended for **adult operators**. If you are a parent or guardian and you believe a child under 13 has created an account or that we have collected data about a child under 13 without verifiable parental consent, contact us at **[YOUR CONTACT EMAIL]** and we will delete the data promptly.

Repasito does not knowingly collect personal data from children under 13 for commercial purposes, does not show targeted advertising, and does not track children across apps or websites.

---

## 10. Security

We protect your data with industry-standard measures:

- TLS encryption for all data in transit.
- Row-Level Security (RLS) in Supabase so that one user cannot read another user's data.
- Server-side environment variables for all credentials.
- No third-party analytics or advertising SDKs.

No system is perfectly secure. If we discover a breach affecting your data, we will notify you and the relevant supervisory authority within 72 hours as required by GDPR Art. 33.

---

## 11. Changes to this policy

We may update this Privacy Policy when we change the app. The "Last updated" date at the top of this page will reflect the most recent change. For material changes we will notify you in-app before the change takes effect.

---

## 12. Contact

If you have any questions about this Privacy Policy or our handling of your data, contact us at:

gaborgasko@gmail.com
