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

# Lab 2 – Microsoft Intune Compliance and Device Configuration Policies

## **Objective**

The objective of this lab was to configure and manage Microsoft Intune Compliance and Configuration policies for both Windows and Apple mobile devices. Compliance policies were created to define the security requirements devices must meet before being considered compliant, while configuration profiles were used to enforce password complexity, device restrictions, and security settings across managed endpoints.

---

# **Scenario 1 – Review Existing Windows Configuration Policies**

Existing Windows configuration policies were reviewed within Microsoft Intune to verify the Endpoint Security policies created in the previous lab. This provides administrators with a central location to manage and review deployed Windows configuration profiles.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Devices → Windows → Configuration**.
2. Reviewed existing Windows configuration profiles.
3. Verified previously created Endpoint Security policies.

## **Screenshots**

**Figure 1.** Reviewing existing Windows configuration policies.

---

# **Scenario 2 – Configure Windows 10/11 Compliance Policy**

A Windows 10/11 Compliance policy was created to define the security requirements managed Windows devices must meet before being considered compliant. Password complexity, BitLocker encryption, and device health settings were configured to strengthen endpoint security.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Devices → Windows → Compliance**.
2. Created a new Windows 10/11 Compliance policy.
3. Configured password and device security settings.
4. Configured Device Health requirements including BitLocker encryption.
5. Reviewed the compliance policy.
6. Created the policy and verified it was successfully deployed.

## **Screenshots**

**Figure 2.** Configuring Windows password security requirements.

**Figure 3.** Configuring Windows Device Health compliance settings.

**Figure 4.** Reviewing the Windows compliance policy before creation.

**Figure 5.** Completed Windows 10/11 Compliance policy.

---

# **Scenario 3 – Configure Apple Mobile Device Restrictions Policy**

An Apple Mobile Device Restrictions configuration profile was created to enforce password complexity and additional security restrictions for managed Apple devices. Configuration profiles allow administrators to centrally enforce security settings across enrolled mobile devices.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Devices → Apple Mobile → Configuration**.
2. Created a new Device Restrictions profile.
3. Configured password complexity requirements.
4. Configured additional password protection settings.
5. Reviewed the configuration profile.
6. Created the policy and verified it was successfully deployed.

## **Screenshots**

**Figure 6.** Creating the Apple Mobile Device Restrictions profile.

**Figure 7.** Configuring Apple Mobile password requirements.

**Figure 8.** Configuring additional Apple Mobile device restrictions.

**Figure 9.** Reviewing the Device Restrictions profile before creation.

**Figure 10.** Completed Apple Mobile Device Restrictions policy.

---

# **Scenario 4 – Assign the Apple Mobile Device Restrictions Policy**

The Apple Mobile Device Restrictions policy was assigned to a security group to demonstrate how Microsoft Intune deploys configuration profiles to targeted users or devices. Security groups provide administrators with a scalable method for managing policy assignments across an organization.

## **Steps Performed**

1. Created a new Apple Mobile security group.
2. Added users to the security group.
3. Assigned the Device Restrictions policy to the group.
4. Verified group membership and policy assignment.

## **Screenshots**

**Figure 11.** Creating the Apple Mobile security group.

**Figure 12.** Assigning the Device Restrictions policy to the security group.

**Figure 13.** Reviewing the Apple Mobile security group membership.

---

# **Scenario 5 – Configure Apple Mobile Compliance Policy**

An Apple Mobile Compliance policy was created to define the security requirements Apple devices must satisfy before they are considered compliant. Password requirements, jailbreak detection, and additional security controls were configured to improve mobile device security.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Devices → Apple Mobile → Compliance**.
2. Created a new Apple Mobile Compliance policy.
3. Configured password and security requirements.
4. Configured device health settings.
5. Reviewed the compliance policy.
6. Created the policy.

## **Screenshots**

**Figure 14.** Configuring Apple Mobile compliance settings.

**Figure 15.** Configuring Apple Mobile password compliance requirements.

**Figure 16.** Reviewing the Apple Mobile Compliance policy before creation.

---

# **Scenario 6 – Monitor Apple Mobile Compliance Policy**

After deployment, the Apple Mobile Compliance policy was reviewed using the Microsoft Intune monitoring dashboard. The policy properties and monitoring information were examined to verify successful deployment. As no Apple devices were enrolled within the lab environment, the compliance dashboard reported zero compliant and zero noncompliant devices, which is the expected behaviour until managed devices begin reporting.

## **Steps Performed**

1. Opened the completed Apple Mobile Compliance policy.
2. Reviewed the policy properties.
3. Opened the Monitor tab.
4. Verified the compliance status.

## **Screenshots**

**Figure 17.** Monitoring the Apple Mobile Compliance policy.

**Figure 18.** Reviewing the Apple Mobile Compliance policy properties.

---

# **Recommendations**

Based on this lab, the following security practices are recommended:

- Deploy Compliance policies to ensure managed devices satisfy organizational security requirements before accessing corporate resources.
- Require BitLocker encryption and strong password policies to improve Windows endpoint security.
- Configure Apple Mobile Device Restrictions to enforce password complexity and strengthen mobile device protection.
- Assign policies through security groups to simplify administration and improve policy management.
- Regularly monitor device compliance within Microsoft Intune to identify noncompliant devices and maintain a secure endpoint environment.

---

# **Conclusion**

This lab demonstrated how Microsoft Intune can be used to centrally configure and manage Compliance and Configuration policies across Windows and Apple mobile devices. Windows Compliance policies were created to enforce endpoint security requirements, while Apple Mobile Device Restriction and Compliance policies were configured to strengthen mobile device security. Security groups were used to deploy policies to targeted users, and the monitoring dashboard was reviewed to validate policy deployment and compliance reporting. Together, these features demonstrate how Microsoft Intune helps organizations standardize security configurations and maintain compliance across multiple device platforms.
