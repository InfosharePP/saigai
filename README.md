# 災害対応アプリケーションを使用したPower Appsソリューションテンプレート
(Disaster Countermeasures for Microsoft Dataverse environment, built by Infoshare Inc.)

<p align="center">	
<img alt="download" src="https://img.shields.io/github/downloads/InfosharePP/saigai/total?color=brightgreen.svg"/>	
</p>

## はじめに

**
アプリケーション概要

COVID-19の世界的流行や集中豪雨や台風による激甚災害の頻発により、地方自治体の業務継続計画の重要性がより一層増しております。  
災害対応アプリケーションは、緊急事態の混乱の中で錯綜する情報を迅速に把握できるよう、多岐にわたる被害やそれらへの対応状況、避難所の利用状況、職員の安否情報などに関する入力フォーム、入力された情報を自動的に集約、見える化するダッシュボードなどを提供するサンプルテンプレートです。  
平時に職員や組織の情報、収容人数やペットの受け入れ可否、設備状況などの避難所に関する情報など、災害対応に必須となる情報の整備を行い、   
緊急時に、職員はモデル駆動アプリケーション上で、「いつ、だれが受け付け、どこの、どのような内容を、だれから入手したか」といった時系列に沿う、クロノロジー型の情報の記録が簡便に行えます。
さらに、記録された情報は自動的に集計され、見える化されたダッシュボードとして閲覧できます。   
職員の安否確認については、「[安否確認アプリケーション](https://github.com/InfosharePP/anpi)」の機能を搭載しており、職員の安否確認を迅速に行えます。  
本テンプレートは、利用に際しMicrosoft Dataverseのライセンスを必要とし、Power Appsキャンバスアプリケーションとモデル駆動型アプリケーションを使用します。


## 構成内容
本テンプレートは次の要素で構成されています
 1. Microsoft Dataverseに展開するソリューション（マネージド・アンマネージド）
 2. エンドユーザー利用Power Appsキャンバスアプリケーション(安否確認アプリケーション)
 3. 管理者向け展開ガイド
 4. エンドユーザー向け利用者ガイド
 
## 展開・利用に必要な条件
本テンプレートを展開・利用するには有償のPower Appsライセンスが必要です。詳しくは下記をご参照いただくか、日本マイクロソフト担当者までお問い合わせください。
[https://powerapps.microsoft.com/ja-jp/pricing/](https://powerapps.microsoft.com/ja-jp/pricing/)

## 必要なMicrosoft Dataverseソリューション
本キャンバスアプリを利用するには、Microsoft Dataverse環境とMicrosoft Dataverseソリューションが展開されている必要があります。

## 準備されている言語
本テンプレートは日本語で準備されており、日本語にのみ対応します。

## 主な機能
緊急時に地方自治体が錯綜する情報を迅速に把握できるよう、「情報収集」「情報集約」を中心に、以下の代表的な機能があります。

 - 各種マスタの記録・閲覧：災害対応に必須となる、災害の定義、施設情報、対応の記録、被害報告（公式ソース）、状況報告などの情報の記録・閲覧が可能
 - 全体レポートの閲覧：記録された情報を自動的に集約し、見える化したダッシュボードである災害サマリーの閲覧が可能
 - 職員の安否確認: 「[安否確認アプリケーション](https://github.com/InfosharePP/anpi)」の機能を搭載しており、職員の安否確認を迅速に行うことが可能

 
**各種マスタの記録・登録 <災害の定義>**
![災害の定義](https://infoshare.co.jp/wp-content/uploads/2021/06/1_災害の定義.png)

**各種マスタの記録・登録 <施設情報>**
![災害の定義](https://infoshare.co.jp/wp-content/uploads/2021/06/2_施設情報.png)

**各種マスタの記録・登録 <市民提供情報>**
![災害の定義](https://infoshare.co.jp/wp-content/uploads/2021/06/3_市民提供情報.png)

**各種マスタの記録・登録 <対応状況>**
![災害の定義](https://infoshare.co.jp/wp-content/uploads/2021/06/4_対応状況.png)

**各種マスタの記録・登録 <対応状況のパソコンからの記録>**
![災害の定義](https://infoshare.co.jp/wp-content/uploads/2021/06/5_対応状況_記録PC.png)

**各種マスタの記録・登録 <対応状況のスマートフォンからの記録>**
![災害の定義](https://infoshare.co.jp/wp-content/uploads/2021/05/6_対応状況_記録SP.png)

**全体レポートの閲覧**
![災害サマリー](https://infoshare.co.jp/wp-content/uploads/2021/06/7_災害サマリー.png)

**安否確認の報告および閲覧**
![安否確認の報告および閲覧](https://infoshare.co.jp/wp-content/uploads/2021/05/5_安否確認の報告・閲覧.png)


## ダウンロード
以下のリンクより最新版バージョンをダウンロードいただけます。  
    [最新のリリースページへ移動](https://github.com/InfosharePP/saigai/releases/)


## 展開方法
管理者向け展開ガイドを参照してください

## マネージドソリューションとアンマネージドソリューション
2種類のソリューションを用意しています。インストールにはマネージドソリューションを使用することをおすすめします。アンマネージドは開発環境への展開や、追加の開発・カスタマイズを実施する環境で展開してください。

## FAQ

 - Q.内容や機能をカスタマイズすることは可能ですか？
	 - A.可能です。カスタマイズすることを前提にシンプルで汎用的な作りになっています
 
 - Q.展開パートナーはどのように見つけることができますか？
	 - A.日本マイクロソフト担当者までお問い合わせください


**免責事項**

本テンプレートはサンプルであり、Microsoft Power Appsにおいて、参考情報の提供や、個人と企業のコミュニケーションを促進する目的でのみ使用することができます。本テンプートおよび関連サービスは、恒久的なアプリケーション使用を意図したものではありません。インフォシェア株式会社、また日本マイクロソフトはそのような目的で本テンプレートおよび関連サービスを使用するライセンスや権利を本テンプレート利用組織に付与していません。
本テンプレートおよび関連サービスは、各企業のニーズを全て含めるように設計されたものではなく、そのような用途で使用されるものではありません。実際の利用や必要な追加のカスタマイズは導入支援パートナーに確認・依頼してください。
本テンプレートおよび関連サービスのいかなる使用においても、利用者がすべてリスクと責任を負うものとします。また、実装した本テンプレートおよび関連マイクロソフト サービスの使用に関して、適切な警告や情報をエンドユーザーに提供することについても、利用者が責任を負うものとします。
本テンプレートは、日本国内での使用のみを目的とし、欠陥などがある可能性を含んだままの状態で提供されており、いかなる種類の保証も適用されません。
