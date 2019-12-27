### Steps of Zero Trust
##### ゼロトラストのステップ

ZTA requires three fundamental steps, applied at the level of applications and services within the network:  
ZTAには、3つの基本的な手順が必要です。これらは、ネットワーク内でアプリケーションとサービスのレベルで適用されます。  

1. Verify the user (authentication, part 1)  
ユーザーを確認します。（認証、パート１）  
1. Verify the device (authentication, part 2)   
デバイスを確認します。（認証、パート２）  
1. Verify access privileges (authorization)   
アクセス権限を確認する（承認）  

These three layers of verification are accomplished through a series of compliance checks based on the characteristics of each.  
検証のこれら3つの層は、それぞれの特徴に基づいた一連のコンプライアンスチェックによって実現されます。

These compliance checks can include information ranging from device encryption to user patterns of behavior, and can continue to expand as more information about users and devices is collected.  
これらのコンプライアンスチェックはデバイスの暗号化からユーザーのふるまいパターンの情報まで含めることができ、ユーザーやデバイスに関する情報をさらに収集し、拡張し続けることができます。

Failing any of these checks will label the user or device as “non-compliant” and deny access to that user or device.  
これらのチェックのいずれかに失敗すると、ユーザーまたはデバイスに「非準拠」のラベルが付けられ、そのユーザーまたはデバイスへのアクセスを拒否します。

While it is optimal to maintain a common set of compliance checks across a network and organization using modernized software systems, it is still possible to implement this critical piece of zero trust into networks that are dispersed and use legacy hardware and software, as in the case of DoD.  
近代化されたソフトウェアシステムを使用して、ネットワークおよび組織全体でコンプライアンスチェックの共通セットを維持することが最適ですが、DoDの場合のように、分散され、レガシーハードウェアおよびソフトウェアを使用するネットワークでもゼロトラストの重要な部分を実装することはまだ可能です。  

DoD Service-or agency-specific applications and systems can be built to have their own compliance checks, driving all users and devices that interface with them to adhere to those rulesets.  
DoDサービスまたはエージェンシー固有のアプリケーションとシステムは、独自のコンプライアンスチェックを持ち、そのルールを順守するためにそれらと接続しているユーザーとデバイスが駆動するように構築することができます。

This in turn can influence users and devices outside the orbit of those Services/agencies, which must similarly comply with those requirements to gain access.  
これは、それらのサービス・エージェンシーの範囲外のユーザーとデバイスに影響を及ぼす可能性があり、同様にこれらの要件に準拠する必要があります。

In this way, a ZTA can act as a virus (albeit a secure, trustworthy virus), “infecting” third party users or devices by forcing them to meet compliance standards if they hope to gain access.  
この方法では、ZTAはウイルス（安全で信頼できるウイルスではありますが）として機能し、サードパーティのユーザーやデバイスに「感染」し、アクセスを希望する場合は、コンプライアンス基準を満たすよう強制します。

This in turn will make it easier for those third parties to eventually implement zero trust into their own applications and services, as they will already have certain standards of compliance on which they can build.   
これは、サードパーティが既に特定のコンプライアンス基準を持っている独自のアプリケーションやサービスの中で、最終的にゼロトラストを実装するのを容易にします。  

Compliance metrics can (and should) be iterative.   
コンプライアンスメトリックは反復可能です（反復する必要があります）。  

ZTA can begin with a set of modest identity and device health checks, then develop a more sophisticated set over time depending on the sensitivity of the applications and services in question and the desired restrictions on access.  
ZTAは控えめなIDおよびデバイスのヘルスチェックのセットから始めることができます。そして問題のアプリケーションとサービスの機密性、およびアクセスの望ましい制限について、時間に応じてより洗練されたセットを開発します。

Each “generation” of compliance checks will have the ability to add more nuance to access control as more information about users and devices is collected, building a more comprehensive digital picture of them.  
コンプライアンスチェックの各「世代」には、それらのより包括的なデジタル状態の構築がされ、ユーザーとデバイスに関する詳細情報が収集されるため、アクセス制御に差異を追加する機能を持たせます。

These checks will ensure not only the identity, but the integrity of users and devices: while identity checks will map the characteristics of each, integrity checks can run health diagnostics on devices to look for compromise.  
これらのチェックにより、IDだけでなく、ユーザーとデバイスの整合性を確保します。IDチェックはそれぞれの特性をマッピングしますが、整合性チェックでは、デバイスのヘルス診断を実行して、セキュリティ侵害を探します。 

If a device has the appropriate characteristics but demonstrates compromise (e.g., lack of encryption, virus infection), then the device will be deemed non-compliant and will be denied access.  
もしデバイスが適切な特性を持ち、セキュリティ侵害（例：暗号化の欠如、ウイルス感染）を示せば、デバイスは非準拠とみなされ、アクセスが拒否されます。

One such identity check includes the management of certificates, which will help verify identity in ZTA by pairing public keys with the devices requesting access to an application or service.  
このようなIDチェックの1つに、証明書の管理が含まれ、ZTAでの公開鍵をアプリケーションまたはサービスへのアクセスを要求するデバイスとペアリングによるIDの検証に役立ちます。

While certificates on their own may be stolen or imitated, ZTA protects against this risk by including certificates and public keys as one attribute for users and devices that must be corroborated with multiple other attributes in order to authenticate and grant a request for access.  
証明書自体が盗まれたり模倣されたりする可能性がありますが、証明書と公開鍵を含める必要があるユーザーとデバイスの1つの属性として認証を行い、アクセスのリクエストを許可するために、他の複数の属性で裏付けることにより、ZTAはこのリスクから保護します。

Additionally, certificates can be strengthened by including both user and device data into the certificate, requiring verification of both to enable access for either.  
さらに、検証の中にユーザーとデバイスの両方のデータを含めることと、いずれかのアクセスを有効にするために両方の検証が必要とすることにより、証明書を強化できます。

In advanced ZTA, this health inspection may ultimately be applied to the application or service being accessed  
高度なZTAでは、この健全性検査は最終的にアプリケーションまたはアクセスされているサービスに適用される場合があります。

　- once the access requester has been verified, the zero trust model might then query the access destination to ensure the security of that destination.  
アクセス依頼者（要求？）が確認されると、ゼロトラストモデルはアクセス先を照会して、その宛先のセキュリティを確保します。

By transitioning from a “one-way handshake” to a “two-way handshake” model, an organization can better ensure that neither the users and devices nor the applications and services are compromised and infect one another.  
「一方向ハンドシェイク」から「双方向ハンドシェイク」モデルへ移行することにより、組織はより確実にユーザーとデバイスもアプリケーションとサービスも侵害されず、互いに感染することもありません。

More advanced forms of ZTA can also protect applications and services by applying microsegmentation to discrete areas within each application and service, building specific access rules for each of those areas.  
ZTAのより高度な型式は、各アプリケーションおよびサービス内の個別エリアへのマイクロセグメンテーション、特定のこれらの各領域のアクセスルールの構築を適用することによりアプリケーションとサービスを保護することもできます。

This methodology would protect against adversaries that penetrated the network perimeter and the application or service itself, limiting the data access and maneuverability of those adversaries.  
この方法論は、ネットワークの境界、アプリケーションもしくはサービス自体に侵入した敵から保護し、データアクセスや敵の機動性を制限します。

As in the case of microsegmentation at the application and service level, microsegmentation within those entities should require authentication and authorization specific to the subsegment in question, enabling a more precise “least-privilege access” model of security.   
アプリケーションとサービスレベルでのマイクロセグメンテーションの場合のように、それらのエンティティ内のマイクロセグメンテーションには、問題のサブセグメントに固有の認証と、セキュリティのより正確な「最小特権アクセス」モデルの認可を必要とします。
