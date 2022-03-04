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

-------------
## Pre Rendering and Data Fetching

Next.js pre-renders html for each page in advance

>CRA does not

Test it by disabling js (dev tools) on Next.js and CRA apps

### Static Generation v.s. Server-side Rendering 

You can use Static Generation for many types of pages, including:

* Marketing pages
* Blog posts
* E-commerce product listings
* Help and documentation

### Static gen with data



>for later https://medium.com/codex/creating-a-basic-dapp-with-web3-and-nextjs-2ee94af06517