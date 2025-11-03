# 簿記とは（はじめに読む）

簿記は、事業で発生するあらゆる「お金に換算できる出来事」を、一定のルールで記録・整理・報告する仕組みです。個人事業主にとっては、日々の記帳から決算・申告までをつなぐ実務の土台になります。

> [!TIP]
> 本ノートは「青色申告・複式簿記（発生主義）」を前提にまとめています。まずは全体像を掴み、必要な章へ進みましょう。

## 何のために簿記をする？（目的）

- 経営の見える化（売上・費用・利益・資金の状況を把握）
- 税務申告のための証拠と計算根拠を整える（青色申告の控除を受ける）
- 取引先や金融機関への説明責任（信頼性のある数字）

## 簿記のコア原則（複式簿記）

- 取引は「借方（左）」「貸方（右）」の2側面で必ず記録する
- 左右の金額は常に一致する（ダブルチェックの仕組み）
- 借方で増えるのは「資産・費用」、貸方で増えるのは「負債・純資産・収益」

> 詳細: [`daily-activities/account.md`](../daily-activities/account.md)

## 会計サイクル（全体像）

```mermaid
flowchart LR
  classDef p fill:#e0f2fe,stroke:#0284c7,color:#0f172a,rx:6,ry:6;
  classDef r fill:#dcfce7,stroke:#16a34a,color:#0f172a,rx:6,ry:6;

  A[取引の発生]:::p --> B[仕訳帳に記録]:::p --> C[総勘定元帳へ転記]:::p --> D[試算表]:::p
  D --> E[決算整理]:::p --> F[損益計算書]:::r --> G[貸借対照表]:::r
```

> 全体の詳細と日次・月次・年次の関係は: [`overview/bookkeeping-flow.md`](../overview/bookkeeping-flow.md)

## 簿記で扱う5つの要素

- 資産（現金・預金・売掛金・備品など）
- 負債（買掛金・未払金・借入金など）
- 純資産（元入金・事業主借・利益の蓄積）
- 収益（売上など）
- 費用（仕入・経費など）

> 5要素と左右の関係式は: [`daily-activities/account.md`](../daily-activities/account.md)

## 取引の記録単位（仕訳）

- 1件の取引を「いつ／だれに／何を／いくら／どの科目で」記録する
- 代表例：`借方: 消耗品費 / 貸方: 現金`（文房具を現金で購入）
- 実務で頻出の仕訳テンプレは: [`basics/journal-entries.md`](./journal-entries.md)

## 実務で使う主な帳簿

- 仕訳帳（すべての取引を時系列で記録）
- 総勘定元帳（科目別に集計）
- 試算表（借方・貸方の整合をチェック）
- 財務諸表（損益計算書・貸借対照表）

> 帳簿の種類と役割: [`blue-tax-return/types-of-accounting-books.md`](../blue-tax-return/types-of-accounting-books.md)

## まず何から始める？（ロードマップ）

1. 全体像の把握: [`overview/bookkeeping-flow.md`](../overview/bookkeeping-flow.md)
2. 基礎概念の習得: [`daily-activities/account.md`](../daily-activities/account.md)
3. 仕訳の型を覚える: [`basics/journal-entries.md`](./journal-entries.md)
4. 日々の実践: [`daily-activities/daily-activities.md`](../daily-activities/daily-activities.md)
5. 月次の締め: [`what-to-do-every-month/what-to-do-every-month.md`](../what-to-do-every-month/what-to-do-every-month.md)

> [!NOTE]
> 「現金主義」との違い、消費税の扱い、按分や減価償却などは、実践ページと併せて徐々に身につければOKです。

