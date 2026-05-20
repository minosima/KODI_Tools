# KODI_Tools
KODIを音楽サーバーとして使用しています。
スマートプレイリストに任意の画像が設定できる方法を見つけたので、
簡単に専用画像を作成するツールとスマートプレイリストを作成するツール（日本人アーティストの表記揺れ対応）を作りました。
作成までの試行錯誤、手順は下記にメモしています。
https://ncos1.hatenablog.com/



＊　日本人アーティストの表記揺れ対応の例
姓・名
松任谷　由実
まつとうや　ゆみ
を入力すれば、下記のアーティスト名を自動で補完するので表記揺れをカバーできるはず。
姓名間の空白の全角半角、ローマ表記の姓名逆順、ローマ字の訓令式・ヘボン式・両方混在を自動生成しています。
        <value>松任谷由美</value>
        <value>松任谷 由美</value>
        <value>松任谷　由美</value>
        <value>まつとうや ゆみ</value>
        <value>マツトウヤ ユミ</value>
        <value>まつとうや　ゆみ</value>
        <value>マツトウヤ　ユミ</value>
        <value>matsutouya yumi</value>
        <value>matutouya yumi</value>
        <value>yumi matsutouya</value>
        <value>yumi matutouya</value>
