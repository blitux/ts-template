# TypeScript Project Template

A minimal, modern TypeScript project template to kickstart your Node.js applications with best practices and essential tooling.

## Features

- **TypeScript 5.8+** - Latest TypeScript with strict type checking
- **Modern Module System** - Using Node.js ESM format
- **Fast Development** - Using [tsx](https://github.com/esbuild-kit/tsx) for instant startup without compilation
- **Testing** - Configured with [Vitest](https://vitest.dev/) for fast, simple testing
- **Code Quality** - [Biome](https://biomejs.dev/) for linting and formatting
- **Optimal Configuration** - Sensible defaults for TypeScript and tooling

## Getting Started

### Prerequisites

- Node.js 18+ recommended
- Yarn 4+ (included as the package manager)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ts-template.git my-project
cd my-project

# Install dependencies
yarn install
```

## Scripts

- `yarn start` - Run the compiled application
- `yarn build` - Build the TypeScript project to JavaScript
- `yarn dev` - Run the application with live reloading
- `yarn test` - Run tests
- `yarn lint` - Check code quality with Biome
- `yarn format` - Format code with Biome

## Project Structure

```
ts-template/
├── src/               # Source files
│   └── index.ts       # Main entry point
├── biome.json         # Biome configuration
├── package.json       # Project metadata and dependencies
├── tsconfig.json      # TypeScript configuration
├── vitest.config.ts   # Vitest configuration
└── README.md          # This file
```

## Customizing

1. Update `package.json` with your project details (name, version, etc.)
2. Modify `tsconfig.json` if you need specific TypeScript compiler options
3. Adjust `biome.json` for linting and formatting preferences

## License

[MIT](LICENSE)