## アプリ作成時以下を設定(要検討)
Would you like to use ESLint with this project?<br>
→Yes<br>
Would you like to use Tailwind CSS with this project?<br>
→Yes<br>
Would you like to use `src/` directory?<br>
→No<br>
Would you like to use App Router?<br>
→Yes<br>
Would you like to customize the default import alias (@/*)?<br>
→No<br>
参考：[create-next-appで訊かれていること](https://zenn.dev/ikkik/articles/51d97ff70bd0da#%E2%9C%94-would-you-like-to-customize-the-default-import-alias%3F)
```
next-app % npx create-next-app . --typescript
✔ Would you like to use ESLint? … No / Yes
✔ Would you like to use Tailwind CSS? … No / Yes
✔ Would you like to use `src/` directory? … No / Yes
✔ Would you like to use App Router? (recommended) … No / Yes
✔ Would you like to customize the default import alias (@/*)? … No / Yes
Creating a new Next.js app
```
## 手順

### git clone
```
git clone https://github.com/honda-takuto-sf/next-app.git
```

### ローカルサーバー起動
```
npm run dev
```
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
