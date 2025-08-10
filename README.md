# PushPal Privacy Policy

Last updated: 2025-08-08

PushPal ("the App") is provided by [Your Company/Name] ("we", "us", or "our"). This policy explains what information we collect, how we use it, and your choices.

We designed PushPal to collect only what is necessary to provide core features like creating posts, chatting, and receiving notifications. We do not sell your personal data and we do not run third‑party advertising SDKs.

## 1) Information We Collect

- Personal Information you provide
  - Account details such as email address, display name, and profile information you add (e.g., bio, profile photo).
- User‑Generated Content (UGC)
  - Photos and images you capture with the camera or select from your gallery for profiles, posts, community posts, and chat messages.
  - Text content such as posts, comments, and chat messages.
- Device & App Information (minimal)
  - Basic device and app information (device model, OS version, app version) transmitted in the normal course of network requests.
- Push Notifications
  - A device push token (from Firebase Cloud Messaging) so we can deliver notifications. The token may be stored with your user account and refreshed periodically. We do not use the token for tracking or advertising.
- Location (optional)
  - If you grant location permission, we may access approximate or precise location to enable location‑aware features (e.g., surfacing relevant communities or tagging content). Location is accessed only when you use features that request it and is not collected in the background for advertising or tracking.

## 2) How We Use Information

- Provide core features: creating and viewing posts, communities, and messages; uploading media; sending and receiving push notifications.
- Operate, maintain, and improve the App, including performance, reliability, and user experience.
- Safety, security, and integrity: prevent abuse, troubleshoot issues, and comply with legal obligations.

We do not use your data for third‑party targeted advertising. We do not sell personal information.

## 3) Data Storage and Processing

- Backend services
  - We use Supabase to host our database and file storage (media uploads such as images). Your data is stored on Supabase infrastructure in the region configured for our project. Media you upload is stored in private buckets (e.g., for posts, chat images) with access controls. Data is encrypted in transit (HTTPS). Encryption at rest is provided by our hosting providers.
  - We use Firebase Cloud Messaging (Google) to deliver push notifications. FCM processes your device push token and message delivery metadata.
- On‑device storage
  - Photos and content remain on your device unless you choose to upload/share them. If you remove content in the App, associated cloud copies are deleted as part of that action (subject to caching and backups by our providers).

## 4) Retention

- Account data is retained while your account is active. You may request deletion of your account, after which we delete or anonymize personal data within a reasonable period unless retention is required by law or for legitimate business purposes (e.g., security, fraud prevention, dispute resolution).
- User‑generated content (posts, messages, media) is retained until you delete it or delete your account. Some data may persist in backups for a limited time.

## 5) Sharing of Information

We do not sell your data. We share information only in these cases:
- Service Providers and Infrastructure
  - Supabase (database and storage) to store your account data and media you choose to upload.
  - Firebase Cloud Messaging by Google to send push notifications to your device.
  - Other providers we may use for hosting, content delivery, or email support, all bound by contractual confidentiality and data protection obligations.
- Legal, safety, and rights
  - When required by applicable law, lawful requests, or to protect the rights, safety, and property of users, the public, or us.

## 6) Permissions and Platform Disclosures

Android permissions requested by the App (as declared in the Android manifest):
- android.permission.CAMERA: Used only when you choose to capture photos within the App (e.g., profile, posts, chat, and bug reports). Not used in the background.
- android.permission.READ_EXTERNAL_STORAGE / WRITE_EXTERNAL_STORAGE (legacy devices): Used to let you pick images from your gallery for upload. On modern Android versions, the App uses scoped access so we only access the specific items you select.
- android.permission.ACCESS_COARSE_LOCATION / android.permission.ACCESS_FINE_LOCATION (optional): If granted, used to enable location‑aware features (e.g., surfacing relevant communities or tags). Not used for background tracking or advertising.
- android.permission.INTERNET and android.permission.ACCESS_NETWORK_STATE: Required for network connectivity.

iOS permission disclosures:
- Camera access is requested to capture photos you choose to upload.
- Photo Library access is requested to allow you to pick images for upload.

You can deny or revoke these permissions in your device settings. Some features may not work without the respective permission.

## 7) Children’s Privacy

The App is not directed to children under 13. If you believe a child has provided personal information, please contact us and we will take steps to delete such information.

## 8) Your Choices and Rights

- Access and updates: You can view and update certain profile information in the App.
- Permissions: You can deny or revoke camera, photos, and location permissions at any time in your device settings.
- Content deletion: You can delete posts, images, and messages you control. Cloud copies associated with deleted items will be removed subject to provider backup windows.
- Account deletion: You can request account deletion from within the App (if available) or by contacting us at the email below.

## 9) Security

We use reasonable administrative, technical, and organizational measures to protect your information. No method of transmission or storage is 100% secure, but we aim to minimize risk and apply industry best practices. All data transmitted between the App and our servers is encrypted in transit (HTTPS).

## 10) International Transfers

Your information may be processed and stored in countries other than your own. Where applicable, we implement appropriate safeguards to protect your information consistent with applicable law.

## 11) Changes to This Policy

We may update this policy from time to time. We will update the "Last updated" date above and, where required, provide additional notice in the App.

## 12) Contact Us

- Email: [your-contact@email.com]
- [Business Name]
- [Postal Address (optional)]

---

### Summary of Data Practices (for app store disclosure)
- Data collection: Account info you provide; UGC (posts, messages, images) you choose to upload; optional location if enabled; push token for notifications. No third‑party advertising SDKs.
- Data sharing: With service providers (Supabase, Firebase) only to operate the App. No data sales.
- Purpose of use: App functionality, communications, security, and improvement.
- Security: Encryption in transit; provider‑managed encryption at rest.
- Retention and deletion: Retained while account active; deletion available for account and content. 
