# Privacy Policy

**Last updated:** April 28, 2026

This Privacy Policy describes how **PersonaX AI** ("we", "us", or "our") collects, uses, and shares information about you when you use the PersonaX AI mobile application and related services (the "App").

If you do not agree with this Policy, please do not use the App.

---

## 1. Who we are

PersonaX AI is operated by Joben Barrera, an independent developer based in the Republic of the Philippines.

For any questions about this Policy, contact us at **jobenbarrera@gmail.com**.

---

## 2. Information we collect

### 2.1 Information you provide

- **Account information** — your email address and a password (stored as a salted hash by our authentication provider; we never see your plaintext password).
- **Profile data** — your display name, optional profile picture, theme preferences, and onboarding answers used to personalize your AI assistants.
- **Assistant configuration** — system prompts, knowledge documents, and capability settings you configure for each assistant you create.
- **Conversation content** — messages you send to your assistants and the responses they generate.
- **Uploaded files** — any documents, images, or other files you attach to conversations.
- **Integration credentials** — when you connect a third-party service (e.g. Telegram, Discord), we store the access tokens or webhook URLs needed to operate that integration.

### 2.2 Information collected automatically

- **Device & log data** — IP address (transient, not retained), device type, OS version, app version, and basic crash diagnostics, used to troubleshoot bugs.
- **Usage data** — credit consumption events, API request counts, and timestamps used to enforce tier limits.

### 2.3 Information from third parties

If you sign in via an OAuth provider in the future, we may receive your email and profile data from that provider. (At the date of this Policy, only email/password sign-in is supported.)

---

## 3. How we use your information

We use the information described above to:

- Authenticate you and keep your account secure.
- Provide the core features of the App: creating, training, and chatting with AI assistants.
- Forward your prompts and uploaded content to AI providers (see §4) so they can generate responses.
- Persist your conversations so you can return to them later.
- Enforce free-tier credit limits and prevent abuse.
- Communicate with you about your account (e.g. password reset emails, security notices).
- Diagnose and fix bugs and crashes.

We do **not** sell your personal information. We do **not** use your conversation content to train any AI model.

---

## 4. Third-party processors

The App relies on the following service providers, each of whom processes data on our behalf:

| Provider  | What they process | Where to read more |
|-----------|--------------------|--------------------|
| **Supabase** | Account auth, database, file storage | https://supabase.com/privacy |
| **OpenAI** | Your prompts, conversation context, and uploaded content for AI inference (chat, image generation, code interpreter, web search) | https://openai.com/policies/privacy-policy |
| **Telegram** *(only if you connect a Telegram integration)* | Bot token + your messages forwarded between Telegram and the App | https://telegram.org/privacy |
| **Discord** *(only if you connect a Discord integration)* | OAuth token + slash command interactions | https://discord.com/privacy |

When you send a message to an assistant, the message content (and any attached files) is transmitted to OpenAI for processing. OpenAI's API terms state they do not use API inputs to train their models, and inputs are retained for up to 30 days for abuse monitoring before deletion.

---

## 5. Data retention

- **Account & profile data** — retained for as long as your account is active.
- **Conversations & uploads** — retained for as long as your account is active, or until you delete them in-app.
- **Diagnostic logs** — retained for up to 30 days, then automatically purged.
- **Account deletion** — when you delete your account from within the App (Profile → Danger Zone → Delete account), all of the above is permanently removed within 30 days, except where we are required to retain certain records by law.

---

## 6. Your rights

Depending on where you live, you may have the right to:

- **Access** the information we hold about you.
- **Correct** inaccurate information (most fields are editable from the App).
- **Delete** your account and all associated data (use the in-app account deletion flow, or contact us).
- **Object** to certain processing.
- **Withdraw consent** at any time by deleting your account.

To exercise any of these rights, email **jobenbarrera@gmail.com** with the subject line "Privacy Request".

We will respond within 30 days.

---

## 7. Children

The App is not intended for children under 13. We do not knowingly collect personal information from anyone under 13. If you believe a child under 13 has provided us with personal information, please contact us so we can delete it.

---

## 8. Security

We implement reasonable safeguards to protect your information:

- All network traffic is encrypted in transit (HTTPS / TLS).
- Passwords are stored as salted hashes; we never see your plaintext password.
- Database access is restricted by row-level security policies — your data is only accessible to your authenticated session.
- Integration tokens are stored encrypted at rest.

No system is perfectly secure. If we become aware of a data breach affecting your information, we will notify you within 72 hours of confirming the breach.

---

## 9. International transfers

Our infrastructure providers (Supabase, OpenAI) operate servers in the United States and other regions. By using the App, you consent to your information being transferred, stored, and processed outside the Philippines, including in jurisdictions that may have different data protection laws.

---

## 10. Changes to this Policy

We may update this Policy from time to time. When we do, we will update the "Last updated" date at the top, and — if the change is material — notify you in the App or by email. Continued use of the App after a change indicates acceptance of the updated Policy.

---

## 11. Governing law

This Policy is governed by the laws of the **Republic of the Philippines**. Any dispute arising out of or relating to this Policy shall be resolved by the competent courts of the Philippines.

---

## 12. Contact

**Email:** jobenbarrera@gmail.com
**Subject prefix for privacy requests:** Privacy Request
