# エレメント

Craft CMS の根本的に重要でユニークな特徴は、エレメントという概念です。

エレメントは、コンテンツの最も基本的な単位です。

ウェブベースのコンテンツ管理システムであるため、多くの場合、エレメントにはユニークな URL が含まれています。テキスト、画像、他のコンテンツとの重要な関係性、言語・サイト・まだ公開されていない下書きによるバリエーションさえも含むかもしれません。

コントロールパネルには、Craft が利用可能なエレメントの *種類* が表示されます。

- [**アセット**](assets.md)はボリュームにアップロードされたファイルを保管します。
- [**カテゴリ**](categories.md)はフォルダ構造に似た分類で、ネストさせることができます。
- [**エントリ**](entries.md)は下書き、リビジョン、および、ライブプレビューが可能な投稿です。それらは「シングル」と呼ばれる一回限りのものとして存在したり、「セクション」へ日付で順序づけられていたり、「ストラクチャー」として視覚的に並べられたりします。
- [**グローバル設定**](globals.md)は特定のページや他のコンテンツに紐づかない流動的なコンテンツのかたまりで、サイトの各ページに表示したい情報のかたまりに最適です。
- [**行列ブロック**](matrix-blocks.md)は強力で、他のエレメントタイプで使用できるコンテンツを簡単に結び付けたり、グループ化して並び替えることができます。
- [**タグ**](tags.md)は素早く入力して再利用できるように最適化されたフラットな分類です。
- [**ユーザー**](users.md)はメールアドレスと権限を持つ人間向けのアカウントで、カスタマイズ可能なグループに編成されます。

使用するエレメントタイプの数や組み合わせ方に制限はありません。サードバーティ製のプラグインを使用したり、追加のエレメントタイプを含む独自のプラグインを作成できます。

それぞれのエレメントタイプは何らかの点でユニークですが、**すべての** エレメントはどのようなコンテンツを収集・保管すべきかを厳密に特定する独自の[カスタムフィールド](fields.md)で構成されていることを理解することが重要です。