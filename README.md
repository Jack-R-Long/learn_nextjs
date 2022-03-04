This is a starter template for [Learn Next.js](https://nextjs.org/learn).

# Notes

## Client Side Navigation

page transition with js instead of browser refreshes
`import Link from 'next/link'`

## SASS - Syntactically Awesome Style Sheet

nextJS image component `Image`
image rendering speed is a part of core web vitals https://web.dev/vitals/#core-web-vitals

script and head also replace html tags

### Now we are actually getting into style sheets

jsx style tags 
components dir to make components that are shared across all pages

## _app.js Top Level Component


``` js
export default function App({ Component, pageProps }) {
  return <Component {...pageProps} />
}
```
have to restart dev server after adding
In Next.js, you can add global CSS files by importing them from pages/_app.js. You **cannot** import global CSS anywhere else.



