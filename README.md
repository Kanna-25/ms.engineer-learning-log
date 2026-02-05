# ms.engineer-learning-log

# 🗓️学習ログ

このリポジトリは、学習内容・実行したコマンド・理解したことを記録するためのものです。

---

## 📌 目的
- 学習内容を言語化・アウトプットする習慣をつける

---

## 🛠 使用技術・ツール
- OS：macOS
- Docker
- nginx
- Git / GitHub
- ターミナル（bash / zsh）

---

## 📅 学習ログ

### 2026-02-05
**Dockerの仕組み**
**Dockerで nginx を起動して Web 表示**

#### ✏️ 学んだこと、実行したこと
- Docker を Macにインストール
- nginx イメージを使用してコンテナを起動
- Dockerの仕組み（Dockerエンジン、Dockerコンテナ、Docker イメージ、Docker レジストリ）
- Docker レジストリはインターネット上に保管できるクラウドみたいなイメージ

#### 👀 印象に残ったコマンド（1〜3個）
```bash
docker run -d -p 8080:80 nginx
→nginxコンテナをバックグラウンドで起動し、localhost:8080からアクセスできるようにする
