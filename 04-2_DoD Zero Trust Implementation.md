### Questions to Ask When Implementing  
##### ゼロトラストを実装するときのQ&A

Zero Trust Implementing ZTA involves a gradual shift across the entire network, services, and computing devices space.  
ZTAの実装には、ネットワーク全体、サービス、およびコンピューティングデバイススペース全体にわたる段階的な移行が伴います

Implementation is a journey that can result in a successively more secure organization with each additional step taken.  
実装は、安全性を継続的に高めることができる旅です

Below are a set of questions you can ask to see if your organization is effectively implementing ZTA.  
以下は、あなたの組織がZTAを効果的に実装するときに、あなたが確認できる質問集です。

1. In a world where the network boundary cannot be trusted, encryption of data in transit and at rest is critical.  
ネットワーク境界が信頼できない世界では、転送中および保存中のデータの暗号化はとても重要です。

  Does your organization have a plan to ensure that 100% of data transmitted between devices and stored on mass storage is securely   encrypted?  
組織には、デバイスと大容量記憶装置に保存されているデータは安全に暗号化され、データの100％が確実に送信されるようにする計画がありますか？

  Does the organization have a robust and secure encryption key management strategy?  
  組織には、堅牢で安全な、暗号化キーの管理戦略はありますか？
<br>
  
2. Many recent cybersecurity exploits leverage the vulnerability of the network boundary to access incompletely secured systems accessible in the network.  
最近の多くのサイバーセキュリティエクスプロイトは、ネットワーク境界の脆弱性を活用してネットワーク内でアクセス可能な不完全に保護されたシステムにアクセスします。  
  It is critical to ensure that piercing the network perimeter does not enable network access.  
ネットワーク境界を穴をあけても、ネットワークアクセスは有効にならないことを確認することが重要です。

  Is your organization aggressively searching for and reducing traditional inside the network vulnerabilities, such as data stored in u nsecured locations, excessive use of service accounts, and standing administration privileges?  
あなたの組織は、安全でない場所に保存されたデータ、過度の使用などのネットワークの脆弱性、サービスアカウントの数及び永続的な管理権限のような、ネットワーク内の従来からの脆弱性を積極的に検索し、削減していますか？
<br>
  
3. ZTA requires verification of the true identity of the user and device accessing a system.  
ZTAでは、システムにアクセスするユーザーとデバイスの真のIDの検証が必要です。

Is your organization enforcing Multi-factor Authentication on 100% of the services and servers available to users on all end user, devices including mobile devices?  
あなたの組織は、全てのエンドユーザー、モバイルを含むデバイスのユーザーが利用できるサーバーとサービスの100％で多要素認証を実施していますか？
<br>

4. Strong ZTA requires verification that only healthy devices can access an organization’s computing resources.  
強力なZTAでは、正常なデバイスのみが組織のコンピューティングリソースにアクセスできることを検証する必要があります。

Does your organization have processes in place to continuously scan all end user devices for malicious software, and is device health a real time criterion for accessing your organization’s services?  
あなたの組織は、適所にエンドユーザーのデバイスを継続的に悪意あるソフトウェアについてスキャンするプロセスはありますか？また、デバイスの健全性は組織のサービスにアクセスするためのリアルタイム基準ですか？
<br>

5. In ZTA, a user’s identity alone should not provide access to the organization’s services.  
ZTAでは、ユーザーのIDだけでは、組織のサービスへのアクセスを提供すべきではありません。

These access rights are strictly applied depending on the user’s role in the organization, and those rights should change whenever that user’s role changes.  
これらのアクセス権は、組織内のユーザーの役割に応じて厳密に適用されますが、そして、それらの権利は、そのユーザーの役割が変更するに変わるべきです。

Does your organization have a strategy in place to apply access rights strictly based on a user’s role and to dynamically change those rights when a user’s role in the organization changes?  
あなたの組織は、厳密にユーザーの役割に基づいてアクセス権を適用し、ユーザーの組織における役割が変更になったとき動的に権限を変更するという戦略を実施していますか？
<br>

6. Ultimately, ZTA espouses that the network boundary provides no protection, and that the most secure services are those resilient enough to connect directly to the internet.  
最終的に、ZTAは、ネットワーク境界が防護を担うのではなく、最も安全なサービスとは、インターネットに直接接続するのに十分な回復力のあるサービスです。

Is your organization planning the migration of all critical services to directly connect to the internet and building the necessary security to enable these services to be secure in this internet-facing construct?  
あなたの組織は、直接インターネットに接続した全ての重要なサービスの移行と、これらのサービスを有効にするために必要なセキュリティの構築を計画していますか？
<br>

7. As ZTA principles and design structures are introduced into a network, they should be built while bearing in mind the future scope and required maintenance of the network.  
ZTAの原則と設計構造がネットワークに導入されると、それはネットワークの将来の範囲と必要なメンテナンスを念頭に置いて構築されています。

Is your organization designing ZTA for scalability, supportability, and life-cycle management?  
あなたの組織は、スケーラビリティ、サポート性、ライフサイクル管理のためのZTAを設計していますか？
<br>

8. While some DoD network requirements are unique to the Department, many others have solutions readily available in the commercial sector.  
国防総省のネットワーク要件には部門固有のものもありますが、他の多くの要件は商業部門ですぐに利用できるソリューションです。

Does your organization have a strategy for determining what you buy (commercially) and what you custom develop (or pay for custom development)?  
あなたの組織は、何を購入するか（商業的に）、何をカスタム開発（またはカスタム開発の支払い）するかを決定する戦略はありますか？
<br>
