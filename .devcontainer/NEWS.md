# v1.3.0 (2022/11/5)

- dotfilesとSSH agentの設定は必要ならdocker-compose.override.ymlで行うよう変更
- .envファイルによる設定をシンプルな構成に変更
- RSPMスナップショットからrenvをインストールするよう修正

# v1.2.0 (2022/10/17)

- renvのバージョンを0.16.0に変更
- 起動時のスクリプト実行にs6を使用するよう修正

# v1.1.1 (2022/05/31)

- DESCRIPTION ファイルの renv のバージョンが 0.15.4 になっていた問題を修正

# v1.1.0 (2022/05/29)

- renv のバージョンを 0.15.5 に修正
- README を修正
- docker-compose.yml を compose.yml に変更
- .env.example のコメントを修正
- コンテナにインストール済みの renv でプロジェクトをロードするよう修正

# v1.0.0 (2022/05/03)

- R のバージョンを 4.2.0 に、renv のバージョンを 0.15.4 に修正
- VS Code Remote Container でも起動できるように修正
- SSH 鍵ファイルのマウントに代えて SSH Agent を利用するよう修正
- renv によるバージョン固定で "explicit" なスナップショットタイプを推奨
- コンテナ起動スクリプトを修正
- フォルダ構成を変更