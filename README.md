# nuxt-netlify-app
A demo app to show how to launch a nuxt app in netlify.


## Prerequisites

- [node](https://nodejs.org/en/) - Recommend you have the latest LTS version installed.
- A text editor, recommend [VS Code](https://code.visualstudio.com/) with the [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) extension.
- A terminal, recommend using [VS Code's integrated terminal](https://code.visualstudio.com/docs/editor/integrated-terminal).

- [yarn](https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable) - recommend to install Yarn through the npm package manager.
    - `npm install --global yarn`


## Using create-nuxt-app

To get started quickly, you can use create-nuxt-app .

```
yarn create nuxt-app <project-name>
```

It will ask you some questions (name, Nuxt options, UI framework, TypeScript, linter, testing framework, etc). To find out more about all the options see the create-nuxt-app documentation .

```
> yarn create nuxt-app nuxt-netlify-app
yarn create v1.22.15
...
create-nuxt-app v4.0.0
✨  Generating Nuxt.js project in nuxt-netlify-app
? Project name: (nuxt-netlify-app)
```

TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale. Detecting errors in code without running it is referred to as static checking. Determining what’s an error and what’s not based on the kinds of values being operated on is known as static type checking.

TypeScript checks a program for errors before execution, and does so based on the kinds of values, it’s a static type checker.

```
? Programming language:
  JavaScript
❯ TypeScript
```

Yarn is a package manager for your code. It allows you to use and share code with other developers from around the world. Yarn does this quickly, securely, and reliably so you don't ever have to worry.

```
? Package manager: (Use arrow keys)
❯ Yarn
  Npm
```

```
? UI framework:
  None
  Ant Design Vue
  BalmUI
  Bootstrap Vue
  Buefy
  Chakra UI
  Element
  Oruga
  Primevue
  Tachyons
❯ Tailwind CSS
  Windi CSS
  Vant
  View UI
  Vuetify.js
```

```
? Nuxt.js modules: (Press <space> to select, <a> to toggle all, <i> to invert selection)
 ◯ Axios - Promise based HTTP client
 ◯ Progressive Web App (PWA)
❯◯ Content - Git-based headless CMS
```

```
? Linting tools: (Press <space> to select, <a> to toggle all, <i> to invert selection)
 ◯ ESLint
❯◯ Prettier
 ◯ Lint staged files
 ◯ StyleLint
 ◯ Commitlint
```

```
? Testing framework:
❯ None
  Jest
  AVA
  WebdriverIO
  Nightwatch
```

```
? Rendering mode: (Use arrow keys)
❯ Universal (SSR / SSG)
  Single Page App
```

```
? Deployment target:
  Server (Node.js hosting)
❯ Static (Static/Jamstack hosting)
```

```
? Development tools: (Press <space> to select, <a> to toggle all, <i> to invert selection)
 ◯ jsconfig.json (Recommended for VS Code if you're not using typescript)
 ◯ Semantic Pull Requests
❯◯ Dependabot (For auto-updating dependencies, GitHub only)
```

```
? What is your GitHub username? (chrisatrotter)
```

```
? Version control system: (Use arrow keys)
❯ Git
  None
```

```
🎉  Successfully created project nuxt-netlify-app

  To get started:

	cd nuxt-netlify-app
	yarn dev

  To build & start for production:

	cd nuxt-netlify-app
	yarn build
	yarn start


  For TypeScript users.

  See : https://typescript.nuxtjs.org/cookbook/components/
✨  Done in 391.39s.
```

Once all questions are answered, it will install all the dependencies. The next step is to navigate to the project folder and launch it:

```
cd nuxt-netlify-app
yarn dev
```