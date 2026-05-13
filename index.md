# Buzzed — Privacy Policy

**Last updated:** 2026-05-13

Buzzed is an iOS cocktail recipe and bar utility app. This policy explains what data Buzzed handles and what it does not.

---

## Who we are

Buzzed is developed and operated by Carl Heijbel, an independent iOS developer based in Sweden. We are reachable at the email address listed under **Contact** below.

---

## What data we collect

**None.** Buzzed does not have a backend server, does not create user accounts, and does not collect any data from your device.

Everything you do in Buzzed is stored locally on your device using the iOS UserDefaults system:

- The cocktails you save as favourites
- The custom cocktails you author in "Make Your Buzz"
- The drinks you log in the Buzz Meter (BAC tracker)
- Your acknowledgment of the BAC tracker disclaimer ("buzzed.bac.disclaimerAcknowledged")
- Your in-app preferences

All of this lives only on your device. It is never transmitted to us, to Apple beyond standard iOS backup behaviour, or to any third party.

---

## What we don't collect

Buzzed does **not** collect, transmit, or store any of the following:

- Your name, email address, phone number, postal address, or any contact information
- Your location — precise or approximate
- Your photos, contacts, calendar, microphone, or camera
- Your device identifiers (IDFA, advertising ID, etc.)
- Analytics events, crash reports, or usage telemetry of any kind
- Cookies or web-style tracking identifiers
- Health data, fitness data, or HealthKit information

Buzzed does not display advertisements and does not share data with advertisers.

---

## Third-party services

Buzzed uses one third-party service: **Google's Gemini API**, accessed via Firebase AI Logic (the official Google SDK for iOS), to generate cocktail recipes for novel ingredient combinations that fall outside the app's bundled cocktail database of 80+ classic cocktails.

When you tap "Generate" with an ingredient combination Buzzed does not recognise from its database, the following information is sent to Google:

- The names of the ingredients you selected (e.g. "Tequila, lime juice, agave syrup")
- A structured free-text prompt asking for a cocktail recipe based on those ingredients

The following is **not** sent to Google:

- Your identity, device identifier, email address, account, or any personal information
- Your saved recipes, your Buzz Meter log, or any other locally-stored data
- Your location

Note on IP addresses: Google's infrastructure captures the IP address of every HTTPS request as a standard networking function. Buzzed has no control over this and does not log, store, or use your IP address itself.

Google's privacy policy governs how Google handles this transient inference data: https://policies.google.com/privacy. Google's responsible AI policy is here: https://ai.google.dev/responsible.

All other Buzzed features — the bundled cocktail database, the Classics list, the Make Your Buzz authoring flow, the procedural cocktail glass visual, the Buzz Meter, and the party games — work **fully offline** and contact no external servers.

---

## Data retention

**On your device:** Local data (saved cocktails, custom recipes, Buzz Meter log entries, and preferences) persists until you delete the Buzzed app. Deleting the app removes all of this data automatically; iOS does not retain app container data after deletion.

**On our servers:** None. We have no servers and retain no user data.

**On Google's side:** Google's data retention for AI inference requests is governed by Google's own privacy policy. As of this writing, Google states that free-tier Gemini API inputs may be used for service improvement subject to Google's data policies. Because Buzzed sends no personally identifiable information, the privacy impact of any such retention is minimal. For questions about Google's retention practices, contact Google directly via the privacy link above.

---

## Your rights

Because Buzzed collects no personal data, traditional data-subject rights (right to access, right to erasure, right to portability) have no application — there is nothing held by us to access, delete, or transfer.

To delete all Buzzed-related data from your device, delete the Buzzed app. iOS removes all of the app's local storage container automatically at that point.

**GDPR / CCPA users:** Buzzed is not a data controller or processor with respect to your personal data, because no such data is collected or processed by Buzzed. If Google's processing of the transient inference inputs is in scope for your jurisdiction, please contact Google directly using the privacy URL in the Third-party services section above.

---

## Children

Buzzed is rated 17+ on the App Store because it is an alcohol-themed application. Buzzed is not directed at children and should not be used by anyone under the legal drinking age in their jurisdiction. We do not knowingly collect data from anyone, including children.

---

## Contact

For questions or concerns about this privacy policy, contact the developer at:

**heijbelcarl@gmail.com**

---

## Changes to this policy

If this policy changes in a material way, the "Last updated" date at the top of the document will be revised. Material changes will be summarised in the app's App Store release notes for the version that introduces them. Continued use of Buzzed after any change constitutes acceptance of the revised policy.

---

## Governing law

This policy is governed by the laws of Sweden, the developer's country of residence. Disputes arising from this policy will be subject to the jurisdiction of the Swedish courts.
