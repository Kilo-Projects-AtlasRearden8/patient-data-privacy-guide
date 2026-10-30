# Patient Data Privacy Guide

A beginner-friendly manual for healthcare workers and anyone handling patient information: HIPAA basics, what never to paste into AI chatbots, securing work devices, and safe information sharing.

**Published by Asdale Dynamics, LLC** — beginner-friendly AI education, books, and guides. Founded by Dylan Asdale, registered nurse turned AI author. Learn more at dylanasdale.github.io.

---

## Before we start: this is education, not legal advice

This guide explains healthcare data privacy in plain English. It is **not legal advice**, **not medical advice**, and **not a substitute for your employer's policies**. HIPAA rules can vary by situation, and your workplace may have stricter rules than the law requires. When in doubt, ask your organization's privacy officer or compliance department before you act.

The examples in this guide are fictional. Do not treat any name, ID, or date here as real patient data.

---

## How to use this guide

Read it top to bottom, or jump to the section you need right now:

1. [HIPAA basics](#hipaa-basics) — what the law covers and what it means day to day
2. [What never to paste into AI chatbots](#what-never-to-paste-into-ai-chatbots) — protecting patients when you use AI
3. [Securing your work devices](#securing-your-work-devices) — locks, updates, Wi-Fi, lost devices
4. [Safe information sharing](#safe-information-sharing) — who, how, and when to share patient information
5. [Quick-reference checklist](#printable-checklist) — print and keep at your station

Each section has step-by-step instructions and a "right now" action you can take today.

---

## 1. HIPAA basics

### What HIPAA is

HIPAA (the Health Insurance Portability and Accountability Act) is a U.S. federal law that sets national standards for protecting patients' health information. Its privacy rules limit who can see, use, and share protected health information — and require reasonable safeguards to keep it safe.

You don't need to memorize the law. You need to know three things:

1. **What counts as protected information**
2. **Who is allowed to see it**
3. **What to do if something goes wrong**

### What counts as protected health information (PHI)

PHI is any information about a patient's health, healthcare, or payment for healthcare that **could identify that person**. It exists on paper, on screens, and spoken out loud.

PHI includes, for example:

- Patient names, initials, or nicknames
- Medical record numbers, account numbers, and other IDs
- Addresses, phone numbers, email addresses
- Dates related to care (birth dates, admission dates, discharge dates, appointment dates)
- Photos, videos, or voice recordings of a patient
- Diagnoses, conditions, test results, medications, and treatment plans
- Insurance information and billing details
- Anything else that, alone or combined with other details, could identify the patient

**De-identified information** has had all 18 HIPAA identifiers removed (or been certified by a statistician). Properly de-identified data is not PHI. Removing a name is usually not enough — a rare diagnosis plus a zip code plus a date can still identify someone.

### The minimum necessary rule

When you use or share PHI, use or share only the minimum amount needed to do the job. If a task requires only a diagnosis, don't include the patient's address or phone number. If you're asking a question about one patient, don't mention other patients in the same message.

### Who may see PHI

PHI may be shared for treatment, payment, and healthcare operations — and only with people who need it to do their jobs. A nurse on a patient's care team generally needs to see that patient's chart. A billing specialist may need diagnosis codes but not clinical notes. A coworker who is not involved in the patient's care does not need to see the chart "just out of curiosity."

Looking up a family member, friend, neighbor, or celebrity's record without a work reason is a HIPAA violation, even if you never tell anyone.

### Common ways PHI gets exposed (accidentally)

Most HIPAA incidents are mistakes, not malice:

- Leaving a computer unlocked at the nurses' station
- Talking about a patient in an elevator, cafeteria, or hallway
- Sending patient information to a personal email account
- Texting PHI on a personal phone or consumer messaging app
- Tossing printed PHI in a regular trash can instead of a shred bin
- Posting about work on social media, even without names ("the car accident patient in room 412" can still identify someone)
- Giving information over the phone without verifying who you're talking to

### If something goes wrong: what to do

If you suspect PHI was seen, sent, lost, or stolen by someone who shouldn't have it:

1. **Don't panic, and don't cover it up.** Quick reporting limits harm.
2. **Tell your supervisor or privacy officer right away.** Follow your organization's incident-reporting process.
3. **Don't delete, alter, or "fix" records.** That can make an investigation harder.
4. **Don't notify the patient yourself unless your privacy officer tells you to.** Breach notifications follow a legal process.

Reporting a mistake promptly is almost always better than hiding it.

---

## 2. What never to paste into AI chatbots

### The rule

**Never paste real patient information — or anything that could identify a real patient — into an AI chatbot.** Not names, not initials, not partial details, not "just this once."

When you type something into most AI chatbots, that text may be:

- Stored on the provider's servers
- Reviewed by human trainers or contractors
- Used to train future versions of the model
- Exposed in a data breach at the AI company
- Reproduced in another user's response

That makes pasting PHI into a chatbot a likely HIPAA breach and a reportable incident. Even free or "personal" accounts count.

### What never to paste (examples — all fictional)

| Never paste | Safer alternative |
|-------------|-------------------|
| "Jane Doe, MRN 123456, admitted 03/14 with pneumonia" | "A patient admitted with pneumonia last week" |
| Full birth date, address, or phone number | Age range only, if needed ("a patient in their 60s") |
| Photo of a patient's wristband, chart, or screen | No photo; describe the situation without identifiers |
| Lab results with patient name attached | "A glucose result of 320 mg/dL in a patient with diabetes" (no identifiers) |
| Screenshots of the EHR | No screenshots; paraphrase the clinical question |
| Anything said by a specific patient you can name | "A patient asked about side effects of this medication" |

**If you can't say it in a hospital elevator, don't paste it into a chatbot.**

### Using AI safely at work

Do this:

- Ask general medical questions ("What are common side effects of lisinopril?")
- Draft patient education in plain language, then customize it yourself with no patient details
- Summarize publicly available information (drug labels, guidelines)
- Use AI tools your organization has approved and vetted, under a business associate agreement if PHI is involved
- Paste only de-identified, fictional scenarios ("Write a sample discharge note for a fictional patient with COPD")

Don't do this:

- Paste real patient names, IDs, dates, or details
- Ask a chatbot to "fix" or "complete" a real patient's note
- Upload photos of patients, wristbands, charts, or screens
- Use personal AI accounts for work tasks involving patient information
- Assume a chatbot is private because you logged in

### If you already pasted something

If you realize you pasted PHI into an AI chatbot:

1. Stop — don't paste anything else.
2. Report it to your supervisor or privacy officer immediately, same as any other potential breach.
3. Note exactly what was pasted, when, and which tool you used. That helps your privacy officer assess the risk.

Reporting quickly is not a career-ending mistake. Hiding it is.

### Local-first AI option

If your work involves sensitive information and you want to experiment with AI, run models **locally on your own computer** using tools like Ollama, LM Studio, or GPT4All. Local models process text on your machine — nothing leaves your device. Even then, follow your employer's policies and don't assume local use automatically makes PHI acceptable; ask your privacy officer first.

---

## 3. Securing your work devices

Work devices hold access to patient systems. A lost phone, an unlocked laptop, or a weak password can expose hundreds of patients' records.

### Lock your devices — every time

- Set your computer, phone, and tablet to lock automatically after a short idle time (5 minutes or less).
- Lock your computer whenever you walk away: **Windows: Win + L**, **Mac: Control + Command + Q** or close the lid.
- Never leave a logged-in work device unattended, even "for a minute" at the nurses' station.

### Use strong, unique passwords

- Use a different password for every work account. If one is stolen, the others stay safe.
- Make work passwords long — 14+ characters is a good target. A passphrase of 3–4 random words works well and is easier to type.
- Store passwords in a password manager (your organization may provide one). Don't write them on sticky notes.
- Change default passwords on any new device before you use it.

### Turn on multi-factor authentication (MFA)

Wherever your organization offers it, turn on MFA for work accounts (email, EHR, scheduling systems). Use an authenticator app rather than text messages when you have the choice. MFA blocks most account-takeover attacks even if your password is stolen.

### Keep software updated

- Install operating system and app updates when your IT department makes them available. Updates fix security holes attackers actively exploit.
- Don't ignore update prompts on work devices.
- Only install software approved by your organization. Games, browser extensions, and "free" tools on work devices can introduce malware.

### Use safe networks

- Connect work devices to your organization's secured Wi-Fi, not public Wi-Fi in cafes or airports.
- If you must access work systems from home, use your organization's VPN if provided.
- Don't log into work accounts on shared or public computers (library kiosks, a friend's laptop).

### Email and messages

- Send PHI only through secure channels your organization approves (secure email, encrypted messaging platforms, the EHR's built-in messaging).
- Don't forward work email to a personal account.
- Don't text PHI through consumer apps unless your organization has specifically approved that app for clinical communication.
- Check the recipient's address twice before sending anything with patient details.

### Lost or stolen devices

If a work phone, laptop, or badge is lost or stolen:

1. Report it to your IT department and supervisor immediately.
2. IT can often remotely lock or wipe the device.
3. Time matters — report it as soon as you notice, not at the end of your shift.

### When you leave or change roles

- Return all work devices, badges, and keys.
- Don't keep copies of patient information on personal devices, USB drives, or personal cloud accounts.
- Your access to patient systems should be removed when your role changes — confirm it has been.

### Before you dispose of anything

Never toss a work computer, phone, tablet, or printed PHI in the trash. Give devices to IT for secure wiping, and put printed PHI in a shred bin.

### Your "right now" action

Lock your computer the next time you step away, and set it to auto-lock after 5 minutes or less. That single habit prevents most casual snooping.

---

## 4. Safe information sharing

### Ask three questions before you share

1. **Does this person need the information to care for this patient?** (Treatment, payment, or operations — not curiosity.)
2. **Is this the minimum necessary information?**
3. **Is this channel secure and approved?**

If the answer to any question is no, don't share — and ask your privacy officer instead.

### Who you can generally share with

- Members of the patient's current care team who need the information for treatment
- The patient themselves (patients have a right to their own records)
- People the patient has authorized in writing
- Public health authorities in specific required situations (certain infectious diseases, abuse reporting, etc.) — follow your organization's policy
- Billing and insurance staff for payment purposes, limited to what they need

### Who you generally should not share with

- Family or friends of the patient, unless the patient has agreed or an emergency situation permits it under your policy
- Coworkers not involved in the patient's care
- Reporters, callers claiming to be from "the hospital," or anyone who cannot prove who they are
- Anyone over an insecure channel (personal email, consumer texting, social media)

### Verify before you share

If someone calls asking for patient information:

1. Don't confirm or deny anything until you verify who they are.
2. Ask for their name, organization, and callback number.
3. Call them back through a number you already know — not the one they give you.
4. Confirm with your supervisor or privacy officer if you're unsure.

The same applies to emailed requests: check the sender's actual address, not just the display name.

### Secure sharing channels

Preferred:

- Secure organizational email
- The EHR's secure messaging
- Approved encrypted messaging platforms
- Fax to a verified number (with a cover sheet, confirming the recipient)

Avoid unless specifically approved:

- Personal Gmail, Yahoo, or other personal email
- Consumer texting apps (WhatsApp, iMessage, SMS) for PHI
- Social media, Slack/Discord workspaces not managed by your organization
- USB drives and personal cloud storage (Dropbox, Google Drive personal accounts)

### Patients sharing their own information

Patients can share their own health information however they want — it's their data. You can help by explaining their rights, but never pressure a patient to share, and never share on their behalf without their clear permission.

### Saying no

If a coworker asks you to look up a patient "just to check," or to text a photo of a chart, say:

> "I can't share that — it's patient information, and I'd be breaking privacy rules. If you need it for patient care, let me help you request it the right way."

You are protecting the patient and your coworkers by saying no.

### Your "right now" action

Check one thing today: confirm you know who your organization's privacy officer or compliance contact is, and save their contact info in your phone. If you ever have a privacy question or incident, you'll know exactly who to call.

---

## 5. Printable checklist

See [`docs/checklist.md`](docs/checklist.md) or open [`site/checklist.html`](site/checklist.html) for a printable, checkbox-style checklist you can keep at your station.

---

## Quick-reference: never share list

Never paste, text, email, post, or tell anyone outside the care team:

- Patient names or initials
- MRNs, account numbers, or other IDs
- Full dates of birth, admission, discharge, or appointments
- Addresses, phone numbers, email addresses
- Photos of patients, wristbands, charts, or screens
- Diagnoses, test results, medications tied to a real patient
- Anything said by a named patient

If it could identify a real patient, treat it as PHI.

---

## Attribution & disclaimer

Created by **Asdale Dynamics, LLC** — beginner-friendly AI education founded by Dylan Asdale, registered nurse turned AI author and founder of Asdale Dynamics, LLC (Indiana, formed October 2026). Dylan's book *The Massive AI Manual* and hub site [dylanasdale.github.io](https://dylanasdale.github.io) explain AI plainly, step by step, like a friend would.

© 2026 Asdale Dynamics, LLC.

**Educational only — not legal advice.** HIPAA requirements depend on your specific situation. Contact your organization's privacy officer or compliance department for guidance that applies to your workplace. All patient names and examples in this guide are fictional.
