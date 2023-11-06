# CloudFormationによる環境のコード化  
CloudFormationにより、第五回課題の環境を構築しました。　　

CloudFormationテンプレートはスタック分割を行い、以下の3層構造にしました。  
1. Application Layer
2. Security Layer
3. Network Layer  
* CloudFormationテンプレートのコードは**l10cloud-formation**ディレクトリに保存しました。  

以下にスタック作成したときにできたリソースの画像を添付します。

# 構築された環境
- スタック作成でできたリソース群
![Alt text](img/lesson10/L10-Network-Stack-Resource.png)
![Alt text](img/lesson10/L10-Security-Stack-Resource.png)
![Alt text](img/lesson10/L10-App-Stack-Resource.png)
- VPC
![Alt text](img/lesson10/L10-Vpc.png)
- EC2のセキュリティグループ
![Alt text](img/lesson10/Ec2-Security.png)
- RDSのセキュリティグループ
![Alt text](img/lesson10/RDS-Security.png)
- ALBのセキュリティグループ
![Alt text](img/lesson10/ALB-Security.png)
- 作成されたEC2
![Alt text](img/lesson10/L10-Ec2.png)
- 作成されたRDS
![Alt text](img/lesson10/L10-Rds.png)
- 作成されたALBのリスナーとルール
![Alt text](img/lesson10/L10-Alb.png)
- ALBのターゲットグループ
![Alt text](img/lesson10/L10-Alb-Tg.png)
- 作成されたS3
![Alt text](img/lesson10/L10-S3.png)
