# Lab 1 – Microsoft Intune Endpoint Security Policies

## **Objective**

The objective of this lab was to configure and manage Microsoft Intune Endpoint Security policies to strengthen the security posture of Windows endpoints. Several security policies were created to demonstrate how Intune can centrally manage antivirus protection, disk encryption, endpoint detection and response (EDR), and attack surface reduction controls.

---

# **Scenario 1 – Configure Microsoft Defender Antivirus Policy**

A Microsoft Defender Antivirus policy was created to enable centralized antivirus management for Windows devices. Default Microsoft Defender security settings were configured to provide real-time protection, cloud-delivered protection, archive scanning, email scanning, and network file scanning.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Endpoint Security → Antivirus**.
2. Created a new Microsoft Defender Antivirus policy for Windows devices.
3. Configured Microsoft Defender protection settings.
4. Reviewed the policy after creation.

## **Screenshots**

**Figure 1.** Creating a new Microsoft Defender Antivirus policy.

**Figure 2.** Configuring Microsoft Defender Antivirus settings.

**Figure 3.** Completed Microsoft Defender Antivirus policy.

---

# **Scenario 2 – Configure BitLocker Disk Encryption Policy**

A BitLocker Disk Encryption policy was created to enforce full disk encryption on managed Windows devices. This policy helps protect data stored on endpoint devices by requiring encryption and enabling secure recovery options.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Endpoint Security → Disk Encryption**.
2. Created a new BitLocker policy.
3. Enabled device encryption.
4. Reviewed the completed BitLocker policy.

## **Screenshots**

**Figure 4.** Creating the BitLocker disk encryption policy.

**Figure 5.** Completed BitLocker policy.

---

# **Scenario 3 – Configure Endpoint Detection and Response (EDR)**

An Endpoint Detection and Response (EDR) policy was created to onboard Windows devices into Microsoft Defender for Endpoint. This enables advanced threat detection, investigation, and response capabilities through Microsoft Defender.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Endpoint Security → Endpoint Detection and Response**.
2. Created a new EDR policy.
3. Configured the onboarding package and required settings.
4. Reviewed the completed EDR policy.

## **Screenshots**

**Figure 6.** Configuring the Endpoint Detection and Response (EDR) policy.

**Figure 7.** Completed Endpoint Detection and Response (EDR) policy.

---

# **Scenario 4 – Configure Attack Surface Reduction Policy**

An Attack Surface Reduction policy was created using the Device Control profile to reduce the risk of removable media and peripheral-based attacks. USB connections and Bluetooth functionality were restricted to demonstrate how Intune can limit unauthorized devices from connecting to managed endpoints.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Endpoint Security → Attack Surface Reduction**.
2. Created a new Device Control policy.
3. Configured device control settings.
4. Restricted USB connectivity.
5. Restricted Bluetooth connectivity.
6. Completed the policy configuration.

## **Screenshots**

**Figure 8.** Configuring the Attack Surface Reduction Device Control policy.

**Figure 9.** Configuring USB and Bluetooth restrictions.

---

# **Recommendations**

Based on this lab, the following security practices are recommended:

- Enable Microsoft Defender Antivirus policies to provide centralized malware protection across managed devices.
- Enforce BitLocker encryption to protect sensitive data if a device is lost or stolen.
- Deploy Endpoint Detection and Response (EDR) to improve threat detection and incident response capabilities.
- Restrict removable media and external device access using Attack Surface Reduction policies to reduce the risk of malware infections and unauthorized data transfer.
- Regularly review Endpoint Security policies to ensure they align with organizational security requirements and Microsoft security best practices.

---

# **Conclusion**

This lab demonstrated how Microsoft Intune can be used to centrally manage endpoint security through multiple policy types. Microsoft Defender Antivirus, BitLocker Disk Encryption, Endpoint Detection and Response (EDR), and Attack Surface Reduction policies were successfully configured to improve device protection. Implementing these controls helps strengthen endpoint security, reduce attack surfaces, protect sensitive data, and improve an organization's overall security posture.
