# Incident Report: Brute Force & Malware Injection

## Incident Description
A former employee guessed default administrative passwords to gain access to a web host. Once inside, they modified the website's source code to embed a malicious JavaScript function that prompted visitors to download malware.

## Remediation
- **Stronger Password Policies:** Enforce complexity and regular rotation.
- **IAM:** Immediate revocation of credentials for former employees.
- **Access Control:** Implement the **Principle of Least Privilege** to limit the impact of a compromised administrative account.
