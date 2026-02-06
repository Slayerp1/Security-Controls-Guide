# 🛡️ Security Controls Configuration & Testing Guide

A beginner-friendly guide to configuring and testing the four key security control types using Windows Server 2019 and PowerShell.

> **Environment:** PC10 VM, Domain: Structureality, User: Jaime (LocalAdmin)

---

## 📂 Contents

- [Preventive Control - File Share Permissions](Preventive%20Control%20-%20File%20Share%20Permissions)
- [Detective Control - Object Access Auditing](Detective%20Control%20-%20Object%20Access%20Auditing)
- [Directive Control - Login Warning Banner](Directive%20Control%20-%20Login%20Warning%20Banner)
- [Corrective Control - File Integrity and Auto Restore](Corrective%20Control%20-%20File%20Integrity%20and%20Auto%20Restore)
- [Comparison Table](Comparison%20Table)

---

## 🧠 What Are Security Controls?

**Preventive** — Stops unwanted actions before they occur

**Detective** — Records/logs events for later review

**Directive** — Guides/instructs users toward compliant behavior

**Corrective** — Detects issues and actively restores secure state

---

## 🔑 Key Takeaways

- Security is **defense-in-depth** — use multiple control types together
- Always **test** after configuration to verify effectiveness
- Tailor controls to your organization's **risk profile**, **policy**, and **compliance requirements**
- In production use **Group Policy** for domain-wide settings
- Centralize logs (SIEM) for detective controls
- Schedule/automate corrective scripts
- Document changes and report deviations

---

## 📚 Frameworks Referenced

- NIST
- CIS
- Common security control frameworks

---

## ⚖️ Legal Reminder

✅ Your own lab environment · ✅ Authorized company systems · ✅ With written permission

❌ Unauthorized systems · ❌ Production without change management approval

---

## 🤝 Contributing

Found a mistake or want to add a control? Open a PR!

## 📄 License

MIT License — feel free to use and share.
