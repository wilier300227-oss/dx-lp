# RAINBOW工房 DX・Web制作 LP

Web制作・業務DXサービスのランディングページ。

## 技術スタック

- [Astro](https://astro.build/) 5
- [Tailwind CSS](https://tailwindcss.com/) v4
- TypeScript

## ローカル開発

```bash
npm install
npm run dev       # localhost:4321
npm run build     # dist/ に本番ビルド
npm run preview   # ビルド結果をローカルで確認
```

## デプロイ

Cloudflare Pages（GitHub 連携による自動デプロイ）

- Build command: `npm run build`
- Output directory: `dist`
