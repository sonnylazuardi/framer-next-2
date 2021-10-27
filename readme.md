# Framer / Next.js Quickstart

This is a [Next.js](https://nextjs.org/) boilerplate project setup to work with [Framer Handshake](https://paper.dropbox.com/doc/Handshake-FAQ--BS5dWtu0Qab832m~Cm3UernGAg-r7i5VHyohHULTu54FdVjL), a way to directly ship visual components from your canvas to your production site leveraging the [ES Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules) standard.

## Quickstart

Clone this repository and run the command to start the development server.

```
git clone https://github.com/framer/next.js.git
yarn run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Handshake

[Framer](https://www.framer.com/) is a canvas based interactive design tool that helps you quickly design interactive components, from buttons to hero animations to cards and much more.

Typically, these elements have to manually get rebuilt in React if you are ready to actually use them on your website. Framer does this automatically and exposes every component as a versioned ESM JavaScript module with a React component.

Because modern tools like [Next.js](https://nextjs.org/) are starting to support ESM and url imports, you can directly import canvas components into your web project, eliminating the rebuild step thus saving a lot of time.

## Existing Next.js Projects

If you want to add these capabilities to an existing Next.js project, you have to enable experimental ESM / url import support. You can find the exact steps in [this overview](https://paper.dropbox.com/doc/Handshake-FAQ--BTAPTP5CFEUwn8MdfmmsVJwDAg-r7i5VHyohHULTu54FdVjL#:uid=441999709291662620383132&h2=%E2%8F%AD-Setup-with-NextJS).


