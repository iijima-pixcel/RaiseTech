# CloudFormationによる環境のコード化  
CloudFormationにより、第五回課題の環境を構築しました。　　

CloudFormationテンプレートはスタック分割を行い、以下の3層構造にしました。  
1. application layer
2. security layer
3. network layer  
* CloudFormationテンプレートのコードは**l10cloud-formation**ディレクトリに保存しました。  

以下にスタック作成したときにできたリソースの画像を添付します。

# 構築された環境
- スタック作成でできたリソース群
![Alt text](img/lesson10/l10net-stack-source.png)
![Alt text](img/lesson10/l10security-stack-source.png)
![Alt text](img/lesson10/l10ap-stack-source.png)
- vpc
![Alt text](img/lesson10/l10vpc.png)
- ec2のセキュリティグループ
![Alt text](img/lesson10/l10ec2security.png)
- rdsのセキュリティグループ
![Alt text](img/lesson10/l10rdssecurity.png)
- albのセキュリティグループ
![Alt text](img/lesson10/l10albsecurity.png) 
- 作成されたec2
![Alt text](img/lesson10/l10ec2.png)
- 作成されたrds
![Alt text](img/lesson10/l10rds.png)
- 作成されたalbのリスナーとルール
![Alt text](img/lesson10/l10alb.png)
- albのターゲットグループ
![Alt text](img/lesson10/l10albtarget.png)　 
- 作成されたs3
![Alt text](img/lesson10/l10s3.png)
