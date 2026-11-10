# Privacy Policy

**Fera: Meal Planner & AI-Chef**

This policy explains what Fera collects, why, who we share it with, and the choices and rights you have. Fera is a meal planner built local-first: your planning data stays on your device, and we collect only what we need to run the Service.

**Last updated:** November 10, 2026 **Effective date:** November 10, 2026

This Privacy Policy describes how Daniil Leonov ("Fera," "we," "us," "our"), the developer of Fera: Meal Planner & AI-Chef, handles personal information when you use the Fera mobile app and website (the "Service"). It applies to users of the Service in the United States and, where applicable, to users protected by the GDPR and CCPA/CPRA. For the purposes of the GDPR, Daniil Leonov is the data controller.

## 1. Information we collect

### Information you provide

- **Account details:** your email address and name, and the identifiers we receive when you sign in with Apple or Google (such as a unique account ID and the email you authorize). Sign-in is handled by Clerk, our authentication provider, which keeps this account record. See Section 3.
- **Planning data:** the meal plans you build, recipes you save, your budget, and preferences (e.g. dietary preferences and allergens you set, macro and nutrition goals, household size, and the store you choose). Planning data is stored locally on your device — see Section 4.
- **Location for finding stores (optional):** when you look for grocery stores near you, the app asks for permission to use your device's location. If you allow it, the app reads your location once, rounds the coordinates to two decimal places (about 1 km) on your device, and sends them through Fera's backend to Kroger to find nearby stores. If you decline, you can enter a ZIP code instead. Neither your coordinates nor your ZIP code are stored on our servers, and the app does not track your location in the background.
- **Recipe content and photos:** recipes and links you import, photos you add, and ingredient photos you choose to scan.
- **AI Chef requests:** the questions and requests you send to the AI Chef, together with the preferences needed to answer them.
- **Purchase information:** subscription product, purchase and renewal dates, trial status, and entitlement. Apple processes payment details; we do not receive your card number.
- **Communications:** messages you send us for support or feedback.

### Information collected automatically

- **Device and usage data:** device type and operating system, app version, language, general interaction events, crash logs, and approximate (non-precise) location inferred from your IP address.
- **Sign-in sessions:** when you sign in, Clerk records the session, including the device and IP address used, so your sign-in stays secure and you can sign out of all devices from the app.
- **Advertising identifiers:** where you permit it through Apple's App Tracking Transparency prompt, we and our attribution partners may process advertising identifiers (such as Apple's IDFA) to measure our marketing campaigns. See Section 7.

Dietary choices, allergies, nutrition goals, and food preferences can reveal health-related information. We use this information only to personalize meal planning. Fera does not provide medical advice.

## 2. How we use your information

- To create and maintain your account and verify your subscription.
- To generate meal plans, recipe ideas, and AI Chef answers, and to build your grocery list.
- To find grocery stores near you and show grocery prices for your plan.
- To operate, secure, debug, and improve the Service.
- To measure the performance of our marketing campaigns (with your permission where required).
- To respond to your support requests and send service-related notices.
- To comply with legal obligations and enforce our Terms of Service.

Where the GDPR applies, our legal bases are: performance of a contract (running the Service you subscribe to), our legitimate interests (securing and improving the Service), your consent (for location access, advertising attribution, and website analytics), and compliance with legal obligations.

## 3. How we share information

We do not sell your personal information for money. We share data only with service providers and partners who help us run the Service:

- **Clerk** — our authentication provider. It handles sign-in with Apple and Google and stores your account record: your email address, name, Apple or Google account identifier, and sign-in sessions (including the device and IP address used). When you delete your account, your Clerk account is deleted.
- **Supabase** — hosts Fera's backend functions. They verify your sign-in, check your subscription, apply usage limits, and forward AI and grocery requests. Supabase stores only your account ID, your subscription status, and usage counters. It does not store your meal plans, recipes, photos, or location.
- **Apple and Google Sign-In** — identity providers when you choose to sign in with them.
- **Kroger** — grocery store and price data. When you search for stores, your rounded coordinates or the ZIP code you entered are sent to Kroger through our backend. When you view prices, the names of the items on your grocery list and the store you chose are sent. Kroger does not receive your name, email address, or account ID.
- **PostHog** — product analytics linked to your account ID, including app interactions, searches, onboarding preferences, and subscription events. Website analytics require cookie consent.
- **RevenueCat** — subscription validation and management, including your account ID, App Store transactions, and entitlement status.
- **Google Gemini** — AI processing for the AI Chef, meal plan generation, ingredient recognition from food photos, and extraction of recipes from pasted text or linked pages. See "AI features, photo scans, and recipe imports" below.
- **TikTok** — advertising attribution for our marketing campaigns, including device identifiers and selected events such as registration, login, trial start, and purchase. Collection requires your App Tracking Transparency permission; denying or withdrawing it stops further TikTok events.

Under certain privacy laws (e.g. the CCPA/CPRA), sharing data with advertising partners for cross-context behavioral advertising may be considered a "sale" or "share." You can opt out — see Sections 5 and 7. We may also disclose information to comply with law or to protect rights, safety, and security.

### AI features, photo scans, and recipe imports

The AI Chef, meal plan generation, photo scanning, and recipe import use Google Gemini as an AI service provider. Content is sent through Fera's backend only when you use these features. You must review and accept this Privacy Policy before creating an account.

- **AI Chef and meal plans:** your requests and the relevant preferences (such as dietary preferences, allergens, nutrition goals, and budget) are sent to Google Gemini to generate a response. Responses are stored on your device.
- **Photo scans:** the food photos you select are sent to Google Gemini to identify ingredients. We do not store these photos on our servers. Detected ingredients are saved on your device.
- **Recipe imports:** pasted recipe text, or recipe text extracted from a link you provide, is sent to Google Gemini to identify the recipe, ingredients, instructions, and other details. Following a link also requests content from the source website. Imported recipes are saved on your device.
- **Your choices:** photo scanning and recipe import are optional — you can enter ingredients and recipes by hand. To withdraw consent or raise a privacy concern, contact heisleonov@gmail.com.

Photos and text may contain personal information, so include only the food or recipe content you want processed. We use Google's paid Gemini API services. Under Google's terms for these services, Google does not use prompts, files, or responses to improve its products or train its models. Google logs prompts and responses for a limited period (currently up to 55 days) solely to detect abuse and for legally required disclosures. Withdrawing consent prevents future transfers but does not undo processing that has already occurred. See the [Gemini API Terms of Service](https://ai.google.dev/gemini-api/terms) for the provider's current terms.

Advertising attribution uses a separate Apple system permission (App Tracking Transparency); accepting this policy does not grant it.

## 4. Data storage and retention

Fera is local-first. Your meal plans, recipes, photos, grocery lists, preferences, and AI responses are stored only on your device. We do not keep copies of this data on our servers.

Because this data lives on your device, deleting the Fera app deletes it, and it cannot be recovered by us. We plan to add optional iCloud sync so your data can be kept across reinstalls and devices. If enabled, that data will be stored in your own iCloud account under Apple's terms, and we will update this policy before the feature launches.

Data held by us and our providers (your account record in Clerk, your subscription status and usage counters in Supabase, analytics, and subscription records) is kept for as long as your account is active or as needed to provide the Service. If you delete your account, we delete your Clerk account and our Supabase records, and delete or de-identify the remaining data within a commercially reasonable period (typically within 30 days), including requesting erasure of account-linked analytics and subscription-provider profiles. Processor requests may complete asynchronously. Apple sign-in authorization is revoked as part of deletion. Records we must keep for legal, accounting, or security reasons may remain for their required retention periods.

You can delete your account in the app under Profile → Account → Delete Account. Deleting your account or the app does not cancel your App Store subscription — cancel it separately in your App Store account settings.

## 5. Your rights

Depending on where you live, you may have the right to access, correct, export (portability), or delete your personal data, to object to or restrict certain processing, and to withdraw consent. If you are in the EEA/UK (GDPR) or California (CCPA/CPRA), these rights apply to you, including the right not to be discriminated against for exercising them. EEA/UK users may also lodge a complaint with their local data protection authority.

- **Access and export:** request a copy of the data we hold about you. Data stored only on your device is already under your control.
- **Deletion:** delete your account in the app or by request.
- **Location:** you can turn off location access for Fera at any time in Settings → Privacy & Security → Location Services, and enter a ZIP code instead.
- **Opt out of ad tracking / "sale" or "share":** use your device tracking controls described in Section 7.

To exercise any right, email heisleonov@gmail.com. We may need to verify your identity first.

## 6. Children's privacy

Fera is not directed to children. The Service is intended for users aged 13 and older, and we do not knowingly collect personal information from children under 13 (consistent with COPPA). If you believe a child under 13 has provided us personal information, contact heisleonov@gmail.com and we will delete it.

## 7. App Tracking Transparency and tracking choices

On iOS, we ask for your permission through Apple's App Tracking Transparency (ATT) prompt before tracking you across apps and websites owned by other companies. If you decline, we will not use TikTok to collect your identifiers or app activity for advertising measurement. You can change this at any time in Settings → Privacy & Security → Tracking. On the web, non-essential analytics load only after you consent via our cookie banner.

## 8. International data transfers

We and our service providers may process and store information in countries other than where you live, including the United States. Where required, we rely on appropriate safeguards (such as the EU Standard Contractual Clauses) to protect your information when it is transferred internationally.

## 9. Cookies and similar technologies

Our website uses essential cookies to function and, with your consent, analytics cookies. You can change your choices at any time through the cookie banner.

## 10. Security

We use reasonable technical and organizational measures to protect your information, including encryption in transit and access controls. Data stored on your device is protected by your device's security features. No method of transmission or storage is completely secure, so we cannot guarantee absolute security.

## 11. Changes to this policy

We may update this policy from time to time. We will revise the "Last updated" date above and, for material changes, provide additional notice where required.

## 12. Contact us

Questions or requests about privacy? Email heisleonov@gmail.com.
