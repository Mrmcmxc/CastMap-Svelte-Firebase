

![screencapture-localhost-3000-2022-08-03-21_31_43](https://user-images.githubusercontent.com/82994490/182723363-97dd1c76-b0a9-4b12-8abc-b57252efb9d4.png)

![screencapture-localhost-3000-fish-2022-08-03-21_34_11](https://user-images.githubusercontent.com/82994490/182723483-83512917-a8fd-460b-86dd-ba589751a5db.png)

![screencapture-localhost-3000-about-2022-08-03-21_34_56](https://user-images.githubusercontent.com/82994490/182723502-94f7337d-62c0-443a-9bbd-daeeb0cf445b.png)



[![Cybernetically enhanced web apps: Svelte](https://sveltejs.github.io/assets/banner.png)](https://svelte.dev)![Uploading screencapture-localhost-3000-fish-2022-08-03-21_34_11.png…]()



[![npm version](https://img.shields.io/npm/v/svelte.svg)](https://www.npmjs.com/package/svelte) [![license](https://img.shields.io/npm/l/svelte.svg)](LICENSE.md) [![Chat](https://img.shields.io/discord/457912077277855764?label=chat&logo=discord)](https://svelte.dev/chat)


## What is Svelte?

Svelte is a new way to build web applications. It's a compiler that takes your declarative components and converts them into efficient JavaScript that surgically updates the DOM.

Learn more at the [Svelte website](https://svelte.dev), or stop by the [Discord chatroom](https://svelte.dev/chat).


## Supporting Svelte

Svelte is an MIT-licensed open source project with its ongoing development made possible entirely by fantastic volunteers. If you'd like to support their efforts, please consider:

- [Becoming a backer on Open Collective](https://opencollective.com/svelte).

Funds donated via Open Collective will be used for compensating expenses related to Svelte's development such as hosting costs. If sufficient donations are received, funds may also be used to support Svelte's development more directly.


## Development

Pull requests are encouraged and always welcome. [Pick an issue](https://github.com/sveltejs/svelte/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc) and help us out!

To install and work on Svelte locally:

```bash
git clone https://github.com/sveltejs/svelte.git
cd svelte
npm install
```

> Do not use Yarn to install the dependencies, as the specific package versions in `package-lock.json` are used to build and test Svelte.
To build the compiler and all the other modules included in the package:

```bash
npm run build
```

To watch for changes and continually rebuild the package (this is useful if you're using [npm link](https://docs.npmjs.com/cli/link.html) to test out changes in a project locally):

```bash
npm run dev
```

The compiler is written in [TypeScript](https://www.typescriptlang.org/), but don't let that put you off — it's basically just JavaScript with type annotations. You'll pick it up in no time. If you're using an editor other than [Visual Studio Code](https://code.visualstudio.com/), you may need to install a plugin in order to get syntax highlighting and code hints, etc.


### Running Tests

```bash
npm run test
```

To filter tests, use `-g` (aka `--grep`). For example, to only run tests involving transitions:

```bash
npm run test -- -g transition
```


## svelte.dev

The source code for https://svelte.dev, including all the documentation, lives in the [site](site) directory. The site is built with [SvelteKit](https://kit.svelte.dev).

### Is svelte.dev down?

Probably not, but it's possible. If you can't seem to access any `.dev` sites, check out [this SuperUser question and answer](https://superuser.com/q/1413402).

## License

[MIT](LICENSE.md)
