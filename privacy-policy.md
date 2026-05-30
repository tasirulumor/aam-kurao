# Privacy Policy — আম কুড়াও (Aam Kurao)

**Effective Date:** 30-05-2026
**Last Updated:** 30-05-2026

---

## 1. Introduction

Welcome to **আম কুড়াও (Aam Kurao)** ("we", "our", or "us"). We are committed to protecting your privacy. This Privacy Policy explains what information we collect, how we use it, and your rights regarding your data when you use our mango delivery Android application.

By using Aam Kurao, you agree to the collection and use of information as described in this policy.

---

## 2. Information We Collect

### 2.1 Information You Provide Directly

- **Phone Number:** When you create an account or log in, we collect your mobile phone number. This is used as your unique account identifier.
- **Delivery Address:** When you place an order, we collect your delivery address to fulfill your order.
- **Order Details:** We collect information about the products you order, quantities, prices, and timestamps.

### 2.2 Information Collected Automatically

- **Anonymous Session Data:** Before you create an account, we assign you a temporary anonymous session identifier via Firebase Authentication. This allows us to save your cart and session without requiring you to sign up immediately.
- **Cart Data:** Your current cart contents (product names, quantities, and prices) are stored locally on your device using Android SharedPreferences. This data stays on your device and is not transmitted to our servers unless you place an order.
- **Order History:** Once you place an order, order details are stored in our cloud database (Firebase Firestore) and linked to your account.

### 2.3 Device Information

We may automatically collect basic device information through Firebase services, including:
- Device type and model
- Operating system version
- App version
- Unique device identifiers (used by Firebase internally)

We do **not** collect your precise GPS location, contacts, camera data, or microphone data.

---

## 3. How We Use Your Information

We use the information we collect for the following purposes:

| Purpose | Data Used |
|---|---|
| Creating and managing your account | Phone number |
| Processing and fulfilling your orders | Phone number, delivery address, order details |
| Displaying your order history | Order details |
| Maintaining your cart between sessions | Cart data (stored locally on device) |
| Recovering anonymous carts when you sign up | Anonymous session ID, cart data |
| Improving app performance and fixing bugs | Device information (via Firebase) |
| Preventing fraud and ensuring security | Phone number, session identifiers |

We do **not** use your data for advertising, sell your data to third parties, or use it for any purpose beyond operating the app and processing your orders.

---

## 4. How We Store Your Information

### 4.1 Cloud Storage (Firebase Firestore)
Your account information and order history are stored securely in Google Firebase Firestore, a cloud-hosted NoSQL database. Data is protected by Firebase Security Rules that ensure only authenticated users can access their own data.

### 4.2 Local Device Storage (SharedPreferences)
Your cart data is stored locally on your device using Android SharedPreferences. This data is private to the app and is not accessible to other apps on your device.

### 4.3 Authentication (Firebase Authentication)
Your phone number and session tokens are managed by Firebase Authentication, a service provided by Google LLC. Passwords are never stored by us — all authentication is handled securely by Firebase.

---

## 5. Third-Party Services

Aam Kurao uses the following third-party services that may collect and process your data:

| Service | Provider | Purpose | Privacy Policy |
|---|---|---|---|
| Firebase Authentication | Google LLC | User login via phone number | https://policies.google.com/privacy |
| Firebase Firestore | Google LLC | Storing orders and account data | https://policies.google.com/privacy |
| Google Play Services | Google LLC | App distribution and device services | https://policies.google.com/privacy |

These services are governed by their own privacy policies. We recommend reviewing them.

---

## 6. Data Sharing

We do **not** sell, trade, or rent your personal information to third parties.

We may share your information only in the following limited circumstances:
- **Service Providers:** With Google/Firebase to operate our backend infrastructure.
- **Legal Requirements:** If required by law, court order, or government authority in Bangladesh.
- **Business Transfer:** In the event of a merger, acquisition, or sale of assets, user data may be transferred as part of the transaction.

---

## 7. Data Retention

- **Account Data:** We retain your phone number and account information for as long as your account exists.
- **Order History:** Order records are retained indefinitely so you can access your past purchases.
- **Anonymous Sessions:** Anonymous session data is automatically cleaned up when you sign up (the anonymous UID is merged or discarded) or when you log out (a new anonymous session begins).
- **Cart Data:** Local cart data on your device is cleared when you complete an order or uninstall the app.

You may request deletion of your account and associated data at any time by contacting us (see Section 11).

---

## 8. Children's Privacy

Aam Kurao is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe we have inadvertently collected information from a child, please contact us immediately and we will delete it.

---

## 9. Security

We take reasonable measures to protect your personal information:

- All data transmitted between the app and Firebase is encrypted using HTTPS/TLS.
- Firebase Security Rules restrict database access to authenticated users only.
- We use phone-number-based OTP (one-time password) authentication, eliminating the risk of weak passwords.

However, no method of transmission or storage is 100% secure. We cannot guarantee absolute security of your data.

---

## 10. Your Rights

Depending on applicable law (including the Digital Security Act and proposed Personal Data Protection Act of Bangladesh), you may have the right to:

- **Access** the personal data we hold about you.
- **Correct** inaccurate or incomplete data.
- **Delete** your account and associated personal data.
- **Withdraw consent** for data processing (note: this may limit your ability to use the app).

To exercise any of these rights, please contact us using the information in Section 11.

---

## 11. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy, please contact us:

**App Name:** আম কুড়াও (Aam Kurao)
**Developer/Owner:** Tasirul Umor
**Email:** umortasirul@gmail.com
**Address:** Ahsanullah hall , BUET, Dhaka , Bangladesh

---

## 12. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last Updated" date at the top of this page. We encourage you to review this policy periodically. Continued use of the app after changes constitutes your acceptance of the revised policy.

---

## 13. Governing Law

This Privacy Policy is governed by and construed in accordance with the laws of the **People's Republic of Bangladesh**. Any disputes shall be subject to the exclusive jurisdiction of the courts of Bangladesh.

---

*This privacy policy was prepared for আম কুড়াও (Aam Kurao), a mango delivery application operating in Bangladesh.*
