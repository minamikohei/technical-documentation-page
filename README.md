# [技術ドキュメントページ](https://minamikohei.github.io/technical-documentation-page/)

[freeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/) レスポンシブウェブデザインのレスポンシブウェブデザインプロジェクト

***

ユーザーストーリー:

1. id="main-doc" を持ち、ページのメインコンテンツ (技術ドキュメント) が入る main 要素があります
2. #main-doc 要素内には、それぞれのクラスが main-section である section 要素が複数あります。 最低でも 5 個必要です
3. 各 .main-section 内の最初の要素は、そのセクションの主なトピックを説明するテキストが入った header 要素となっています。
4. クラスが main-section の各 section 要素には、それぞれの header のテキストに対応する id も設定されています。 すべてのスペースはアンダースコアに置き換える必要があります (例: "JavaScript and Java" というヘッダーを含む section には、対応する id="JavaScript_and_Java" が必要です)
5. .main-section 要素には、(それぞれではなく) 合計で少なくとも 10 個の p 要素が含まれます
6. .main-section 要素には、(それぞれではなく) 合計で少なくとも 5 個の code 要素が含まれます
7. .main-section 要素には、(それぞれではなく) 合計で少なくとも 5 個の li 要素が含まれます
8. id="navbar" を持つ nav 要素が 1 つあります
9. ナビゲーションバー (navbar) の要素には、技術ドキュメントのトピックを説明するテキストが入った header 要素が 1 つ含まれています
10. さらに、ナビゲーションバーには nav-link のクラスを持つリンク (a) 要素が含まれています。 このリンクは、クラス main-section の各要素に対応して 1 つずつ存在します
11. #navbar 内の header 要素は、ナビゲーションバーのどのリンク (a) 要素よりも前に置かれなければなりません
12. nav-link クラスの各要素には、各 section 内の header テキストに対応するテキストが含まれていなければなりません (例えば、もし "Hello world" セクション / ヘッダーがあるならば、ナビゲーションバーには "Hello world" というテキストを含む要素が必要です)
13. ナビゲーションバーの要素をクリックすると、ページは #main-doc 要素内の対応するセクションに移動します (例えば、"Hello world" のテキストを含む .nav-link 要素をクリックしたならば、その id を持ち、対応するヘッダーを含む section 要素に移動しなければなりません)
14. 通常サイズのデバイス (ノート PC、デスクトップ) 上では、id="navbar" を持つ要素は画面の左側に表示され、常にユーザーから見える状態にしなければなりません
15. この技術ドキュメントには、少なくとも 1 つのメディアクエリが使われている必要があります
