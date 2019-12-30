This report is a product of the Defense Innovation Board (DIB).  
このレポートは、Defense Innovation Board（DIB）の製品です。

The DIB is a Federal Advisory Committee established to provide independent advice to the Secretary of Defense.  
DIBは連邦政府諮問委員会であり、国防長官に独立したアドバイスを提供します。

Statements, opinions, conclusions, and recommendations in this report do not necessarily represent the official position of the Department of Defense (DoD).  
これに関する記述、意見、結論、および推奨事項レポートは、国防総省（以下DoD）の公式の立場を必ずしも表すものではありません。

# The Road to Zero Trust (Security) 
# ゼロトラストへの道（セキュリティ）
### Kurt DelBene, Milo Medin, Richard Murray 9 July 2019
### カート デルベネ、ミロ メディン、リチャード マレー 2019年7月9日
### BLUF（Bottom Line Up Front：はじめに結論を述べる）

Zero Trust Architecture (ZTA) has the ability to fundamentally change the effectiveness of security and data sharing across DoD networks.  
Zero Trust Architecture（ZTA）には、DoDネットワーク全体でのセキュリティおよびデータ共有の有効性を根本的に変える能力があります。

From a security perspective, ZTA can better track and block external attackers, while limiting security breaches resulting from internal human error.  
セキュリティの観点から、ZTAは、外部の攻撃者を追跡およびブロックする一方で、内部の人間に起因するセキュリティ侵害を制限することをより良くすることができます。

From a data sharing perspective, ZTA can better manage rules of access for users and devices across DoD to facilitate secure sharing, from the enterprise center to the tactical edge.  
データ共有の観点から、ZTAは、エンタープライズセンターから戦術的な最前線（edge）まで、ユーザーのアクセス規則と安全な共有を促進するDoD全体のデバイスを、より適切に管理することができます。

Furthermore, the network design and flexibility of ZTA will help DoD more rapidly adopt and implement critical network technologies and enablers, ranging from cloud computing to artificial intelligence and machine learning.  
さらに、ZTAのネットワーク設計と柔軟性は、DoDによるクラウドコンピューティングから人工知能・機械学習に及ぶ重要なネットワークテクノロジーとイネーブラーのより迅速な導入と実装を手助けするでしょう。

DoD cybersecurity is at a critical juncture.  
DoDのサイバーセキュリティは重要な時期です。

Its networks are growing in size and complexity, requiring massive amounts of rapid data transfer to maintain situational awareness on the digital and physical battlefield.  
そのネットワークは、デジタルや物理的な戦場の状況認識を維持するために大量の高速データ転送が必要となり、規模と複雑さが増しています。

This expansion is stretching existing cybersecurity apparatuses to their breaking point, as an ever-growing number of users and endpoints increases the attack surface of the network.  
この拡張により、ユーザーとエンドポイントがネットワークの攻撃対象領域を拡大するため、既存の境界点にあるサイバーセキュリティ装置が絶えず増加しています。

This challenge is not unique to DoD - the commercial sector is facing the same challenges, and their networks are constantly building new connections to a broad range of other networks that drive new vulnerabilities.  
この課題はDoDに限ったことではありません-商業部門も同じことに直面しています課題、そしてそれらのネットワークは、新しい脆弱性を引き起こす他の広範囲のネットワークとの新しい接続を常に構築しています。

As a result, public and private sector are reassessing the current method of “perimeter” security and are considering new methods.   
その結果、公共部門と民間部門は再び「境界」セキュリティの現在の方法を評価し、新しい方法を検討しています。 

One such method is “zero trust,” which could drive a step-change in security improvement across commercial and DoD networks.  
そのような方法は「ゼロトラスト」であり、これにより商用およびDoDネットワークのセキュリティの改善に段階的な変化がもたらされる可能性があります。

Zero Trust Architecture (ZTA) can significantly offset vulnerabilities and threats across DoD networks by creating discrete, granular access rules for specific applications and services within a network.  
Zero Trust Architecture（ZTA）は、ネットワーク内の特定のアプリケーションおよびサービスに対する個別の詳細なアクセスルールの作成による、DoDネットワーク全体の脆弱性と脅威を大幅に相殺できます。

Some of the most severe cases of network breaches could have been prevented using basic zero trust principles  
基本的なゼロトラストの原則を使用していれば、ネットワーク侵害の最も深刻なケースのいくつかは防止できた可能性があります。

for example, had ZTA access rules been applied to Edward Snowden, he would have been unable to obtain the broad range of documents that he released to the public.  
たとえば、ZTAアクセスルールがエドワード・スノーデンに適用されていた場合、彼は彼が一般に公開した広範囲の文書を入手できなかったでしょう。

Instead, he was given “system administrator” privileges within the NSA network, which provided him blanket access to resources and files.  
むしろ、彼はNSAネットワーク内での「システム管理者」特権を与えられました。そしてその特権は、彼にリソースとファイルへの包括的なアクセスを提供しました。

This method of blind trust in users and devices inside the perimeter the network is not sustainable, and will continue to put national security information and operations at risk until it is resolved.  
境界内のユーザーとデバイスへの盲目的な信頼のこの方法は、持続可能ではなく、セキュリティ情報と運用は、解決されるまで危険にさらされます。
