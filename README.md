# Next.js + Tailwind CSS Example

This example shows how to use [Tailwind CSS](https://tailwindcss.com/) [(v3.0)](https://tailwindcss.com/blog/tailwindcss-v3) with Next.js. It follows the steps outlined in the official [Tailwind docs](https://tailwindcss.com/docs/guides/nextjs).

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example) or preview live with [StackBlitz](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/with-tailwindcss)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/next.js/tree/canary/examples/with-tailwindcss&project-name=with-tailwindcss&repository-name=with-tailwindcss)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), or [pnpm](https://pnpm.io) to bootstrap the example:

```bash
npx create-next-app --example with-tailwindcss with-tailwindcss-app
# or
yarn create next-app --example with-tailwindcss with-tailwindcss-app
# or
pnpm create next-app --example with-tailwindcss with-tailwindcss-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).



************************************************

## MIGHT BE A LITTLE CONFUSING, BUT I USED THE '/POST/[post_id]' ROUTE/FOLDER TO HOUSE INDIVIDUAL POSTS
## I USED THE '/POSTS/[blogost]' ROUTE OR FOLDER TO HOUSE THE COLLECTION OF POSTS
## I ADDED THE CATEGORY PAGE TO THE INDEX PAGE



## FOR PULLING THE TEXT FROM THE SANITY API, I USED A PACKAGE CALLED PORTABLETEXT. THE FULL BREAKDOWN OF THE USE OF THIS PACKAGE CAN BE FOUND IN THE BLOGPOST COMPONENT



## USER A PACKAGE CALLED 'REACT-HOOK-FORM' FOR SUBMITTING THE COMMENT DETAILS A USER ADDS TO A BLOGPOST
## I USED TWO FUNCTIONS CALLED USEFORM AND SUBMITHANDLER FOR THESE FUNCTIONS.
## A FULL BREAKDOWN OF THIS CAN BE FOUND IN THE BLOGPOST COMPONENT


## REACT-HOOK-FORM IS MORE LIKE A REACT HOOK.


## THE SUBMITHANDLER FUNCTION OF THE REACTHOOK FORM IS A TYPESCRIPT INTERFACE FOR THE CUSTOM FUNCTION THAT HANDLES THE LOGIC BEHIND SUBMITTING. THIS SUBMISSION HANDLING FUNCTION IS THE ONE YOU WROTE YOURSELF.

## DESTRUCTURE THE REGISTER, HANDLESUBMIT AND THE FORMSTATE : {ERROR} FROM THE USEFORM HOOK
## YOU ADD THE REGISTER FUNCTION TO ALL OF THE INPUT FIELDS IN YOUR FORM, AND SPECIFY WHETHER THEY ARE REQUIRED FIELDS OR NOT
## THE HANDLESUBMIT FUNCTION IS A BUILT-IN FUNCTION FROM THE REACT-HOOK-FORM. IT TAKES IN THE SUBMISSION HANDLING FUNCTION YOU WROTE AS AN ARGUMENT

## THE SUBMISSION HANDLING FUNCTION YOU WROTE, HAS TO BE AN ASYNC FUNCTION.
## INSIDE IT, YOU PUT AN AWAIT FETCH REQUEST, TO AN API YOU MUST HAVE SPECIFIED IN A FILE INSIDE YOUR API ROUTE IN YOUR PAGES FOLDER
## CHECK OUT THE CODE FOR MORE INFORMATION

## STUDIO DEPLOYED TO HTTPS://BLOGRR.SANITY.STUDIO/