# Azure Identity and Access Management (IAM) Checklist ✅

This checklist outlines the essential steps to secure your Azure AD environment. Use it to verify that your identity and access management controls adhere to Zero Trust best practices.

- [ ] **🔐 Enforce Multi-Factor Authentication (MFA):** Require MFA for all users, especially for privileged and administrative accounts.
- [ ] **📶 Implement Conditional Access Policies:** Configure policies to restrict access based on user location, device state, and risk level.
- [ ] **👥 Enforce Role-Based Access Control (RBAC):** Assign only the minimum necessary privileges to each user or group.
- [ ] **🛡️ Deploy Azure AD Privileged Identity Management (PIM):** Use PIM to manage, monitor, and audit elevated access.
- [ ] **🔄 Enable Self-Service Password Reset (SSPR):** Allow users to securely reset their own passwords.
- [ ] **📝 Configure Password Policies:** Enforce strong password complexity, expiration, and history requirements.
- [ ] **📊 Monitor Sign-In Activity:** Regularly review Azure AD sign-in logs for suspicious activity.
- [ ] **🚫 Disable Legacy Authentication:** Block or restrict protocols that do not support modern authentication.
- [ ] **🛠️ Use Managed Identities:** Replace stored credentials in code with managed identities for Azure services.
- [ ] **🔍 Implement Sign-In Risk Policies:** Configure policies to challenge or block high-risk sign-in attempts.
- [ ] **📋 Regularly Review User Access:** Audit and remove stale, inactive, or unnecessary user accounts.
- [ ] **🤝 Govern External and Guest Access:** Limit and monitor external user access through conditional policies.
- [ ] **📢 Set Up Alerting:** Configure alerts for anomalous sign-in patterns or suspicious account activity.
- [ ] **🔒 Secure API and Application Access:** Enforce OAuth and OpenID Connect for secure application authentication.
- [ ] **📚 Provide IAM Training:** Educate users on best practices for account security and phishing awareness.
- [ ] **🖥️ Enable Security Defaults:** Use Azure AD Security Defaults to quickly enable baseline security settings.
- [ ] **🔗 Integrate with Microsoft Defender for Identity:** Leverage additional threat detection for identity-related risks.
- [ ] **💼 Regularly Update IAM Documentation:** Maintain current policies and procedures for identity management.
- [ ] **🔄 Automate User Provisioning/Deprovisioning:** Use automation tools to quickly update access as users join or leave.
- [ ] **🕵️‍♂️ Perform Periodic Access Reviews:** Schedule regular reviews of permissions and adjust as needed.
- [ ] **🚀 Enforce Application Security Policies:** Use Conditional Access App Control for cloud application sessions.
