# Example: SaaS Data Breach Crisis Communication

**Company:** CloudPath (B2B project management SaaS, 12,000 business customers)  
**Crisis:** Unauthorized third-party access to customer email address database  
**Discovered:** Tuesday, 2:14 PM PDT  
**Scope:** Email addresses of 12,000 customers accessed. No passwords, payment data, or project files affected. Access window: 72 hours (Saturday 6 AM – Tuesday 2 PM).  
**Status at time of communication:** Contained (access revoked, vulnerability patched)  
**Spokesperson:** Sarah Chen, CEO

---

## PROMPT 1 OUTPUT: Holding Statement (posted 2:47 PM — 33 minutes after discovery)

### Version 1 — Empathetic Tone (SELECTED)
"We became aware earlier today of a security incident affecting CloudPath customer accounts. This is unacceptable, and we are deeply sorry for any concern this causes our customers. Our security team has already contained the incident and is conducting a thorough investigation. We will share a full update — including what happened, what was accessed, and what we're doing — by 6 PM PDT today. If you have immediate concerns, please contact security@cloudpath.com."

*Tone: Empathy 9/10, Formality 5/10*  
*Best for: Social media, status page, email header*

### Version 2 — Corporate/Formal Tone
"CloudPath has identified and contained a security incident involving unauthorized access to certain customer data. We are actively investigating the scope of this incident with the assistance of third-party security specialists. We are committed to transparency and will provide a comprehensive update with all material details no later than 6 PM PDT. Customers with questions may contact our dedicated response team at security@cloudpath.com."

*Tone: Empathy 5/10, Formality 9/10*  
*Best for: Regulated industry customers, investor communication, legal record*

### Version 3 — Transparent/Direct Tone
"At 2:14 PM today, we discovered that an unauthorized party accessed our customer email database. We shut down the access within two hours of discovery. Right now our security team is working to understand exactly what was accessed and when. We'll share everything we know by 6 PM PDT — we won't wait until we have a perfect story." 

*Tone: Empathy 7/10, Formality 4/10*  
*Best for: Tech-forward customer base, companies with transparency as a core value, Hacker News*

### DO-NOT-SAY Checklist
1. **"We take security very seriously"** — Every company says this. In a crisis, it sounds like deflection and doesn't describe any action.
2. **"No sensitive data was compromised"** — Email addresses ARE sensitive data. This phrase minimizes the incident and will be quoted back against you.
3. **"This was an isolated incident"** — You don't know this yet. Saying it forces you to walk it back.
4. **"We have no evidence that..."** — Technically true, legally careful, but sounds evasive. Journalists will write "CloudPath claims..."
5. **"We cannot comment on an ongoing investigation"** — Fine for law enforcement matters; sounds like hiding something for a data breach.
6. **"Our systems are secure"** — Demonstrably false at this moment.
7. **"This was a sophisticated attack"** — May be true, but sounds like blame-shifting. Doesn't matter how sophisticated it was.
8. **"A small number of..."** — 12,000 is not small to those 12,000 people.
9. **"We apologize if..."** — The "if" negates the apology. You know something happened.
10. **"We have notified the appropriate authorities"** — This implies regulatory reporting obligations that may not exist for this incident type; consult legal first.

---

## PROMPT 2 OUTPUT: Full Public Statement (posted 5:58 PM — 4 hours after discovery)

**FOR IMMEDIATE RELEASE**  
**CloudPath Security Incident Update — April 21, 2026**

On Tuesday, April 21 at 2:14 PM PDT, CloudPath's security monitoring system detected unauthorized third-party access to our customer email address database. We immediately revoked that access and launched a full investigation. This statement reflects everything we know as of 6 PM PDT.

**What was accessed:** Email addresses associated with 12,000 CloudPath business accounts. No passwords, payment information, project data, or account credentials were accessed or compromised. The access window was 72 hours, from Saturday April 18 at 6 AM PDT through Tuesday April 21 at 2 PM PDT, when our systems detected and terminated the intrusion.

**What we've done:** Within two hours of discovery, we revoked the unauthorized access token, patched the API vulnerability that enabled the breach, and engaged CrowdStrike to conduct a forensic audit of our systems. We have notified the FBI Cyber Division as a precautionary measure. We are individually notifying every affected customer via email today.

**What we're changing:** We are implementing mandatory API key rotation every 30 days (previously no expiration), adding rate-limit monitoring on all authentication endpoints, and conducting a full third-party security audit of our infrastructure. These changes will be complete by May 15. We will publish the audit results publicly.

*"We built CloudPath to be the most trusted project management platform for the teams that rely on us. We failed to live up to that trust today. I'm sorry. We will do whatever it takes to earn it back."* — Sarah Chen, CEO

Affected customers will receive individual notification emails with specific guidance. Customers with questions can reach our security response team at security@cloudpath.com or 1-800-555-0147 (available 24/7 through April 28). We will publish another update by noon tomorrow with forensic audit preliminary findings.

**Frequently Asked Questions:**

*What exactly happened?*  
An unauthorized party exploited a vulnerability in our API authentication system to gain read access to our customer email address database. We do not yet know who was responsible or how they discovered the vulnerability. CrowdStrike is actively investigating.

*Why did this happen?*  
Our API keys had no expiration policy. The attacker used a compromised key — we're still determining how it was compromised — to access the email database. We have since revoked all existing API keys and implemented mandatory 30-day rotation.

*Are my data or accounts at risk?*  
Only email addresses were accessed. Passwords, payment data, project files, and account credentials were not accessed and are not at risk. As a precaution, we recommend being alert to phishing emails that may reference CloudPath in the coming weeks.

*What are you doing about it?*  
Access has been revoked and the vulnerability has been patched. CrowdStrike is conducting a forensic audit. We are individually notifying all 12,000 affected customers. We are publishing a full security roadmap by April 28.

*How do I know this won't happen again?*  
It won't — because the specific vulnerability has been patched. But "trust us" isn't enough. That's why we've engaged an independent third-party auditor and will publish their findings publicly. No security system is 100% perfect, but we will show our work.

---

## PROMPT 3 OUTPUT: Internal Communications

### Communication 1 — Immediate Notification (sent 2:35 PM, 21 min after discovery)

**#company-wide Slack | Subject: Security Incident — Read Now**

Team — we discovered a security incident at 2:14 PM today. Here's what you need to know right now.

**What happened:** Unauthorized access to our customer email database was detected and terminated. No passwords, payment data, or project files were affected. We're investigating.

**What to do right now:**
- Do NOT discuss specifics with anyone outside the company
- If a customer calls or messages: use the script below
- If a journalist contacts you: do not comment, forward to press@cloudpath.com immediately
- If you're not sure: ask before you act

**Approved script for customer contact:**
*"We're aware of a security incident and our team is actively responding. Our CEO will share a full statement with all customers by 6 PM today. I'll make sure you get that directly."*

**What NOT to say:**
- Don't say it was "just email addresses" — minimize nothing
- Don't say it's been "fully resolved" — investigation is ongoing
- Don't speculate on how it happened
- Don't tell customers to "not worry"
- Don't discuss it on personal social media

**Questions?** Contact Marcus Webb (VP Engineering) or Sarah Chen directly. Do not guess.

**Next update:** 5:30 PM today, before public statement goes live.

---

### Communication 2 — Post-Resolution Update (sent 8:00 PM)

**#company-wide Slack | Subject: Security Incident — Resolved. Here's what we learned.**

Team — the CloudPath security incident is resolved. Here's the full picture and what we're changing.

**What happened:** An API key with no expiration date was compromised and used to read our customer email database over 72 hours. Our monitoring caught it. We shut it down and patched the vulnerability within 2 hours of detection.

**What we did:** CrowdStrike is completing a forensic audit. FBI Cyber Division notified. All 12,000 affected customers individually emailed. Public statement published at 6 PM. Press response: 3 inbound inquiries handled by PR, no major coverage as of 8 PM.

**What we're changing:**
1. API keys now expire every 30 days — no exceptions
2. Rate-limit anomaly detection on all auth endpoints — live tomorrow
3. Full third-party security audit, results published publicly by May 15
4. Annual security training mandatory for all engineers (scheduling next week)
5. Incident response playbook created — you'll all see it by end of next week

**To the support team:** You handled 47 customer calls today with professionalism and calm. The approved script held. Customer sentiment was "concerned but trusting" in every case. That mattered.

**To engineering:** You patched a live vulnerability in 90 minutes while managing customer communications. That's the team I'd want in a crisis.

We made a mistake. We owned it. We fixed it. Now we build so it doesn't happen again.

— Sarah

---

### Social Media Guidance for Employees

**What you can post:**
If you choose to post, use only: *"CloudPath is handling a security incident with full transparency. Our CEO's statement: [link]"*

**What not to post:**
- No speculation about cause
- No sharing of customer information
- No criticism or defense of the company's response
- No "it wasn't that bad" framing

**If friends ask:** "I can't share details while we're responding, but our CEO published a full public statement. I can send you the link."

**If you get a negative comment on your personal accounts:** Do not engage. Screenshot and send to pr@cloudpath.com.

**One rule:** When in doubt, say nothing publicly and flag internally.

---

## PROMPT 4 OUTPUT: Media Q&A Prep Kit

### The 10 Hardest Questions

**Category 1: What Happened**

*Q1: "Why did it take 72 hours to detect unauthorized access to customer data?"*  
**Approved answer:** "Our monitoring systems identified the anomaly and we terminated access within two hours of detection. The 72-hour window refers to how long the unauthorized access existed before we caught it — not how long we knew about it. We've since implemented real-time rate-limit monitoring so anomalies like this will be flagged within minutes."  
**Off-limits phrases:** "missed," "delayed response," "failed to catch"  
**Bridge:** Yes — pivot to monitoring improvement

*Q2: "How many customers were affected and what exactly was taken?"*  
**Approved answer:** "Email addresses associated with 12,000 CloudPath business accounts were accessed. Nothing else — no passwords, payment data, or project content. We've confirmed this through our forensic analysis with CrowdStrike."  
**Off-limits phrases:** "only email addresses," "just contact information," "minor breach"  
**Bridge:** No — answer factually, no pivot needed

**Category 2: Why It Happened**

*Q3: "Who is responsible for this breach, and why weren't basic security controls in place?"*  
**Approved answer:** "We are responsible. An API key with no expiration policy was compromised — that's a gap in our controls that we should have caught sooner. We're not deflecting accountability. That's exactly why we've already patched it, engaged CrowdStrike, and are publishing an independent security audit."  
**Off-limits phrases:** "sophisticated attack," "nation-state," "not our fault," "attacker's fault"  
**Bridge:** Yes — pivot to remediation actions

*Q4: "Is this a sign of broader security problems at CloudPath?"*  
**Approved answer:** "One specific vulnerability does not mean our entire system is compromised. CrowdStrike's forensic audit will give us — and our customers — an independent answer to exactly that question. We're publishing their findings publicly so customers don't have to take our word for it."  
**Off-limits phrases:** "our systems are secure," "isolated incident," "we can assure you"  
**Bridge:** Yes — pivot to audit transparency

**Category 3: Accountability**

*Q5: "Will anyone at CloudPath face consequences for this?"*  
**Approved answer:** "Our focus right now is on the forensic investigation and protecting customers. Once CrowdStrike completes their audit, we'll have a full picture of what happened and will address it internally. I'm not going to prejudge the findings."  
**Off-limits phrases:** "I can't comment," "HR matter," "not relevant"  
**Bridge:** No — redirect to audit process

*Q6: "Do your customers have grounds to sue CloudPath over this breach?"*  
**Approved answer:** "I'd refer legal questions to our counsel. What I can tell you is that we've acted quickly, transparently, and are making every affected customer whole in terms of information and remediation. Our focus is on them."  
**Off-limits phrases:** "no legal liability," "we're covered," "they agreed to our terms"  
**Bridge:** No — refer to legal, pivot to customer support

**Category 4: What You're Doing**

*Q7: "Why should customers trust that you've actually fixed this?"*  
**Approved answer:** "Because we're not asking them to take our word for it. We've engaged an independent third-party auditor — CrowdStrike — and we're publishing their full findings publicly by May 15. If there are additional problems, you'll see them in that report."  
**Off-limits phrases:** "trust us," "we can guarantee," "it won't happen again"  
**Bridge:** Yes — pivot to audit transparency

*Q8: "Have you notified all affected customers?"*  
**Approved answer:** "Yes. All 12,000 affected customers received individual email notification today by 7 PM PDT. We also published a public statement at 6 PM and have a 24/7 response team available through April 28."  
**Off-limits phrases:** "most," "the majority," "we're working on it"  
**Bridge:** No — factual answer

**Category 5: Future Prevention**

*Q9: "What stops this from happening again?"*  
**Approved answer:** "Three things: mandatory API key rotation every 30 days effective today, real-time anomaly detection on all authentication endpoints launching tomorrow, and a full third-party security audit with published results. We've also made incident response training mandatory for all engineers."  
**Off-limits phrases:** "this was a one-time thing," "we've learned our lesson," "we've taken steps"  
**Bridge:** Yes — pivot to specific, time-bound commitments

*Q10: "Are you considering offering affected customers any compensation or credit?"*  
**Approved answer:** "We're focused on full transparency and remediation right now. We're having that conversation internally and will communicate directly with customers about what we're offering. I want to make sure anything we announce is meaningful, not symbolic."  
**Off-limits phrases:** "we're not required to," "email addresses aren't that sensitive," "no plans"  
**Bridge:** No — acknowledge and commit to follow-up

---

### Bridge Phrase Library

1. **Empathy bridge:** "I understand why you're asking that. What I can tell you is..."
2. **Factual bridge:** "The facts as we know them are... and what that means is..."
3. **Forward bridge:** "More important than what happened is what we're doing about it..."
4. **Accountability bridge:** "We take full responsibility for this. And the action we've taken is..."
5. **Transparency bridge:** "We're committed to showing our work. That's why we're publishing..."
6. **Customer-first bridge:** "Every decision we're making right now starts with one question: what's best for our customers. And that means..."
7. **Investigation bridge:** "The independent forensic audit will answer that definitively. What I can tell you now is..."
8. **Timeline bridge:** "We'll have a complete answer to that by [date]. What I can confirm right now is..."
9. **Correction bridge:** "I want to make sure I address that accurately — the actual situation is..."
10. **Close bridge:** "I want to come back to the most important point here..."

---

### Approved Sound Bites

1. "We failed to protect our customers' data, and we own that completely."
2. "We're not asking anyone to trust us — we're publishing the independent audit so you can judge for yourself."
3. "Every decision we've made in the last six hours has started with one question: what do our customers need to know right now?"

---

### Spokesperson Briefing Sheet

**Today's 3 key messages:**
1. We detected it, we contained it, and it's patched.
2. Only email addresses were accessed — no passwords, payment data, or project files.
3. We're publishing the independent audit results publicly so customers don't have to take our word for it.

**Off-limits topics:**
- Legal liability / litigation (refer to counsel)
- Specific attacker identity / attribution (CrowdStrike investigating)
- Internal personnel decisions (HR process)
- Specific customer names or company names affected

**Quick reference:**
- If asked about how attacker got in: "API key with no expiration — a gap we've now fixed"
- If asked about notification timing: "All 12,000 notified by 7 PM, 5 hours after discovery"
- If asked about data sold/misused: "No evidence of that; CrowdStrike monitoring"
- If asked about regulatory reporting: "Refer to legal counsel"
- If asked for customer quote: "Not appropriate to name customers; their privacy is why we're here"

**How to handle "no comment" without saying it:**
- Instead of "no comment": "I can't speak to that specifically right now, but what I can tell you is..."
- Instead of "I don't know": "I don't have that information in front of me. What I do know is..."
- Instead of silence: "That's a fair question. Let me make sure I answer it accurately..."

**Video interview reminders:**
- Pause before answering — don't rush
- Don't nod while journalist asks hostile questions
- Look at the interviewer, not the camera
- If you misspeak: "Let me correct that..." and restate clearly
