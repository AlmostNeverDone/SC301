# Microsoft Entra ID User Management: <br/>Provisioning, Licensing, Roles, and Bulk Operations

Microsoft Entra ID 使用者管理：<br/>帳號建立、授權、角色與批次管理

<br/>

---------

<h2>Outline｜專題簡介</h2>

This project demonstrates fundamental user management operations in Microsoft Entra ID, including user provisioning, sign-in validation, license assignment, external user invitation, directory role assignment, and bulk user creation.

本專題展示 Microsoft Entra ID 中的基礎使用者管理操作，包括使用者帳號建立、登入驗證、授權指派、外部使用者邀請、目錄角色配置，以及批次建立使用者。

The lab simulates common Identity and Access Management (IAM) administrative tasks performed during user onboarding and account management within a cloud identity environment.

本實驗模擬雲端身分環境中常見的身分與存取管理（IAM）工作，包括新使用者建立與帳號管理流程。

The project also demonstrates different methods of assigning directory roles and introduces CSV-based bulk provisioning to improve efficiency when managing multiple user accounts.

本專題同時示範不同的目錄角色指派方式，並導入以 CSV 為基礎的批次帳號建立流程，以提升大量使用者管理時的作業效率。
<br/>

---------

<h2>Key Learning Outcomes｜主要學習成果</h2>

* Create and configure new user accounts in Microsoft Entra ID<br/>
建立與設定 Microsoft Entra ID 使用者帳號

* Validate newly provisioned user accounts through sign-in testing<br/>
透過登入測試驗證新建立的使用者帳號

* Assign Microsoft service licenses to individual users<br/>
為個別使用者指派 Microsoft 服務授權

* Invite external users into an Entra ID tenant<br/>
邀請外部使用者加入 Entra ID 租戶

* Understand the difference between internal members and external users<br/>
理解內部成員與外部使用者的基本差異

* Assign Microsoft Entra directory roles to users<br/>
為使用者指派 Microsoft Entra 目錄角色

* Explore different role assignment workflows through user and role management interfaces<br/>
透過使用者與角色管理介面操作不同的角色指派流程

* Understand Active and Eligible role assignment options<br/>
理解 Active 與 Eligible 角色指派方式

* Perform bulk user provisioning using CSV templates<br/>
使用 CSV 範本批次建立使用者帳號

* Validate successfully created users after provisioning operations<br/>
於帳號建立完成後驗證使用者建立結果
<br/>

---------

<h2>Tools and Concepts Covered｜涵蓋工具與概念</h2>

| Category 分類                                      | Tools / Concepts 工具 / 概念       |
| ------------------------------------------------ | ------------------------------ |
| Cloud Identity Management <br/>雲端身分管理          | Microsoft Entra ID |
| User Provisioning <br/>使用者建立                    | User account creation<br/>使用者帳號建立 |
| User Validation <br/>使用者驗證                      | Sign-in testing<br/>登入測試 |
| User Types <br/>使用者類型                           | Member and External User<br/>內部成員與外部使用者 |
| External Identity <br/>外部身分                      | External user invitation<br/>外部使用者邀請 |
| License Management <br/>授權管理                     | Microsoft 365 Admin Center |
| Role Management <br/>角色管理                        | Microsoft Entra Roles & Administrators |
| Role Assignment <br/>角色指派                        | Active and Eligible assignments<br/>Active 與 Eligible 指派 |
| Identity Administration <br/>身分管理                | Microsoft Entra Admin Center |
| Bulk User Management <br/>批次使用者管理              | Bulk Create |
| Data Import <br/>資料匯入                            | CSV user provisioning template<br/>CSV 使用者建立範本 |
| Identity and Access Management <br/>身分與存取管理     | User lifecycle administration<br/>使用者生命週期管理 |


<br/>

---------

<h2>Materials and Methods｜材料與方法</h2>

[Environment]

* Microsoft Azure Portal (Azure 雲端管理平台)</b>
* Microsoft Entra ID tenant (Entra ID 租戶環境)</b>
* Azure Resource Group (Azure 資源群組)</b>

[Tasks]

* Create a New User (建立新用戶)
* Add a license to the user (為使用者新增許可證)
* Invite an external user (邀請外部用戶)
* Assign a role to a user (為使用者指派角色)
* Bulk import users (批次導入用戶)
<br/>

---------

<h2>Practice｜實踐</h2> <p align="center">

<p align="center">
<b>Task 1-1: Create a New User Account<br/> (建立新使用者帳號)</b><br/>
<img src="https://i.imgur.com/90xDZpo.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Created a new user account in Microsoft Entra ID and configured the required identity properties for cloud access.<br/>
在 Microsoft Entra ID 中建立新的使用者帳號，並設定雲端存取所需的基本身分屬性<br/>
<br />
<br />
<b>Task 1-2: Validate New User Sign-In<br/> (驗證新使用者登入)</b><br/>
<img src="https://i.imgur.com/N3oXIvR.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Signed in with the newly provisioned account to verify that <br/>the user could successfully authenticate to the Microsoft Entra environment.<br/>
使用新建立的帳號登入 Microsoft Entra 環境，確認使用者帳號能夠成功完成身分驗證<br/>
<br />
<br />
<b>Task 2: Assign a License to the User<br/> (為使用者指派授權)</b><br/>
<img src="https://i.imgur.com/dWrJHlF.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Assigned a Microsoft service license to the newly created user through the Microsoft 365 Admin Center.<br/>
透過 Microsoft 365 Admin Center 為新建立的使用者指派 Microsoft 服務授權<br/>
<br />
<br />
<b>Task 3: Invite an external user<br/> (邀請外部用戶)</b><br/>
<img src="https://i.imgur.com/xvMrkGq.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Invited an external user to the Microsoft Entra tenant to demonstrate external identity onboarding<br/> and cross-organization access scenarios.<br/>
邀請外部使用者加入 Microsoft Entra 租戶，以示範外部身分建立與跨組織存取情境<br/>
<br />
<br />
<b>Task 4-1: Assign an Eligible Directory Role<br/> (指派 Eligible 目錄角色)</b><br/>
<img src="https://i.imgur.com/cVnVND5.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Assigned the Attribute Definition Reader role to the user using the Eligible assignment type.<br/>
使用 Eligible 指派方式，為使用者配置 Attribute Definition Reader 目錄角色<br/>
<br />
<br />
<b>Task 4-2: Assign a Directory Role through Roles & Administrators<br/> (透過 Roles & Administrators 指派目錄角色)</b><br/>
<img src="https://i.imgur.com/8Ex31LG.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Assigned the Attribute Log Reader role through the Roles & Administrators interface and verified the resulting role assignment.<br/>
透過 Roles & Administrators 介面指派 Attribute Log Reader 角色，並驗證角色指派結果<br/>
<br />
<br />
<b>Task 5-1: Prepare the Bulk User CSV Template<br/> (準備批次使用者 CSV 範本)</b><br/>
<img src="https://i.imgur.com/SvAymsA.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Prepared a CSV-based user provisioning file using the Microsoft Entra bulk user template.<br/>
使用 Microsoft Entra 批次使用者範本準備 CSV 帳號建立檔案<br/>
<br />
<br />
<b>Task 5-2: Bulk Create and Validate Users<br/> (批次建立並驗證使用者)</b><br/>
<img src="https://i.imgur.com/GuHbMdh.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Uploaded the CSV provisioning file and verified that multiple user accounts were successfully created in Microsoft Entra ID.<br/>
上傳 CSV 使用者建立檔案，並確認多個使用者帳號已成功建立於 Microsoft Entra ID<br/>
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
