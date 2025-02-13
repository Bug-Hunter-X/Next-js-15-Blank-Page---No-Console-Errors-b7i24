# Next.js 15 Blank Page Bug

This repository demonstrates a subtle bug in Next.js 15 where a simple application renders a blank page without any errors in the browser's console.  The issue is particularly tricky to debug because of the lack of error messages.

## Bug Description

A basic Next.js 15 application, containing only a simple `Home` component, fails to render any content.  The browser displays a blank page, and the console remains clear of any errors. This makes it very hard to track down the problem.

## Solution

The solution involves ensuring that the Next.js application is correctly configured and that there are no unexpected issues with the project's file structure or dependencies.  In some cases, it may be due to improper export of the component.  The provided solution checks for this.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the blank page in your browser.
