# 第3回 解答

## 演習

- 第1回（素のLLM）とエージェントの回答の違い：make_quizを呼び出す
- `--trace` で見えたツール呼び出し（ツール名と引数）：[tool call]   make_quiz
- 1つの質問での LLM 呼び出し回数（`requests`）：2
- 追加したツールと、docstring に書いた説明：make_quiz、指定した回の用語から１つを選び、確認問題と答えを返す。

## 宿題

- 取り組んだレベル：実装
- やったこと：`save_learning_log` を追加し、学習内容を日時付きの Markdown ファイルとして `learning_log/` に保存するようにした。
- 結果：`requires_approval=True` を設定し、CLI で保存内容を表示して利用者の確認を受けてから実行できるようになった。
- 気づき・疑問：
