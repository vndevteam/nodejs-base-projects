<p align="center">
  <a href="/">
    <img src="https://avatars.githubusercontent.com/u/105472712?s=72&v=4" alt="Nestjs Project" width=72 height=72>
  </a>

  <h3 align="center">NestJS boilerplate</h3>
</p>

## Description

## Installation

```bash
$ pnpm install
```

## Running the app

```bash
# development
$ pnpm run start

# watch mode
$ pnpm run start:dev

# debug mode
$ pnpm run start:debug

# production mode
$ pnpm run start:prod
```

## Test

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```

## Migration

```bash
# generate new migration file from changed in database
$ NAME=create-users-table pnpm run migration:generate

# create new migration file
$ NAME=create-users-table pnpm run migration:create

# run migration files
$ pnpm run migration:up

# revert migration files
$ pnpm run migration:down
```

## Project Structure

```text
│   # Root directory of the project
│   │
│   ├───.eslintrc.js
│   │   # Configuration file for ESLint, a tool for ensuring code quality and adherence to coding standards
│   │
│   ├───.gitignore
│   │   # File specifying patterns of files and directories to be ignored by Git during version control
│   │
│   ├───.prettierrc
│   │   # Configuration file for Prettier, a code formatter to maintain consistent and aesthetically pleasing code
│   │
│   ├───nest-cli.json
│   │   # Configuration file for Nest CLI, providing commands and tools for NestJS development
│   │
│   ├───package.json
│   │   # Project description file for Node.js, specifying dependencies, scripts, and other project configurations
│   │
│   ├───pnpm-lock.yaml
│   │   # Lock file for pnpm, a package manager for Node.js
│   │
│   ├───README.md
│   │   # Documentation file providing information about the project, including installation and usage instructions
│   │
│   ├───tsconfig.build.json
│   │   # TypeScript configuration for building and deploying the application
│   │
│   └───tsconfig.json
│       # TypeScript configuration for development and testing
│
├───src
│   │   # Source code directory containing the application's main modules
│   │
│   ├───api
│   │   └───users
│   │       │   # Module handling user-related functionality
│   │       │
│   │       ├───dto
│   │       │   # Data Transfer Objects for the user module
│   │       │
│   │       └───entities
│   │               # Entities representing objects in the database for the user module
│   │
│   ├───auth
│   │   │   # Module handling user authentication
│   │   │
│   │   ├───decorator
│   │   │   # Placeholder for potential decorators
│   │   │
│   │   └───guard
│   │       # Placeholder for potential guards
│   │
│   ├───background
│   │       # Directory for background tasks or services
│   │
│   ├───common
│   │   ├───constants
│   │   │   # Global constants used throughout the application
│   │   │   └───enums
│   │   │       # Enums defining fixed data types
│   │   │
│   │   ├───errors
│   │   │   # Directory for error-related components and handling
│   │   │
│   │   ├───filters
│   │   │   # Directory for handling and filtering requests and responses
│   │   │
│   │   ├───interceptors
│   │   │   # Directory for handling and modifying requests and responses before or after passing through controllers
│   │   │
│   │   └───utils
│   │       # Directory for common utility functions and support functions
│   │
│   ├───config
│   │       # Configuration files or settings
│   │
│   └───types
│           # Custom data types used throughout the application
│
└───test
        # Directory containing test files for the source code

```

## License
