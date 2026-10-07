# ポケモンチャンピオンズ戦略ページ

[公開ページ](https://otake-shol.github.io/pokemon-strategy/)

シングル・ダブルの構築、技・持ち物・能力ポイント、選出方針、採用理由、実戦での確認事項を掲載する非公式の個人用戦略ページ。

## 情報の基準日

現在のダブルページは2026年10月4〜5日の相談と、10月5日朝のサーフゴー＋ふうせん採用指示に対応する保存HTML。9月25日のダブル・9月13日のシングルは[履歴ページ](https://otake-shol.github.io/pokemon-strategy/history.html)に保持する。情報は記録当時の内容で、新構成の勝率は未検証。

## 更新手順

非公開の記録用リポジトリで構築記録を編集し、`python3 scripts/build_site.py`でページを再生成する。生成した`index.html`・`history.html`・`.nojekyll`をこのリポジトリにコピーし、コミット・プッシュする。

GitHub Pagesは`main`ブランチのルートを公開する。会話ログ、個別対戦記録、認証情報を含めない。
