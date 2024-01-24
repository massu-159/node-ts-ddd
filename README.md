# node-ts-ddd

Typescriptを使ったドメイン駆動設計を学習するための書籍在庫サンプル。

jestでテスト実施。

Expressでサーバー構築。

ORMにprismaを利用。

Dockerを使ってDB(postgresql)を用意。

urlはこちら
https://github.com/massu-159/node-ts-ddd


## 目次
1. 環境構築
2. アプリケーションの仕様

## 1. 環境構築

### 1-1. ライブラリ インストール

```
npm install
# または
yarn
# または
pnpm install
# または
bun install
```

## 2. アプリケーションの仕様

### 2-1. 仕様
- 書籍
  - タイトル
  - 価格
- 在庫
  - ステータス
  - 在庫数

### 2-2. 構成技術
    "@types/express": "^4.17.21",
    "@types/jest": "^29.5.11",
    "@types/lodash": "^4.14.202",
    "@types/node": "^20.11.5",
    "@typescript-eslint/eslint-plugin": "^6.19.1",
    "eslint": "^8.56.0",
    "eslint-import-resolver-typescript": "^3.6.1",
    "eslint-plugin-import": "^2.29.1",
    "jest": "^29.7.0",
    "prisma": "^5.8.1",
    "ts-jest": "^29.1.2",
    "ts-node": "^10.9.2",
    "tsconfig-paths": "^4.2.0",
    "typescript": "^5.3.3"
    "@prisma/client": "^5.8.1",
    "express": "^4.18.2",
    "lodash": "^4.17.21",
    "nanoid": "^3.3.7",
    "reflect-metadata": "^0.2.1",
    "tsyringe": "^4.8.0"
