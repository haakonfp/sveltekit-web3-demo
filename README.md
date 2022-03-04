# SvelteKit Web3 Demo App
> JavaScript, NPM, Svelte-Web3, Web3Modal, and WalletConnect

The project contains a SvelteKit Skeleton project featuring a Web3Modal Button with WalletConnect.
The project mainly uses Svelte (HTML, CSS, and JavaScript). 

You can adapt elements from this repo into a SvelteKit project using TypeScript, PostCSS, TailwindCSS, and more.
Additionally, this project does not have ESLint, Prettier or similar (to keep it simple).

Note that the current ``WalletConnectProvider`` targets the Binance Smart Chain.
This can easily be changed in the Web3Modal ``providerOptions``.

Quick Start (more details below): 
```shell
$ npm install && npm run build && npm run dev -- --open
```

---

## Project Background

I made this project to provide a resource for Svelte/SvelteKit developers wanting to build Web3 (d)apps.
There are few resources around at the moment, and I hope this project is helpful for kickstarting SvelteKit web3 projects.

At the time of creation, there are issues with importing the ``@WalletConnect/web3-provider`` in .svelte-files.
Thus, the WalletConnect has been imported as CDN/script tag in ``src/app.html``, making it available to all files in the project.

### Svelte-Web3 and Svelte-Ethers-Store

An important contribution to Svelte/SvelteKit projects using ``web3.js`` is [svelte-web3](https://www.npmjs.com/package/svelte-web3).
There is also a version tailored to ``ethers.js``, namely [svelte-ethers-store](https://www.npmjs.com/package/svelte-ethers-store).
These packages provide a set of readable Svelte stores, simplifying the use of web3 features across your project.

These packages were developed by [clbrge](https://github.com/clbrge), who deserves praise for the Quality-of-Life features these provide.

### Help build the Svelte Web3 Ecosystem

I recommend others to join the [Svelte EVM Discord Server](https://discord.gg/7yXuwDwaHF) to meet other likeminded developers,
contribute to the Svelte Web3 ecosystem, and get technical help and guidance if needed. 
For example, you can join to help define and build reusable Svelte-Web3 Components!

I encourage you to pass on knowledge of Svelte/SvelteKit Web3 development, and contribute to open-source projects.

---

## What is Svelte and SvelteKit?

[Svelte](https://svelte.dev) is a new approach to building User Interfaces.
It is comparable to React and Vue, with differences in DOM handling and compilation.
More notably, Svelte has a very clean UI implementation in its .svelte-files.
It requires way less boilerplate code than React and Vue, and it is very intuitive.

SvelteKit is the web app framework packing everything into one functional web app.
SvelteKit is a new framework, and you may therefore encounter certain bugs and quirks.

Svelte and SvelteKit has very good official documentation and tutorials.
It is recommmended to check them out and understand Svelte/SvelteKit before diving into this project.

---

## Get Started with the SvelteKit Web3 Demo

Once cloned, the dependencies can be installed with the command:
```shell
$ npm install
```

The project can be built using the following command:
```shell
$ npm run build
```

The project can be run to localhost:3000/ using:
```shell
$ npm run dev
```

---

## Contribute to the Demo Project

If you're a better Svelte/SvelteKit developer than me (very likely), you probably see ways to improve and streamline this project.

If you want to contribute, it would be very helpful for the community if you forked it and created a Pull Request here.
Please only do so with thoroughly tested code, good formatting, and descriptions of the commits done.

I will go over all PRs as fast as I can! Thank you!

---

## Author(s) and Contributor(s)

Project created by [haakonfp](https://github.com/haakonfp).
