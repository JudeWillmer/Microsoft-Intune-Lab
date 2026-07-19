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
<img width="1918" height="993" alt="Image 1" src="https://github.com/user-attachments/assets/122d7f44-1085-4c96-8134-dc25769a16ed" />

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
<img width="1918" height="993" alt="Image 2" src="https://github.com/user-attachments/assets/1f93ed6d-33d8-4702-b8f1-bbc0d215ee2a" />
<img width="1918" height="993" alt="Image 3" src="https://github.com/user-attachments/assets/da2c0328-ecaa-4e69-9141-054db730c8b8" />
<img width="1918" height="995" alt="Image 4" src="https://github.com/user-attachments/assets/e025a4b1-608e-4bff-9455-4df897211260" />
<img width="1918" height="993" alt="Image 5" src="https://github.com/user-attachments/assets/68ac0cfe-8b89-4525-afdd-ba26b4c337bd" />

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
<img width="1918" height="1010" alt="Image 6" src="https://github.com/user-attachments/assets/675f9a4e-df81-4584-bd5b-838cf4f86a5f" />
<img width="1918" height="1008" alt="Image 7" src="https://github.com/user-attachments/assets/08e043a2-01a6-4054-85ec-aefa3a6daded" />
<img width="1918" height="1010" alt="Image 8" src="https://github.com/user-attachments/assets/00e2c17e-9296-411d-8e85-8ec9c87c8955" />
<img width="1918" height="1010" alt="Image 9" src="https://github.com/user-attachments/assets/943b969d-5883-4d1f-987f-3cdbf048eabf" />
<img width="1918" height="1010" alt="Image 10" src="https://github.com/user-attachments/assets/0dc69a82-950b-42ba-8f73-6c231e653434" />

---

# **Scenario 4 – Assign the Apple Mobile Device Restrictions Policy**

The Apple Mobile Device Restrictions policy was assigned to a security group to demonstrate how Microsoft Intune deploys configuration profiles to targeted users or devices. Security groups provide administrators with a scalable method for managing policy assignments across an organization.

## **Steps Performed**

1. Created a new Apple Mobile security group.
2. Added users to the security group.
3. Assigned the Device Restrictions policy to the group.
4. Verified group membership and policy assignment.

## **Screenshots**
<img width="1918" height="1010" alt="Image 11" src="https://github.com/user-attachments/assets/558bb7c3-dd6e-4e97-800d-395b0572469d" />
<img width="1918" height="1010" alt="Image 12" src="https://github.com/user-attachments/assets/334464ef-e18c-41d3-8f20-0275da96952b" />
<img width="1918" height="1008" alt="Image 13" src="https://github.com/user-attachments/assets/3e484a16-e0cc-4108-9e38-fb3c33e069dd" />

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
<img width="1918" height="1008" alt="Image 14" src="https://github.com/user-attachments/assets/d80aeefe-a293-4d89-be4a-18226c539065" />
<img width="1918" height="1010" alt="Image 15" src="https://github.com/user-attachments/assets/e073944c-6543-4421-b349-b0e78445b4c1" />
<img width="1918" height="1010" alt="Image 16" src="https://github.com/user-attachments/assets/f15b2758-2716-4a7c-907b-45271ee668bc" />

---

# **Scenario 6 – Monitor Apple Mobile Compliance Policy**

After deployment, the Apple Mobile Compliance policy was reviewed using the Microsoft Intune monitoring dashboard. The policy properties and monitoring information were examined to verify successful deployment. As no Apple devices were enrolled within the lab environment, the compliance dashboard reported zero compliant and zero noncompliant devices, which is the expected behaviour until managed devices begin reporting.

## **Steps Performed**

1. Opened the completed Apple Mobile Compliance policy.
2. Reviewed the policy properties.
3. Opened the Monitor tab.
4. Verified the compliance status.

## **Screenshots**
<img width="1918" height="1010" alt="Image 17" src="https://github.com/user-attachments/assets/144245ff-014d-4642-8c0e-83df64f00d3f" />
<img width="1918" height="1010" alt="Image 18" src="https://github.com/user-attachments/assets/2691abb0-ce6b-49c2-870e-9f5114434fbb" />

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

# Lab 3 – Microsoft Intune Application Deployment

## **Objective**

The objective of this lab was to deploy and manage applications using Microsoft Intune across Windows, Android, and iOS platforms. Applications were added from the Microsoft Store (new), Built-in app catalogue, and Apple App Store, then assigned to security groups to demonstrate centralized application deployment using Microsoft Intune.

---

# **Scenario 1 – Deploy a Windows Application from the Microsoft Store**

A Windows application was deployed using the Microsoft Store (new) integration within Microsoft Intune. Adobe Acrobat Reader DC was selected, assigned to a Windows device group, and reviewed to verify successful deployment.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Apps → All Apps → Add**.
2. Selected **Microsoft Store app (new)**.
3. Searched for **Adobe Acrobat Reader DC**.
4. Selected the application.
5. Assigned the application to the **Windows Devices** security group.
6. Reviewed and created the deployment.
7. Verified the application properties and assignment.

## **Screenshots**
<img width="1918" height="1008" alt="Image 1" src="https://github.com/user-attachments/assets/5995b077-818e-4511-a895-08cdcf9b6fb8" />
<img width="1918" height="1010" alt="Image 2" src="https://github.com/user-attachments/assets/e04679e6-09ab-41d5-9f38-c8cc372f83c9" />
<img width="1918" height="1010" alt="Image 3" src="https://github.com/user-attachments/assets/4ff1280c-157c-4810-af39-40a4197577e0" />

---

# **Scenario 2 – Deploy a Built-in Android Application**

A built-in Android application was deployed using Microsoft Intune's Built-in app catalogue. Microsoft Edge was selected and assigned to an Android security group, demonstrating how Microsoft applications can be quickly deployed without requiring installation packages.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Apps → All Apps → Add**.
2. Selected **Built-in app**.
3. Chose **Microsoft Edge (Android)**.
4. Assigned the application to the Android security group.
5. Created the deployment.
6. Verified the application properties.

## **Screenshots**
<img width="1918" height="1010" alt="Image 4" src="https://github.com/user-attachments/assets/e841eb13-9062-463e-890e-e85a043f05c1" />
<img width="1918" height="1010" alt="Image 5" src="https://github.com/user-attachments/assets/9ce75fe3-62db-476d-a0ab-38592eb64461" />

---

# **Scenario 3 – Deploy an iOS App Store Application**

An iOS application was deployed from the Apple App Store using Microsoft Intune. Microsoft Outlook was selected, assigned to an iOS device group, and verified within the iOS application inventory to demonstrate centralized application management for Apple devices.

## **Steps Performed**

1. Navigated to **Microsoft Intune → Apps → All Apps → Add**.
2. Selected **iOS Store app**.
3. Searched for **Microsoft Outlook**.
4. Selected the application.
5. Assigned the application to the **iOS Devices** security group.
6. Reviewed and created the deployment.
7. Verified the application properties and deployment within the iOS application inventory.

## **Screenshots**
<img width="1917" height="1006" alt="Image 6" src="https://github.com/user-attachments/assets/6221c495-d5d6-4023-9c42-00ec182ba9b5" />
<img width="1918" height="1010" alt="Image 7" src="https://github.com/user-attachments/assets/91816d6d-c6e3-4e92-bd5e-996b30d4f8f7" />
<img width="1916" height="1007" alt="Image 8" src="https://github.com/user-attachments/assets/822729f5-15f0-4af2-835c-dad7db960391" />

---

# **Recommendations**

Based on this lab, the following best practices are recommended:

- Deploy applications through Microsoft Intune to centrally manage software distribution across multiple platforms.
- Use security groups to target application deployments to specific users or device collections.
- Validate application assignments after deployment to ensure successful distribution.
- Utilize Built-in applications where available to simplify Microsoft application deployment.
- Regularly review application inventories within Intune to verify deployment status and maintain application compliance.

---

# **Conclusion**

This lab demonstrated how Microsoft Intune provides centralized application deployment across Windows, Android, and iOS platforms. Applications were successfully deployed from the Microsoft Store, the Built-in application catalogue, and the Apple App Store, then assigned to device groups for targeted deployment. Reviewing application properties and inventories confirmed successful configuration, demonstrating how Microsoft Intune simplifies enterprise application management while providing consistent software deployment across multiple operating systems.
