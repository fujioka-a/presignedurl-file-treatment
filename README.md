# presignedurl-file-treatment
AWS公式に乗っ取り、署名付きURLを使用したS3ファイル配置・取得機能の開発（ApplicationComposerを使用）

## 環境構築
pyenv install 3.11.2
pyenv local 3.11.2
pyenv rehash

## AWSリソース操作
### デプロイ
sam sync --stack-name presignedurl-app-stack
### 削除
sam delete --stack-name presignedurl-app-stack
