# Windows Security Audit Report

## Objective

Perform a basic security audit on a Windows system to evaluate security configurations related to authentication, firewall protection, system updates, antivirus protection, and disk encryption.

---

## 1. Password Policy

Minimum Password Length: 0 characters  
Password Complexity: Disabled  

### Security Risk

A minimum password length of 0 characters and disabled complexity requirements allow users to create weak or empty passwords. This significantly increases the risk of:

- Unauthorized access
- Password guessing attacks
- Brute force attacks

### Recommendation

To improve system security:

- Set **minimum password length to at least 12 characters**
- Enable **password complexity requirements**
- Enforce passwords that contain:
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Special characters
- Configure **account lockout policies** to prevent brute-force attacks.

---

## 2. Firewall Status

Windows Defender Firewall is enabled for the network profiles.

### Security Status

Firewall protection helps prevent unauthorized access to the system and blocks potentially malicious traffic.

### Recommendation

- Regularly review firewall rules.
- Block unnecessary inbound connections.
- Monitor firewall logs for suspicious activity.

---

## 3. System Updates

Windows Update was checked to verify whether the system is receiving security patches.

### Security Importance

Regular updates ensure the system is protected against newly discovered vulnerabilities.

### Recommendation

- Enable **automatic Windows updates**
- Install security patches regularly
- Reboot systems when required after updates.

---

## 4. Antivirus Protection

Windows Defender real-time protection is enabled.

### Security Importance

Real-time protection helps detect and block malicious software before it compromises the system.

### Recommendation

- Perform **weekly full system scans**
- Keep antivirus definitions updated
- Avoid downloading software from untrusted sources.

---

## 5. Disk Encryption

BitLocker Status: Disabled

### Security Risk

Without disk encryption, data stored on the device is vulnerable if the computer is:

- Lost
- Stolen
- Physically accessed by an unauthorized individual

An attacker could remove the hard drive and access the data directly.

### Recommendation

Enable **BitLocker Drive Encryption** to protect sensitive data.

Benefits include:

- Protects files from unauthorized access
- Encrypts the entire drive
- Ensures data remains secure even if the device is stolen.

---

## Conclusion

The system demonstrates some basic security protections such as firewall and antivirus protection. However, significant improvements are required to strengthen authentication and data protection mechanisms.

Key improvements recommended include:

- Enforcing strong password policies
- Enabling BitLocker disk encryption
- Maintaining regular system updates
- Monitoring security logs and firewall activity

Implementing these recommendations will significantly improve the system’s security posture.