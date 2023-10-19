# 第六回課題
1. CloudTrail のイベント情報

![Alt text](img/lesson6/cloud_trail1.png)
lesson5のインスタンスの起動時のイベント情報

![Alt text](img/lesson6/cloud_trail2.png)
セキュリティグループの変更

![Alt text](img/lesson6/cloud_trail3.png)
cloud trailのログ記録の開始

2.  CloudWatchアラームで、ALBのアラームを設定して、メール通知をする

![Alt text](img/lesson6/unhealty_count.png)
unhealty_countが0以上の時、メールするように設定。また、OKの時もメールするように設定

![Alt text](img/lesson6/unhealty_alarm.png)
サンプルアプリを停止し、alarmのメールが来ることを確認。

![Alt text](img/lesson6/unhealty_ok.png)
サンプルアプリを再起動し、OKのステータスになったことの確認のメールがくる。

3. AWS 利用料の見積  
https://calculator.aws/#/estimate?id=c439b06c107373119a66453739196aaed37f758b

4. AWSの利用料

![Alt text](img/lesson6/%E5%85%88%E6%9C%88%E3%81%AEec2.png)
先月分のec2の請求

![Alt text](img/lesson6/%E4%BB%8A%E6%9C%88%E3%81%AE%E8%AB%8B%E6%B1%82.png)
今月の請求　Elastic IPアドレスの分、無料利用枠を超えている