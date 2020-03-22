# Zero Trust Starter’s Pack:Glossary
ゼロトラストスターターズパック：用語集  
<br>
### Authentication:「認証」
 “Authentication” is the identity confirmation for users and devices using attributes (e.g., name, location, time, etc.) universally recognized and tracked across the network.  
「認証」とは、ネットワーク全体であまねく認識され、かつ、追跡された属性（名前、場所、時間など）を使用したユーザーとデバイスの本人確認です。

“Multi-factor authentication” (MFA) describes the process of cross-checking multiple attributes to verify identity.  
「多要素認証(MFA)」は、本人確認のための複数の属性をクロスチェックするプロセスを示しています。  
<br>

### Authorization:「承認」
 “Authorization” describes the access privileges granted to users and devices.  
「承認」とは、ユーザーとデバイスに付与されるアクセス権限を示しています。

Perimeter security authorization grants access to the network, while zero trust authorization grants access to individual applications and services within the network. 
境界セキュリティ承認はネットワークへのアクセスを許可し、ゼロトラスト承認は、ネットワーク内の個々のアプリケーションとサービスへのアクセスを許可します。  

Authorization is linked to authentication attributes, and can include “Role-Based Access Control” (RBAC) and “Attribute- Based Access Control” (ABAC), describe different approaches to authorization of user and device access.
承認は、認証属性にリンクされており、ユーザーおよびデバイスへのアクセスの承認に対するさまざまなアプローチを説明する「役割に基づいたアクセス制御(RBAC)」や「属性に基づいたアクセス制御」を含めることができます。  

RBAC provides a common set of access rules based on pre-defined user roles, whereas ABAC provides access based on the combination of multiple user attributes which can include a user’s role. 
RBACは、事前に定義されたユーザーの役割に基づいて、共通のアクセスルールを提供します。一方、ABACは、複数のユーザー属性（ひとりのユーザーの役割を含む）の組み合わせに基づいてアクセスを提供します。  

### Certificate authority:「認証局」
“Certificate authority” (CA) is a trusted entity that issues and manages digital certificates used for secure communication in a public network.  
「認証局」（CA）は、パブリックネットワークでの安全な通信に使用されるデジタル証明書を発行および管理する信頼できる存在です。  

CA confirms the ownership of public keys associated with the subject of the certificate.  
認証局は、証明書のサブジェクトに関連付けられている公開鍵の所有権を確認します。  

In zero trust, CA will serve a critical function in verifying content and content sources at the application and service level.  
ゼロトラストでは、認証局はアプリケーションおよびサービスレベルでコンテンツとコンテンツソースを検証する決定的な機能を果たします。  

### Identity and Access Management:「ＩＤ管理とアクセス管理」
“Identity and Access Management” (IAM) includes the processes, policies, and technologies that enable verification of users and devices requesting access to applications and services within a network.   
「ＩＤ管理とアクセス管理」(IAM)には、ネットワーク内のアプリケーションとサービスへのアクセスを要求するユーザーとデバイスの検証を可能にするプロセス、ポリシー、およびテクノロジーが含まれています。  

This includes the “authentication” and “authorization” mechanisms of ZTA.  
これには、ZTAの「認証」と「承認」メカニズムが含まれています。  

“Privileged Identity Management” (PIM) falls under the category of IAM and assigns varying degrees of access to different tiers of users, allowing the access controller to better monitor “Privileged Identities” (PIs) that have higher levels of permission.  
「特権ＩＤの管理」(PIM)は、IAMのカテゴリーに分類され、さまざまなレベルのアクセスをさまざまなユーザー層に割り当てるため、アクセスコントローラーは、より高いレベルのアクセス許可を持つ "特権ID"（PIs）をより適切に監視できます。  

### Least-privilege access:「最小特権アクセス」
“Least-privilege access” is a core principle of zero trust, and requires that users and devices only be granted access to the information, applications, and services absolutely necessary for them to function.  
「最小特権アクセス」はゼロトラストの基本原則であり、ユーザーとデバイスが機能するために絶対に必要な情報、アプリケーション、およびサービスへのアクセスのみを許可する必要があります。  
Least-privilege access can also be referred to as “Principle of Least Privilege” (PoLP).  
最小特権アクセスは、「最小特権の原則」(PoLP)とも呼ばれます。  

### Key management:「キー管理」
“Key management” refers to the protection, storage, back up, and organization of encryption keys used to protect data being transferred between end points.  
「キー管理」とは、エンドポイント間で転送されるデータを保護するために使用される暗号化キーの保護、保存、バックアップ、および編成を指します。  

In the context of a zero trust network, encryption becomes increasingly important as a method of protecting data traveling across the network.  
ゼロトラストネットワークのコンテキストでは、ネットワーク上を移動するデータを保護する方法として暗号化がますます重要になります。  

Public Key Infrastructure (PKI) manages the creation and assignment of digital certificates and their accompanying encrypted public keys.  
公開鍵基盤（PKI）は、デジタル証明書とそれに付随する暗号化された公開キーの作成と割り当てを管理します。  

### Microsegmentation:「マイクロセグメンテーション」
“Microsegmentation” is a method of creating secure zones within the network at the applications and services layer or below to allow better monitoring of lateral network traffic and management of access to those zones.  
「マイクロセグメンテーション」とは、アプリケーションおよびサービスレイヤー以下でネットワーク内にセキュアゾーンを作成し、横方向のネットワークトラフィックのより良い監視とそれらのゾーンへのアクセス管理を可能にする方法です。  

Microsegmentation could enable zero trust principles by allowing administrators to control authentication and authorization at a more granular level than the network perimeter.   
管理者がネットワーク境界よりも詳細なレベルで認証と承認を制御できるようにすることで、マイクロセグメンテーションは、ゼロ信頼の原則を実現できます。

### Perimeter model:「境界モデル」
“Perimeter model” refers to the traditional method of cybersecurity, which focuses on the defense of the edge of a network, or network “perimeter.”  
「境界モデル」とは、ネットワークの端またはネットワーク「境界」の防御に焦点を当てたサイバーセキュリティの従来の方法を指します。  

Once users and devices are granted access to the network, they are more easily able to move laterally into different applications and services within the network.  
ネットワークへのアクセスが許可されたユーザーとデバイスは、ネットワーク内のさまざまなアプリケーションとサービスに横方向に簡単に移動できます。  

### Secure Sockets Layer/Transport Layer Security Encryption:「SSL／TSL　暗号化」  
Secure Sockets Layer (SSL) and its follow-on, Transport Layer Security (TLS), are cryptographic protocols that protect data being transferred between end points by verifying connection security and performing “handshake” authentication between a client and a server.   
SSLとその後継であるTSLは、接続セキュリティを検証し、クライアントとサーバー間の「ハンドシェイク」認証を実行することにより、エンドポイント間で転送されるデータを保護する暗号プロトコルです。
