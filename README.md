# NHTS_template

【非公式】日本伝熱学会主催「日本伝熱シンポジウム」の LaTeX 原稿テンプレート

> [!NOTE]
> 未完成なのでまだ使わないでください．

非公式のテンプレートなので，使用方法に関しての公益社団法人日本伝熱学会への問い合わせはご遠慮ください．

## リポジトリ内のファイルの説明

- `.gitignore`: Git で管理しないファイル一覧
- `README.md`: このファイル
- `latexmkrc`: latexmk で LaTeX を実行する際に必要なファイル
- `settings.sty`: 原稿テンプレートのスタイルファイル
- `template-a.tex`: 日本語の講演アブストラクト原稿（A4 用紙 1 枚）
- `template-ae.tex`: English abstract manuscript (International sessions, 1 page of A4 size)
- `template-p.tex`: 日本語の講演論文原稿（A4 用紙 2--6 枚）
- `template-pe.tex`: English full-size manuscript (International sessions, 2--6 pages of A4 size)

## 使用方法

`template-a.tex`, `template-ae.tex`, `template-p.tex`, `template-pe.tex` のうち，必要なテンプレートを選択してください．
原稿の設定が書かれている `settings.sty` をメインの文書ファイルと同じ階層に用意してください．
latexmk で実行する際は `latexmkrc` を使用してください．
リポジトリ内で用意しているものではなくご自身が普段使用している `latexmkrc` でも構いません．
現在のテンプレートは LuaLaTeX での実行を想定して作成しています．


