# Nevyula

Windows 向けのファイルマネージャーです。

## 動作環境

- Windows 10 / 11（64 ビット）
- Microsoft Edge WebView2 ランタイム（Windows 11 と最近の Windows 10 には最初から入っています）

## ダウンロード

**[最新版のダウンロード](https://github.com/mashimaro1005/Nevyula-Release/releases/latest)**（インストーラーとポータブル版は Releases にあります）

| ファイル | 内容 |
|---|---|
| `Nevyula_<版>_x64-setup.exe` | インストーラー版。スタートメニューへの登録とアンインストーラーが付きます |
| `nevyula_<版>_x64_portable.zip` | ポータブル版。展開したフォルダーから、そのまま起動できます |
| `LICENSE.txt` | 使用許諾契約書。インストール・使用の前にお読みください |
| `THIRD-PARTY-NOTICES.txt` | 本ソフトウェアに含まれる第三者のソフトウェア等のライセンス |

### インストーラー版

`Nevyula_<版>_x64-setup.exe` を実行し、表示に従ってインストールしてください。
設定などのデータは `%APPDATA%`・`%LOCALAPPDATA%` に保存されます。

### ポータブル版

zip を書き込みできる場所（Program Files の下以外）に展開し、`nevyula\nevyula.exe` を起動してください。
設定などのデータは、同じフォルダーの `data` に保存されます。

- 設定で「サービスを使用する」をオンにすると、サービスの exe が Program Files の下にコピーされ、
  Windows のサービスとして登録されます。アプリのフォルダーを消す前に、設定でオフにしてください。
- 詳しくは、zip の中のファイル `portable` を参照してください。

## 使用許諾

本ソフトウェアは無償でお使いいただけます。インストール・使用・再配布の条件は `LICENSE.txt`（使用許諾契約書）に定めています。
インストーラー版ではインストールの途中に、同じ内容への同意を求める画面が出ます。
ポータブル版では、展開・使用した時点で同意したものとみなします（zip にも `LICENSE.txt` が入っています）。

本ソフトウェアに含まれる第三者のソフトウェア等のライセンスは `THIRD-PARTY-NOTICES.txt` をご覧ください
（インストーラー版ではインストール先のフォルダー、ポータブル版では zip の中にも入っています）。

## 謝辞

Nevyula は、Gaku 氏の [Tablacus Explorer](https://tablacus.github.io/explorer.html) に大きな影響を受けて生まれました。
タブやペインを自在に組み合わせてファイルを扱うという考え方は、Tablacus Explorer から学んだものです。
長年にわたり開発と公開を続けてこられたことに、深い敬意と感謝を表します。

Tablacus Explorer の魅力は、多くの利用者が作り、公開してきたアドオンにもあります。
Nevyula の機能には、それらのアドオンから着想を得たものが少なくありません。
アドオンを作り、公開してこられたすべての作者の皆さまに、心より感謝いたします。

また、Nevyula は利用者の PC に入っている [7-Zip](https://www.7-zip.org/) と [Everything](https://www.voidtools.com/) を呼び出して、
圧縮・展開と検索に使えるようにしています。すばらしいソフトウェアを公開してくださっている作者の方々に感謝します。

7-Zip は Igor Pavlov 氏の著作物です。Everything は voidtools の製品です。
各名称は、それぞれの権利者の商標または登録商標です。

本ソフトウェアに含まれるオープンソースのソフトウェア・アイコンの作者の皆さまにも、心より感謝いたします
（一覧は `THIRD-PARTY-NOTICES.txt` にあります）。
