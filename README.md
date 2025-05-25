# budy-backend

Laravelで構築したダイエットアプリ「Budy」のバックエンドAPIです。

## 公開URL

- フロントエンド（Vercel）: https://budy-diet.vercel.app  
- APIエンドポイント（ローカル）: http://localhost/api

---

##  環境構築

### 必要要件

- Docker
- Laravel Sail（同梱）

### セットアップ手順

```bash
git clone https://github.com/your-username/budy-backend.git
cd budy-backend

# コンテナ起動
./vendor/bin/sail up -d

# マイグレーション
./vendor/bin/sail artisan migrate
