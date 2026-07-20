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

# Lab 4 – Microsoft Entra ID User and Group Management

## **Objective**

The objective of this lab was to manage users and groups within Microsoft Entra ID by creating user accounts, configuring user properties, reviewing sign-in activity, managing deleted users, configuring Self-Service Password Reset (SSPR), creating Microsoft 365 and Security groups, assigning group members, and implementing dynamic group membership rules based on user attributes.

---

# **Scenario 1 – Create a New User**

A new Microsoft Entra ID user account was created with basic identity information and additional organizational properties. The account was then reviewed within the Users list to verify successful creation.

## **Steps Performed**

1. Navigated to **Microsoft Entra Admin Center → Users → New User**.
2. Entered the user's identity information.
3. Configured user properties including job title, department, and company.
4. Reviewed and created the user account.
5. Verified the user within the Microsoft Entra Users list.

## **Screenshots**
<img width="1918" height="1011" alt="Image 1" src="https://github.com/user-attachments/assets/7dfa8082-3e1c-4232-b8ec-fbdbfb17a6fe" />
<img width="1918" height="1011" alt="Image 2" src="https://github.com/user-attachments/assets/8e7ffe73-0f8f-43f6-9a49-4640a1d6cf11" />
<img width="1918" height="1008" alt="Image 3" src="https://github.com/user-attachments/assets/55643529-8029-45ff-bd45-f0d3dbfa0d9e" />

---

# **Scenario 2 – Review User Sign-in Logs**

Microsoft Entra ID sign-in logs were reviewed to monitor authentication activity, successful sign-ins, and user access information.

## **Steps Performed**

1. Navigated to **Microsoft Entra Admin Center → Users → Sign-in Logs**.
2. Reviewed recent user authentication events.
3. Verified successful sign-in activity and associated details.

## **Screenshots**
<img width="1918" height="1010" alt="Image 4" src="https://github.com/user-attachments/assets/3512a619-e433-49b7-841d-fe8e3c2d4cd8" />

---

# **Scenario 3 – Manage Deleted Users**

Deleted user accounts were reviewed within Microsoft Entra ID to demonstrate the ability to restore or permanently remove user accounts during the retention period.

## **Steps Performed**

1. Navigated to **Microsoft Entra Admin Center → Users → Deleted Users**.
2. Reviewed recently deleted user accounts.
3. Verified available restore and permanent deletion options.

## **Screenshots**
<img width="1918" height="1010" alt="Image 5" src="https://github.com/user-attachments/assets/474d893c-616b-4b0d-8d61-eb09af36dc3e" />

---

# **Scenario 4 – Configure Self-Service Password Reset (SSPR)**

Self-Service Password Reset settings were reviewed to demonstrate how organizations can allow users to securely reset their own passwords while reducing administrative workload.

## **Steps Performed**

1. Navigated to **Microsoft Entra Admin Center → Password Reset**.
2. Reviewed the Self-Service Password Reset configuration.
3. Examined the available deployment options.

## **Screenshots**
<img width="1918" height="1010" alt="Image 6" src="https://github.com/user-attachments/assets/5425e8a8-01ed-4aec-871c-548f6ace864e" />

---

# **Scenario 5 – Create Microsoft 365 and Security Groups**

Both Security Groups and Microsoft 365 Groups were created to demonstrate different group types available within Microsoft Entra ID for permission management, collaboration, and resource access.

## **Steps Performed**

1. Navigated to **Microsoft Entra Admin Center → Groups → New Group**.
2. Created a Security Group.
3. Created a Microsoft 365 Group.
4. Reviewed all groups within the Groups dashboard.

## **Screenshots**
<img width="1918" height="1010" alt="Image 7" src="https://github.com/user-attachments/assets/8a03f0cf-7a18-424f-aa00-3cb0588ad9b5" />
<img width="1918" height="1010" alt="Image 8" src="https://github.com/user-attachments/assets/009bbd2d-cddc-4a42-888f-0d39084f9fee" />
<img width="1918" height="1010" alt="Image 9" src="https://github.com/user-attachments/assets/4211fd55-fc0f-46d9-b58d-1fd58079b328" />

---

# **Scenario 6 – Add Members to an Assigned Security Group**

Users were manually assigned to a Security Group to demonstrate role-based access management and centralized user administration.

## **Steps Performed**

1. Opened the Security Group.
2. Selected **Members → Add Members**.
3. Selected users to add to the group.
4. Saved the changes.
5. Verified successful group membership.

## **Screenshots**
<img width="1918" height="1008" alt="Image 10" src="https://github.com/user-attachments/assets/98027d8b-c34d-4d44-b7ad-007a1c85d716" />
<img width="1918" height="1008" alt="Image 11" src="https://github.com/user-attachments/assets/75c5d62d-5099-4c0b-a570-e3bc0bd0a12b" />

---

# **Scenario 7 – Configure Dynamic Membership Rules**

A Dynamic User Security Group was created using department-based membership rules. Microsoft Entra ID automatically evaluated user attributes and assigned eligible users to the group.

## **Steps Performed**

1. Created a new Security Group.
2. Selected **Dynamic User** as the membership type.
3. Configured a dynamic membership rule using the **Department** attribute.
4. Saved the rule.
5. Verified automatic user membership.

## **Screenshots**
<img width="1918" height="1008" alt="Image 12" src="https://github.com/user-attachments/assets/63306b2c-d2f9-465b-85db-85d1bbe54442" />
<img width="1918" height="1008" alt="Image 13" src="https://github.com/user-attachments/assets/d31c656d-dc89-4278-b0a3-3f71f086434d" />
<img width="1918" height="1011" alt="Image 14" src="https://github.com/user-attachments/assets/194d0c0a-c1ef-4a9b-a3e7-ec6509d056bd" />

---

# **Recommendations**

Based on this lab, the following best practices are recommended:

- Use Microsoft Entra ID to centrally manage user identities and organizational groups.
- Monitor sign-in logs regularly to identify unusual authentication activity.
- Configure Self-Service Password Reset (SSPR) to reduce administrative overhead while improving user productivity.
- Use Security Groups to simplify permission management and application assignments.
- Use Microsoft 365 Groups to support collaboration across Microsoft 365 services.
- Implement Dynamic Groups where possible to automate membership based on user attributes and reduce manual administration.

---

# **Conclusion**

This lab demonstrated core identity and access management tasks within Microsoft Entra ID. User accounts were created and configured, authentication activity was reviewed, deleted users were managed, Self-Service Password Reset settings were examined, multiple group types were created, users were assigned to Security Groups, and Dynamic Groups were configured using department-based membership rules. These administrative tasks demonstrate essential Microsoft Entra ID skills used to manage users, automate group membership, strengthen identity security, and simplify administration within modern Microsoft 365 environments.

# Lab 5 – Microsoft Intune Device Enrollment Configuration

## **Objective**

The objective of this lab was to configure Microsoft Intune enrollment settings used to onboard and manage Windows devices. This included configuring Automatic Enrollment, managing Device Enrollment Limits, creating Enrollment Notifications for Windows devices, and reviewing Windows Hello for Business settings to strengthen authentication and streamline the device enrollment process.

---

# **Scenario 1 – Configure Automatic Enrollment**

Automatic Enrollment was configured to allow Windows devices joined to Microsoft Entra ID to automatically enroll into Microsoft Intune for centralized device management.

## **Steps Performed**

1. Navigated to **Microsoft Intune Admin Center → Devices → Enrollment → Automatic Enrollment**.
2. Configured the **MDM User Scope** to **All**.
3. Verified the default MDM enrollment URLs.
4. Confirmed the Windows Information Protection (WIP) configuration.
5. Saved the enrollment configuration.

## **Screenshots**
<img width="1918" height="1010" alt="Image 1" src="https://github.com/user-attachments/assets/2e99565d-ae22-4a92-aaa9-1e3a9b50ad30" />

---

# **Scenario 2 – Configure Device Enrollment Limits**

Device Enrollment Limits were reviewed to control the maximum number of devices a user can enroll into Microsoft Intune.

## **Steps Performed**

1. Navigated to **Devices → Enrollment → Device Limit Restrictions**.
2. Opened the default enrollment restriction.
3. Reviewed the maximum device enrollment limit.
4. Verified the device limit configuration.

## **Screenshots**
<img width="1918" height="1010" alt="Image 2" src="https://github.com/user-attachments/assets/bad60566-262b-4761-9b5b-17e9d59205c3" />

---

# **Scenario 3 – Create an Enrollment Notification**

An Enrollment Notification was created to automatically notify users when a Windows device has successfully enrolled into Microsoft Intune.

## **Steps Performed**

1. Navigated to **Devices → Enrollment → Enrollment Notifications**.
2. Created a new Windows Enrollment Notification.
3. Enabled Push Notifications.
4. Configured the notification subject and enrollment message.
5. Assigned the notification to the **Windows Devices** security group.
6. Reviewed the configuration before deployment.
7. Created the notification.
8. Verified the notification within the Enrollment Notifications dashboard.

## **Screenshots**
<img width="1918" height="1010" alt="Image 3" src="https://github.com/user-attachments/assets/12d59b71-41b1-4f04-87cd-be747e644d11" />
<img width="1918" height="1010" alt="Image 4" src="https://github.com/user-attachments/assets/142d9d98-df1a-458a-878f-55d9c6502309" />
<img width="1918" height="1010" alt="Image 5" src="https://github.com/user-attachments/assets/0bcbfbf3-e010-4d06-9f89-9c0d800f28f6" />
<img width="1918" height="1011" alt="Image 6" src="https://github.com/user-attachments/assets/e42b140b-5685-47d3-9860-07d8824c5267" />

---

# **Scenario 4 – Configure Windows Hello for Business**

Windows Hello for Business settings were reviewed to demonstrate how organizations configure passwordless authentication using PINs, biometrics, and Trusted Platform Module (TPM) security.

## **Steps Performed**

1. Navigated to **Devices → Enrollment → Windows Hello for Business**.
2. Reviewed the Windows Hello for Business configuration.
3. Verified TPM requirements.
4. Reviewed PIN configuration settings.
5. Confirmed Windows Hello for Business was enabled for users.

## **Screenshots**
<img width="1918" height="1010" alt="Image 7" src="https://github.com/user-attachments/assets/daa7a99d-71ec-45d9-8379-5ac65e15893b" />

---

# **Recommendations**

Based on this lab, the following best practices are recommended:

- Configure Automatic Enrollment to simplify Windows device onboarding into Microsoft Intune.
- Apply Device Enrollment Limits to prevent excessive device registrations.
- Implement Enrollment Notifications to keep users informed during the enrollment process.
- Enable Windows Hello for Business to strengthen endpoint authentication using passwordless sign-in methods.
- Regularly review enrollment policies to ensure devices are onboarded securely and consistently across the organization.

---

# **Conclusion**

This lab demonstrated the foundational Microsoft Intune enrollment settings required before deploying managed Windows devices. Automatic Enrollment was configured to streamline device onboarding, Device Enrollment Limits were reviewed to control user registrations, Enrollment Notifications were created to provide user feedback during enrollment, and Windows Hello for Business settings were examined to strengthen authentication. Together, these configurations establish a secure and standardized enrollment process for Windows devices within Microsoft Intune.

# Lab 6 - Action1 RMM Endpoint Management

## Objective

This lab demonstrates the use of Action1 Remote Monitoring and Management (RMM) to onboard managed endpoints, deploy third-party software, install Windows updates, remediate vulnerabilities, generate hardware inventory reports, and monitor automation tasks. These activities showcase essential endpoint management, patch management, reporting, and automation capabilities used by IT administrators.

---

## Scenario 1 – Onboard a Windows Endpoint

### Steps Performed

1. Downloaded the Action1 Windows agent.
2. Verified the downloaded installer.
3. Confirmed the Action1 Agent was available in Microsoft Intune.
4. Verified the endpoint successfully appeared in the Action1 console.

### Screenshots
<img width="1918" height="1010" alt="Image 1" src="https://github.com/user-attachments/assets/9d29dc05-1089-49a9-86c9-9b8fcfa6ff30" />
<img width="1918" height="1010" alt="Image 2" src="https://github.com/user-attachments/assets/17fafda1-947a-4cc5-a956-cd65f2ad99d6" />
<img width="1918" height="1010" alt="Image 3" src="https://github.com/user-attachments/assets/48b31f35-c47f-4ddd-a00e-5ced9fa4b6cd" />
<img width="1918" height="1010" alt="Image 4" src="https://github.com/user-attachments/assets/ac08f5a9-8048-49e7-bdfb-11ec6f19d2a5" />

---

## Scenario 2 – Deploy Third-Party Software

### Steps Performed

1. Created a software deployment automation.
2. Selected Google Chrome and Adobe Acrobat Reader.
3. Configured the deployment automation.
4. Verified the deployment completed successfully.

### Screenshots
<img width="1918" height="1008" alt="Image 5" src="https://github.com/user-attachments/assets/9d5ac9bc-b587-4788-a074-fdb2c812f870" />
<img width="1918" height="1010" alt="Image 6" src="https://github.com/user-attachments/assets/389f3912-7277-4a7c-8ff9-c2535090c323" />
<img width="1918" height="1011" alt="Image 7" src="https://github.com/user-attachments/assets/537602a8-dc41-4864-a60b-0cc31b477735" />
<img width="1918" height="1010" alt="Image 8" src="https://github.com/user-attachments/assets/a9db72e8-a9e0-41c3-8903-a2e5e7cfd90f" />

---

## Scenario 3 – Deploy Windows Updates

### Steps Performed

1. Reviewed available Windows updates.
2. Selected a pending security update.
3. Deployed the update to the managed endpoint.

### Screenshots
<img width="1918" height="1010" alt="Image 9" src="https://github.com/user-attachments/assets/fb384050-b214-4795-8dcf-73f7819de2af" />

---

## Scenario 4 – Remediate Vulnerabilities

### Steps Performed

1. Reviewed detected vulnerabilities.
2. Selected an affected endpoint.
3. Initiated vulnerability remediation.

### Screenshots
<img width="1918" height="1010" alt="Image 10" src="https://github.com/user-attachments/assets/aca396c9-378b-4621-86a2-a53faed0c0fa" />

---

## Scenario 5 – Generate Hardware Inventory Reports

### Steps Performed

1. Accessed the Hardware Summary report.
2. Reviewed endpoint hardware information.
3. Generated an inventory report.

### Screenshots
<img width="1918" height="1008" alt="Image 11" src="https://github.com/user-attachments/assets/ffed7197-b9e8-4750-9d69-aa4d63bf3714" />

---

## Scenario 6 – Review Automation History

### Steps Performed

1. Opened Automation History.
2. Reviewed completed deployment and remediation tasks.
3. Verified successful execution of automation jobs.

### Screenshots
<img width="1918" height="1011" alt="Image 12" src="https://github.com/user-attachments/assets/e3c6f201-9927-47a0-a49a-ab1d65c528e3" />

---

## Scenario 7 – Review Automation Details

### Steps Performed

1. Opened the deployment job details.
2. Reviewed each deployment task performed.
3. Verified successful completion of all deployment actions.

### Screenshots
<img width="1918" height="1010" alt="Image 13" src="https://github.com/user-attachments/assets/e6aff238-d5eb-46ef-87e0-462dcd01a66b" />

---

## Recommendations

- Use automation policies to standardize software deployment across managed endpoints.
- Regularly deploy Windows and third-party application updates to reduce security risks.
- Monitor vulnerabilities and remediate critical issues promptly.
- Review automation history to verify successful task execution and troubleshoot failed deployments.
- Generate hardware inventory reports to support asset management and lifecycle planning.

---

## Conclusion

This lab demonstrated how Action1 can be used to manage Windows endpoints through centralized automation. The exercises covered endpoint onboarding, software deployment, Windows patch management, vulnerability remediation, reporting, and automation monitoring. Together, these tasks provide a practical overview of how RMM platforms streamline endpoint administration, improve security posture, and reduce manual management effort in enterprise environments.
