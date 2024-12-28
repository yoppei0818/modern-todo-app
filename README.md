学びメモ）

- tsconfig.json について
  - tsconfig.app.json は、src 以下をコンパイル対象とする
  - tsconfig.node.json は、vite.config.ts をコンパイル対象とする
    - Node.js 向けのコンパイラオプション
  - tsconfig.json はそれらを集約するファイルとして機能
  - 複数の tsconfig ファイルを定義する上で共通化したい設定を利用する場合は extends を使用する
