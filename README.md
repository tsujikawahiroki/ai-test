# README
同様の開発環境構築に向けたREADMEとなります。

## ベースとなる環境
MacOS：Mojave 10.14.3（任意）
python：3.6.6（推奨）
pip：19.0.3（任意）

## 参考文献&URL
・[Pythonによるあたらしいデータ分析の教科書](https://www.amazon.co.jp/Python%E3%81%AB%E3%82%88%E3%82%8B%E3%81%82%E3%81%9F%E3%82%89%E3%81%97%E3%81%84%E3%83%87%E3%83%BC%E3%82%BF%E5%88%86%E6%9E%90%E3%81%AE%E6%95%99%E7%A7%91%E6%9B%B8-AI-TECHNOLOGY-%E5%AF%BA%E7%94%B0-%E5%AD%A6/dp/4798158348)  
・[Python3インストール（Mac編）](https://qiita.com/ms-rock/items/72b8f1abc661c539bb09)  
・[MacでPythonを使って『機械学習』を学ぶための環境構築](https://qiita.com/yoshizaki_kkgk/items/4663148a2b3ca078ddbc)

## コマンド集
// python仮想環境作成  
`python3.6 -m venv <仮想環境名>`

// python仮想環境起動  
`source <仮想環境名>/bin/activate`

// git cloneしたrequirementsファイルを使用してpip installを行う  
`pip install -r ~/ai-test-git/devkit/requirements.txt`

// python仮想環境停止  
`deactivate`

// python仮想環境削除  
`rm -fr <仮想環境名>`
