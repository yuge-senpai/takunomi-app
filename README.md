# 宅飲みスマホアプリ

## 概要
- 家飲み会の注文・集金・思い出管理をサポートするスマホアプリ
- Uber Eats等API連携、PayPay/LINE Pay集金、アルバム・ゲーム機能搭載

## 画面イメージ
1. ホーム（店舗選択・希望時刻設定）
2. ウォレット（集金状況管理）
3. 商品選択（カゴ、カテゴリ、ペアリング提案）
4. 飲み会詳細（日時・場所・参加者・通知）
5. 思い出（アルバム・ゲーム・投票）

## 技術スタック
- フロント: React Native (Expo)
- バックエンド: Firebase（仮/後で検討）
- 決済API: PayPay/LINE Pay
- 配送API: Uber Eats等

## 使い方
1. `git clone https://github.com/yuge-senpai/takunomi-app.git`
2. `cd takunomi-app`
3. `npm install`
4. `expo start` で開発モード起動

## 開発リスト
- [ ] 画面雛形の作成
- [ ] 店舗選択・商品一覧
- [ ] 集金機能
- [ ] 注文連携
- [ ] 思い出機能（アルバム・ゲーム・投票）
