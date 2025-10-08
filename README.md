# Microsoft-Defender-For-Endpoint-Security

# 🧪 MDE Labs – Trial Environment Setup

This repository outlines how to set up a **free trial environment** for testing **Microsoft Defender for Endpoint (MDE)** on endpoint devices using:

- A **Microsoft 365 E5 trial** (includes Defender and Intune)
- An **Azure free account** to deploy Linux virtual machines

---

## 🎯 Purpose

To help security engineers and cloud architects quickly spin up a lab for evaluating Microsoft Defender for Endpoint workloads — without incurring licensing or infrastructure costs.

---

## 🟢 Step 1: Create Microsoft 365 E5 Trial

1. Visit the official Microsoft Security Trial Portal:  
   👉 [Start Defender for Endpoint Trial](https://www.microsoft.com/en-in/security/business/get-started/start-free-trial)

2. Sign in with your Microsoft account and follow the prompts to create a **Microsoft 365 E5 trial tenant**.

3. Once activated, you’ll gain access to:
   - Microsoft Defender for Endpoint
   - Microsoft Intune
   - Microsoft Defender XDR
   - Azure AD Premium P2

4. Access the Defender portal here:  
   🔗 [https://security.microsoft.com](https://security.microsoft.com)

---

## ☁️ Step 2: Set Up Azure Free Account

1. Sign up for an Azure free account (₹15,500 or $200 credits for 30 days):  
   👉 [Create Azure Free Account](https://azure.microsoft.com/en-in/free/)

2. Use the free credits to deploy VMs for testing:
   - Recommended OS: Ubuntu 20.04 LTS, RHEL 8, CentOS 7
   - VM Size: B1s or B2s for lightweight testing

3. Ensure outbound internet access is enabled for Defender connectivity.

---

## 📚 Official Microsoft Resources

- [Microsoft Defender for Endpoint Overview](https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/microsoft-defender-endpoint)
- [Azure Free Trial Details](https://azure.microsoft.com/en-in/free/)
- [Microsoft Intune Overview](https://www.microsoft.com/en-us/security/business/endpoint-management/microsoft-intune)
- [Microsoft 365 Defender Portal](https://security.microsoft.com)

---
