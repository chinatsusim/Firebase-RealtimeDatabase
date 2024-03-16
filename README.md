kadai04_chatApp
②課題内容（どんな作品か）
スマホアプリ風のチャットアプリをつくりました。 OpenAIのChatAPIも使用して、テキスト入力すると、AIが自動応答するようにしました。

③DEMO
https://chinatsusim.github.io/Firebase-RealtimeDatabase/

④工夫した点
ネイティブアプリっぽさを出すために、viewportメタタグ使用、スクロールバーを非表示、ヘッダーとフッターの固定をしました。
送信ボタンクリックだけでなく、エンターキーでも送信されるようにしました。
OpenAIによる応答か、自分の入力かは、呼び出したオブジェクトの値に応じて、class属性の異なるHTMLをoutputするようにし、それぞれ異なるCSSをあてることで、メッセージ主体を分かりやすくしました。
プロンプトに応答文字制限をつけ、max_tokenも設定することで、トークン量を節約するようにしました。
④難しかった点・次回トライしたいこと(又は機能)
せっかくリアルタイムDBが使えるようになったので、もしかするとChat情報が入るメッセージデータベースとユーザー情報データベースをID突合して複雑なデータ活用ができるのかと思っており、次回以降チャレンジしたいです。
⑤質問・疑問・感想、シェアしたいこと等なんでも
ネイティブアプリっぽさを出したいのに、どんなにCSSを触ってもスマホ最適化されずviewportメタタグにたどり着きました。
