# Microsoft Entra ID User Management Practice

Microsoft Entra ID 使用者管理實作

<br/>

---------

<h2>Outline｜專題簡介</h2>

This project demonstrates basic identity administration tasks in Microsoft Entra ID, covering user creation, license assignment, external user invitation, role assignment, and bulk user provisioning.

本專題實作 Microsoft Entra ID 的基礎身分管理工作，涵蓋使用者建立、授權指派、外部使用者邀請、角色指派，以及批次使用者佈建。

In this scenario, we use both the Microsoft Entra admin center and Microsoft 365 admin center to manage user identities and related access settings.

在本案中，我們將同時使用 Microsoft Entra 管理中心和 Microsoft 365 管理中心來管理使用者身分和相關的存取設定。
<br/>

---------

<h2>Key Learning Outcomes｜主要學習成果</h2>

* Create and verify user accounts in Microsoft Entra ID<br/>
建立並驗證 Microsoft Entra ID 使用者帳戶

* Assign a Microsoft license to a user<br/>
為使用者指派 Microsoft 授權

* Invite and manage an external user as a guest<br/>
邀請並管理外部使用者

* Assign directory roles to users and configure assignment types<br/>
為使用者指派目錄角色並設定角色指派類型

* Perform bulk user provisioning using a CSV template<br/>
使用 CSV 範本進行批次使用者佈建

* Understand basic identity administration workflows across Microsoft Entra ID and Microsoft 365<br/>
理解 Microsoft Entra ID 與 Microsoft 365 中的基礎身分管理流程
<br/>

---------

<h2>Tools and Concepts Covered｜涵蓋工具與概念</h2>

| Tools and Concepts                | 工具與概念                     |
| --------------------------------- | ------------------------- |
| Microsoft Entra ID                | Microsoft Entra 身分識別與存取管理 |
| Microsoft Entra admin center      | Microsoft Entra 管理中心      |
| Microsoft 365 admin center        | Microsoft 365 管理中心        |
| User Management                   | 使用者管理                     |
| User Accounts                     | 使用者帳戶                     |
| User Principal Name               | 使用者主體名稱 (UPN)                  |
| Member and Guest Users            | 成員與來賓使用者                  |
| Microsoft License Assignment      | Microsoft 授權指派            |
| External User / Guest Invitation  | 外部使用者／來賓邀請                |
| Microsoft Entra Directory Roles   | Microsoft Entra 目錄角色      |
| Role Assignment                   | 角色指派                      |
| Eligible Assignment               | 可啟用的角色指派                  |
| Active Assignment                 | 啟用中的角色指派                  |
| Bulk User Creation                | 批次使用者建立                   |
| CSV User Provisioning             | CSV 使用者佈建                 |
| Multi-Factor Authentication       | 多因素驗證 (MFA)                    |


<br/>

---------

<h2>Materials and Methods｜材料與方法</h2>

[Environment]

* Microsoft Azure Portal (Azure 雲端管理平台)</b>
* Microsoft Entra ID tenant (Entra ID 租戶環境)</b>
* Azure Resource Group (Azure 資源群組)</b>

[Tasks]

* Prepare Azure Environment and Resource Group (準備 Azure 環境與資源群組)
* Create Test Storage Account (建立測試儲存體帳戶)
* Create Security Group in Entra ID (建立 Entra ID 安全性群組)
* Create New User Account (建立新使用者帳戶)
* Add User to Security Group (將使用者加入安全性群組)
* Assign Reader Role at Resource Group Scope (於資源群組範圍指派 Reader 角色)
* Verify Effective Permissions with IAM (使用 IAM 驗證有效權限)
* Review RBAC Activity Logs (檢視 RBAC 活動記錄)
* Enable Temporary Access Pass (啟用臨時存取通行證)
* Generate TAP for New User (為新使用者產生 TAP)
* Validate Least-Privilege Access Model (驗證最小權限存取模型)
<br/>

---------

<h2>Practice｜實踐</h2> <p align="center">

<p align="center">
<b>Task 1: Prepare Azure Environment and Resource Group<br/> (準備 Azure 環境與資源群組)</b><br/>
<img src="https://i.imgur.com/VMFYfoX.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 2: Create Test Storage Account<br/> (建立測試儲存體帳戶)</b><br/>
<img src="https://i.imgur.com/yVu7sLp.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 3: Create Security Group in Entra ID<br/> (建立 Entra ID 安全性群組)</b><br/>
<img src="https://i.imgur.com/DJn5GGI.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 4: Create New User Account<br/> (建立新使用者帳戶)</b><br/>
<img src="https://i.imgur.com/8jHy811.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 5: Add User to Security Group<br/> (將使用者加入安全性群組)</b><br/>
<img src="https://i.imgur.com/SZ6YEpF.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Group-based access control simplifies permission management by assigning permissions to groups instead of individual users.<br/> 群組式存取控制可透過群組集中管理權限，而非逐一指派給個別使用者<br/>
<br />
<br />
<b>Task 6: Assign Reader Role at Resource Group Scope<br/> (於資源群組範圍指派 Reader 角色)</b><br/>
<img src="https://i.imgur.com/WQBu73g.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* The Reader role allows viewing Azure resources while preventing modification or deletion actions.<br/> Reader 角色允許檢視 Azure 資源，但禁止修改或刪除操作<br/>
<br />
<br />
<b>Task 7: Verify Effective Permissions with IAM<br/> (使用 IAM 驗證有效權限)</b><br/>
<img src="https://i.imgur.com/N14ZufQ.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* IAM Check Access validates inherited permissions and confirms effective RBAC access at the selected scope.<br/> IAM Check Access 可驗證繼承權限，並確認使用者於指定範圍內的有效 RBAC 存取權限<br/>
<br />
<br />
<b>Task 8: Review RBAC Activity Logs<br/> (檢視 RBAC 活動記錄)</b><br/>
<img src="https://i.imgur.com/HpN5jQT.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Azure Activity Logs provide audit trails for RBAC configuration changes and administrative actions.<br/> Azure Activity Log 可提供 RBAC 設定變更與管理操作的稽核紀錄<br/>
<br />
<br />
<b>Task 9: Enable Temporary Access Pass<br/> (啟用臨時存取通行證)</b><br/>
<img src="https://i.imgur.com/rvvzAeV.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Temporary Access Pass (TAP) enables secure onboarding without requiring immediate MFA device enrollment.<br/> 臨時存取通行證(TAP) 可在尚未完成 MFA 裝置註冊前提供安全登入方式<br/>
<br />
<br />
<b>Task 10: Generate TAP for New User<br/> (為新使用者產生 TAP)</b><br/>
<img src="https://i.imgur.com/DohgHxw.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* TAP provides temporary time-limited authentication credentials for secure first-time access.<br/> TAP 提供具時效性的臨時驗證憑證，用於安全的首次登入流程<br/>
<br />
<br />
<b>Task 11-1: Sign in as Restricted User<br/> (以受限權限使用者登入)</b><br/>
<img src="https://i.imgur.com/5g8Kczd.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* The user successfully inherited Reader permissions through group membership.<br/> 使用者成功透過群組繼承 Reader 權限<br/>
<br />
<br />
<b>Task 11-2: Validate Least-Privilege Restriction<br/> (驗證最小權限限制)</b><br/>
<img src="https://i.imgur.com/ResVJsw.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Write operations were blocked as expected, validating the least-privilege access model.<br/> 系統成功阻止寫入操作，驗證最小權限模型運作正常<br/>
<br />
<br />

  
---------

<h2>Results｜專題結論</h2>

This project demonstrated how Microsoft Entra ID and Azure RBAC can be used to implement a structured least-privilege access model within a cloud environment.

本專題展示了如何利用 Microsoft Entra ID 與 Azure RBAC，在雲端環境中實作具結構性的最小權限存取模型。

Through the creation of users, security groups, RBAC role assignments, and Temporary Access Pass (TAP) authentication workflows, the project successfully simulated a realistic employee onboarding and access validation process in Microsoft Azure.

透過建立使用者、安全性群組、RBAC 角色指派，以及臨時存取通行證（TAP）驗證流程，本專題成功模擬了 Microsoft Azure 中貼近實務的新進人員帳號建立與權限驗證流程。

The lab also demonstrated how Azure IAM tools and Activity Logs can be used to verify effective permissions and audit administrative actions. By testing access using a restricted Reader account, the project confirmed that users could view resources while being prevented from performing unauthorized modifications.

本實驗同時展示如何利用 Azure IAM 工具與 Activity Log 驗證有效權限與稽核管理操作。透過使用受限的 Reader 帳號進行測試，成功確認使用者能夠檢視資源，但無法執行未授權的修改操作。

Overall, the project provided practical experience in identity management, RBAC configuration, secure onboarding workflows, and cloud access validation practices commonly used in enterprise Azure environments.

整體而言，本專題提供了企業 Azure 環境中常見的身分管理、RBAC 權限配置、安全帳號啟用流程，以及雲端存取驗證的實務操作經驗。

<br />
<br />


---------

<h2>Security Insight｜安全洞察</h2>


Group-based RBAC significantly improves access management scalability and security consistency. Instead of assigning permissions directly to individual users, organizations can centrally manage permissions through security groups, reducing administrative complexity and minimizing configuration errors.

群組式 RBAC 可大幅提升權限管理的可擴展性與安全一致性。組織可透過安全性群組集中管理權限，而非直接對個別使用者逐一授權，藉此降低管理複雜度與設定錯誤風險。

The project also highlights the importance of the least-privilege principle in cloud environments. Even though the user account successfully authenticated and accessed Azure resources, RBAC restrictions prevented unauthorized resource creation and modification activities.

本專題同時凸顯最小權限原則在雲端環境中的重要性。即使使用者成功完成驗證並存取 Azure 資源，RBAC 限制仍有效阻止未授權的資源建立與修改行為。

Temporary Access Pass (TAP) provides a secure onboarding mechanism for newly created accounts by allowing temporary authentication without requiring immediate MFA device enrollment. However, TAP should be tightly controlled, monitored, and disabled when no longer required to reduce potential abuse risks.

臨時存取通行證(TAP) 提供了一種安全的新帳號啟用機制，使使用者在尚未完成 MFA 裝置註冊前仍可進行臨時驗證。然而 TAP 應受到嚴格控管、監控，並於不再需要時停用，以降低潛在濫用風險。

Azure Activity Logs and IAM validation tools also demonstrate the importance of visibility and auditing within cloud security operations. Administrative actions such as RBAC role assignments can leave clear audit trails, helping organizations support incident investigation, compliance, and security monitoring.

Azure Activity Log 與 IAM 驗證工具則展現了雲端安全營運中「可視性（Visibility）」與「稽核（Auditing）」的重要性。RBAC 角色指派等管理操作皆會留下清楚的稽核紀錄，有助於組織進行事件調查、法規遵循與安全監控。

From a defensive perspective, properly scoped RBAC assignments, centralized identity management, MFA enforcement, and continuous auditing are critical components of securing enterprise cloud environments.

從防禦角度而言，正確範圍的 RBAC 權限配置、集中式身分管理、多因素驗證（MFA）以及持續性稽核，皆是保護企業雲端環境的重要核心要素。



<br />
<br />

---------

<h2>Reference｜參考</h2>

* [Microsoft] [Microsoft Certified: Azure Fundamentals (AZ-900)](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/?practice-assessment-type=certification)<br/>
* [Microsoft] [Apply Azure skills in guided projects](https://learn.microsoft.com/en-us/training/paths/introduction-cloud-infrastructure-apply-azure-skills-guided-projects/)<br/>
<br/>
