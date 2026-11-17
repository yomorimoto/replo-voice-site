---
title: RepLo Voice プライバシーポリシー / Privacy Policy
---

# RepLo Voice プライバシーポリシー

**最終更新日:** 2026-11-17

本ポリシーは、モバイルアプリ「RepLo Voice」（以下「本アプリ」）における個人情報および関連データの取扱いについて説明します。


---

## 1. 概要

RepLo Voice は、筋トレのレップ記録を音声などで残すためのアプリです。**ワークアウトログは端末内にのみ保存**され（クラウド同期は行いません）、広告 SDK や第三者分析 SDK によるトラッキングは行いません。

---

## 2. 収集・利用するデータ

### 2.1 ワークアウトログ（端末内）

本アプリは、種目・レップ数・重量・日付などの**ワークアウト記録**を、お使いのデバイス上に保存します。これらのデータは、記録の表示・分析・習慣化機能のために利用されます。

### 2.2 マイクおよび音声認識

音声で記録する場合、本アプリは**マイク**へのアクセスと**音声認識**（Apple の `SFSpeechRecognizer` 等）を利用します。認識処理のため、音声データが **Apple の音声認識サービスへ送信される場合があります**（Apple のプライバシー方針および端末・OS 設定に従います）。本アプリは、音声を第三者広告・分析事業者に送信しません。本アプリ独自のサーバーへ音声を送ることもありません。

### 2.3 ローカル通知

未記録リマインドなどのため、**端末上のローカル通知**を送信することがあります。通知の内容は端末内で生成され、当社サーバーへ送信されません。通知の許可は OS の設定で変更できます。

### 2.4 購入情報（StoreKit / Apple）

プレミアム機能の購入・復元は **Apple の StoreKit** を通じて行われます。支払い処理・領収情報は Apple が管理します。本アプリは、購入状態の確認に必要な範囲で StoreKit の情報を利用します。

### 2.5 収集しないもの

- **広告・トラッキング** — 行いません
- **第三者分析 SDK** — 組み込んでいません
- **HealthKit** — 利用していません
- **写真ライブラリ** — 利用していません（ボディ写真機能は取り下げ済みのため、写真へのアクセスは行いません）

※ 「収集しない」は、本アプリが上記カテゴリのデータを広告・分析目的で取得・送信しないことを意味します。音声認識時に Apple のサービスへ音声が送られる場合は、上記 2.2 の説明に従います。

---

## 3. データの保存場所と共有

| データ | 保存場所 | 第三者共有 |
|--------|----------|------------|
| ワークアウトログ | 端末内のみ | なし |
| 音声（認識時） | 認識処理に必要な範囲（Apple の音声認識サービスを利用する場合あり） | Apple（音声認識サービス利用時。端末外へ送信される場合あり） |
| 購入状態 | Apple / 端末（StoreKit） | Apple |
| ローカル通知 | 端末内 | なし |

本アプリの運営者は、広告・分析目的でユーザーのワークアウト内容や音声を販売・共有しません。

---

## 4. データの保持・削除

ワークアウトログは、アプリのアンインストールまたは端末上でのデータ削除まで端末内に残ります。アプリを削除すると記録も削除されます（端末のバックアップに含まれる場合は、Apple のバックアップの仕組みに従います）。

---

## 5. お子様について

本アプリは、特定の年齢層を対象としたサービスではありません。保護者の監督のもとでご利用ください。

---

## 6. ポリシーの変更

本ポリシーを改定する場合、本ページの最終更新日を更新します。重要な変更がある場合は、合理的な方法でお知らせすることがあります。

---

## 7. お問い合わせ

プライバシーに関するお問い合わせは、以下までご連絡ください。

[サポートページ](https://yomorimoto.github.io/replo-voice-site/) に記載の連絡先までお問い合わせください。

---

# Privacy Policy (English)

**Last updated:** 2026-11-17

This Privacy Policy describes how the mobile app **RepLo Voice** (“the App”) handles information.


### Summary

- **Workout logs** are stored **only on your device** (no cloud sync).
- **Microphone and speech recognition** may be used; speech processing may involve **Apple’s speech services** and audio **may leave the device**.
- **Local notifications** may remind you to log workouts; they are generated on device.
- **Purchases** are handled via **Apple StoreKit**.
- **No ads, no analytics SDKs, no HealthKit, no photo library access** (body-photo feature withdrawn).

### Data we use

| Category | Purpose | Notes |
|----------|---------|--------|
| Workout / fitness logs | Logging, history, analytics in-app | On device only |
| Audio / speech | Voice-to-log | Mic + Apple speech recognition; may leave device to Apple; not sent to our own servers |
| Purchase status | Premium entitlement | Via StoreKit / Apple |
| Local notifications | Reminders | On device only |

### What we do not collect

- Advertising identifiers for tracking
- Third-party analytics SDK data
- HealthKit data
- Photos / photo library content

“Do not collect” means the App does not gather or send those categories for ads/analytics. Audio may still go to Apple for speech recognition (see above).

### Contact

Please use the contact listed on the [support page](https://yomorimoto.github.io/replo-voice-site/).

---

*Published at https://yomorimoto.github.io/replo-voice-site/privacy — source: replo-voice `docs/store/privacy/privacy-policy.md`.*
