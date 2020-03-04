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

### Certificate authority:
“Certificate authority” (CA) is a trusted entity that issues and manages digital certificates used for secure communication in a public network.

CA confirms the ownership of public keys associated with the subject of the certificate.

In zero trust, CA will serve a critical function in verifying content and content sources at the application and service level.

### Identity and Access Management:
“Identity and Access Management” (IAM) includes the processes, policies, and technologies that enable verification of users and devices requesting access to applications and services within a network. 

This includes the “authentication” and “authorization” mechanisms of ZTA.

“Privileged Identity Management” (PIM) falls under the category of IAM and assigns varying degrees of access to different tiers of users, allowing the access controller to better monitor “Privileged Identities” (PIs) that have higher levels of permission.

### Least-privilege access:
“Least-privilege access” is a core principle of zero trust, and requires that users and devices only be granted access to the information, applications, and services absolutely necessary for them to function.

Least-privilege access can also be referred to as “Principle of Least Privilege” (PoLP).

### Key management:
“Key management” refers to the protection, storage, back up, and organization of encryption keys used to protect data being transferred between end points.

In the context of a zero trust network, encryption becomes increasingly important as a method of protecting data traveling across the network.

Public Key Infrastructure (PKI) manages the creation and assignment of digital certificates and their accompanying encrypted public keys.

### Microsegmentation:
“Microsegmentation” is a method of creating secure zones within the network at the applications and services layer or below to allow better monitoring of lateral network traffic and management of access to those zones.

Microsegmentation could enable zero trust principles by allowing administrators to control authentication and authorization at a more granular level than the network perimeter. 

### Perimeter model:
“Perimeter model” refers to the traditional method of cybersecurity, which focuses on the defense of the edge of a network, or network “perimeter.”

Once users and devices are granted access to the network, they are more easily able to move laterally into different applications and services within the network.

### Secure Sockets Layer/Transport Layer Security Encryption:
Secure Sockets Layer (SSL) and its follow-on, Transport Layer Security (TLS), are cryptographic protocols that protect data being transferred between end points by verifying connection security and performing “handshake” authentication between a client and a server. 
