# FloorCraft Privacy Policy

**Last updated:** 12 November 2026
**Applies to:** FloorCraft (iOS) and FloorCraft Pro (macOS)

## Who we are

FloorCraft is a floor-plan scanning and editing app developed by **Umoview NZ Ltd**, a New Zealand registered company. Umoview NZ Ltd is the data controller for the information described in this policy. If you have any questions about this policy or how we handle your information, email **FloorCraftPro@gmail.com**.

## What this policy covers

This policy explains what personal information FloorCraft and FloorCraft Pro collect, how we use it, who else sees it, and the choices you have. It applies to the iOS app, the macOS app, and any data stored in our cloud (Supabase) on your behalf.

## What we collect

### When you create an account
- **Email address** — captured via Sign in with Apple. If you use "Hide My Email" on Apple's prompt, we only ever see a private relay address.
- **Apple user identifier** — a stable per-app ID from Apple that lets us recognise you next time you sign in.
- **A FloorCraft user ID** — we generate a unique UUID for your account inside our database.

### When you scan or edit plans
- **Floor plan data** — the rooms, walls, doors, windows, features and dimensions your scans produce, plus any edits, notes, or reference images you add.
- **Scan metadata** — property name/address you enter, when the scan was made or last modified.
- **Thumbnail images** — a small preview rendered from your plan for the library view.

These are all things **you** create. We store them so they sync across your iPhone and Mac. We do not look at the content of your scans and we do not share them with anyone except as described below.

### When you subscribe or buy a pack
- **Subscription status** — whether you have an active Pro or Team subscription, when it renews or expires, which products you purchased.
- **Pack credits** — a ledger of pack-export grants and uses tied to your FloorCraft user ID.

Payment information (card details, Apple ID) is handled by **Apple** through the App Store. We never see your card or Apple ID password.

### On-device only — never sent to us
- **LiDAR scanning data** — the raw depth data your iPhone's LiDAR produces while scanning is processed entirely on your device by Apple's RoomPlan framework. Only the resulting simplified floor plan (rooms, walls, openings) is saved and synced. Raw depth frames are not uploaded.

## Third-party services we use

- **Apple (Sign in with Apple, StoreKit, iCloud Keychain)** — authentication, payments, session storage. Apple's privacy policy applies to the data they process on our behalf.
- **Supabase (Supabase Inc., USA)** — stores your account record, scans, teams, and subscription ledger. Data is held in Supabase's managed Postgres and object storage.
- **RevenueCat (RevenueCat Inc., USA)** — validates your App Store purchases and tracks your subscription state so entitlements work across iPhone and Mac.

We do not use third-party analytics, advertising SDKs, or trackers. We do not share your personal information with anyone for marketing.

## How we use your information

- **To provide the service** — sign you in, store your scans, sync between your devices, enforce subscription limits, calculate pack credits.
- **To support you** — respond to questions you send to FloorCraftPro@gmail.com.
- **To meet legal obligations** — comply with lawful requests from authorities, enforce our terms.

We do not use your information to train AI models.

## How we store and protect your information

- Your Supabase account, scans, and subscription state are stored in managed Postgres and storage buckets protected by row-level security rules — your records are only readable by your own authenticated session.
- Session tokens are stored in iCloud Keychain on your device so you stay signed in across iPhone and Mac.
- All network communication with Supabase and RevenueCat uses TLS.

## How long we keep your information

- **Account and scans** — until you ask us to delete them. Deleted scans are marked tombstoned for a short period so other devices can sync the deletion, then removed from storage.
- **Subscription ledger** — kept as long as your account exists for accurate billing history. A compliant audit trail of grants and uses is required by Apple's receipt reconciliation.
- **Logs** — Supabase and RevenueCat retain transient server logs for troubleshooting as per their own policies. We don't retain additional logs on our side.

## Your rights

Depending on where you live, you may have the right to:

- **Access** a copy of the information we hold about you.
- **Correct** inaccurate information.
- **Delete** your account and all associated data. You can do this in-app: on iPhone open the Account sheet and tap **Delete account**; on Mac choose **FloorCraft → Delete Account…** from the menu. The deletion takes effect immediately. If you prefer, email **FloorCraftPro@gmail.com** from the address on your account and we'll complete the deletion within 30 days.
- **Port** your data to another service.
- **Object** or **restrict** certain uses of your information.
- **Withdraw consent** where we rely on consent as the legal basis.

To exercise any of these, email **FloorCraftPro@gmail.com** from the address on your account. We'll respond within 30 days.

If you're in the EU/UK, we process your data under the GDPR. If you're in New Zealand, the Privacy Act 2020 applies. If you're in California, the CCPA applies — note that we do not sell personal information.

## Children

FloorCraft is not directed at children under 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us information, email us and we will delete it.

## Changes to this policy

If we update this policy, we'll change the "Last updated" date at the top and, for significant changes, notify you in-app or by email. Continued use after the effective date means you accept the updated policy.

## Contact

**FloorCraftPro@gmail.com**

For urgent privacy concerns, write "PRIVACY" in the subject line so it gets routed quickly.
