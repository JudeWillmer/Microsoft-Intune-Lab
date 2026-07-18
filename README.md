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
<img width="1918" height="992" alt="Image 1" src="https://github.com/user-attachments/assets/360102c3-bfae-455d-ac57-df43cf9e3666" />
<img width="1918" height="993" alt="Image 2" src="https://github.com/user-attachments/assets/24b571af-b87b-4be6-be0f-af78b7907274" />
<img width="1918" height="993" alt="Image 3" src="https://github.com/user-attachments/assets/12f0ce8b-7558-4245-a918-486a55ec8b7d" />

---

# **Scenario 2 – Configure BitLocker Disk Encryption Policy**

A BitLocker Disk Encryption policy was created to enforce full disk encryption on managed Windows devices. This policy helps protect data stored on endpoint devices by requiring encryption and enabling secure recovery options.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Endpoint Security → Disk Encryption**.
2. Created a new BitLocker policy.
3. Enabled device encryption.
4. Reviewed the completed BitLocker policy.

## **Screenshots**
<img width="1918" height="992" alt="Image 4" src="https://github.com/user-attachments/assets/87980f41-0630-422c-93eb-92ff9155eab3" />
<img width="1918" height="993" alt="Image 5" src="https://github.com/user-attachments/assets/1e38addb-cf30-4812-b143-449dee93c106" />

---

# **Scenario 3 – Configure Endpoint Detection and Response (EDR)**

An Endpoint Detection and Response (EDR) policy was created to onboard Windows devices into Microsoft Defender for Endpoint. This enables advanced threat detection, investigation, and response capabilities through Microsoft Defender.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Endpoint Security → Endpoint Detection and Response**.
2. Created a new EDR policy.
3. Configured the onboarding package and required settings.
4. Reviewed the completed EDR policy.

## **Screenshots**
<img width="1918" height="992" alt="Image 6" src="https://github.com/user-attachments/assets/9dc7edef-680e-4c3e-8b32-330f2d60557c" />
<img width="1918" height="993" alt="Image 7" src="https://github.com/user-attachments/assets/0768a2eb-ac44-4263-8663-57014eea345f" />

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
<img width="1918" height="993" alt="Image 8" src="https://github.com/user-attachments/assets/895b9911-41a5-4b75-bbd4-40fabca77e6e" />
<img width="1918" height="992" alt="Image 9" src="https://github.com/user-attachments/assets/133427b8-7c40-41b5-a664-e0fea7227564" />

---

# **Recommendations**

- Enable Microsoft Defender Antivirus policies to provide centralized malware protection across managed devices.
- Enforce BitLocker encryption to protect sensitive data if a device is lost or stolen.
- Deploy Endpoint Detection and Response (EDR) to improve threat detection and incident response capabilities.
- Restrict removable media and external device access using Attack Surface Reduction policies to reduce the risk of malware infections and unauthorized data transfer.
- Regularly review Endpoint Security policies to ensure they align with organizational security requirements and Microsoft security best practices.

---

# **Conclusion**

This lab demonstrated how Microsoft Intune can be used to centrally manage endpoint security through multiple policy types. Microsoft Defender Antivirus, BitLocker Disk Encryption, Endpoint Detection and Response (EDR), and Attack Surface Reduction policies were successfully configured to improve device protection. Implementing these controls helps strengthen endpoint security, reduce attack surfaces, protect sensitive data, and improve an organization's overall security posture.
