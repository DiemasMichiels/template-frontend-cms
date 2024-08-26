# Template frontend CMS

A NextJS template with Sveltia CMS integration with its own next auth and github login.

## Dependencies

Main dependencies used:

- [React](https://github.com/facebook/react)
- [Next.js](https://github.com/vercel/next.js/)
- [Sveltia CMS](https://github.com/sveltia/sveltia-cms)
- [Typescript](https://github.com/microsoft/TypeScript) (dev)
- [Sass](https://github.com/sass/dart-sass) (dev)
- [Eslint](https://github.com/eslint/eslint) (dev)
- [Prettier](https://github.com/prettier/prettier) (dev)

## Getting Started

### Environment variables

Add following ENV variables to a file in the root names: `env.local`

| Name            | Description            |
| --------------- | ---------------------- |
| NEXTAUTH_URL    | URL of website         |
| NEXTAUTH_SECRET | Randomly generated key |
| GITHUB_ID       | OAuth project id       |
| GITHUB_SECRET   | OAuth secret key       |

### Running

First, install the dependencies:

```bash
npm install
```

After, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
