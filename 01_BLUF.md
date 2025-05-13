
This report is a product of the Defense Innovation Board (DIB).
The DIB is a Federal Advisory Committee established to provide independent advice to the Secretary of Defense.
Statements, opinions, conclusions, and recommendations in this report do not necessarily represent the official position of the Department of Defense (DoD).

# The Road to Zero Trust (Security)
Kurt DelBene, Milo Medin, Richard Murray – 9 July 2019

### BLUF (Bottom Line Up Front)
Zero Trust Architecture (ZTA) has the ability to fundamentally change the effectiveness of security and data sharing across DoD networks.
From a security perspective, ZTA can better track and block external attackers, while limiting security breaches resulting from internal human error.
From a data sharing perspective, ZTA can better manage rules of access for users and devices across DoD to facilitate secure sharing, from the enterprise center to the tactical edge.
Furthermore, the network design and flexibility of ZTA will help DoD more rapidly adopt and implement critical network technologies and enablers, ranging from cloud computing to artificial intelligence and machine learning.

DoD cybersecurity is at a critical juncture.
Its networks are growing in size and complexity, requiring massive amounts of rapid data transfer to maintain situational awareness on the digital and physical battlefield.
This expansion is stretching existing cybersecurity apparatuses to their breaking point, as an ever-growing number of users and endpoints increases the attack surface of the network.
This challenge is not unique to DoD – the commercial sector is facing the same challenges, and their networks are constantly building new connections to a broad range of other networks that drive new vulnerabilities.
As a result, public and private sector are reassessing the current method of “perimeter” security and are considering new methods.
One such method is “zero trust,” which could drive a step-change in security improvement across commercial and DoD networks.
Zero Trust Architecture (ZTA) can significantly offset vulnerabilities and threats across DoD networks by creating discrete, granular access rules for specific applications and services within a network.
Some of the most severe cases of network breaches could have been prevented using basic zero trust principles – for example, had ZTA access rules been applied to Edward Snowden, he would have been unable to obtain the broad range of documents that he released to the public.
Instead, he was given “system administrator” privileges within the NSA network, which provided him blanket access to resources and files.
This method of blind trust in users and devices inside the perimeter the network is not sustainable, and will continue to put national security information and operations at risk until it is resolved.

このレポートは、Defense Innovation Board（DIB：国防イノベーション委員会）によって作成されたものです。
DIBは国防長官に対して独立した助言を行うことを目的に設置された連邦政府の諮問委員会です。
本レポートに記載されている意見、結論、提言等は、必ずしも国防総省（DoD）の公式見解を示すものではありません。

# ゼロトラストへの道（セキュリティ）
カート・デルベネ、ミロ・メディン、リチャード・マレー
2019年7月9日

### はじめに（BLUF）
Zero Trust Architecture（ZTA：ゼロトラスト・アーキテクチャ）は、DoDネットワーク全体におけるセキュリティとデータ共有の効果を根本的に変える可能性を持っています。

セキュリティの観点では、ZTAは外部の攻撃者の追跡および遮断をより適切に行うとともに、内部の人的ミスによるセキュリティ侵害の影響を抑えることができます。

データ共有の観点では、ZTAはDoD内のユーザーやデバイスに対するアクセスルールをより適切に管理し、エンタープライズの中枢から最前線の現場まで、安全な情報共有を可能にします。

さらに、ZTAのネットワーク設計と柔軟性は、クラウドコンピューティングから人工知能（AI）、機械学習（ML）に至るまで、重要なネットワーク技術やその基盤の導入・実装を迅速に推進するうえで、DoDにとって大きな支援となるでしょう。

現在、DoDのサイバーセキュリティは重大な転換点にあります。
ネットワークの規模と複雑性が増す中で、デジタルおよび物理的な戦場における状況認識を維持するためには、膨大かつ迅速なデータ転送が求められています。

このような拡張により、増え続けるユーザーとエンドポイントによって攻撃対象領域（アタックサーフェス）が拡大し、従来のサイバーセキュリティ体制は限界に達しつつあります。

この課題はDoDだけでなく、民間部門にも共通しています。
民間ネットワークも他の多種多様なネットワークと新たな接続を次々と築いており、それによって新たな脆弱性が生まれています。

その結果、公的・民間の双方が、これまでの「境界防御型セキュリティ」の手法を見直し、新たなアプローチの検討を始めています。

その一つが「ゼロトラスト」であり、商用ネットワークとDoDネットワークの双方において、セキュリティの抜本的な改善をもたらす可能性があります。

ZTAは、ネットワーク内の特定アプリケーションやサービスに対して個別かつ詳細なアクセスルールを設定することで、DoD全体の脆弱性や脅威を大幅に緩和することができます。

実際、ゼロトラストの基本原則を適用していれば、防げたであろう深刻なネットワーク侵害の事例も存在します。

たとえば、ZTAのアクセス制御がエドワード・スノーデンに適用されていれば、彼が公開した大量の機密文書にアクセスすることはできなかったはずです。

しかし実際には、NSAネットワーク内で「システム管理者」権限が彼に与えられたことで、あらゆるリソースやファイルに無制限のアクセスが可能となっていました。

このように、ネットワーク内部のユーザーやデバイスに対して無条件に信頼を置く仕組みはもはや持続可能ではなく、改善されない限り国家の安全保障情報や運用を危険にさらし続けることになります。

