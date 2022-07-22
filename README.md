# NEXT.js강의

-   리액트 라이브러리를 셋팅+ 사용하기쉽게
-   server를 가지고있기때문에 , 백앤드와의 휴먼리소스 리스 하지않기위해.
-   SSR,SEO에 대한 기능들을 내장해놓고 안내해주는것.
-   SSR를 위해 생겨난것이 아니고 좀더 편하고 기능들을 사용하게 도와주기위해 만들어놓은것.
-   SSR같은 기능들을 위해 만들어진것.
-   DEV SERVER
    -   build ⇒ index.html,_.js,_.css, assets/\*
    -   PHP server , Java spring server, express server
    -   NEXT - sever를 가지고있다. (리액트는 x)
        -   server(express)
        -   ssr-seo(0), scr-seo(x)
    # markdown
    -   mdx - markdown 진화버전
    -   db용 서버 + api 서버 + front서버(seo를위해ssr사용)
        mdx는기존 리액트에서는안됨 ssr에서해야함(넥스트에서)
        넥스트 = ssr + csr 의 하이브리드
    useEffect() 서버에서 안됨.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

-   [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
-   [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
