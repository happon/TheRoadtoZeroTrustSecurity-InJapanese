### What is Zero Trust?
##### ゼロトラストは何ですか？
ZTA moves away from the perimeter approach and instead assumes, as the name would suggest, zero trust in the network itself.  
ZTAは、境界アプローチから遠ざかり、名称が示すように、代わりにネットワーク自体への信頼をゼロにすることを想定します。  

By assuming that the network is compromised, security can take a more nuanced approach by guarding access to the resources within the network and building strong authentication and authorization standards to allow specific access based on user- and device-specific attributes.  
ネットワークが危険にさらされていると想定することにより、セキュリティは、ネットワーク内のリソースへのアクセスを保護することと、強力な認証とユーザーおよびデバイス固有の属性に基づいて特定のアクセスを許可する認証基準の構築により、絶妙なアプローチをとることができます。  

ZTA operates on a “least-privilege access” model by only granting users and devices access to the applications, services and data that are absolutely necessary for their role within an organization.  
ZTAは、ユーザーとデバイスに対し、組織内の役割に絶対必要なアプリケーション、サービス及びデータへのアクセスのみ許可することにより、「最小特権アクセス」モデルで動作します。  

By using “role” as a centerpiece for determining access, an organization can share its resources and data with more precision, and quickly expand or limit a user’s access as he or she takes on different roles.  
アクセスを決定する最も重要な事項として「役割」を使用することにより、組織はリソースとデータをより正確に共有でき、ユーザーが様々な役割を引き受けるときにユーザーのアクセスを迅速に拡張・制限することができます。  

Perimeter security will continue to serve as the first line of defense, but blind reliance on it will increase the risk of network breach and data interception.  
境界セキュリティは引き続き防御の最前線として機能しますが、それに対する盲目的な依存はネットワーク侵害とデータ傍受のリスクを高めます。  

ZTA can gap-fill for perimeter security by catching network breachers at the next layer of access, matching the identity of users and devices to authorizations associated with those users and devices to ensure access is granted appropriately and securely.  
ZTAは、アクセスの次の層でネットワーク侵害者を捕まえ、ユーザーのIDを照合し、デバイスがそれらのユーザーとデバイスに関連付けられた認証にアクセスして、アクセスが許可されていることを適切かつ安全に確認することにより、境界セキュリティのギャップを埋めることができます。

ZTA shifts the emphasis from the perimeter of a network to the discrete applications and services within a network, building more specific access controls to those specific resources.  
ZTAは、ネットワークの境界から重点を、ネットワーク内の個別のアプリケーションとサービス、より具体的なアクセス制御を構築するそれらの特定のリソースへとシフトします。  

This method of wrapping security around applications and services is known as “microsegmentation,” and it allows for more targeted security and management of access beyond traditional perimeter security.  
アプリケーションとサービスの周辺にセキュリティをラップするこの方法は、「マイクロセグメンテーション」として知られ、よりターゲットを絞ったセキュリティと従来の境界セキュリティを超えたアクセスの管理を可能にします。  

By decreasing reliance on security around the perimeter of a network, the security of the data packets going in and out of a ZTA system becomes even more critical.  
ネットワークの境界周辺のセキュリティへの依存を減らすことにより、ZTAシステムを出入りするデータパケットのセキュリティはさらにクリティカルなものになります。  

As a result, encryption of those data packets is one of the most fundamental requirements of any ZTA, and should be standard in any good security architecture and data transfer (including protocols like SSL and TLS).  
その結果、それらのデータパケットの暗号化は、あらゆるZTAの最も重要な要件の一つであり、優れたセキュリティアーキテクチャとデータ転送（SSLやTLSのようなプロトコルを含む）の基準となるべきです。  

The authentication and authorization process is also critical to the success of ZTA because it provides explicit verification of users and devices for each application and service, rather than implicit verification that assumes safety and grants access once a user and device has entered into the network.  
認証および承認プロセスもまた、ZTAの成功のため重要です。なぜならそれは、安全を前提としてユーザーとデバイスに一度アクセスを許可しネットワークに入れてしまう暗黙の検証ではなく、各アプリケーションとサービスのユーザーとデバイスの明示的な検証を提供するためです。
