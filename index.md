---
layout: default
title: LinguaFlow Privacy Policy
---

# Privacy Policy for LinguaFlow

**Last updated: 2 August 2026**

LinguaFlow ("the app") is a Mandarin Chinese learning app that turns videos you
already own into interactive lessons. This policy explains exactly what the app
collects, what it does not, and what control you have.

The short version: **your videos, audio and transcripts never leave your
device.** The only things that reach a server are your account email (if you
choose to sign in), a single sentence at a time when you explicitly ask for an
AI explanation, and your subscription status.

---

## Who we are

LinguaFlow is developed by I Nyoman Surya Pradipta.

**Contact:** suryapradipta@icloud.com

We are the data controller for the limited personal data described below.

---

## What stays on your device

The core of LinguaFlow runs entirely offline. The following **never leave your
device and are never uploaded to us or anyone else**:

- **Your video files.** Imported videos are copied into the app's private
  storage and stay there.
- **Extracted audio.** Created locally to run speech recognition, stored
  locally.
- **Transcripts and translations.** Produced on-device by Apple's Speech and
  Translation frameworks.
- **Your saved words, sentences, review history and study statistics.** All of
  this lives in a local database on your device.
- **Your pronunciation recordings.** Practice recordings are scored on-device
  and are not uploaded.

Deleting the app deletes all of this permanently.

---

## What we collect

### 1. Account information — only if you sign in

LinguaFlow can be used **without an account** in guest mode. If you choose to
use Sign in with Apple, we receive:

- **Your email address** (or Apple's private relay address, if you chose to
  hide your email)
- **A user identifier** used to associate your account with your subscription
  and daily usage allowance

We use this only to identify your account, apply your subscription, and enforce
the free tier's daily AI limit. **We never use it for advertising and never
sell it.**

Authentication and account storage are handled by **Supabase** (Supabase Inc.),
acting as our data processor.

### 2. Text you explicitly send to AI features

When you tap **Explain** on a subtitle line, or request **pronunciation
feedback**, the app sends to our server:

- The single sentence being explained (and, for pronunciation, what the speech
  recogniser heard you say)
- Your approximate learner level and chosen language

That text is forwarded to **OpenAI** to generate the explanation, and the
result is cached on your device so repeat views cost nothing.

**This only happens when you actively tap an AI feature.** No audio is sent —
only text. Video, audio files and full transcripts are never sent.

OpenAI processes this data as our provider under their API terms and, per those
terms, **does not use it to train their models**.

### 3. Subscription status

If you subscribe to LinguaFlow Pro, Apple processes the payment. We never see
your payment details. We receive and store only the transaction identifier and
whether your subscription is active, so the app can unlock Pro features across
your devices.

### 4. Feedback you send us

If you use **Send Feedback**, your email app opens with a prefilled message
containing your app version, iOS version and device model. You can edit or
remove any of it before sending. We receive whatever you choose to send.

---

## What we do NOT do

- We do **not** track you across other apps or websites.
- We include **no** advertising SDKs, and **no** analytics or crash-reporting
  SDKs.
- We do **not** sell or rent your personal data to anyone, ever.
- We do **not** create advertising profiles.
- We do **not** access your photo library beyond the specific video you pick.

---

## Permissions the app asks for

| Permission | Why | Optional? |
|---|---|---|
| **Microphone** | Recording your voice for shadowing practice and pronunciation scoring | Yes — only needed for Practice |
| **Speech Recognition** | Transcribing video audio and scoring pronunciation | Yes — needed to process videos |
| **Photo library** | Only the specific video you choose to import | Yes — you can import from Files instead |

### A note on speech recognition

LinguaFlow uses **on-device speech recognition by default**. If the on-device
Chinese model is unavailable, the app will ask for your **explicit permission**
before sending audio to Apple's servers for transcription. This never happens
silently, and you can turn it off at any time under **Me → Server Speech
Recognition**. Any such processing is covered by
[Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

---

## Children's privacy

LinguaFlow is not directed at children under 13, and we do not knowingly
collect personal data from them. If you believe a child has provided us
personal data, contact us and we will delete it.

---

## Your rights and choices

- **Use the app anonymously.** Guest mode requires no account.
- **Delete your account and all associated data at any time**, directly in the
  app: **Me → Delete Account**. This permanently erases your account, email,
  subscription record and cached AI responses from our servers. It cannot be
  undone.
- **Delete local data** by deleting the app.
- **Request a copy of your data** by emailing suryapradipta@icloud.com.

If you are in the EEA or UK, you have rights under GDPR to access, correct,
export, restrict or erase your data, and to object to processing. If you are in
California, you have rights under CCPA/CPRA — note that we do not sell personal
information. Email us to exercise any of these; we respond within 30 days.

Our legal basis for processing under GDPR is **performance of a contract**
(providing the app's features you request) and **consent** (optional features
such as server-based speech recognition).

---

## Data retention

- Account data is kept until you delete your account.
- Cached AI responses are kept until you delete your account or the app.
- We do not retain video, audio or transcript content at all, because we never
  receive it.

## International transfers

Our processors (Supabase, OpenAI) may process data on servers outside your
country, including in the United States, under appropriate safeguards such as
Standard Contractual Clauses.

## Third-party processors

| Processor | Purpose | Policy |
|---|---|---|
| Supabase Inc. | Authentication, account storage, backend functions | https://supabase.com/privacy |
| OpenAI, L.L.C. | Generating AI explanations and pronunciation feedback | https://openai.com/policies/privacy-policy |
| Apple Inc. | App distribution, subscriptions, optional server speech recognition | https://www.apple.com/legal/privacy/ |

## Security

Data in transit is encrypted with TLS. Backend access is protected by
authenticated requests and row-level security, so one account cannot read
another's data. AI provider keys are held server-side and never shipped in the
app.

## Changes to this policy

If we make material changes we will update the date at the top of this page and
note the change in the app's release notes.

## Contact

Questions about this policy or your data:

**suryapradipta@icloud.com**
