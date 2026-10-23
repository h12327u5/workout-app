今日の筋トレ種目（Androidのホーム画面に追加できるアプリ版）

【ファイル】
index.html / manifest.webmanifest / sw.js / icon-192.png / icon-512.png / icon-maskable-512.png
この6つを、同じ場所（同じフォルダ）に置いて公開します。

【公開のしかた（GitHub Pagesの例・無料）】
1. GitHubにログインし、新しいリポジトリを作る（名前は例：workout）
2. 「Add file」→「Upload files」で、上の6つのファイルをアップロードして Commit
3. リポジトリの Settings → Pages → Branch を main / (root) にして Save
4. 数分後に https://ユーザー名.github.io/workout/ で開ける

※ 公開されるのはアプリの画面だけです。種目や記録は、各端末のブラウザ内にだけ保存されます。
※ HTTPSで公開されるサービスなら、Netlify や Cloudflare Pages でも同じ6つで動きます。

【Androidへの入れ方】
1. Chromeで公開したURLを開く
2. 右上のメニュー（⋮）→「ホーム画面に追加」（または「アプリをインストール」）
3. ホーム画面のアイコンから、アプリのように全画面で起動できる

【今のデータを移す】
今使っているページで「Out」でファイルを保存 → Androidのアプリで「In」でそのファイルを選ぶ。
