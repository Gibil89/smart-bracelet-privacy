# Privacy Policy for Smart Bracelet

**Last updated:** September 2026

This Privacy Policy describes how the "Smart Bracelet" application (for mobile and Wear OS) collects, uses, and protects your information.

## 1. Information We Do Not Collect
Our application is built on a privacy-first, Peer-to-Peer (P2P) architecture. We **do not** have a centralized database, and we **do not** collect, store, or share your personal information (such as your name, email address, or location).

## 2. Permissions and Device Data
To provide its core functionality, the app requires certain on-device permissions:
*   **Camera:** Used strictly locally on your device to scan the pairing QR code. Images are never recorded, saved, or transmitted to any server.
*   **Internet / Network State:** Required to send and receive haptic feedback and animations via Google Firebase Cloud Messaging (FCM).

## 3. Communication Data (Tokens)
To pair your devices, the app generates an FCM (Firebase Cloud Messaging) token. This token is an anonymous string of characters used to route messages between you and your partner. 
*   These tokens are exchanged directly between users via QR code.
*   Messages are routed temporarily through a secure Cloudflare Worker solely for delivery purposes. Message content (animation IDs, haptic patterns) is not stored permanently.

## 4. In-App Purchases
Our application offers premium features via Google Play Billing. All payment processing is handled securely by Google. We do not have access to your credit card information, billing address, or personal financial data. Your premium status is verified locally and through Google's APIs.

## 5. Third-Party Services
The app uses the following third-party services, which have their own privacy policies:
*   **Google Play Services & Firebase Cloud Messaging** (for message delivery and billing)
*   **Cloudflare** (for secure message routing)

## 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes. 

## 7. Contact Us
If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at: 89.toth.tamas@gmail.com
