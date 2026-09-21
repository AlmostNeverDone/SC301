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
* Microsoft Entra admin center (Microsoft Entra 管理中心)</b>
* Microsoft 365 admin center (Microsoft 365 管理中心)</b>

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
* The green-bordered area contains sample data, the blue-bordered area contains newly added users, <br/>and the red-bordered area contains required data that must be filled in before uploading.<br/>
綠色框線區域為範本資料，藍色框線區域為本次新增使用者，紅色框線處則是上傳前必填資料<br/>
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

---------

<h2>Results｜專題結論</h2>

This project provided practical experience with fundamental identity and user administration tasks in Microsoft Entra ID. The workflow covered user provisioning, sign-in validation, service license assignment, external guest onboarding, directory role assignment, and bulk user creation.

本專題提供 Microsoft Entra ID 基礎身分與使用者管理的實務操作經驗，流程涵蓋使用者帳號建立、登入驗證、服務授權指派、外部 Guest 使用者建立、目錄角色指派，以及批次使用者建立。

The project demonstrated that identity administration involves more than simply creating user accounts. User properties such as usage location, user type, licensing status, and assigned directory roles can directly affect the services and administrative capabilities available to each identity. External user invitation demonstrated how Microsoft Entra ID supports collaboration with identities outside the organization while maintaining a separate Guest user classification within the tenant. The directory role exercises also demonstrated multiple administrative workflows for assigning built-in Microsoft Entra roles, while bulk user provisioning introduced a more scalable approach to creating multiple identities through CSV-based operations.

本專題展示身分管理不僅是建立使用者帳號，Usage Location、User Type、License 狀態以及目錄角色等使用者屬性，都可能直接影響身分可使用的服務與管理權限。外部使用者邀請流程則展示 Microsoft Entra ID 如何支援組織外部身分進行協作，同時透過 Guest 使用者類型在租戶中維持不同的身分分類。目錄角色實作展示了使用不同管理介面指派 Microsoft Entra 內建角色的方式；批次使用者建立則進一步導入以 CSV 為基礎的大量帳號建立流程，提升使用者管理的可擴展性。

Overall, the project demonstrated a basic identity lifecycle workflow in Microsoft Entra ID, from initial account provisioning and service enablement to external collaboration, administrative delegation, and scalable user management.

整體而言，本專題展示了 Microsoft Entra ID 中基礎的身分生命週期管理流程，從帳號建立與服務啟用，到外部協作、管理權限委派，以及可擴展的使用者管理方式。

<br />
<br />

<br />
<br />


---------

<h2>Security Insight｜安全洞察</h2>


Identity Lifecycle Management (身分生命週期管理)

User provisioning should be treated as part of an identity lifecycle rather than as an isolated account creation task. Creating an identity, validating access, assigning required services, reviewing privileges, and managing the account at scale are interconnected administrative activities.

使用者建立應視為身分生命週期的一部分，而非單純的帳號建立操作。建立身分、驗證存取、指派所需服務、檢視權限，以及大量管理帳號，皆屬於彼此關聯的身分管理流程。


User Attributes and Service Access (使用者屬性與服務存取)

Identity attributes can directly affect access to cloud services. During the lab, license assignment depended on the user having a valid Usage Location, demonstrating that incomplete or incorrect identity properties can cause downstream access and provisioning failures.

身分屬性會直接影響雲端服務的存取與配置。本實驗中，License 指派需要使用者具備有效的 Usage Location，說明不完整或錯誤的身分屬性可能導致後續的存取與服務配置失敗。


External Identity Management (外部身分管理)

Microsoft Entra ID allows external collaborators to be represented as Guest users within the tenant. Separating external identities from internal Members helps administrators apply different access policies and maintain clearer visibility over users who originate outside the organization.

Microsoft Entra ID 可將外部協作者以 Guest 使用者形式建立於租戶中。將外部身分與內部 Member 分類管理，有助於套用不同的存取政策，並提升對組織外部使用者的可視性。


Role-Based Administrative Delegation (角色式管理權限委派)

Directory roles allow administrative permissions to be delegated according to operational responsibilities rather than granting unrestricted administrative access. Built-in roles provide a structured way to separate responsibilities and support the principle of least privilege.

目錄角色可依據實際管理職責委派行政權限，而非直接授予不受限制的管理權限。Microsoft Entra 內建角色提供結構化的權限分工方式，有助於實踐最小權限原則。


Bulk Provisioning and Validation (批次建立與驗證)

Bulk user creation improves scalability but also increases the impact of configuration errors. CSV-based provisioning should therefore be followed by validation of bulk operation results and the resulting user objects instead of assuming that a successful submission means every account was created successfully.

批次建立使用者能提升管理效率，但設定錯誤的影響範圍也會同步擴大。因此使用 CSV 進行大量帳號建立後，應進一步驗證 Bulk Operation 結果與實際產生的使用者物件，而不能僅依據提交成功訊息判斷所有帳號皆已建立完成。


Administrative Verification (管理操作驗證)

Identity administration should include verification after each significant change. Sign-in testing, reviewing assigned licenses, confirming Guest user type, checking directory role assignments, and validating bulk-created accounts help ensure that configuration changes produce the intended result.

身分管理中的重要變更完成後應進行驗證。透過登入測試、確認 License 狀態、驗證 Guest 使用者類型、檢查目錄角色，以及確認批次建立帳號結果，可確保實際設定符合原先預期。


<br />
<br />

---------

<h2>Reference｜參考</h2>

* [Microsoft] [Microsoft Certified: Identity and Access Administrator Associate (SC-300)](https://learn.microsoft.com/en-us/credentials/certifications/identity-and-access-administrator/?practice-assessment-type=certification)<br/>
* [Microsoft] [Get started with identity and access labs](https://learn.microsoft.com/en-au/training/modules/get-started-identity-access-labs/)<br/>
<br/>
