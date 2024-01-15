# Service Studio
OutSystemsでは、IDE（統合開発環境）は独自のものが提供されます。名称はService Studio（サービススタジオ）です。

Service Studioは、プロジェクト形式でアプリケーション開発を管理します。必要なモジュール、ライブラリなど、全てのパーツをひとまとめにしたものが**Application**というプロジェクト単位になります。

ローコード開発では、いきなりコーディングを行うことはあまりありません。OutSystemsも同じで、基本的にはGUIベースで開発を進めていきます。途中、必要に応じて、簡単なクエリーやスクリプトを記述することがあります。また、拡張機能を実装する場合は通常のコーディングに近い形を行うこともあります。

![Screenshot 2024-01-15 at 17 16 01](https://github.com/taijihagino/low-code-dev/assets/12064399/9776020f-74a1-4776-bee1-2d6ac3116c3f)

# 静的Webアプリを作成してみる
では、簡単な静的Webアプリを作成してみましょう。

この手順を行うことで、Service Studioの使い方を学んでいきます。

## Applicationの作成
1. Service Studioを起動し、「New Application」を選択します。
![Screenshot 2024-01-15 at 17 24 03](https://github.com/taijihagino/low-code-dev/assets/12064399/c0763674-c32c-45a0-90c8-5bec765e3de4)

2. アプリ開発方法の選択画面（How do you want to start?）で、「From scratch」を選択します。
![Screenshot 2024-01-15 at 17 27 13](https://github.com/taijihagino/low-code-dev/assets/12064399/893d085e-6bae-4df9-b7ab-a2bb6f4e3222)

* ここで、「From an app」を選択すると、OutSystemsで用意しているテンプレートからアプリを作成することもできますが、今回は勉強のためにスクラッチ開発を選択します。
![Screenshot 2024-01-15 at 17 26 55](https://github.com/taijihagino/low-code-dev/assets/12064399/ae7748f9-c3a4-488f-a95f-bc0519934a09)

3. 開発するアプリの種類（What are you building?）で、「Reactive Web App」を選択します。
![Screenshot 2024-01-15 at 17 27 46](https://github.com/taijihagino/low-code-dev/assets/12064399/c453d8ce-9616-4d2d-b3ac-7bdb8ee41fbf)

* モバイルアプリやタブレットアプリを選択することもできますが、今回のチュートリアルはウェブアプリ開発とします。なお、**Reactive Web App** はOutSystemsでの用語で、あまり一般的ではありません。

4. アプリ名とアイコンの色を任意のものに指定する。ここではアプリ名を「練習アプリ」、アイコンの色を水色にしました。
   選択したら「Create App」ボタンをクリックします。
![Screenshot 2024-01-15 at 17 29 05](https://github.com/taijihagino/low-code-dev/assets/12064399/30356d2f-587a-4081-b787-6f890c516823)

5. アプリケーションの内容画面になるので、モジュールを作成します。「Module name」はデフォルトのままでOKです。「Chose module type」はプルダウンになっていますが、デフォルトで選択されている「Reactive Web App」のままでOKです。そのまま「Create Module」ボタンをクリックします。
OutSystemsでは、**Application**の配下に**Module**をいくつもぶら下げることができます。チーム開発を行う場合、モジュール単位で開発者を分けることもあります。
![Screenshot 2024-01-15 at 17 30 00](https://github.com/taijihagino/low-code-dev/assets/12064399/4316aaa4-6def-49db-bcd5-d3a1a3ec1e9a)

6. IDEを確認します。何も作成されていないブランクの画面が表示されることを確認します。
![Screenshot 2024-01-15 at 18 09 05](https://github.com/taijihagino/low-code-dev/assets/12064399/24a6fbc1-a29c-4526-b457-dd2edbb191ba)
 
## 右サイドペインのタブの確認
1. IDEの右側にはタブが4つ並んでいるペインが表示されています。それぞれ、以下の役割を持つので、必要に応じて切り替えて開発を進めます。

* Processes：バッチ処理などのワークフローを作成、管理する際に使用します。
* Interface：User Interfaceや、ワイヤーフレームを作成、管理する際に使用します。
* Logic：サーバーサイド処理、クライアントサイド処理、外部APIの制御などに使用します。
* Data：データベースを始めとしたEntityの管理、ERダイアグラムの管理、その他データ系の作成、管理などに利用します。
  ![Screenshot 2024-01-15 at 18 09 05](https://github.com/taijihagino/low-code-dev/assets/12064399/512cd54e-54df-42ac-babe-74168dc9e552)

## 画面（Screen）の追加
1. Interfaceタブから、Mainflowを右クリックし「Add screen」を選択します。
   ![Screenshot 2024-01-15 at 18 20 18](https://github.com/taijihagino/low-code-dev/assets/12064399/6be079fd-3cf8-40ca-a487-b481deaf883e)

2. 
