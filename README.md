# @qbane/sveltekit-template

My opinionated SvelteKit template in pure JavaScript.

This template is derived from [the official template](https://github.com/sveltejs/kit-template-default).

Some notable customizations are:

0. `package-lock.json` is NOT committed on purpose
1. Vite 6.0 and Vitest 3.0 is included
2. The included adapter is changed from `auto` to `@sveltejs/adapter-node`, assuming that you are not targeting [any specific deployment target](https://svelte.dev/docs/kit/adapter-auto).

## Instructions

```bash
git clone https://github.com/qbane/sveltekit-template.git
cd sveltekit-template
rm -rf .git .github
git init
npm i
```
