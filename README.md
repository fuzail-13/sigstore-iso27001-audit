# ISO/IEC 27001:2022 Audit Report: Sigstore Ecosystem

> **Audit Scope & Methodology:** This security assessment evaluates the Sigstore ecosystem (Fulcio, Rekor, Cosign) against ISO/IEC 27001:2022 ISMS standards. The audit was conducted strictly using open-source documentation, public GitHub repositories, and transparency log architectures as a Third-Party Risk Management (TPRM) evaluation.

---

## 📄 Full Audit Document
👉 **[Click here to view or download the complete Audit Report (PDF)](./https://drive.google.com/file/d/1zaIaYj0bTF2lKdj0ik-hME4CtK9lLqvU/view?usp=drive_link)**

---

## 📌 Executive Summary
* **Target System:** Sigstore Ecosystem (Digital Signature & Supply Chain Integrity)
* **Standard:** ISO/IEC 27001:2022
* **Audit Verdict:** **Certify with Conditions**
* **Key Findings:** Identified 6 Minor Non-Conformities (NCRs), primarily around centralized ISMS documentation, incident response testing, and compensating control formalization.

## 🛠️ Key Technical Focus Areas
* **OIDC & Identity Verification:** Security controls surrounding Fulcio root CA and short-lived certificate issuance.
* **Log Immutability vs. Data Privacy:** Analyzing the architectural friction between Rekor transparency log immutability and GDPR Article 17 (Right to Erasure).
* **Compensating Controls:** Evaluating open-source contribution guidelines and code review enforcement as operational substitutes for traditional employment contracts.
