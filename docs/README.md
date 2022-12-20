# [your-company] Frontend

A collection of reusable packages designed for [your-company] products and experiences.

[Browse packages ➡️]()

## Disclaimer

Code snippets below uses `pnpm` as the package manager, but you can use `npm`, `yarn` or any of your choice.

Check the [npm vs yarn vs pnpm commands cheatsheet](https://dev.to/equiman/npm-vs-yarn-vs-pnpm-commands-cheatsheet-3el8) to find the corresponding command of your package manager.

## Installation

Packages in this repository can have peer dependencies. When installing a package make sure to have them installed first:

```
pnpm info {package}@{version} peerDependencies
```

Since these are all peer dependencies, they need to be on the specified major version. Undefined behavior may occur when trying to use these peer dependencies on different major versions.

## Usage

Install packages you’re interested in using, for example, a button:

```
pnpm install @my-kit/button
```

```jsx
import Button from '@my-kit/button';

<Button>Hello world!</Button>;
```

## Roadmap

Check the [roadmap]() to see what we have in mind to put on [your-company] Frontend.

## Contributing

Currently, [your-company] Frontend is only accepting contributions from [your-company] employees. If you are an [your-company] employee you can [find information about this on our internal docs]().

## Projects that uses [your-company] Frontend

- [Project 1]()
- [Project 2]()

## Browser support

[your-company] Frontend supports:

|       ![chrome](images/chrome.png)        |      ![safari](images/safari.png)       | ![firefox](images/firefox.png) | ![edge](images/edge.png) |
| :---------------------------------------: | :-------------------------------------: | :----------------------------: | :----------------------: |
| Latest ✅ Latest Android ✅ Latest iOS ✅ | Latest on latest macOS ✅ Latest iOS ✅ |           Latest ✅            |        Latest ✅         |

### License

[Specify license your project may have. Remember that this is a monorepo, so different parts can have different licenses].
