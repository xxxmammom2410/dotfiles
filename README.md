installシェルスクリプト実行でパッケージ群を自動インストールされる

### タイリングコントロール
```
skhd --start-service
brew start yabai
yabai --start-service
```
アプリ内での新規ウィンドウのタイル管理は対象アプリの再起動が必要


### quartoの準備
quartoに必要なパッケージをpipでインストールするために仮想環境が必要
python3 -m venv .venv 
source .venv/bin/activate
deactivate