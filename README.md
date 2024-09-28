# python-lib-test
pythonのライブラリをpoetryで作るサンプル

## 開発の流れ

1. `mylib/module.py`に関数などを作成
2. `mylib/__init__.py`に関数などを追加
3. poetry buildを実行
4. githubにpush

## 使い方

1. `pip install git+https://github.com/skmochi/python-lib-test`を実行
2. ブランチ指定が必要なら末尾に`@ブランチ名`を追加
3. `import mylib`から使う
