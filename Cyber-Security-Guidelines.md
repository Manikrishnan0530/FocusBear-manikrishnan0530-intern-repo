##  Research & Learning

### Common Cyber Security Threats in a Remote Work Environment

Remote work introduces several unique vulnerabilities:

- **Phishing attacks** — Deceptive emails or messages designed to steal credentials or install malware.
- **Unsecured Wi-Fi** — Using public or poorly secured networks exposes data to interception (man-in-the-middle attacks).
- **Weak or reused passwords** — A single compromised password can cascade across multiple accounts.
- **Unpatched software** — Outdated operating systems and apps contain known exploits that attackers can leverage.
- **Social engineering** — Manipulating people into revealing sensitive information through impersonation or false urgency.
- **Insecure file sharing** — Sending sensitive documents over unencrypted channels or personal email.
- **Ransomware** — Malicious software that encrypts files and demands payment for their release.

### Best Practices for Keeping Devices and Accounts Secure

- Keep your operating system, browser, and all software up to date.
- Use a VPN when connecting to public or untrusted networks.
- Only install software from verified, trusted sources.
- Enable full-disk encryption on work devices (e.g. FileVault on macOS, BitLocker on Windows).
- Regularly review which apps and services have access to your accounts and revoke what's unnecessary.
- Never leave devices unattended and unlocked in shared spaces.
- Back up important data regularly to a secure, encrypted location.

### Why It's Important to Lock Your Computer When Away from Your Desk:

- **Unauthorised access** to sensitive company data, internal tools, or user information.
- **Session hijacking** — someone using an already-authenticated session to act as you.
- **Physical tampering** — installation of keyloggers or other malicious software.
- **Accidental data exposure** — a visible screen can reveal confidential information to bystanders.

Locking your screen takes one second and eliminates these risks entirely. It should be a reflex, not an afterthought.

**Best practice:** Set your device to automatically lock after 2–5 minutes of inactivity, and use `Win + L` (Windows) or `Ctrl + Cmd + Q` (macOS) to lock instantly when stepping away.

### How to Handle Phishing Attempts and Suspicious Links

1. **Pause before clicking** — Urgency and fear are common phishing tactics. Slow down.
2. **Check the sender's actual email address** — Display names can be spoofed; the domain rarely can.
3. **Hover over links before clicking** — Check whether the destination URL matches the expected site.
4. **Never enter credentials via a link in an email** — Navigate directly to the site instead.
5. **Be suspicious of unexpected attachments** — Even from known contacts (their account may be compromised).
6. **Report it** — Forward phishing attempts to the appropriate person/team and delete the message.
7. **When in doubt, verify out-of-band** — Contact the sender via a separate channel (e.g. Slack or phone) to confirm legitimacy.

### What Makes a Strong Password, and Why Use a Password Manager

**A strong password:**
- Is at least 16 characters long.
- Uses a mix of uppercase, lowercase, numbers, and symbols.
- Is completely unique — never reused across sites.
- Is not based on personal information (names, birthdays, etc.).
- Ideally, is a randomly generated string or a long passphrase.

**Why a password manager is essential:**
- Humans cannot memorise dozens of unique, complex passwords — so without a manager, people reuse passwords, which is the single biggest account security risk.
- A password manager generates, stores, and autofills strong credentials securely.
- It also alerts you if a saved password appears in a known data breach.
- Recommended options: **1Password**, **Bitwarden**, or **Dashlane**.

### Why Two-Factor Authentication (2FA) Is Important

A password alone is a single point of failure. If it's stolen, phished, or guessed, an attacker has full access. **2FA adds a second layer** — even if your password is compromised, the attacker still can't get in without the second factor.

**Enable 2FA on:**
- Email accounts (especially work email)
- Password manager
- Code repositories (GitHub, GitLab, etc.)
- Cloud storage (Google Drive, Dropbox, etc.)
- Any tool with access to company or user data

**Preferred 2FA methods (most to least secure):**
1. Hardware security key (e.g. YubiKey)
2. Authenticator app (e.g. Authy, Google Authenticator, 1Password built-in)
3. SMS — better than nothing, but vulnerable to SIM-swapping attacks

## Reflections

### Security Measures I Currently Follow / Where I Can Improve

**Currently following:**
- Using a password manager for most accounts.
- Enabling 2FA on primary accounts (email, GitHub).
- Keeping my OS and browser updated.
- Being cautious with email links and attachments.

**Areas for improvement:**
- Ensuring *every* work-related account has 2FA enabled, not just the most obvious ones.
- Being more consistent about locking my screen when stepping away — making it a true habit rather than something I remember occasionally.
- Auditing old saved passwords for reuse or weakness and updating them proactively.

### How to Make Secure Behaviour a Habit

Security works best when it's embedded into routine rather than treated as a checklist:

- **Pair habits with triggers** — e.g. "Every time I stand up from my desk, I lock my screen."
- **Use tooling that reduces friction** — A good password manager makes using strong, unique passwords *easier* than reusing one.
- **Build a security-aware mindset** — Before clicking any link or downloading any file, ask: "Do I expect this? Does this make sense?"
- **Normalise reporting** — Treat flagging suspicious activity as a routine, valued action rather than something that causes alarm.

### Steps I Will Take to Ensure Passwords and Accounts Are Secure

- [1] Audit all work accounts and confirm each has a unique, strong password stored in the password manager.
- [2] Enable 2FA on every account that supports it, prioritising those with access to company or user data.
- [3] Set automatic screen lock to trigger after 3 minutes of inactivity on both computer and phone.
- [4] Review and revoke unnecessary third-party app permissions on key accounts.

### What I Would Do If I Suspected a Security Breach or Suspicious Activity

1. **Do not panic, but act quickly.**
2. **Immediately change the password** of the affected account from a trusted device.
3. **Revoke active sessions** if the platform allows it.
4. **Notify the relevant person at Focus Bear** (manager, tech lead, or security contact) — even if I'm uncertain, it's always better to flag it.
5. **Document what I observed** — timestamps, what was unusual, what I clicked or did prior.
6. **Check for lateral impact** — if the compromised account shared credentials with others (it shouldn't, but check), address those too.
7. **Follow any incident response steps** provided by the company.

## Tasks Completed

- [1] Reviewed all work accounts — strong, unique passwords confirmed via password manager.
- [2] 2FA enabled on all key work accounts.
- [3] Computer set to auto-lock after 3 minutes; phone biometric lock enabled with short timeout.
- [4] This document created and saved to the company wiki / GitHub.

## New Cyber Security Habit at Focus Bear

> **"Lock before I walk."**  
> Every time I leave my desk — even for a minute — I will lock my screen using the keyboard shortcut before standing up. This will be treated as a non-negotiable, automatic behaviour, the same as saving a file before closing it.
