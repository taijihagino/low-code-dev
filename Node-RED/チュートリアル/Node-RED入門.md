# Node-REDを使ってみよう

ここでのNode-RED入門編は、[ワンフットシーバスの田中正吾さん](https://x.com/1ft_seabass?s=20)のコンテンツを利用させていただきます。正吾さん、ありがとうございます！

<!--
コンテンツは[こちら](https://1ft-seabass.github.io/node-red-beginner-handson-05/)から
-->

## GitHub Codespaces の準備 〜 Node-REDの起動

GitHubにログインし、[こちらのリポジトリ](https://github.com/taijihagino/node-red-codespaces/tree/main)にアクセスします。

<img width="1429" alt="Screenshot 2025-01-19 at 14 23 31" src="https://github.com/user-attachments/assets/98b1441b-0619-4436-80c3-2213fb0abab4" />

「Code」と書かれたプルダウンボタンをクリックし、「Codespaces」タブから「Create codespaces on main」ボタンをクリックします。

![Screenshot 2025-01-19 at 14 24 25](https://github.com/user-attachments/assets/4b3b1355-e5c4-4543-b704-66ad6c266865)

ブラウザ版VSCodeが別タブで起動します。自動で、必要なモジュールがインストールされるので、そのまましばらく待ちます。<br>
すべてインストールされると、Node-REDが起動しますので、出力にある ``http://127.0.0.1:1880`` のところにマウスを乗せて「Follow link」をクリックします。

<img width="1103" alt="Screenshot 2025-01-19 at 14 16 54" src="https://github.com/user-attachments/assets/614a0dc9-486b-42f9-80a5-a99d633b68ed" />

Node-REDが別ダブで起動します。プロジェクトを作成するか、既存リポジトリからプロジェクトを開くかなど聞かれますが、ここでは「Not right now」をクリックして次に進みます。

<img width="1447" alt="Screenshot 2025-01-19 at 14 17 31" src="https://github.com/user-attachments/assets/68b5dae2-bbb2-44a8-b9ad-b9916e681501" />

Node-REDフローエディタが表示されたら成功です。これでNode-REDでの開発が可能になりました。

<img width="1442" alt="Screenshot 2025-01-19 at 14 31 15" src="https://github.com/user-attachments/assets/9062f20b-7a46-4a04-b6c1-b58fe19c1294" />


## フローの作成

公式サイトの[初めてのフロー](https://nodered.jp/docs/tutorials/first-flow)を参考に進めてみましょう。
